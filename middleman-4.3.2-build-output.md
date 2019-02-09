```
middleman-4.3.2 [*detached*] ❯ bundle exec middleman build --verbose
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
       error  build/stylesheets/site.css
Error: File to import not found or unreadable: test.
        on line 1 of source/stylesheets/site.css.scss
>> @import "test";

   ^

/Volumes/Dev/personal/middleman-import-examples/middleman-4.3.2/source/stylesheets/site.css.scss:1
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/sassc-2.0.0/lib/sassc/engine.rb:49:in `render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/renderers/sass.rb:55:in `evaluate'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/tilt-2.0.9/lib/tilt/template.rb:109:in `render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/file_renderer.rb:79:in `render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/template_renderer.rb:184:in `_render_== Finishing Request: stylesheets/test.css (0.01s)
with_all_renderers'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/template_renderer.rb:147:in `block in render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/activesupport-5.0.7.1/lib/active_support/notifications.rb:166:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/util.rb:21:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/template_renderer.rb:146:in `render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/sitemap/resource.rb:154:in `render'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/rack.rb:112:in `process_request'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/rack.rb:66:in `block in call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/rack.rb:65:in `catch'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/rack.rb:65:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/urlmap.rb:68:in `block in call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/urlmap.rb:53:in `each'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/urlmap.rb:53:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-autoprefixer-2.10.0/lib/middleman-autoprefixer/extension.rb:53:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/head.rb:12:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/lint.rb:49:in `_call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/lint.rb:37:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/builder.rb:153:in `call'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/mock.rb:74:in `request'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/rack-2.0.6/lib/rack/mock.rb:56:in `get'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:232:in `block in output_resource'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/activesupport-5.0.7.1/lib/active_support/notifications.rb:166:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/util.rb:21:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:225:in `output_resource'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:487:in `call_with_index'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:458:in `process_incoming_jobs'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:440:in `block in worker'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:431:in `fork'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:431:in `worker'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:422:in `block in create_workers'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:421:in `each'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:421:in `each_with_index'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:421:in `create_workers'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:361:in `work_in_processes'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/parallel-1.13.0/lib/parallel.rb:267:in `map'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:137:in `output_resources'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:97:in `block in prerender_css'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/activesupport-5.0.7.1/lib/active_support/notifications.rb:166:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/util.rb:21:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:95:in `prerender_css'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:65:in `block in run!'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/activesupport-5.0.7.1/lib/active_support/notifications.rb:166:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/util.rb:21:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/builder.rb:64:in `run!'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_reference.rb:43:in `send_to'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/call_with.rb:76:in `call_with'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/contracts-0.13.0/lib/contracts/method_handler.rb:138:in `block in redefine_method'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-cli-4.3.2/lib/middleman-cli/build.rb:80:in `block in build'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/activesupport-5.0.7.1/lib/active_support/notifications.rb:166:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-core-4.3.2/lib/middleman-core/util.rb:21:in `instrument'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-cli-4.3.2/lib/middleman-cli/build.rb:79:in `build'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/command.rb:27:in `run'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:126:in `invoke_command'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:133:in `block in invoke_all'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:133:in `each'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:133:in `map'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:133:in `invoke_all'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/group.rb:232:in `dispatch'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:115:in `invoke'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor.rb:40:in `block in register'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/command.rb:27:in `run'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/invocation.rb:126:in `invoke_command'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor.rb:387:in `dispatch'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/thor-0.20.3/lib/thor/base.rb:466:in `start'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/middleman-cli-4.3.2/bin/middleman:70:in `<top (required)>'
/Users/stevensloan/.rbenv/versions/2.6.1/bin/middleman:23:in `load'
/Users/stevensloan/.rbenv/versions/2.6.1/bin/middleman:23:in `<top (required)>'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli/exec.rb:74:in `load'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli/exec.rb:74:in `kernel_load'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli/exec.rb:28:in `run'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli.rb:463:in `exec'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/vendor/thor/lib/thor/invocation.rb:126:in `invoke_command'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/vendor/thor/lib/thor.rb:387:in `dispatch'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli.rb:27:in `dispatch'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/vendor/thor/lib/thor/base.rb:466:in `start'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/cli.rb:18:in `start'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/bundler-1.17.2/exe/bundle:30:in `block in <top (required)>'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/2.6.0/bundler/friendly_errors.rb:124:in `with_friendly_errors'
/Users/stevensloan/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/gems/bundler-1.17.2/exe/bundle:22:in `<top (required)>'
/Users/stevensloan/.rbenv/versions/2.6.1/bin/bundle:23:in `load'
/Users/stevensloan/.rbenv/versions/2.6.1/bin/bundle:23:in `<main>'
      create  build/stylesheets/test.css
== Building files
== Request: /javascripts/site.js
== Request: /index.html
== Request: /images/.keep
== Finishing Request: javascripts/site.js (0.0s)
== Finishing Request: images/.keep (0.0s)
      create  build/javascripts/site.js
      create  build/images/.keep
== Finishing Request: index.html (0.01s)
      create  build/index.html
There were errors during this build
```