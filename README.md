# Lautus Tech

![social-preview-image](https://user-images.githubusercontent.com/3909046/219942674-9894853e-def8-4180-84b8-6b577dacfcaa.png)

Accessible Astro Starter is a ready to use, SEO and a11y friendly blogging theme. It
contains plenty of accessible components to build several page types, Tailwind CSS to
help you build faster and example pages such as a dynamic Blog, 404, Markdown and MDX.
This theme is designed to help you build your project faster and provide a solid base
for accessibility!

🚀 [Live Preview](https://accessible-astro.netlify.app/)

## ♿ (Accessibility) Features

- Tailwind CSS support
- Prettier integration with `prettier-plugin-astro` and `prettier-plugin-tailwind`
- ESLint integration with strict accessibility settings for `eslint-plugin-jsx-a11y`
- Markdown and MDX support with examples included in the theme
- Uses the awesome `astro-icon` package for the icons
- Excellent Lighthouse/PageSpeed scores
- Accessible landmarks such as `header`, `main`, `footer`, `section` and `nav`
- Outline focus indicator which works on dark and light backgrounds
- Several `aria` attributes which provide a better experience for screen reader users
- `[...page].astro` and `[post].astro` demonstrate the use of dynamic routes and provide
  a basic blog with breadcrumbs and pagination
- `404.astro` provides a custom 404 error page which you can adjust to your needs
- `Header.astro` component included in the `DefaultLayout.astro` layout
- `Footer.astro` component included in the `DefaultLayout.astro` layout
- `SkipLinks.astro` component to skip to either the main menu or the main content
- `Navigation.astro` component with keyboard accessible (dropdown) navigation (arrow
  keys, escape key)
- `ResponsiveToggle.astro` component with an accessible responsive toggle button for the
  mobile navigation
- `DarkMode.astro` component toggle with accessible button and a user system preferred
  color scheme setting
- `SiteMeta.astro` SEO component for setting custom meta data on different pages
- `.sr-only` utility class for screen reader only text content (hides text visually)
- `prefers-reduced-motion` disables animations for users that have this preference
  turned on
- Ships with many components such as Accordions, Breadcrumbs, Modals,
  Pagination [and many more](https://accessible-astro.dev/accessible-components)
- A collection of utility classes such as breakpoints, button classes, font settings,
  resets and outlines in `src/assets/scss/base`

## 🚀 Getting started

Clone this theme locally and run any of the following commands in your terminal:

| Command           | Action                                       |
|:------------------|:---------------------------------------------|
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |
