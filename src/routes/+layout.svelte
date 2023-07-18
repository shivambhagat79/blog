<script>
    import "../app.css";
    import Navbar from "../components/Navbar.svelte";
    import Footer from "../components/Footer.svelte";
    export const prerender = true;
</script>

<Navbar />

<slot />

<Footer />