<script>
    import "../app.css";
</script>

<div class="wrapper">
    <div class="">
        <slot />
    </div>
</div>

<style>

    /* @font-face {
      font-family: 'Virgil';
      src: url('/Virgil.woff2') format('woff2'), /* Modern Browsers */
           /* url('/Virgil.woff') format('woff'); /* Older Browsers */
      /* Add more src entries if you have additional font file formats */
    /*} */

    .wrapper {
        width: 100%;
        height: 100%;
        /* font-family: 'Virgil',  sans-serif; */
        font-family: 'Cantarell', sans-serif;
    }

    .container {
        width: 100%;
        max-width: 100%;
        margin: 0 auto;
    }
</style>
