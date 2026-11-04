+++
template = "homepage.html"

[extra]
path_to_exp = "exp_edu/experience/_index.md"
path_to_edu = "exp_edu/education/_index.md"

meta = [
    { property = "og:title", content = "Apollo-portfolio" },
    { property = "og:description", content = "Un tema portfolio moderno e minimalista basato su Zola." },
    { property = "og:url", content = "https://example.com" },
    { property = "og:image", content = "https://example.com/image.png" },
]
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
    <p class="homepage-hero-subtitle">Un tema portfolio moderno e minimalista basato su Zola.</p>
</div>

# Avvio rapido

1.  **Aggiungi il tema come sottomodulo:**
    ```bash
    git submodule add https://github.com/lasercata/apollo-portfolio themes/apollo-portfolio
    ```
2.  **Configura il tuo `config.toml`:**
    Imposta `theme = "apollo-portfolio"` e aggiungi la configurazione del tuo sito.
3.  **Avvia il server Zola:**
    ```bash
    zola serve
    ```
