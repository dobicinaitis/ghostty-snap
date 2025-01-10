<h1>
<p align="center">
  <img src="snap/gui/icon.png" alt="Logo" width="128">
  <br>Ghostty Snap
</h1>

Snap packaging for the [Ghostty](https://github.com/ghostty-org/ghostty) terminal emulator.

> [!NOTE]
> **This is an unfinished symphony.** \
> The Snap was rejected by the Snap Store because an upstream Snap will be published
> [soon](https://github.com/ghostty-org/ghostty/pull/3931).

## Installation

Get it from the [Snap Store](https://snapcraft.io/ghostty-unofficial) or install using the command line.

**Latest release**

```bash
snap install ghostty-unofficial --classic
```

**Latest pre-release**

```bash
snap install ghostty-unofficial --classic --channel=tip
```

**Create an alias** (optional)

You can create a Snap alias to refer to it simply as `ghostty` in the CLI.

```bash
sudo snap alias ghostty-unofficial ghostty
```

## Useful

Set Ghostty as your default terminal emulator in Gnome:

```shell
gsettings set org.gnome.desktop.default-applications.terminal exec 'ghostty'
```

You should now be able to open it using the keyboard shortcut `ctrl + shift + t`.
