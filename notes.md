- https://talks.mikerogers.io/videos/installing-ruby-on-rails
- https://guides.rubyonrails.org/configuring.html#configuring-a-database

```bash
bin/rails generate scaffold Product \
         title:string description:text image_url:string price:decimal
```

```bash
bin/rails db:migrate
```

```bash
git push -u origin main
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/costin-doctolib/depot.git/'
```

```bash
bin/rails server
```

```bash
bin/rails test
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/db/seeds.rb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/app/assets/images/
- https://www.vexels.com/png-svg/preview/196935/simple-crystal-icon

```bash
bin/rails db:seed
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/app/assets/stylesheets/products.scss

```bash
bundle
```

```bash
bundle info sassc-rails
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/app/views/layouts/application.html.erb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/app/views/products/index.html.erb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_a/.gitignore
- https://media.pragprog.com/titles/rails6/code/rails6/depot_b/app/models/product.rb
- https://api.rubyonrails.org/classes/ActiveSupport/TestCase.html
- http://docs.seattlerb.org/minitest
- https://media.pragprog.com/titles/rails6/code/rails6/depot_c/test/models/product_test.rb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_c/test/fixtures/products.yml
- https://media.pragprog.com/titles/rails6/code/rails6/depot_b/test/controllers/products_controller_test.rb

```bash
bundle add byebug --group 'development,test'
```

```bash
bin/rails generate controller Store index
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_d/app/views/store/index.html.erb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_d/app/assets/stylesheets/store.scss
- https://github.com/rails/turbolinks
- https://media.pragprog.com/titles/rails6/code/rails6/depot_e/app/assets/stylesheets/application.scss
- https://api.rubyonrails.org/classes/ActionView/Helpers/NumberHelper.html#method-i-number_to_currency
- https://media.pragprog.com/titles/rails6/code/rails6/depot_e/test/controllers/store_controller_test.rb
- https://github.com/rails/rails-dom-testing + https://edgeguides.rubyonrails.org/4_2_release_notes.html#assert-select

```bash
bin/rails test:controllers
```

```bash
bin/rails dev:cache
```

- https://signalvnoise.com/posts/3113-how-key-based-cache-expiration-works
- https://guides.rubyonrails.org/caching_with_rails.html

```bash
bin/rails generate scaffold Cart
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_f/app/controllers/concerns/current_cart.rb
- https://signalvnoise.com/posts/3372-put-chubby-models-on-a-diet-with-concerns

```bash
bin/rails generate scaffold LineItem product:references cart:belongs_to
```

```bash
bin/rails db:migrate
```

- https://media.pragprog.com/titles/rails6/code/rails6/depot_f/app/models/line_item.rb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_f/app/models/cart.rb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_f/app/models/product.rb
- https://media.pragprog.com/titles/rails6/code/rails6/depot_f/test/controllers/products_controller_test.rb
