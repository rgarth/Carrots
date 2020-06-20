# Carrots

Golang KudosBot for Slack

## Installation

* Setup the Bots app <https://app.slack.com/apps/A0F7YS25R-bots?next_id=0>, save the token somewhere secret
* Create the MySQL db, I have included the commands I used
* Update the carrots.json file
* Build the app

    ```
    go get
    go build
    ```

* Run the app

    ```
    SLACKTOKEN=xoxb-... MYSQLPASS=... ./carrots
    ```

* Invite the bot to your channel