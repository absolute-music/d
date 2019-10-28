# Typings

This allows you to make your bot to start/stop typing in one or more specific channels.

## startTyping

### Param

| Parameters | Description | required |
| :--- | :--- | :--- |
| channel | Channel to start typing | Yes |

### Example

```text
const dl = require("discord.lib")
dl.startTyping("channelid")
dl.login("token", "Typing started!")
```

## stopTyping

### Param

| Parameters | Description | Required |
| :--- | :--- | :--- |
| channelid | Channelid | yes |
| force | Force to stop? | no |

### Example

```text
const dl = require("discord.lib")
dl.stopTyping("channelid", true)
dl.login("token", "Typing started!")
```

