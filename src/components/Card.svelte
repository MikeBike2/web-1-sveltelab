<script>
    import Picture from './Picture.svelte';
    import Details from './Details.svelte';
</script>

<section>
    <Picture />
    <Details />
</section>

<style>
    section {
        display: flex;
        border: 1px solid black;
        padding: 1.5em;
        gap: 1em;
    }
</style>
