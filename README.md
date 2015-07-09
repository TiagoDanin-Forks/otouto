# otouto

The plugin-wielding, multi-purpose Telegram chat bot.

Public bot runs on [@mokubot](http://telegram.me/mokubot).

Requires lua-socket and lua-sec. [dkjson](https://github.com/LuaDist/dkjson/) is provided.

`lua bot.lua`

###Configuration

Most config.json entries are self-explanatory.

Giphy key provided is the public test key, and is subject to rate limitation.

TIME_OFFSET is the time difference, in seconds, between your system clock. It is often necessary for accurate output of the time plugin.

"admins" table includes the ID numbers, as integers, of any privileged users. These will have access to the admin plugin and any addition privileged commands.

"people" table is for the personality plugin:
`"123456789": "foobar"`

ID number must be a string.