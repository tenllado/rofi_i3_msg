# i3 msg rofi modi

A rofi mode to use rofi as an interface to send commands to i3, having a history
of previously runned commands shown in the rofi window.

## Usage

rofi -show i3-msg -modi i3-msg:<path-to-rofi_i3_msg.sh>

The most convenient way to use it is to bind the latter command to a key in the
i3 config file.
