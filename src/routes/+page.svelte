<script lang="ts">
	import {
		IconBook,
		IconBuildingSkyscraper,
		IconBuildingCommunity,
		IconSparkles
	} from '@tabler/icons-svelte';
	import ScifiDashboard from '$lib/assets/scifi-dashboard.jpg';
</script>

<section class="relative h-screen w-full overflow-hidden">
	<img
		src={ScifiDashboard}
		alt="scifi-dashboard"
		class="absolute inset-0 h-full w-full bg-cover bg-center bg-no-repeat"
	/>
	<div class="absolute inset-0 bg-background/50"></div>
	<div class="relative h-full w-full">
		<div class="container mx-auto h-full px-4">
			<div class="flex h-full flex-col justify-center">
				<h1 class="mb-4">AI-Powered Intelligent Solutions</h1>
				<p class="max-w-2xl">
					From automated customer service to intelligent tutoring, empower your business with AI
				</p>
			</div>
		</div>
	</div>
</section>

<section class="bg-gray-800 px-4 py-16">
	<div class="mx-auto max-w-6xl">
		<h2 class="mb-12 text-center text-3xl font-bold">Our Services</h2>
		<div class="grid gap-8 md:grid-cols-2">
			<div class="rounded-lg bg-gray-700 p-6">
				<IconSparkles class="mb-4 h-12 w-12 text-blue-500" />
				<h3 class="mb-3 text-xl font-bold">AI Customer Service Assistant</h3>
				<p class="text-gray-300">
					24/7 automated customer support with professional FAE service assistance
				</p>
			</div>
			<div class="rounded-lg bg-gray-700 p-6">
				<IconBook class="mb-4 h-12 w-12 text-green-500" />
				<h3 class="mb-3 text-xl font-bold">AI Learning Tutor</h3>
				<p class="text-gray-300">
					Personalized learning experience with real-time content adaptation based on progress
				</p>
			</div>
		</div>
	</div>
</section>

<section class="px-4 py-16">
	<div class="mx-auto max-w-6xl">
		<h2 class="mb-12 text-center text-3xl font-bold">Pricing Plans</h2>
		<div class="grid gap-8 md:grid-cols-3">
			<div class="rounded-lg border border-gray-700 bg-gray-800 p-8">
				<h3 class="mb-4 text-xl font-bold">Starter</h3>
				<div class="mb-4 text-3xl font-bold">TBD <span class="text-lg">/month</span></div>
				<ul class="mb-8 space-y-3">
					<li>• Basic AI customer service features</li>
					<li>• 1000 conversations per month</li>
					<li>• Basic analytics reports</li>
				</ul>
				<button class="w-full rounded-lg bg-blue-600 py-2 hover:bg-blue-700"> Choose Plan </button>
			</div>

			<div class="rounded-lg border border-gray-700 bg-gray-800 p-8">
				<h3 class="mb-4 text-xl font-bold">Starter</h3>
				<div class="mb-4 text-3xl font-bold">TBD <span class="text-lg">/month</span></div>
				<ul class="mb-8 space-y-3">
					<li>• Basic AI customer service features</li>
					<li>• 1000 conversations per month</li>
					<li>• Basic analytics reports</li>
				</ul>
				<button class="w-full rounded-lg bg-blue-600 py-2 hover:bg-blue-700"> Choose Plan </button>
			</div>

			<div class="rounded-lg border border-gray-700 bg-gray-800 p-8">
				<h3 class="mb-4 text-xl font-bold">Starter</h3>
				<div class="mb-4 text-3xl font-bold">TBD <span class="text-lg">/month</span></div>
				<ul class="mb-8 space-y-3">
					<li>• Basic AI customer service features</li>
					<li>• 1000 conversations per month</li>
					<li>• Basic analytics reports</li>
				</ul>
				<button class="w-full rounded-lg bg-blue-600 py-2 hover:bg-blue-700"> Choose Plan </button>
			</div>
		</div>
	</div>
</section>

<section class="bg-gray-800 px-4 py-16">
	<div class="mx-auto max-w-6xl">
		<h2 class="mb-12 text-center text-3xl font-bold">Success Stories</h2>
		<div class="grid gap-8 md:grid-cols-2">
			<div class="rounded-lg bg-gray-700 p-6">
				<IconBuildingSkyscraper class="mb-4 h-12 w-12 text-purple-500" />
				<h3 class="mb-3 text-xl font-bold">Tech Company A</h3>
				<p class="text-gray-300">
					After implementing our AI customer service system, service efficiency increased by 80% and
					customer satisfaction improved by 40%
				</p>
			</div>

			<div class="rounded-lg bg-gray-700 p-6">
				<IconBuildingCommunity class="mb-4 h-12 w-12 text-purple-500" />
				<h3 class="mb-3 text-xl font-bold">Tech Company B</h3>
				<p class="text-gray-300">
					After implementing our AI customer service system, service efficiency increased by 80% and
					customer satisfaction improved by 40%
				</p>
			</div>
		</div>
	</div>
</section>

<section class="px-4 py-16">
	<div class="mx-auto max-w-6xl text-center">
		<h2 class="mb-8 text-3xl font-bold">Start Your Project</h2>
		<div class="mx-auto max-w-md">
			<button class="w-full rounded-lg bg-blue-600 py-3 text-lg font-semibold hover:bg-blue-700">
				Contact Us
			</button>
		</div>
	</div>
</section>
