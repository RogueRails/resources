# Deployment to Ninefold

Add postgres to your Gemfile in the production group:

```
  group :production do
    gem 'pg'
  end
```

Update your local gemset from WITHIN the vagrant box:

` $ bundle install --without production `

Push your changes to the github repository

` git push origin master `

Follow the Ninefold guides for additional deployment steps:

[Deploying Steps](https://help.ninefold.com/entries/22057914-How-to-Deploy-an-App)