# Installation

1. `git clone https://github.com/BSteffaniak/tmux ~/.config/tmux`
1. `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
1. ubuntu: `./install_tmux_ubuntu` mac: `./install_tmux_macos` 
1. `tmux`
1. `ctrl+a I`
1. Remap `ctrl+;` to `ctrl+s` (for window navigation):
    * Windows: use [AutoHotkey](https://github.com/BSteffaniak/autohk) for app-specific key combos or [PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) for global
    * Mac:
        * Disable mission control spaces key combinations: Preferences > Keyboard > Keyboard Shortcuts > Mission Control > Mission Control
        * Use Karabiner-Elements and import this [ctrl-; -> ctrl-s in kitty complex modification](https://genesy.github.io/karabiner-complex-rules-generator/#eyJ0aXRsZSI6ImtpdHR5OiBjdHJsKzsgLT4gY3RybCtzIiwicnVsZXMiOlt7ImRlc2NyaXB0aW9uIjoia2l0dHk6IGN0cmwrOyAtPiBjdHJsK3MiLCJtYW5pcHVsYXRvcnMiOlt7InR5cGUiOiJiYXNpYyIsImZyb20iOnsibW9kaWZpZXJzIjp7Im1hbmRhdG9yeSI6WyJsZWZ0X2NvbnRyb2wiXX0sImtleV9jb2RlIjoic2VtaWNvbG9uIn0sInRvIjpbeyJyZXBlYXQiOnRydWUsImtleV9jb2RlIjoicyIsIm1vZGlmaWVycyI6WyJsZWZ0X2NvbnRyb2wiXX1dLCJjb25kaXRpb25zIjpbeyJ0eXBlIjoiZnJvbnRtb3N0X2FwcGxpY2F0aW9uX2lmIiwiYnVuZGxlX2lkZW50aWZpZXJzIjpbIi4qa2l0dHkuKiJdfV19XX1dfQ==)
    * Linux: use [XKB](https://www.x.org/wiki/XKB)
