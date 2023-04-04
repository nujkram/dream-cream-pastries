<script>
    import About from '../lib/About.svelte';
	import Chef from '../lib/Chef.svelte';
	import Footer from '../lib/common/Footer.svelte';
    import Navbar from '../lib/common/Navbar.svelte';
	import Contact from '../lib/Contact.svelte';
	import Event from '../lib/Event.svelte';
	import Gallery from '../lib/Gallery.svelte';
	import Hero from '../lib/Hero.svelte';
	import Menu from '../lib/Menu.svelte';
	import Special from '../lib/Special.svelte';
	import Testimonial from '../lib/Testimonial.svelte';
	import WhyUs from '../lib/WhyUs.svelte';
</script>
  <Navbar/>

  <Hero/>

  <main id="main">

    <About/>

    <WhyUs/>

    <Menu/>

    <Special/>

    <Event/>

    

    <Testimonial/>

    <Gallery/>

    <Chef/>

    <Contact/>

  </main><!-- End #main -->

  <Footer/>