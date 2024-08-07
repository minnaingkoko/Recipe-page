<script>
	import omelette from '$lib/images/image-omelette.jpeg';
</script>

<div class="container">
	<img class="omelette" src={omelette} alt="" />
	<h1 class="heading">Simple Omelette Recipe</h1>
	<p class="text">
		An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked
		to perfection, optionally filled with your choice of cheese, vegetables, or meats.
	</p>
	<div class="preparation">
		<h2 class="p-heading">Preparation time</h2>
		<ul>
			<li><b>Total:</b> Approximately 10 minutes</li>
			<li><b>Preparation:</b> 5 minutes</li>
			<li><b>Cooking:</b> 5 minutes</li>
		</ul>
	</div>
	<div class="ingredients">
		<h2 class="i-heading">Ingredients</h2>
		<ul>
			<li>2-3 large eggs</li>
			<li>Salt, to taste</li>
			<li>Pepper, to taste</li>
			<li>1 tablespoon of butter or oil</li>
			<li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
		</ul>
	</div>
	<hr class="line" />
	<div class="instructions">
		<h2 class="i-heading">Instructions</h2>
		<ol>
			<li>
				<b>Beat the eggs:</b> In a bowl, beat the eggs with a pinch of salt and pepper until they are
				well mixed. You can add a tablespoon of water or milk for a fluffier texture.
			</li>
			<li>
				<b>Heat the pan:</b> Place a non-stick frying pan over medium heat and add butter or oil.
			</li>
			<li>
				<b>Cook the omelette:</b> Once the butter is melted and bubbling, pour in the eggs. Tilt the
				pan to ensure the eggs evenly coat the surface.
			</li>
			<li>
				<b>Add fillings (optional):</b> When the eggs begin to set at the edges but are still slightly
				runny in the middle, sprinkle your chosen fillings over one half of the omelette.
			</li>
			<li>
				<b>Fold and serve:</b> As the omelette continues to cook, carefully lift one edge and fold it
				over the fillings. Let it cook for another minute, then slide it onto a plate.
			</li>
			<li><b>Enjoy:</b> Serve hot, with additional salt and pepper if needed.</li>
		</ol>
	</div>
	<hr class="line" />
	<div class="nutrition">
		<h2 class="n-heading">Nutrition</h2>
		<p class="n-text">
			The table below shows nutritional values per serving without the additional fillings.
		</p>
		<div class="row">
			<div class="left">Calories</div>
			<div class="right">277kcal</div>
		</div>
		<hr class="line" />
		<div class="row">
			<div class="left">Carbs</div>
			<div class="right">0g</div>
		</div>
		<hr class="line" />
		<div class="row">
			<div class="left">Protein</div>
			<div class="right">20g</div>
		</div>
		<hr class="line" />
		<div class="row-alt">
			<div class="left">Fat</div>
			<div class="right">22g</div>
		</div>
	</div>
</div>

<style>
	b {
		color: #5f564d;
		font-family: 'Outfit', sans-serif;
	}
	.container {
		width: 736px;
		background-color: white;
		margin-top: 128px;
		margin-bottom: 128px;
		border-radius: 24px;
		display: flex;
		flex-direction: column;
		padding: 40px;
	}
	.omelette {
		width: 656px;
		height: 300px;
		border-radius: 12px;
	}
	.heading {
		color: #312e2c;
		margin-top: 40px;
		margin-bottom: 24px;
		line-height: 100%;
		font-size: 40px;
		font-family: 'YoungSerif', sans-serif;
	}
	.text {
		font-family: 'Outfit', sans-serif;
		font-size: 16px;
		line-height: 150%;
		color: #5f564d;
	}
	.preparation {
		font-family: 'Outfit', sans-serif;
		margin-top: 32px;
		padding: 24px;
		width: 656px;
		height: 172px;
		border-radius: 12px;
		background-color: #fff7fb;
	}
	.p-heading {
		margin-bottom: 16px;
		font-size: 20px;
		font-weight: 600;
		line-height: 100%;
		color: #7a284e;
	}
	.preparation li {
		color: #5f564d;
		font-size: 16px;
		line-height: 150%;
		margin-left: 24px;
		padding-left: 28px;
	}
	.preparation li::marker {
		color: #7a284e;
	}
	.preparation ul {
		display: flex;
		flex-direction: column;
		gap: 8px;
	}
	.ingredients,
	.instructions {
		margin-top: 32px;
		margin-bottom: 32px;
	}
	.i-heading {
		font-family: 'YoungSerif', sans-serif;
		font-size: 28px;
		color: #854632;
		margin-bottom: 24px;
		line-height: 100%;
	}
	.ingredients ul,
	.instructions ol {
		display: flex;
		flex-direction: column;
		gap: 8px;
	}
	.ingredients li,
	.instructions li {
		font-family: 'Outfit', sans-serif;
		color: #5f564d;
		font-size: 16px;
		line-height: 150%;
		margin-left: 24px;
		padding-left: 28px;
	}
	.ingredients li::marker,
	.instructions li::marker {
		color: #854632;
		font-size: 16px;
		font-weight: bold;
		line-height: 150%;
	}
	.line {
		width: 100%;
		height: 1px;
		background-color: #e3ddd7;
	}
	.n-heading {
		font-family: 'YoungSerif', sans-serif;
		font-size: 28px;
		color: #854632;
		margin-top: 32px;
		line-height: 100%;
		margin-bottom: 24px;
	}
	.n-text {
		font-family: 'Outfit', sans-serif;
		margin-bottom: 12px;
		color: #5f564d;
		font-size: 16px;
		line-height: 150%;
	}
	.row,
	.row-alt {
		display: flex;
		flex-direction: row;
		padding: 0 32px;
	}
	.row {
		margin-top: 12px;
		margin-bottom: 12px;
	}
	.row-alt {
		margin-top: 12px;
	}
	.left,
	.right {
		display: flex;
		align-items: center;
		width: 288px;
		height: 24px;
		font-size: 16px;
		line-height: 150%;
		font-family: 'Outfit', sans-serif;
	}
	.left {
		color: #5f564d;
	}
	.right {
		color: #854632;
		font-weight: bold;
	}
	@media only screen and (max-width: 768px) {
		.container {
			width: 616px;
		}
		.omelette {
			width: 536px;
		}
		.preparation {
			width: 536px;
		}
		.left,
		.right {
			width: 228px;
		}
	}
	@media only screen and (max-width: 375px) { 
		.container {
			margin-top: 0;
			margin-bottom: 0;
			padding: 0;
			width: 100%;
			background-color: white;
			border-radius: 0;
			align-items: center;
		}
		.omelette {
			width: 100%;
			height: 171px;
			border-radius: 0;
		}
		.heading {
			width: 311px;
			font-size: 36px;
		}
		.text {
			width: 311px;
		}
		.preparation {
			width: 311px;
			height: 196px;
		}
		.left,
		.right {
			width: 115.5px;
		}
		.ingredients, .instructions, .nutrition {
			width: 311px;
		}
		.nutrition {
			margin-bottom: 40px;
		}
		.line {
			width: 311px;
		}
	}
</style>
