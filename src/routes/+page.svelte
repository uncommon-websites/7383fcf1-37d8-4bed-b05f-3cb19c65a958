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
	title="Find your medication in stock, without the endless calling"
	subtitle="We search nearby pharmacies for you. Most patients get results in 2-24 hours."
	imageSrc="/generated/image-a-candid-documentary-style-photograph-of.webp"
	callsToAction={[
		{
			href: "/start",
			label: "Find my medication"
		},
		{
			href: "/how-it-works",
			label: "How it works"
		}
	]}
/>
<LogoScroller
	label="Trusted by leading healthcare organizations"
	logoUrls={[
		'https://cdn.brandfetch.io/cvs.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/walgreens.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kaiserpermanente.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mayoclinic.org/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Medfinder solves the frustrating problem of medication shortages by searching pharmacy inventories for you. We serve patients who need prescriptions filled but can't find them in stock, eliminating hours of phone calls with our 99% success rate. Most patients receive results within 2-24 hours, with medications located at nearby pharmacies ready for pickup."
/>

<Testimonials
	testimonials={[
		{
			name: "Keisha Williams",
			position: "Parent",
			company: "Atlanta, GA",
			quote:
				"I spent three days calling pharmacies for my son's ADHD medication during the shortage. Medfinder found it in 18 hours. They called over 40 pharmacies for me and saved me from missing work again.",
			image: "/generated/image-1-professional-headshot-of-a-confident-a.webp"
		},
		{
			name: "David Chen",
			position: "Marketing Director",
			company: "Seattle, WA",
			quote:
				"After calling a dozen pharmacies myself with no luck, I tried Medfinder. Within 24 hours they located my prescription at a pharmacy 15 minutes from my office. Worth every penny to get those hours of my life back.",
			image: "/generated/image-professional-headshot-of-asian-american-.webp"
		},
		{
			name: "Maria Rodriguez",
			position: "Nurse",
			company: "Phoenix, AZ",
			quote:
				"Finding my specialty medication used to take a full day of phone calls every month. Medfinder consistently finds it in under 48 hours. The stress relief alone has been life-changing for managing my condition.",
			image: "/generated/image-professional-headshot-of-hispanic-woman-.webp"
		}
	]}
/>

<Features
	title="Why thousands of patients choose Medfinder"
	subtitle="We've helped 15,000+ patients find their medications with a 99% success rate"
	features={[
		{
			title: "99% success rate finding medications",
			description:
				"From specialty drugs to shortage medications, we locate what you need when local pharmacies come up empty. We'll call up to 50 pharmacies on your behalf.",
			imageSrc: "/generated/image-a-diverse-adult-patient-sits-at-a-cozy-k.webp"
		},
		{
			title: "Save hours of frustrating phone calls",
			description:
				"Stop wasting time calling pharmacy after pharmacy hoping someone has your medication in stock. We handle the entire search process for you.",
			imageSrc: "/generated/image-a-person-in-their-40s-or-50s-lounges-com.webp"
		},
		{
			title: "Nationwide pharmacy network",
			description:
				"We search pharmacies starting in your zip code and expand outward until we find your medication in stock. If it's available anywhere, we'll find it.",
			imageSrc: "/generated/image-a-pharmacist-with-a-caring-expression-th.webp"
		},
		{
			title: "Fast results when you need them",
			description:
				"Most patients get matched with a pharmacy within 2-24 hours. Even the hardest-to-find medications typically take just a few days.",
			imageSrc: "/generated/image-a-person-glances-at-their-phone-resting-.webp"
		},
		{
			title: "Money-back guarantee",
			description:
				"If we can't find your medication, you get a full refund. If it goes out of stock before pickup, we restart the search at no charge.",
			imageSrc: "/generated/image-a-patient-stands-in-a-comfortable-home-s.webp"
		},
		{
			title: "Your health information stays private",
			description:
				"HIPAA-compliant platform with encrypted connections ensures your personal and health information remains secure throughout the entire process.",
			imageSrc: "/generated/image-a-healthcare-professional-in-a-modern-we.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop wasting hours searching for your medication"
	subtitle="Get results in 2-24 hours"
	description="Join 15,000+ patients who found their medications with our 99% success rate. If we can't find it, you get a full refund. Most patients receive results within 24 hours—even for the hardest-to-find prescriptions."
	imageSrc="/generated/image-a-candid-documentary-style-image-of-a-pa.webp"
	callsToAction={[
		{
			href: "/start",
			label: "Find my medication",
			variant: "primary"
		},
		{
			href: "/how-it-works",
			label: "How it works",
			variant: "secondary"
		}
	]}
/>
