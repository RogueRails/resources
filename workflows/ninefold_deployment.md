# Deployment to Ninefold

Add postgres to your Gemfile in the production group:

```
  group :production do
    gem 'pg'
  end
```

Move (not duplicate) the mysql2 gem to the development/test group.  Note: the ellipses are meant to represent the rest of the gem list in that group.

```
  group :development, :test do
    gem 'mysql2'
    ...
  end
```

Update your local gemset from WITHIN the vagrant box:

` $ bundle install --without production `

Push your changes to the github repository

` git push origin master `

Follow the Ninefold guides for additional deployment steps:

[Deploying Steps](https://help.ninefold.com/entries/22057914-How-to-Deploy-an-App)
