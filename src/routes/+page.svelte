<script>
 
import Card from '../components/card.svelte';
import Sidebar from '../components/sidebar.svelte';
import Footer from '../components/footer.svelte';
import Header from '../components/header.svelte';

</script>
<header>
     
    <Header/>
</header>



<section>
<Card/>
<Card/>
</section>
<style>
    section {
        display: flex;
    }
    header {
        display: flex;
        justify-content: center;
        border: 3px solid black;
        
    }
</style>