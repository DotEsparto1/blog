# Blog

A basic blog application with articles, comments and reactions. Everything will be updated dynamicaly using hotwire.

1.In one terminal window
  a. gh repo clone Emmanu-Varghese/blog-task
  b. cd blog-task
  c. bundle install
  d. rails db:create
  e. rails db:migrate
  f. rails db:seed
  g. rails assets:precompile
  h. rails s
 
2. In another terminal window(optional)
  a. bundle exec sidekiq
