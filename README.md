# SSH Config Editing Enhanced

![ssh](https://d1m9hpru7ks0a1.cloudfront.net/ssh-96.png)

> Enhanced SSH Config Language Server extension for Visual Studio Code. Provides autocompletion, syntax highlighting, formatting, go to include file definitions and hover support for SSH config directives.

## Features

- Autocompletion: Provides suggestions as you type in an SSH config file
- Better syntax highlighting
- Hover support: You can hover over a keyword to see a brief description of what it does
- Works with the `ms-vscode-remote.remote-ssh-edit` extension
- Formatting directives by spaces configured via `vscode-ssh-config-enhanced.format.indentSize` setting after each Host and Match

Formatting Example:
```properties
Host jamief
HostName ssh.example.com
User jamief
Port 22
IdentityFile ~/.ssh/mykey
```

Becomes:
```properties
Host jamief-rn
  HostName ssh.example.com
  User jamief
  Port 22
  IdentityFile ~/.ssh/mykey
```