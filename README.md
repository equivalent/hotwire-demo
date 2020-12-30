# Hotwire Rails app demo

based on video demo <https://hotwire.dev/> simmilar to
<https://github.com/hotwired/hotwire-rails-demo-chat>

But also contains my own experiments


## Notes:

```
bin/rails hotwire:install

rails webpacker:install # I'm using webpacker for StimulousJS


rails g scaffold room name:string
rails g model message room:references content:text
rails db:migrate
```

