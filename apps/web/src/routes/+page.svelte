<script lang="ts">
	import { MyCounterButton } from '@repo/ui';
	import { MyCounterButton2 } from '@repo/ui2';

	const value = import.meta.env.VITE_LOCAL_VARIABLE_TEST
</script>



<h1>Web</h1>
<MyCounterButton />
<MyCounterButton2 />
<p>value : {value}</p>
