# rails-templates
Quickly generate a rails app with the default [Wagon](https://www.lewagon.com) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).


## Minimal

Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  --database postgresql \
  -m https://raw.githubusercontent.com/lewagon/rails-templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

## Devise

Same as minimal **plus** a Devise install with a generated `User` model and Rspec config.

```bash
rails new \
  --database postgresql \
  -m https://raw.githubusercontent.com/matlopes-lab/rails-templates/main/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
