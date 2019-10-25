# Attachment

Attachment let you attach a file with the message.

### Param

| Parameter | Description | Required |
| :--- | :--- | :--- |
| command | The command name | yes |
| url | url or path to the document | yes |
| buffer | send it as the file or viewable image | no |

If you are sending code files, like javascript file, type anything inside the quotation mark of buffer, it will send as an individual file.

### Examples

examples of using buffer

```text
const dl = require("discord.lib")
dl.attachment("A_file", "./image.js", "true")
dl.login("token", "I am the best bot")
```

example of not using buffer

```text
const dl = require("discord.lib")
dl.attachment("A_file", "www.example.com/image.png")
dl.login("token", "I am the best bot")
```

