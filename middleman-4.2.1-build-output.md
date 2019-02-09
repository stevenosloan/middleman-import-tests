```
middleman-4.2.1 [*detached*] ❯ bundle exec middleman build --verbose
== Activating: file_watcher
== Activating: front_matter
== Activating: data
== Activating: inline_url_rewriter
== Activating: sitemap_ondisk
== Activating: sitemap_import
== Activating: sitemap_endpoint
== Activating: sitemap_proxies
== Activating: sitemap_redirects
== Activating: sitemap_move_files
== Activating: sitemap_ignore
== Activating: external_helpers
== Activating: erb_renderer
== Activating: coffee_renderer
== Activating: haml_renderer
== Activating: sass_renderer
== Activating: markdown_renderer
== Failed Activation `liquid_renderer` : cannot load such file -- liquid
== Failed Activation `slim_renderer` : cannot load such file -- slim
== Failed Activation `less_renderer` : cannot load such file -- less
== Failed Activation `stylus_renderer` : cannot load such file -- stylus
== Activating: default_helpers
== Activating: lorem
== Activating: routing
== Activating: collections
== Change (#<Set: {:source}>): index.html.erb
== Change (#<Set: {:source}>): images/.keep
== Change (#<Set: {:source}>): layouts/layout.erb
== Change (#<Set: {:source}>): javascripts/site.js
== Change (#<Set: {:source}>): stylesheets/test.css.scss
== Change (#<Set: {:source}>): stylesheets/site.css.scss
== Rebuilding resource list
== Reading: Local config: config.rb
== Activating: autoprefixer
== Requesting resource list rebuilding: first_run_change_page
== Requesting resource list rebuilding: first_run_change_page
== Requesting resource list rebuilding: first_run_change_page
Loaded extensions:
== Extension: file_watcher
== Extension: front_matter
== Extension: data
== Extension: inline_url_rewriter
== Extension: sitemap_ondisk
== Extension: sitemap_import
== Extension: sitemap_endpoint
== Extension: sitemap_proxies
== Extension: sitemap_redirects
== Extension: sitemap_move_files
== Extension: sitemap_ignore
== Extension: external_helpers
== Extension: erb_renderer
== Extension: coffee_renderer
== Extension: haml_renderer
== Extension: sass_renderer
== Extension: markdown_renderer
== Extension: default_helpers
== Extension: lorem
== Extension: routing
== Extension: collections
== Extension: autoprefixer
== Change (#<Set: {:source}>): index.html.erb
== Change (#<Set: {:source}>): images/.keep
== Change (#<Set: {:source}>): layouts/layout.erb
== Change (#<Set: {:source}>): javascripts/site.js
== Change (#<Set: {:source}>): stylesheets/test.css.scss
== Change (#<Set: {:source}>): stylesheets/site.css.scss
== Rebuilding resource list
== Requesting resource list rebuilding: touched_file
== Requesting resource list rebuilding: registered_new_manipulator_front_matter
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_ondisk
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_import
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_endpoint
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_proxies
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_redirects
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_move_files
== Requesting resource list rebuilding: registered_new_manipulator_sitemap_ignore
== Requesting resource list rebuilding: registered_new_manipulator_routing
== Requesting resource list rebuilding: registered_new_manipulator_routing
== Requesting resource list rebuilding: registered_new_manipulator_collections
== Rebuilding resource list
== Running manipulator: sitemap_ondisk (0)
== Running manipulator: sitemap_endpoint (0)
== Running manipulator: sitemap_proxies (0)
== Running manipulator: sitemap_redirects (0)
== Running manipulator: sitemap_ignore (0)
== Running manipulator: sitemap_import (1)
== Running manipulator: routing (10)
== Running manipulator: front_matter (20)
== Running manipulator: sitemap_move_files (101)
== Running manipulator: collections (110)
== Running manipulator: routing (130)
== Prerendering CSS
== Request: /stylesheets/site.css
== Request: /stylesheets/test.css
== Finishing Request: stylesheets/test.css (0.01s)
== Finishing Request: stylesheets/site.css (0.01s)
   identical  build/stylesheets/test.css
     updated  build/stylesheets/site.css
== Building files
== Request: /images/.keep
== Request: /javascripts/site.js
== Request: /index.html
== Finishing Request: images/.keep (0.0s)
== Finishing Request: javascripts/site.js (0.0s)
   identical  build/images/.keep
   identical  build/javascripts/site.js
== Finishing Request: index.html (0.01s)
   identical  build/index.html
Project built successfully.
```

Success here is a lie, look at the output for the site.css file.