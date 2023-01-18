# Blog

A basic blog application with articles, comments and reactions. Everything will be updated dynamicaly using hotwire. You can try this on your local machine with the following commands in order

```bash
  1.In one terminal window
    a. gh repo clone Emmanu-Varghese/blog-prototype
    b. cd blog-task
    c. bundle install
    d. rails db:create
    e. rails db:migrate
    f. rails db:seed
    g. rails assets:precompile
    h. rails s
 2.In another terminal window(optional)
    a. bundle exec sidekiq
```
