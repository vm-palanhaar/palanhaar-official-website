<script>

</script>

<header class="flex flex-col relative z-20 header-bg">
    <div class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6">
        <a href="/" class="flex flex-col">
            <h1 class="font-semibold text-2xl tracking-wide text-blue-900">Palanhaar</h1>
            <h1 class="font-semibold text-yellow-400 text-lg tracking-wide">Solutions</h1>
        </a>
        <button class="md:hidden grid place-items-center text-blue-900 hover:text-yellow-400 transition-colors duration-200">
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a href="/our-story" class="duration-200 hover:text-yellow-400 cursor-pointer font-medium text-blue-900">Our story</a>
            <a href="/" class="duration-200 hover:text-yellow-400 cursor-pointer font-medium text-blue-900">Ideas</a>
            <a href="/" class="duration-200 hover:text-yellow-400 cursor-pointer font-medium text-blue-900">Insights</a>
            <a href="/contact-us" class="duration-200 hover:text-yellow-400 cursor-pointer font-medium text-blue-900">Contact us</a>
        </nav>
    </div>
</header>

<style>
.header-bg {
  background: linear-gradient(90deg, #f9f9f9 0%, #fffbe6 100%);
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}
a:hover {
  text-decoration: underline;
}
</style>