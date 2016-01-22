# Lunch-Slack
Post the Norwegian Lunch comic (www.lunchstriper.no) to a slack channel once a week.

![img](http://www.tu.no/migration_catalog/2009/06/25/lunchgjengen0906251112.jpg/alternates/h1080/Lunchgjengen0906251112.jpg)

## Instructions
* Setup appropriate incoming webhooks for your Slack channel.
* Download the Dilbert-Slack application.
* Edit the configurations in the index.js.
* Push the Lunch-Slack application to Heroku.
* Done.
<hr>

## Setup appropriate incoming webhooks for your Slack channel.
* In Slack Home, goto integrations
* Add Incoming webhook
* Select your hook channel
* Configure your channel hook

### Edit the configurations in the index.js.
The index.js file contains important configurations that need to be updated appropriately. **The Lunch-Slack application will not work out of the box.**

###Push the Lunch-Slack application to Heroku.
Dilbert-Slack is not completely contingent on Heroku. You can use other hosting providers such as Digital Ocean, Rackspace, or Modulus, however it does contain the necessary files to be seamlessly running in Heroku.
