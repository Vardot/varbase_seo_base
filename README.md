# Varbase SEO Base

A recipe to manage default installed modules, configs and permissions for Varbase Search Engine Optimization (SEO) Core features and settings.

This recipe provides a complete SEO setup including:
- Meta tag management with Metatag module
- Schema.org structured data support
- Path aliases with Pathauto
- URL redirect management
- XML sitemap generation
- Yoast SEO integration for content optimization
- Script manager for tracking codes
- Entity clone for duplicating content

## Features

### Meta Tags & SEO
- **Metatag**: Comprehensive meta tag management with support for:
  - Facebook Open Graph tags
  - Twitter Cards
  - Mobile-specific tags
  - hreflang for multilingual sites
  - Verification tags for search engines
- **Schema.org**: Structured data support for:
  - Articles
  - Web Pages
  - Web Sites
  - Item Lists
- **Yoast SEO**: Real-time SEO content analysis and optimization

### URL Management
- **Pathauto**: Automatic URL alias generation based on patterns
- **Redirect**: Comprehensive redirect management with:
  - 404 error tracking and fixing
  - Domain-level redirects
  - Automatic redirects on content updates
  - Path normalization

### Sitemaps & Indexing
- **Simple Sitemap**: Automatic XML sitemap generation for:
  - Nodes (content)
  - Taxonomy terms
  - Menu links

### Analytics & Scripts
- **Script Manager**: Centralized management of tracking and analytics scripts

### Content Management
- **Entity Clone**: Duplicate content while preserving SEO settings

## Configuration

The recipe includes default configurations for:
- Metatag defaults for various entity types (nodes, taxonomy terms, users)
- 403/404 error pages with proper meta tags
- Pathauto patterns for clean URLs
- Redirect settings for optimal SEO
- Simple Sitemap settings for efficient crawling

## Permissions

The recipe configures SEO permissions for the following roles:
- **Editor**: Basic Yoast SEO access
- **Content Admin**: Basic Yoast SEO access
- **SEO Admin**: Full SEO management including redirects, meta tags, sitemaps, and scripts
- **Site Admin**: Full SEO management capabilities

## Installation

Add the recipe using composer:
```
composer require drupal/varbase_seo_base:~1.0.0
```

Change directory to `/web` or `/docroot`

Run the Drupal recipe bash script:
```
bash core/scripts/drupal recipe recipes/contrib/varbase_seo_base
```

or

Run the Drush recipe command:
```
drush recipe recipes/contrib/varbase_seo_base
```

## Maintainers

- [Vardot](https://www.drupal.org/vardot)

## License

GPL-2.0-or-later
