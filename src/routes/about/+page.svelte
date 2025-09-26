<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Early access advantage",
			description: "We believe renters deserve first access to great listings before the competition arrives."
		},
		{
			title: "Direct connections",
			description: "Cutting through the noise by connecting renters directly with property owners and managers."
		},
		{
			title: "Community growth",
			description: "Building a network where every new member makes the platform stronger for everyone."
		}
	];
</script>

<SecondaryHero
	title="Get ahead of the market"
	subtitle="Find rentals before they go public"
	imageSrc="/generated/image-a-group-of-young-professionals-in-their-.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Good rentals disappear fast. By the time they reach listing sites, they're already taken. You refresh, set alerts, and still miss out. It's frustrating, competitive, and exhausting for anyone searching for a new home.",
		"Company was built for renters who are tired of coming in last. We give you access to off-market listings directly from agents, landlords, and property managers. These are listings you won't find on traditional platforms—because they're not public yet. Our growing network and early-access model mean you're first in line before competition even knows the listing exists.",
		"We're on a mission to reshape the $50B rental market—starting with renters who want a smarter way to search. Our goal is to bring 1 million users into a faster, fairer, and more efficient rental experience fueled by exclusive data and network effects. Renting shouldn't feel like a race you're always losing. With Company, you're finally ahead."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed as no company team/investor information is available -->

<!-- CTA Section -->
<CallToAction
	title="Stop missing out on great rentals"
	subtitle="Get early access today"
	description="Join thousands of renters who see listings before they hit the market. No more bidding wars, no more missed opportunities. Just early access to the rentals you want."
	imageSrc="/generated/image-candid-medium-shot-of-a-young-profession.webp"
/>
