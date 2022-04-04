<template>
	<div class="container" id="portfolio">
		<h1>
			<img
				src="../assets/icons8-portfolio-32.png"
				alt="portfolio icon"
			/>Portfolio
		</h1>

		<div
			class="portfolio-item row"
			v-for="item in portifolioItems"
			:key="item.title"
		>
			<div class="portfolio-img col-md-4 col-sm-12">
				<img
					class="card-img-top"
					:src="getImgUrl(item.image.src)"
					:alt="item.image.alt"
				/>
			</div>
			<div class="col-md-8 col-sm-12">
				<h4 class="card-title">{{ item.title }}</h4>
				<div class="portfolio-middle">
					<p class="card-text">{{ item.body }}</p>
				</div>
				<div class="tags">
					<span v-for="tag in item.tags" :key="tag" class="tag"
						>#{{ tag }}</span
					>
				</div>
				<div class="portfolio-buttons">
					<a
						v-for="link in item.links"
						:key="link.text"
						:href="link.href"
						target="_blank"
						>{{ link.text }}</a
					>
					<div v-if="item.download">
						<a
							v-for="download in item.download"
							:key="download.text"
							:href="download.download"
							:download="download.download"
							target="_blank"
							>{{ download.text }}</a
						>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
import portfolio from "./portfolio.json";

export default {
	name: "Portfolio",
	data: function() {
		return {
			portifolioItems: portfolio,
		};
	},
	props: {},
	methods: {
		getImgUrl(img) {
			try {
				let images = require.context("./../assets/", false, /\.png$/);
				return images("./" + img + ".png");
			} catch {
				let images = require.context("./../assets/", false, /\.jpg$/);
				return images("./" + img + ".jpg");
			}
		},
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.portfolio-item {
	margin: 2em 0;
	padding: 1em 0.5em;
	box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px,
		rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
}

.portfolio-img {
	text-align: center;
}

.card-img-top {
	max-height: 15em;
	height: 100%;
	width: auto;
	text-align: center;
}

.row .card {
	max-width: 400px;
	margin: 20px;
}

.btn.btn-primary {
	margin-top: 0.2em;
	white-space: normal;
}

.card-title {
	width: 100%;
	text-align: center;
	margin-top: 1em;
}

.tag {
	display: inline-block;
	margin: 0.7em 0.8em;
	font-family: "Noto Sans";
	font-weight: bold;
	color: #3f3f3f;
}

.tags .tag:first-child {
	margin-left: 0;
}

.portfolio-buttons {
	width: 100%;
}

.portfolio-buttons a {
	display: block;
	margin: auto;
	text-align: center;
}

@media only screen and (min-width: 768px) {
	.card-title {
		text-align: left;
	}

	.portfolio-buttons a {
		text-align: left;
	}

	.card-img-top {
		max-height: 13em;
		width: auto;
		max-width: 100%;
		vertical-align: middle;
	}
}
</style>
