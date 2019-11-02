# Doctor Moderation

Doctor Modération is a French bot to moderate the server [Les Laboratoires JS](https://discord.gg/3vC2XWK) on Discord.

# Features

- [x] Ban command
- [x] Kick command
- [x] Ping command
- [x] Help command
- [ ] Clear command
    - [ ] Specific user
    - [ ] From users
    - [ ] Froms bots
    - [ ] Before / after
    - [ ] Regex
    - [ ] Include
    - [ ] Image
    - [ ] Embed
    
- [ ] Warn command
- [ ] Delwarn command
- [ ] Unban command
- [ ] Mute command
- [ ] Unmute command
- [ ] Mod_see command

- [ ] Anti Spam/Flood
- [ ] Anti SelfBot
- [ ] Server Stats
    - [ ] Member Count
    - [ ] Bot Count

- [ ] Server Logs
    - [ ] Message delete
    - [ ] Message update
    - [ ] Role create
    - [ ] Role update
    - [ ] Role delete
    - [ ] Channel create
    - [ ] Channel update
    - [ ] Channel delete
    - [ ] Invite create

- [ ] Mod logs
    - [ ] Warn add
    - [ ] Warn remove
    - [x] Ban
    - [ ] Unban
    - [x] Kick
    - [ ] Mute
    - [ ] Unmute
    - [ ] Mod_see
    
# How to install

Installing DoctorModeration is very easy !

First, `git clone https://github.com/loockeeer/doctor_moderation`
Then, create a file in `src` called `token.json` with your token in a string inside (`"TOKEN"`)

You'll need to install PostgreSQL and then to pipe `database.sql` into it.

TODO : DataBase API (other repository)
