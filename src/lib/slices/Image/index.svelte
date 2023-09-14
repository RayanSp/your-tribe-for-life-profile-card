<script>
	/** @type {import("@prismicio/client").Content.ImageSlice} */
	export let slice;
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<img src={slice.primary.image.url} alt="">
</section>

<article>
	<p>
		Student HvA
	</p>

	<p>
		2005
	</p>

	<p class="github">
		GitHub
	</p>

	<p class="geboorte">
		Geboorteplaats
	</p>
</article>




<style>

	:root {
		--primary:black;
		--secondary: orange;
	}

	section {
		display: flex;
		justify-content: center;
	}

	img {
		width: 10rem;
		height: auto;
	}

	article {
		margin-top: 3rem;
	}

	p {
		color: white;
		font-size: 20px;
		text-align: center;
	}
	
	.geboorte {
		border-bottom: 8px solid var(--secondary);
		width: 100%;
		padding-bottom: 60px;
	}
</style>