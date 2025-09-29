# Personal Blog with Minimal Mistakes

This repository hosts my personal site built with the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme.

## Getting Started

1. Install Ruby and Bundler if they are not already available.
2. Install dependencies:

   ```sh
   bundle install
   ```

3. Run the local development server:

   ```sh
   bundle exec jekyll serve
   ```

4. Open <http://localhost:4000> in your browser.

## Content Structure

- `index.md` – Home page using the theme's `home` layout.
- `_posts/` – Markdown posts using standard Jekyll naming.
- `_pages/` – Stand-alone pages like About and archives.
- `_data/navigation.yml` – Controls the main navigation menu.
- `assets/css/main.scss` – Imports the Minimal Mistakes theme skin and allows custom styles.

Update `_config.yml` with your own details (title, description, social links, etc.) before publishing.
