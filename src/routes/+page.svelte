<script>
	import { PencilIcon, TypeIcon } from 'lucide-svelte';
</script>

<main>
	<div
		class="flex flex-col h-full py-32 sm:h-screen pattern-dots pattern-orange-3 pattern-bg-transparent pattern-opacity-100 pattern-size-8"
	>
		<div
			class="m-auto max-w-xl text-center text-sand-12 selection:bg-orange-2 flex flex-col gap-4 container px-8 sm:px-4"
		>
			<h1 class="text-7xl sm:text-8xl font-black leading-none">thesis on</h1>
			<h1 class="text-7xl sm:text-8xl font-black leading-none">
				<span class="px-8 rounded-xl pb-2 bg-orange-5 leading-none"> easy </span>
				mode
			</h1>
			<p class="mt-4 text-3xl">every little help to get you over the line</p>
			<div class="flex flex-col items-start gap-3 w-full">
				<label class="text-lg text-orange-12 font-bold" for="email">Waiting list</label>
				<div class="w-full flex gap-3 flex-col sm:flex-row">
					<input
						id="email"
						type="text"
						class="w-full px-4 py-2 bg-orange-2 ring-orange-4 ring-2 text-orange-900 rounded-lg"
					/>
					<button class="bg-orange-8 text-orange-1 px-4 font-bold rounded-lg py-2"> Send </button>
				</div>
			</div>
		</div>
	</div>

	<div class="container mx-auto flex flex-col mt-32 px-8 sm:px-4 pb-12">
		<h1 class="text-5xl sm:text-6xl font-black leading-none mb-8">Features</h1>
		<div class="grid grid-cols-1 sm:grid-cols-2 gap-8 text-orange-12">
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<TypeIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">write with ai</p>
				<p class="mt-8">
					Sit non omnis asperiores reprehenderit culpa. Consectetur adipisci cumque assumenda?
				</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<TypeIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">write with ai</p>
				<p class="mt-8">
					Sit non omnis asperiores reprehenderit culpa. Consectetur adipisci cumque assumenda?
				</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<TypeIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">write with ai</p>
				<p class="mt-8">
					Sit non omnis asperiores reprehenderit culpa. Consectetur adipisci cumque assumenda?
				</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<TypeIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">write with ai</p>
				<p class="mt-8">
					Sit non omnis asperiores reprehenderit culpa. Consectetur adipisci cumque assumenda?
				</p>
			</div>
		</div>
	</div>

	<footer class="bg-orange-10 text-orange-1 w-full py-8 px-8">
		<p class="mx-auto container text-2xl sm:text-4xl font-bold">Contact me: tnkevino@gmail.com</p>
	</footer>
</main>
