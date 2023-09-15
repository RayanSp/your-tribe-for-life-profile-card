<script>
	/** @type {import("@prismicio/client").Content.ImageSlice} */
	export let slice;
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<img src={slice.primary.image.url} alt="" />
</section>

<article>
	<p class="student">Student HvA</p>

	<p class="geboorte">2005</p>

	<p class="github">GitHub</p>

	<p class="geboorteplaats">Geboorteplaats</p>
</article>

<style>
	:root {
		--primary: black;
		--secondary: orange;
	}

	.geboorteplaats {
		width: 24rem;
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

	.geboorteplaats {
		border-bottom: 8px solid var(--secondary);
		width: 100%;
		padding-bottom: 60px;
	}

	.geboorte:hover {
		color: var(--secondary);
	}

	.github:hover {
		color: var(--secondary);
		cursor: pointer;
		width: auto;
	}

	.geboorteplaats:hover {
		color: var(--secondary);
	}

	.student:hover {
		color: var(--secondary);
	}
</style>
