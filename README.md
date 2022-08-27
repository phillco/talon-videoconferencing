# talon-videoconferencing

> **Note**
> Development is happening on the [`work` branch](https://github.com/phillco/talon-videoconferencing/tree/work) since this isn't a finished project.

Systems for intelligently controlling videoconferencing software from within Talon (for example, implementing a a "smart mute" that automatically makes Talon sleep when you unmute, and vice versa.)

### Currently supported systems:

* Discord (requires a bit of [setup](https://github.com/phillco/talon-videoconferencing/blob/work/discord.py#L13)): supports a action to globally mute or unmute Discord regardless of whether it's focused, as well as perform a "smart mute toggle" (toggle Discord mute status and put Talon into the opposite state)
