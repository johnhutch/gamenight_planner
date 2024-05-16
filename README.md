# JENRY

Like John Henry, this machine builds new rails.

----

It's a starting point for new rails apps that has all the stuff we typically have to re-do every time. 

## Gems
* Devise: authentication
* Pundit: authorization
* Figaro: Proper env vars and deployment to heroku

## Frontend
* Bootstrap added the right way


# When Spinning Off a New Site

* In config/environments/production.rb, be sure to update `config.action_mailer.default_url_options = { host: 'tbd', port: 3000 }` to your actual production hostname
