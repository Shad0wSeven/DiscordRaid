# DiscordRaid
Raiding method for discord servers

Created by Shad0w7#0320 for experimental purposes only, never used except in private servers with consenting friends.

Created for use to take down Discord servers.

## Method

Now, since most servers block the use of `@everyone` and `@here` as well as large role mentions, the only way to attack a server in this day and age is to manually ping every single person on the server, which cannot be stopped.

### Why this works

- It cannot be stopped by admins. Admins cannot stop a mass ping by a user, except with the use of bots, I'll get to this later. There is no function to stop messages from sending that have mass pings. Once a mass ping is sent, even if it is deleted, it will still be sent and ghost pings will occur, forcing users to respond anyways.
- It cannot be stopped by bots. Bots can recognize mass pings and delete messages, but this creates mass ghost pings. Dyno bot has a feature to auto ban mass pings, which could prove to be a problem, but with enough alternates, you could run through 5 in a single run. Assuming an average of 16 characters per username, this equates to 125 users pinged per message, and with a ban after 1 message, you can calculate how many alts will be needed. Program will output a textfile with exactly 2000 or less characters separated by `----------------` for use with multiple alts. Further testing with Dynobots auto ban will have to be conducted, but for now, an annoying ping, so around 20 pings, for around 1000 users, will requre 160 accounts with the feature on. One way to block this is to immediatly delete mass pings after sending, so mods can't figure out the reason for the pinging, and instead will just not turn on the feature.
- It cannot be stopped by individual users
While users can turn off role mentions and `@everyone`'s they cannot turn off individual pings.

### How to collect names

- Collecting names is farily easy, it requires one to just run selenium over a server in a trusted alt or main, and harvest the username data for the users.

### Creating Alts.

- Creating alts is also not too hard, as using Selenium and Live mail, one can just solve 180 captchas for 180 accounts, while doing something else in the background, while selenium is running, to create a very large amount of accounts. Live captcha is easier to solve than ReCaptcha. 

### Sending Messages

- Logging in to discord on many many accounts in new windows, via logging off and logging in, and then cycling through messages through alts in selenium, although figuring out how good Dyno is at autobanning, is up for contention.
