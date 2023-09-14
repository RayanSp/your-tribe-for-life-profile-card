<script>
	/** @type {import("@prismicio/client").Content.NameSlice} */
	export let slice;
	console.log(slice)
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<h1>{slice.primary.name[0].text}</h1>
</section>



<style>

	h1 {
		text-align: center;
		color: orange;
	}

</style>