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
	centered={false}
	title="Verify once, never ask for a discount again"
	subtitle="Automatic military discounts for San Diego's military community. Link your card, shop anywhere, and save without the awkward conversation."
	imageSrc="/generated/image-a-diverse-military-familyparents-and-chi.webp"
	callsToAction={[
		{
			href: "#download",
			label: "Download app"
		},
		{
			href: "#how-it-works",
			label: "How it works"
		}
	]}
/>
<LogoScroller
	label="Trusted by military-friendly businesses"
	logoUrls={[
		'https://cdn.brandfetch.io/homedepot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/starbucks.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/target.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/24hourfitness.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Valor eliminates the awkward discount conversation for San Diego's military community. Through one-time verification and secure card-linking, active duty members, veterans, and their families automatically receive military discounts at participating businesses without ever asking. We're building financial dignity for those who've served."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "Military Spouse",
			company: "San Diego",
			quote:
				"I used to feel so awkward asking for military discounts, especially as a spouse. With Valor, I've saved over $800 in six months without that uncomfortable moment at checkout. It just works automatically.",
			image: "/generated/image-professional-headshot-of-a-confident-mil.webp"
		},
		{
			name: "James Chen",
			position: "Navy Veteran",
			company: "San Diego",
			quote:
				"I was skeptical about linking my card, but Valor's bank-grade security put my mind at ease. Now I'm saving $150+ monthly at places I already shop. The app found discounts at stores I didn't even know offered them.",
			image: "/generated/image-professional-headshot-of-a-friendly-vete.webp"
		},
		{
			name: "Taylor Williams",
			position: "Active Duty",
			company: "San Diego",
			quote:
				"Before Valor, I'd skip asking for discounts when I was in a hurry or the line was long. Now I never miss out. The app has saved me 20+ hours of awkward conversations and $600 this year alone.",
			image: "/generated/image-professional-headshot-of-an-approachable.webp"
		}
	]}
/>

<Features
	title="Built for military families who deserve better"
	subtitle="No more uncomfortable conversations, no point-of-sale interaction, no hassle. Just automatic savings that recognize your service."
	features={[
		{
			title: "Never ask for a discount again",
			description:
				"Verify your military status once and receive automatic discounts at participating San Diego businesses without the awkward conversation. Shop with dignity while your linked card does the work."
		},
		{
			title: "Completely automatic savings",
			description:
				"Our card-linked technology applies discounts instantly when you shop at participating merchants. No coupons to clip, no apps to open at checkout, no staff interaction required."
		},
		{
			title: "Bank-grade security you can trust",
			description:
				"Your data is protected with AES encryption used by major financial institutions. We never sell or share your personal information, and your privacy is our priority."
		},
		{
			title: "Free for all military families",
			description:
				"Active duty, veterans, and military spouses get lifetime access at zero cost. We believe those who serve shouldn't pay to access the discounts they've earned."
		},
		{
			title: "Growing San Diego merchant network",
			description:
				"From restaurants and retail to services and entertainment, discover military-friendly businesses across San Diego. 61% of military shoppers visit stores more often when discounts are available."
		},
		{
			title: "One-time verification, lifetime access",
			description:
				"Complete a simple verification process once and enjoy automatic discounts forever. No repeated ID checks, no proving your service at every store, no hassle."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join 1,000+ San Diego military families"
	subtitle="Shopping with dignity"
	description="Download the free Valor app today and never ask for a military discount again. Bank-grade security, one-time verification, and automatic savings at participating merchants. Your service deserves recognition without the awkward conversation."
	imageSrc="/generated/image-a-confident-happy-military-family-member.webp"
	callsToAction={[
		{
			href: "https://apps.apple.com/app/valor",
			label: "Download for iOS",
			variant: "primary"
		},
		{
			href: "https://play.google.com/store/apps/details?id=com.valor",
			label: "Download for Android",
			variant: "secondary"
		}
	]}
/>
