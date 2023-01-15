<script setup>
	import image from "../assets/food-ordering.jpg";
</script>
<template>
	<div
		id="works"
		class="p-5 hover:shadow-lg rounded-lg duration-150 border border-transparent hover:border-teal-400 hover:shadow-teal-400"
	>
		<div class="grid gap-3">
			<h1 class="uppercase text-teal-300 font-semibold text-2xl">
				Personal Projects
			</h1>
			<div class="sm:grid sm:grid-cols-2 gap-5">
				<!--  -->
				<div class="sm:col-span-1 flex space-x-4 items-center">
					<a
						href="https://github.com/Norjamille/react-native-food-app"
						target="_blank"
					>
						<img :src="image" class="h-52 rounded-lg" />
						<span class="mt-1 text-teal-300 text-lg"> FOOD ORDERING APP </span>
					</a>
				</div>
			</div>
		</div>
	</div>
</template>
