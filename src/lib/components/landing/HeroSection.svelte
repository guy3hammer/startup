<script lang="ts">
	import { ArrowRightIcon } from 'lucide-svelte';
	import AnimatedShinyText from '$lib/components/magic/AnimatedShinyText/AnimatedShinyText.svelte';
	import BorderBeam from '$lib/components/magic/borderbeam/BorderBeam.svelte';
	import Button from '$lib/components/ui/button/button.svelte';
	import type { ObserverEventDetails } from 'svelte-inview';
	import { inview } from 'svelte-inview';
	import GoogleSvg from '$lib/imgs/Google.svg';
	import GitHubSvg from '$lib/imgs/GitHub.svg';
	import UberSvg from '$lib/imgs/Uber.svg';
	import MicrosoftSvg from '$lib/imgs/Microsoft.svg';
	import NotionSvg from '$lib/imgs/Notion.svg';
	import GemmaSvg from '$lib/imgs/gemma-logo.svg';
	import BertSvg from '$lib/imgs/bert-logo.svg';
	import DockerSvg from '$lib/imgs/docker-logo.svg';
	import PytorchSvg from '$lib/imgs/pytorch-logo.svg';
	import TensorflowSvg from '$lib/imgs/tensorflow-logo.svg';
	import n8nSvg from '$lib/imgs/n8n-logo.svg';
	import AppopsDarkImg from '$lib/imgs/appops-dark.png';
	import AppopsLightImg from '$lib/imgs/appops-light.png';
	import ITopsDarkImg from '$lib/imgs/itops-dark.png';
	import ITopsLightImg from '$lib/imgs/itops-light.png';
	import SecopsDarkImg from '$lib/imgs/secops-dark.png';
	import SecopsLightImg from '$lib/imgs/secops-light.png';
	import DevopsDarkImg from '$lib/imgs/devops-dark.png';
	import DevopsLightImg from '$lib/imgs/devops-light.png';
	let inView = false;
	const handleChange = ({ detail }: CustomEvent<ObserverEventDetails>) => {
		// console.log(detail);
		inView = detail.inView;
	};
</script>

<section id="hero" class="relative mx-auto mt-32 max-w-7xl px-6 text-center md:px-8">
<AnimatedShinyText class="inline-flex items-center justify-center">
			<span>Tired of subsidizing proprietary AI?</span>
		</AnimatedShinyText>
	<h2
		class="-translate-y-4 animate-fade-in text-balance bg-gradient-to-br from-black from-30% to-black/40 bg-clip-text py-6 text-5xl font-medium leading-none tracking-tighter text-transparent opacity-0 [--animation-delay:200ms] dark:from-white dark:to-white/40 sm:text-6xl md:text-7xl lg:text-8xl"
	>
		Embrace the <i>Open Source</i> AI Revolution
				
	</h2>
	<p
		class="mb-12 -translate-y-4 animate-fade-in text-balance text-lg tracking-tight text-gray-400 opacity-0 [--animation-delay:400ms] md:text-xl"
	>
		Retake control of your data, escape lock-in, and empower your team
		<br class="hidden md:block" />
		{' '}
		with cutting-edge AI use cases <i>for pennies on the dollar</i>
	</p>
<AnimatedShinyText class="inline-flex items-center justify-center">
			<span>✨ Schedule Free Consultation</span>
			{' '}
			<ArrowRightIcon
				class="ml-1 size-3 transition-transform duration-300 ease-in-out group-hover:translate-x-0.5"
			/>
		</AnimatedShinyText>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
</section>

