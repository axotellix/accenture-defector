
<!-- [ SCRIPT ] -->
<script>

    // [ IMPORTS: components ]
    import Sidebar from '../components/Sidebar.svelte'

</script>


<!-- [ TEMPLATE: __layout ] -->

<!-- [ partial: sidebar ] -->
<Sidebar />

<!-- [ partial: main ] -->
<main>
    <slot></slot>
</main>
