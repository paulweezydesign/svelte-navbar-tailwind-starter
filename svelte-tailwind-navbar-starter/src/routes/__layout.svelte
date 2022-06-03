<script>
  import '../app.css';
</script>
 <a href="/">Home</a> | <a href="/">About</a> | <a href="/">Contact</a>
<slot />
<style>

  a {
    @apply text-violet-500 focus:text-violet-600 text-xl;
  }
</style>
