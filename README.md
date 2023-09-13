# Hero Component

The **Hero Component** is a UI element typically found at the top of a webpage
or application. It serves as a menu or navigation tool, allowing users to
easily access different sections, pages, or features of the website or app.

With just a few lines of code, you can showcase site logo, site name and sitemap
details (sections and subsections).

## Preview

Here's an example of how the Hero Component might look when rendered:

### Hero

![hero.png](.github/assets/hero.png)



## Getting Started

To use the Hero Components in your `fastn` package, follow these steps:

1. **Add the Hero Dependency**: Open your `FASTN.ftd` file and add
   the following line to include the Hero component:
   ```ftd
   -- fastn.dependency: fastn-community.github.io/midnight-storm-hero
   ```

2. **Use the Hero Component**: In the file where you want to add
   the Hero (e.g., `index.ftd`), you can import the component and
   use it like this:
    ```ftd
   -- import: fastn-community.github.io/midnight-storm-hero as hero

   ;; First Variation
   -- hero.stack: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg

   lorem ipsum

   ;; Second Variation
   -- hero.left-stack: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg
   
   lorem ipsum

   ;; Third Variation
   -- hero.right-stack: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg
   
   lorem ipsum

   ;; Four Variation
   -- hero.heading-left: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg

   lorem ipsum

   ;; Five Variation
   -- hero.heading-right: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg

   lorem ipsum

   ;; Six Variation
   -- hero.heading-center: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   image: $assets.files.images.image.svg

   lorem ipsum

   ;; Seventh Variation
   -- hero.without-image: My Site
   cta-primary-text: View More
   cta-primary-url: /
   cta-secondary-text: Preview
   cta-secondary-url: /
   
   lorem ipsum
   ```

## Customization

Feel free to customize the business card by adding, removing, or modifying
fields.

## Fields

Feel free to reach out if you have any questions or need further assistance.


***Happy coding!***
