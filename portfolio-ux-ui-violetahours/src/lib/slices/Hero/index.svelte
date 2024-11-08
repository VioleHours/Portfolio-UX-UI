<script lang="ts">
	import type { Content } from '@prismicio/client';

	export let slice: Content.HeroSlice;
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<h1 class="mb-2 md:mb-8 text-[clamp(3rem,18.5vmin,13rem)] font-extrabold leading-none tracking-tighter text-nowrap">
		<span class="block text-slate-300">
			{slice.primary.first_name}
		</span>
		<span class="block text-slate-500 -mt-[.2em]">
			{slice.primary.last_name}
		</span>
	</h1>
	<span class="block bg-gradient-to-tr from-violet-300 via-violet-500 to-violet-700 bg-clip-text text-transparent text-2xl font-bold uppercase tracking-[.2em] md:text-4xl">
		{slice.primary.tag_title}
	</span>
</section>
