<script>
	/** @type {import("@prismicio/client").Content.NameSlice} */
	export let slice;
	console.log(slice)
</script>

<section class="name-background" data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<h1>{slice.primary.name[0].text}</h1>
</section>



<style>

	.name-background {
		background-color: black;
		width: 20rem;
		margin-left: 38%;
		border-radius: 15px 15px 0px 0px;
	}

	h1 {
		text-align: center;
		color: rgb(240, 76, 76);
		margin-bottom: 0;
		padding-bottom: 10px;
		padding-top: 15px;
		
	}

</style>