<script>
	import Poster from '$lib/components/Poster.svelte';
	import TagBlock from '$lib/components/TagBlock.svelte';
	import { Icon } from 'svelte-awesome';
	import { chevronDown, chevronRight } from 'svelte-awesome/icons';
</script>

<header class="flex-center relative w-full bg-shark" id="header">
	<Poster />
	<div class="relative mt-3 w-full">
		<div class="absolute left-0 right-0">
			<div class="flex w-full items-center justify-between px-4">
				<a href="https://pythonconferentie.nl">
					<img src="/logo-black.png" alt="Python Conference Logo" class="w-20" />
				</a>
				<div class="pr-1">
					<a class=" inline text-black" target="_blank" rel="noreferrer" href="/code-of-conduct"
						>Code of Conduct<Icon class="ml-4" data={chevronRight} scale={1} /></a
					>
				</div>
			</div>
		</div>

		<div class="mt-20 flex items-center justify-center">
			<a href="https://pythonconferentie.nl" class="w-96">
				<img src="/logo-sopra4.svg" alt="Python Conference Logo" class="" />
			</a>
		</div>
		<div class="mt-8 flex items-center justify-center">
			<TagBlock class="text-lg" backgroundColor="north">
				<div class="text-3xl font-bold">
					PYCON (NL)<span class="px-4">|</span><span class="pr-4 text-ordina">2024</span>
				</div>
			</TagBlock>
		</div>

		<!-- <a
					class="inline"
					target="_blank"
					rel="noreferrer"
					href="https://www.eventbrite.nl/e/tickets-python-conference-utrecht-715964698687"
				>
					<TagBlock class="text-lg" backgroundColor="fountain">
				<div class="flex flex-col">
					<div>tickets.get_yours_for_<span class="font-bold">free</span>()</div>
					<div class="text-xs italic">Registration ends October 8th 23:59</div>
				</div>
			    </TagBlock>
				</a> -->
		<div class="mt-14 flex justify-center">
			<a class="mb-10 inline" href="#info">
				<Icon class="text-white opacity-75" data={chevronDown} scale={3} />
			</a>
		</div>
	</div>
</header>
