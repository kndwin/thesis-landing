<script>
	import { TypeIcon, ZapIcon, FileEditIcon, PackageOpenIcon, WifiOffIcon } from 'lucide-svelte';
</script>

<main class="bg-sand-1">
	<div
		class="flex flex-col h-full py-32 sm:h-screen pattern-dots pattern-orange-1 pattern-bg-transparent pattern-opacity-100 pattern-size-8"
	>
		<div
			class="m-auto max-w-xl text-center text-orange-12 selection:bg-orange-2 flex flex-col gap-4 container px-8 sm:px-4"
		>
			<h1 class="text-7xl sm:text-8xl font-black leading-none">thesis on</h1>
			<h1 class="text-7xl sm:text-8xl font-black leading-none">
				<span class="px-8 rounded-xl pb-2 bg-orange-5 leading-none"> easy </span>
				mode
			</h1>
			<p class="mt-4 text-3xl">every little help to get you over the line</p>
			<div class="flex flex-col items-start gap-3 w-full mt-8">
				<div class="w-full flex gap-3 flex-col sm:flex-row">
					<input
						id="email"
						type="text"
						class="w-full px-4 py-2 bg-orange-2 ring-orange-4 ring-2 text-orange-900 rounded-lg placeholder:text-orange-10 outline-orange-2"
					 placeholder="your email address"
					/>
					<button class="bg-orange-8 text-orange-1 px-4 font-bold rounded-lg py-2"> Send </button>
				</div>
			</div>
		</div>
	</div>

	<div class="container mx-auto flex flex-col mt-32 px-8 sm:px-4 pb-12">
		<h1 class="text-5xl sm:text-6xl font-black leading-none mb-8 text-orange-12">Features</h1>

		<div class="grid grid-cols-1 sm:grid-cols-2 gap-8 text-orange-12">
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<svg
						class="text-orange-1 w-8 h-8"
						role="img"
						viewBox="0 0 24 24"
						xmlns="http://www.w3.org/2000/svg"
						><title>OpenAI</title><path
							d="M22.2819 9.8211a5.9847 5.9847 0 0 0-.5157-4.9108 6.0462 6.0462 0 0 0-6.5098-2.9A6.0651 6.0651 0 0 0 4.9807 4.1818a5.9847 5.9847 0 0 0-3.9977 2.9 6.0462 6.0462 0 0 0 .7427 7.0966 5.98 5.98 0 0 0 .511 4.9107 6.051 6.051 0 0 0 6.5146 2.9001A5.9847 5.9847 0 0 0 13.2599 24a6.0557 6.0557 0 0 0 5.7718-4.2058 5.9894 5.9894 0 0 0 3.9977-2.9001 6.0557 6.0557 0 0 0-.7475-7.0729zm-9.022 12.6081a4.4755 4.4755 0 0 1-2.8764-1.0408l.1419-.0804 4.7783-2.7582a.7948.7948 0 0 0 .3927-.6813v-6.7369l2.02 1.1686a.071.071 0 0 1 .038.052v5.5826a4.504 4.504 0 0 1-4.4945 4.4944zm-9.6607-4.1254a4.4708 4.4708 0 0 1-.5346-3.0137l.142.0852 4.783 2.7582a.7712.7712 0 0 0 .7806 0l5.8428-3.3685v2.3324a.0804.0804 0 0 1-.0332.0615L9.74 19.9502a4.4992 4.4992 0 0 1-6.1408-1.6464zM2.3408 7.8956a4.485 4.485 0 0 1 2.3655-1.9728V11.6a.7664.7664 0 0 0 .3879.6765l5.8144 3.3543-2.0201 1.1685a.0757.0757 0 0 1-.071 0l-4.8303-2.7865A4.504 4.504 0 0 1 2.3408 7.872zm16.5963 3.8558L13.1038 8.364 15.1192 7.2a.0757.0757 0 0 1 .071 0l4.8303 2.7913a4.4944 4.4944 0 0 1-.6765 8.1042v-5.6772a.79.79 0 0 0-.407-.667zm2.0107-3.0231l-.142-.0852-4.7735-2.7818a.7759.7759 0 0 0-.7854 0L9.409 9.2297V6.8974a.0662.0662 0 0 1 .0284-.0615l4.8303-2.7866a4.4992 4.4992 0 0 1 6.6802 4.66zM8.3065 12.863l-2.02-1.1638a.0804.0804 0 0 1-.038-.0567V6.0742a4.4992 4.4992 0 0 1 7.3757-3.4537l-.142.0805L8.704 5.459a.7948.7948 0 0 0-.3927.6813zm1.0976-2.3654l2.602-1.4998 2.6069 1.4998v2.9994l-2.5974 1.4997-2.6067-1.4997Z"
						/></svg
					>
				</div>
				<p class="font-bold text-3xl">Write with AI</p>
				<p class="mt-8">Streamline your writing process with AI assistance from ChatGPT</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<TypeIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">Edit Like a Pro</p>
				<p class="mt-8">Refine your thesis with top-notch editing tools</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<FileEditIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">PDF capabilities</p>
				<p class="mt-8">Take your research to the next level with PDF annotation</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<ZapIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">Blazing fast</p>
				<p class="mt-8">Built with Rust and performance</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<svg
						class="text-orange-1 w-8 h-8"
						role="img"
						viewBox="0 0 24 24"
						xmlns="http://www.w3.org/2000/svg"
						><title>GitHub</title><path
							d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
						/></svg
					>
				</div>
				<p class="font-bold text-3xl">Open Source</p>
				<p class="mt-8">Free to view, use and modify the source code</p>
			</div>
			<div class="py-10 px-12 rounded-xl border border-orange-8 bg-orange-1">
				<div class="p-2 rounded-full bg-orange-9 w-fit h-fit mb-4">
					<WifiOffIcon class="text-orange-1 w-8 h-8" />
				</div>
				<p class="font-bold text-3xl">Offline-first</p>
				<p class="mt-8">Local-first approach means you can work anywhere</p>
			</div>
		</div>
	</div>

</main>
