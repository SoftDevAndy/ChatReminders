# ChatReminders
Oxide Plugin for Rust, Used to remind newer players of features for the first few days of their time on the server.

## Configuring the plugin

The configuration file is found in

'''
config/ChatReminders.json
'''

Whenever you make a change to the plugin you will need to reload it using the following command.

'''
oxide.reload ChatReminders 
'''

The configuration file looks like this

'''
{
  "ALLOW_REMINDERS": true,
  "COLOR_TAG" : "#F5D76E",
  "LOGINS_REQUIRED" : 3,
  "REMINDER_DAYS_PERIOD" : 3,
  "TAG" : "[REMINDER]"
}
'''

**ALLOW_REMINDERS** lets you set if you wish to switch all reminders on or off using true or false.

**COLOR_TAG** is the hex value for the color tag that appears with the reminder message.

**LOGINS_REQUIRED** required is the integer for how many times a player must connect to the server before they stop recieving the messages in conjuction with..

**REMINDER_DAYS_PERIOD** is how many days (from the first time visted date) that the player will recieve reminders for

**TAG** is the text to prepends any reminder sent to the user
