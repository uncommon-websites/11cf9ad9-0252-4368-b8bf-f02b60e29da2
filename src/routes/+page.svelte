<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Find your next home before anyone else"
	subtitle="See rentals early with off-market listings."
	imageSrc="/generated/image-a-young-professional-couple-stands-outsi.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/remax.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coldwellbanker.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/century21.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kw.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Rodriguez",
			position: "Software Engineer",
			company: "CloudTech",
			quote:
				"I found my perfect apartment 2 weeks before it hit the market. Saved me $200/month compared to similar listings and avoided the bidding war stress completely.",
			image: "/generated/image-a-professional-headshot-of-a-smiling-you.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Marketing Manager",
			company: "StartupLab",
			quote:
				"Got early access to a premium downtown loft at below-market rent. The landlord was thrilled to skip the listing fees and I secured my dream place in 3 days instead of 3 months.",
			image: "/generated/image-a-professional-headshot-of-a-friendly-ma.webp"
		},
		{
			name: "Emma Larsson",
			position: "Product Designer",
			company: "DesignStudio",
			quote:
				"Found a rent-stabilized unit in my target neighborhood before it was even renovated. Saved 6 weeks of searching and got first pick of the best units in the building.",
			image: "/generated/image-a-professional-headshot-of-a-confident-w.webp"
		}
	]}
/>

<Features
	title="Why early access matters"
	subtitle="Never miss your perfect rental again"
	features={[
		{
			title: "See listings 7 days early",
			description: "Access off-market rentals before they hit Zillow or Apartments.com, giving you first choice of the best properties.",
			imageSrc: "/generated/image-a-young-professional-stands-in-a-sunlit-.webp"
		},
		{
			title: "Exclusive inventory network",
			description: "Tap into our growing network of landlords and property managers who share listings with us first.",
			imageSrc: "/generated/image-an-exclusive-apartment-building-with-dis.webp"
		},
		{
			title: "Smart rental alerts",
			description: "Get instant notifications for properties matching your criteria the moment they become available.",
			imageSrc: "/generated/image-a-young-person-receives-a-notification-o.webp"
		},
		{
			title: "Early adopter community",
			description: "Join a network of savvy renters who share insider tips and help each other find the best deals.",
			imageSrc: "/generated/image-a-diverse-group-of-young-professionals-e.webp"
		},
		{
			title: "Move faster than competition",
			description: "Apply and secure rentals while other platforms are still waiting for listings to go public.",
			imageSrc: "/generated/image-a-professional-woman-mid-30s-efficiently.webp"
		},
		{
			title: "Skip the rental market chaos",
			description: "Avoid bidding wars and endless scrolling by accessing quality listings before the crowds arrive.",
			imageSrc: "/generated/image-a-confident-young-person-walks-past-rent.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
