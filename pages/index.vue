<template>
	<div>
		<Carousel />
		<div class="container p-5">
			<h1 class="text-center font-weight-bold">
				Program JongKreatif
			</h1>
			<p class="mt-2 text-center">
				Cupcake danish tiramisu powder soda ginger cake. Dessert carrot cake tartsweet marzipan for fruitcake.
			</p>
			<div class="p-3 mt-4 text-center row">
				<div class="col">
					<h2 class="font-weight-bold text-danger">
						JongKoding
					</h2>
					<p class="mt-3">
						Pelatihan pemrograman bersertifikat, langsung dari developer dan inovator berpengalaman
					</p>
					<span class="font-weight-bold">
						Pelajari Lebih
					</span>
				</div>
				<div class="col">
					<h2 class="font-weight-bold text-warning">
						JongDesain
					</h2>
					<p class="mt-3">
						Pelatihan desain grafis, video, dan UIUX bersertifikat, langsung dari desainer dan inovator berpengalaman
					</p>
					<span class="font-weight-bold">
						Pelajari Lebih
					</span>
				</div>
				<div class="col">
					<h2 class="font-weight-bold text-info">
						JongKonten
					</h2>
					<p class="mt-3">
						Pelatihan pembuatan konten bersertifikat, langsung dari content creator dan inovator berpengalaman
					</p>
					<span class="font-weight-bold">
						Pelajari Lebih
					</span>
				</div>
			</div>
		</div>
		<div class="bg-danger">
			<div class="container p-5">
				<div class="p-3 text-center text-white row">
					<div class="col">
						<h1 class="font-weight-bold">1040</h1>
						<span>Students</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold">105</h1>
						<span>Schools</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold">1030</h1>
						<span>Projects</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold">10</h1>
						<span>Affiliates Industries</span>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
import Carousel from '../components/Carousel'

export default {
	components: {
		Carousel
	}
}
</script>