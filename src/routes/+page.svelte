<script>
	import strobbery from '$lib/images/strobbery.jpg';
	import defend from '$lib/images/defend.jpg';
	import ente from '$lib/images/ente.jpg';
	import berg from '$lib/images/berg.jpg';
	import llama from '$lib/images/llama.jpg';
	import monopoly from '$lib/images/monopoly.jpg';
	import traurig from '$lib/images/traurig.jpg';
	import hdl from '$lib/images/hdl.jpg';
	import spaten from '$lib/images/spaten.jpg';
	import rap from '$lib/images/rap.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<!-- <section>
	<h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/+page.svelte</strong>
	</h2>

	<Counter />
	<p>hi</p>
</section> -->
<section>
	<h1>Strobbery --- Artist: Christoph</h1>
	<img src={strobbery} />
</section>

<section>
	<h1>Defend Your Answer --- Artist: Julian</h1>
	<img src={defend} />
</section>

<section>
	<h1>Ente --- Artist: Niklas</h1>
	<img src={ente} />
</section>

<section>
	<h1>Berg --- Artist: Niklas</h1>
	<img src={berg} />
</section>

<section>
	<h1>Llama --- Artist: Niklas</h1>
	<img src={llama} />
</section>

<section>
	<h1>Magnetisches Monopoly --- Artist: Niklas</h1>
	<img src={monopoly} />
</section>

<section>
	<h1>Nicht Traurig Sein --- Artist: Julia</h1>
	<img src={traurig} />
</section>

<section>
	<h1>Das HdL-Integral --- Artist: Julia, Niklas</h1>
	<img src={hdl} />
</section>

<section>
	<h1>Das Spaten-Produkt --- Artist: Niklas</h1>
	<img src={spaten} />
</section>

<section>
	<h1>Rap --- Artist: Julia, Niklas</h1>
	<img src={rap} />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
