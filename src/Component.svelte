<svelte:options tag={null}/>

<script>
	import { LatinKeAksara } from '@sajenid/aksara.js';

	export let latin = "Aksara HTML";
</script>

<span>{LatinKeAksara(latin)}</span>
<slot></slot>