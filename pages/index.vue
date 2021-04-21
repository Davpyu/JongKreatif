<template>
	<div>
		<Carousel />
		<div class="container p-5">
			<h1 class="text-center font-weight-bold text-baloo">
				Program JongKreatif
			</h1>
			<p class="mt-2 text-center text-nunito">
				Cupcake danish tiramisu powder soda ginger cake. Dessert carrot cake tartsweet marzipan for fruitcake.
			</p>
			<div class="p-3 mt-4 text-center row">
				<div class="col">
					<h2 class="font-weight-bold text-danger text-arvo">
						JongKoding
					</h2>
					<p class="mt-3 text-nunito">
						Pelatihan pemrograman bersertifikat, langsung dari developer dan inovator berpengalaman
					</p>
					<span class="font-weight-bold text-baloo">
						Pelajari Lebih
					</span>
				</div>
				<div class="col">
					<h2 class="font-weight-bold text-warning text-arvo">
						JongDesain
					</h2>
					<p class="mt-3 text-nunito">
						Pelatihan desain grafis, video, dan UIUX bersertifikat, langsung dari desainer dan inovator berpengalaman
					</p>
					<span class="font-weight-bold text-baloo">
						Pelajari Lebih
					</span>
				</div>
				<div class="col">
					<h2 class="font-weight-bold text-info text-arvo">
						JongKonten
					</h2>
					<p class="mt-3 text-nunito">
						Pelatihan pembuatan konten bersertifikat, langsung dari content creator dan inovator berpengalaman
					</p>
					<span class="font-weight-bold text-buloo">
						Pelajari Lebih
					</span>
				</div>
			</div>
		</div>
		<div class="bg-danger">
			<div class="container p-5">
				<div class="p-3 text-center text-white row">
					<div class="col">
						<h1 class="font-weight-bold text-arvo">1040</h1>
						<span class="text-nunito">Students</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold text-arvo">105</h1>
						<span class="text-nunito">Schools</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold text-arvo">1030</h1>
						<span class="text-nunito">Projects</span>
					</div>
					<div class="col">
						<h1 class="font-weight-bold text-arvo">10</h1>
						<span class="text-nunito">Affiliates Industries</span>
					</div>
				</div>
			</div>
		</div>
		<div class="p-5">
			<div class="mx-auto text-center w-75">
				<h1 class="font-weight-bold text-baloo">
					Yang Terbaru di JongKreatif
				</h1>
				<p class="mt-3 text-nunito">
					Cupcake danish tiramisu powder soda ginger cake. Dessert carrot cake tartsweet marzipan for fruitcake.
				</p>
			</div>
			<div class="mt-4 row card-deck">
				<Card 
					v-for="(item, index) in benefitObject" 
					:key="index" 
					:item="item"
				>
				</Card>
			</div>
		</div>
		<div class="container p-5 text-center">
			<div class="mx-auto w-75">
				<h1 class="font-weight-bold text-baloo">
					Keuntungan Bergabung Bersama JongKreatif
				</h1>
				<p class="mt-3 text-nunito">
					Cupcake danish tiramisu powder soda ginger cake. Dessert carrot cake tartsweet marzipan for fruitcake.
				</p>
			</div>
			<div class="mt-4 row">
				<BenefitGrid v-for="n in 6" :key="n" />
			</div>
		</div>
		<div class="container p-5 text-center">
			<div class="mx-auto w-75">
				<h3 class="font-weight-bold text-baloo">
					Banyak Industri Telah Berafiliasi dengan Kami
				</h3>
				<p class="mt-3 text-roboto">
					Cupcake danish tiramisu powder soda ginger cake. Dessert carrot cake tartsweet marzipan for fruitcake.
				</p>
			</div>
			<div class="mt-4 row">
				<div class="col">
					<img src="~/assets/img/adrol.png" alt="Adroll">
				</div>
				<div class="col">
					<img src="~/assets/img/segment.png" alt="Segment">
				</div>
				<div class="col">
					<img src="~/assets/img/sendgrid.png" alt="SendGrid">
				</div>
				<div class="col">
					<img src="~/assets/img/toast.png" alt="Toast">
				</div>
			</div>
		</div>
		<Jumbotron />
	</div>
</template>

<script>
import Carousel from '../components/Carousel'
import Jumbotron from '../components/Jumbotron'
import BenefitGrid from '../components/BenefitGrid'
import Card from '../components/Card'

export default {
	data() {
		return {
			benefitObject : [
				{
					src: 'first',
					title: 'Opening Ceremony JongCoding',
					description: 'Muffin lemon drops toffee. Pudding tootsie roll brownie jelly beans.'
				},
				{
					src: 'second',
					title: 'JongDesign, Pelatihan Desain',
					description: 'Muffin lemon drops toffee. Pudding tootsie roll brownie jelly beans.'
				},
				{
					src: 'third',
					title: 'Jago Jadi Konten Kreator!',
					description: 'Muffin lemon drops toffee. Pudding tootsie roll brownie jelly beans.'
				}
			]
		}
	},
	components: {
		Carousel,
		Jumbotron,
		BenefitGrid,
		Card
	}
}
</script>