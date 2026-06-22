# Baklib CMS — Shop theme

A professional **product help center, product manual, operating instructions, video tutorial, and FAQ** theme for Baklib-powered sites. It ships with responsive templates, grouped product category listings, product manuals with tabbed sub-page content, download cards, FAQ accordion lists, search capabilities, and Tailwind CSS–based styling.

Template Git URL: https://github.com/baklib-templates/shop

---

## Features

- **Home** (`templates/index.liquid`): Custom hero search with expandable AI Search integration, followed by configurable homepage sections (FAQs, Products, Topics, Downloads, and Contacts) with support for titles and descriptions.
- **Product details** (`templates/product.liquid`): Title, description, covers, rich-text product introduction, tag navigation, dynamic external action button (e.g. "Shop Now" or "Contact US"), and a tabbed navigation bar for quick access to child pages (FAQs, manuals, videos, downloads).
- **Channels**: 
  - Products category listing (`templates/products.liquid`)
  - Video lists (`templates/videos.liquid` & `templates/video.liquid`)
  - FAQ accordion lists (`templates/faqs.liquid`)
  - Download resource lists (`templates/downloads.liquid`)
- **Settings**: Complete configuration schema in `config/settings_schema.json`, storefront locales in `locales/*.json`, and editor schema translations in `locales/*.schema.json`.

---

## Project Structure

| Path                          | Purpose                                                         |
| ----------------------------- | --------------------------------------------------------------- |
| `templates/`                  | Page and channel templates                                      |
| `snippets/`                   | Reusable partials / Snippets (navigation, footer, grids)        |
| `statics/`                    | Static layout pages (about, sitemap)                            |
| `layout/`                     | `theme.liquid` site shell                                       |
| `config/settings_schema.json` | Theme settings schema                                           |
| `locales/`                    | UI strings (`*.json`) and schema translations (`*.schema.json`) |
| `seeds/`                      | Sample site data (default English)                              |
| `assets/`                     | Built CSS/JS resources                                          |
| `src/`                        | Tailwind CSS and JavaScript sources                             |

---

## Preview

|                   Home                    |                  Product Detail                   |
| :---------------------------------------: | :-----------------------------------------------: |
| ![Home](assets/images/theme/en/index.webp) | ![Product](assets/images/theme/en/product.webp)  |
|               **FAQ List**                |                  **Video Hub**                    |
| ![FAQs](assets/images/theme/en/faqs.webp)  |  ![Videos](assets/images/theme/en/videos.webp)    |

---

## Installation

Find "Shop" in the Baklib template marketplace, click install, and configure your site settings.

|                 1. Select and Install Theme                 |                    2. Basic Index Settings                    |               3. Pages & Channel Configuration                 |
| :---------------------------------------------------------: | :-----------------------------------------------------------: | :------------------------------------------------------------: |
| ![Install Theme](assets/images/guides/001_install-site.png) | ![Index Settings](assets/images/guides/002_index-settings.png) | ![Pages Configuration](assets/images/guides/003_pages.png)     |

---

## Other Documents

- Chinese Overview: [README.zh-CN.md](./README.zh-CN.md)
- Theme Help: [www.baklib.ai/themes](https://www.baklib.ai/themes/shop)
