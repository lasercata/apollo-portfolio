+++
template = "homepage.html"
+++

<style>
.homepage-hero {
    text-align: center;
    padding: 2rem 0;
}

.homepage-hero-title {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.homepage-hero-subtitle {
    font-size: 1.25rem;
    margin-bottom: 1rem;
}

</style>

<div class="homepage-hero">
    <h1 class="homepage-hero-title">Apollo-portfolio</h1>
    <p class="homepage-hero-subtitle">A modern and minimalistic portfolio theme powered by Zola.</p>
</div>

# Quick Start

1.  **Add the theme as a submodule:**
    ```bash
    git submodule add https://github.com/lasercata/apollo-portfolio themes/apollo-portfolio
    ```
2.  **Configure your `config.toml`:**
    Set `theme = "apollo-portfolio"` and add your site's configuration.
3.  **Start the Zola server:**
    ```bash
    zola serve
    ```
