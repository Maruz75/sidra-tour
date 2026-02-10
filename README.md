# Astro SEO Starter

This project is an SEO-friendly website starter built with [Astro](https://astro.build).

## Key Features

- **SEO Optimized**: Pre-configured with `astro-seo` for easy meta tag management.
- **Sitemap**: Automatic sitemap generation using `@astrojs/sitemap`.
- **Robots.txt**: Standard configuration included.
- **Performance**: High performance by default with Astro.

## Deployment to Cloudflare Pages

1.  **Push to GitHub**:
    - Create a new repository on GitHub.
    - Push your code:
      ```bash
      git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
      git branch -M main
      git push -u origin main
      ```

2.  **Connect to Cloudflare Pages**:
    - Go to the [Cloudflare Dashboard](https://dash.cloudflare.com/) > **Pages**.
    - Click **Connect to Git**.
    - Select your new repository.
    - **Build Settings**:
        - **Framework preset**: `Astro`
        - **Build command**: `npm run build`
        - **Build output directory**: `dist`
    - Click **Save and Deploy**.

## Development

```bash
npm run dev
```
