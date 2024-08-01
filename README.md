## LA Referencia Product Information Site Template

This template is designed to create information sites for products on LA Referencia. It is built using Jekyll, a static site generator, and follows a modular structure for easy customization.

### Features

- Responsive design: The template is optimized for different screen sizes and devices.
- Product showcase: Display detailed information about the product, including images, descriptions, specifications, and pricing.
- Documentation: Provide comprehensive documentation for the product, including installation instructions, usage guidelines, and troubleshooting tips.
- Customizable layout: Easily modify the layout and styling of the site to match the product's branding.
- SEO-friendly: The template includes meta tags and structured data to improve search engine visibility.

### Getting Started

To use this template, follow these steps:

0. Install ruby (tested with v3.2)
1. Clone the repository: `git clone https://github.com/lareferencia/lareferencia-ghpages-template.git`
2. Install Jekyll: `gem install jekyll`
3. Navigate to the template directory: `cd lareferencia-ghpages-template`
4. Install requirements `bundle install`                                                         
5. Customize the site by editing the configuration files and adding your product content.
6. Serve development site `bundle exec jekyll serve`
7. Build the site: `bundle exec jekyll build`
8. Deploy the site to your preferred hosting platform.

### Directory Structure

The template follows the following directory structure:

- `_config.yml`: Stores configuration data. Many of these options can be specified from the command line executable but it’s easier to specify them here so you don’t have to remember them.
- `_data/`: This directory is for YAML, JSON, and CSV files. When these files are added here, they can be used throughout your site.
- `_includes/`: This directory is for snippets of code that you can include in your layouts.
- `_layouts/`: This directory is for your layouts. Layouts are chosen on a post-by-post basis in the front matter, which is described in the next section.
- `_pages/`: This directory is for your pages.
- `_posts/`: This directory is for your posts.
- `.gitattributes`: Git attributes file.
- `.github/`: This directory is for GitHub configuration files.
- `.gitignore`: Specifies intentionally untracked files that Git should ignore.
- `404.html`: This file is a custom error page.

- `assets/`: This directory is for your assets such as images and stylesheets.

- `Gemfile`: This file is used by Ruby's dependency manager, Bundler.

- `Gemfile.lock`: This file is where Bundler records the exact versions that were installed. This way, all copies of the app will use the same exact versions of all gems.

- `index.md`: This file is your homepage.

- `jekyll.thor`: This file is a script that can be run from the command line.

- `README.md`: This file is a brief introduction to your project.

- `sitemap.xml`: This file is a list of pages of a website accessible to crawlers or users.