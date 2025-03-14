<script lang="ts">
	import { LoaderIcon, CheckIcon } from 'lucide-svelte';
	import Switch from '$lib/components/ui/switch/switch.svelte';
	import Button from '$lib/components/ui/button/button.svelte';
	import { cn } from '$lib/utils';
	import { fly } from 'svelte/transition';
	import AnimatedShinyText from '$lib/components/magic/AnimatedShinyText/AnimatedShinyText.svelte';

</script>

<section id="pricing">
	<div class="mx-auto flex max-w-screen-xl flex-col gap-8 px-4 py-14 md:px-8">
		<div class="mx-auto max-w-5xl text-center">
			
			<h3 class="text-5xl font-bold tracking-tight text-black dark:text-white sm:text-6xl">
				World Class Resources
			</h3>

			<p class="mt-6 text-xl leading-8 text-black/80 dark:text-white">
				Torgen's <i>Open-Source-first</i> approach to AI transformation is driven by US-based consultants with proven track records for innovation spanning finance, healthcare, manufacturing, logistics, digital media and SaaS.
			</p>
<br>
<br>
<br>
<br>
			<div><h4 class="text-xl font-bold tracking-tight text-black dark:text-white">Flexible Solutions for Companies of All Sizes: </h4></div>
				<br>
				<div><AnimatedShinyText class="inline-flex items-center justify-center">
				<span><h2>AI Strategy Assessment</h2></span>
				</AnimatedShinyText>
				</div>
				<div><p><span><i>e.g., alignment with future state drivers, use case productivity/cost-savings analysis.</i></span></p>
				</div>

			<li><strong>AI Security Assessment</strong> -e.g., data security, identity and access, activity logging, governance and regulatory compliance.</li>

		</div> 	

</section>
