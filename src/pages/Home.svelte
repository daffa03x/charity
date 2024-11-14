<script>
    import Header from "../components/Header.svelte";
    import Welcome from "../components/Welcome.svelte";
    import Footer from "../components/Footer.svelte";
    import CharityList from "../components/CharityList.svelte";
    import Promo from "../components/Promo.svelte";
    import charities from "../data/charities.js";
</script>

    <Header />
    <Welcome />
    <CharityList charities={charities}/>
    <Promo />
    <Footer />