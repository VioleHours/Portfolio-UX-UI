<script lang="ts">
    import {T as Threlte} from '@threlte/core';
    import * as THREE from 'three';
	import Geometry from './Geometry.svelte';
</script>


<Threlte.PerspectiveCamera 
    makeDefault
    position={[0, 0, 25]}
    aspect={1}
    fav={30}
    near={1}
    far={40}
/>

<Geometry />
