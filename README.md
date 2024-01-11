# SEO Recipe

See Packagist page https://packagist.org/packages/smustgrave/seo_recipe

## What is a recipe?
From [initiatve page](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe.md#what-is-a-drupal-recipe)
> Drupal recipes allow the automation of Drupal module install and configuration
via the user interface and via the Drupal recipe runner.
A Drupal recipe is a tool for Site Builders and Developers to add functionality
to a Drupal site. It is like a recipe that provides a series of steps to add
functionality. These steps could be taken manually to arrive at the same point.

## How to apply
`php core/scripts/drupal recipe recipes/contrib/seo_recipe`

## Additional Configuration
This recipe will install some generic settings but SEO can be very unique per project. This is just to get started.

### Easy Breadcrumb
Based configuration should be good but worth taking a look based on project needs.
See [Easy Breadcrumb](https://www.drupal.org/project/easy_breadcrumb) module page for additional module .info.

### External links
Based configuration should be good but worth taking a look based on project needs. 
See [External Liks](https://www.drupal.org/project/extlink) module page for additional module .info.

### Google Tag 
Google tag needs a specific ID to work, and configuration based on needs. Update configuration upon installing recipe.
See [Google Tag](https://www.drupal.org/project/google_tag) module page for additional module info.

### Metatag
There are several submodules associated with metatag, based on your projects SEO needs additional ones may be 
installed. See [metatag module](https://www.drupal.org/project/metatag) for additional module info.

### Pathauto
Based configuration should be good but worth taking a look based on project needs.
See [Pathauto](https://www.drupal.org/project/pathauto) module page for additional module .info.

### Schema.org Metatag
There are several submodules associated with metatag, based on your projects SEO needs additional ones may be
installed. See [schema.org module](https://www.drupal.org/project/schema_metatag) for additional module info.

### Simple XML sitemap
Configuration should be specific to each project. Recommend updating config based on needs upon applying recipe.
See [Simple XML Sitemap](https://www.drupal.org/project/simple_sitemap) for additional module info.

### Sitemap
Configuration should be specific to each project. Recommend updating config based on needs upon applying recipe.
See [sitemap](https://www.drupal.org/project/sitemap) for additional module info.

## Additional module recommendations

### [Search 404](https://www.drupal.org/project/search404)
Instead of showing a standard "404 Page not found", this module performs a search on the keywords in the URL.

For instance, if a user visits http://example.com/does/not/exist, this module will do a search for "does not exist"
and shows the result of the search instead of the 404 page.