<section id="clients" class="mx-auto max-w-7xl px-6 text-center md:px-8">
	<div class="py-14">
		<div class="mx-auto max-w-screen-xl px-4 md:px-8">
			<h2 class="text-center text-sm font-semibold text-gray-600">
				Tailor <i>New Gen</i> OSAI models and agentic workflow
			</h2>
			<h2 class="text-center text-sm font-semibold text-gray-600">
				automation tools to your specific business needs
			</h2>
		<br>
		<br>
		<br>
			<div class="mt-6">
				<ul
					class="flex flex-wrap items-center justify-center gap-x-10 gap-y-6 md:gap-x-16 [&_path]:fill-white"
				>
					<li>
						<img
							alt="Google"
							src={GoogleSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Microsoft"
							src={MicrosoftSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="GitHub"
							src={GitHubSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>

					<li>
						<img
							alt="Uber"
							src={UberSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Notion"
							src={NotionSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Gemma"
							src={GemmaSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Bert-logo"
							src={BertSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Docker-logo"
							src={DockerSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Pytorch"
							src={PytorchSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
					<li>
						<img
							alt="Tensorflow"
							src={TensorflowSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>

					<li>
						<img
							alt="n8n-logo"
							src={n8nSvg}
							class="h-8 w-28 px-2 dark:brightness-0 dark:invert"
							width={28}
							height={8}
						/>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>

<section id="hero" class="relative mx-auto mt-32 max-w-7xl px-6 text-center md:px-8">	

<div
		use:inview={{
			unobserveOnEnter: true,
			rootMargin: '-100px'
		}}
		on:inview_change={handleChange}
		class="relative mt-32 animate-fade-up opacity-0 [--animation-delay:400ms] [perspective:2000px] after:absolute after:inset-0 after:z-50 after:[background:linear-gradient(to_top,hsl(var(--background))_30%,transparent)]"
	>

		<div
			class="rounded-xl border border-white/10 bg-white bg-opacity-[0.01] before:absolute before:bottom-1/2 before:left-0 before:top-0 before:size-full before:opacity-0 before:[background-image:linear-gradient(to_bottom,var(--color-one),var(--color-one),transparent_40%)] before:[filter:blur(180px)] {inView
				? 'before:animate-image-glow'
				: ''}"
		>
			<BorderBeam
				size={200}
				duration={12}
				delay={0}
				colorFrom="var(--color-one)"
				colorTo="var(--color-two)"
			/>

			<img
				src={AppopsDarkImg}
				alt="AppOps- Enrich enterprise applications"
				class="relative hidden size-full rounded-[inherit] border object-contain dark:block"
			/>
			<img
				src={AppopsLightImg}
				alt="AppOps - Enrich enterprise applications"
				class="relative block size-full rounded-[inherit] border object-contain dark:hidden"
			/>
		</div>
	</div>


	<div
		use:inview={{
			unobserveOnEnter: true,
			rootMargin: '-100px'
		}}
		on:inview_change={handleChange}
		class="relative mt-32 animate-fade-up opacity-0 [--animation-delay:400ms] [perspective:2000px] after:absolute after:inset-0 after:z-50 after:[background:linear-gradient(to_top,hsl(var(--background))_30%,transparent)]"
	>

		<div
			class="rounded-xl border border-white/10 bg-white bg-opacity-[0.01] before:absolute before:bottom-1/2 before:left-0 before:top-0 before:size-full before:opacity-0 before:[background-image:linear-gradient(to_bottom,var(--color-one),var(--color-one),transparent_40%)] before:[filter:blur(180px)] {inView
				? 'before:animate-image-glow'
				: ''}"
		>
			<BorderBeam
				size={200}
				duration={12}
				delay={0}
				colorFrom="var(--color-one)"
				colorTo="var(--color-two)"
			/>

			<img
				src={ITopsDarkImg}
				alt="IT Operations - Reduce tedious admin tasks"
				class="relative hidden size-full rounded-[inherit] border object-contain dark:block"
			/>
			<img
				src={ITopsLightImg}
				alt="IT Operations - Reduce tedious admin tasks"
				class="relative block size-full rounded-[inherit] border object-contain dark:hidden"
			/>
		</div>
	</div>

<div
		use:inview={{
			unobserveOnEnter: true,
			rootMargin: '-100px'
		}}
		on:inview_change={handleChange}
		class="relative mt-32 animate-fade-up opacity-0 [--animation-delay:400ms] [perspective:2000px] after:absolute after:inset-0 after:z-50 after:[background:linear-gradient(to_top,hsl(var(--background))_30%,transparent)]"
	>

		<div
			class="rounded-xl border border-white/10 bg-white bg-opacity-[0.01] before:absolute before:bottom-1/2 before:left-0 before:top-0 before:size-full before:opacity-0 before:[background-image:linear-gradient(to_bottom,var(--color-one),var(--color-one),transparent_40%)] before:[filter:blur(180px)] {inView
				? 'before:animate-image-glow'
				: ''}"
		>
			<BorderBeam
				size={200}
				duration={12}
				delay={0}
				colorFrom="var(--color-one)"
				colorTo="var(--color-two)"
			/>

			<img
				src={SecopsDarkImg}
				alt="SecOps - Find and fix security issues"
				class="relative hidden size-full rounded-[inherit] border object-contain dark:block"
			/>
			<img
				src={SecopsLightImg}
				alt="SecOps - Find and fix security issues"
				class="relative block size-full rounded-[inherit] border object-contain dark:hidden"
			/>
		</div>
	</div>

	<div
		use:inview={{
			unobserveOnEnter: true,
			rootMargin: '-100px'
		}}
		on:inview_change={handleChange}
		class="relative mt-32 animate-fade-up opacity-0 [--animation-delay:400ms] [perspective:2000px] after:absolute after:inset-0 after:z-50 after:[background:linear-gradient(to_top,hsl(var(--background))_30%,transparent)]"
	>

		<div
			class="rounded-xl border border-white/10 bg-white bg-opacity-[0.01] before:absolute before:bottom-1/2 before:left-0 before:top-0 before:size-full before:opacity-0 before:[background-image:linear-gradient(to_bottom,var(--color-one),var(--color-one),transparent_40%)] before:[filter:blur(180px)] {inView
				? 'before:animate-image-glow'
				: ''}"
		>
			<BorderBeam
				size={200}
				duration={12}
				delay={0}
				colorFrom="var(--color-one)"
				colorTo="var(--color-two)"
			/>

			<img
				src={DevopsDarkImg}
				alt="DevopsDarkImage"
				class="relative hidden size-full rounded-[inherit] border object-contain dark:block"
			/>
			<img
				src={DevopsLightImg}
				alt="DevopsLightImage"
				class="relative block size-full rounded-[inherit] border object-contain dark:hidden"
			/>
		</div>
	</div>
</section>
