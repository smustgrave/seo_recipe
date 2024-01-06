# SEO Recipe

## What is a recipe?
From [initiatve page](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe.md#what-is-a-drupal-recipe)
Drupal recipes allow the automation of Drupal module install and configuration
via the user interface and via the Drupal recipe runner.
A Drupal recipe is a tool for Site Builders and Developers to add functionality
to a Drupal site. It is like a recipe that provides a series of steps to add
functionality. These steps could be taken manually to arrive at the same point.

## How to apply
`php core/scripts/drupal recipe recipes/contrib/drupal-base`

## Additional Configuration
This recipe will install some generic settings but SEO can be very unique per project. This is just to get started.

### Metatag
There are several submodules associated with metatag, based on your projects SEO needs additional ones may be 
installed. See [metatag module](https://www.drupal.org/project/metatag) for additional module info.

### Schema.org Metatag
There are several submodules associated with metatag, based on your projects SEO needs additional ones may be
installed. See [schema.org module](https://www.drupal.org/project/schema_metatag) for additional module info.
