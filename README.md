# Specific Page Vue with Turbolinks Support

This is a simple Hello World app. It is a Ruby on Rails project that uses Vue.js for one specific page (hence it's name).

```
  yarn install
  rails webpacker:install
  rails webpacker:install:vue
  rails vue:setup
  yarn add vue-turbolinks
  rails db:migrate
  
  rails s
```

Redirect to `/pages` and you'll see "Hello World!"
