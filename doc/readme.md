# Reminders

Some useful commands that will come in handy when it's time to troubleshoot build issues.

```bash
# clean slate
snapcraft clean

# build
snapcraft

# install local snap
snap install --classic --dangerous ./ghostty-unofficial_*.snap

# re-run a specific stage
snapcraft prime

# access the build container's shell before a stage action is executed
snapcraft prime --shell

# access the shell after the stage action is executed
snapcraft prime --shell-after
```

# References

* [Snapcraft documentation](https://snapcraft.io/docs/snapcraft-reference)
* [snapcraft.yaml examples on GitHub](https://github.com/search?o=desc&q=path%3Asnapcraft.yaml+%22plugin%3A+dump%22+&s=indexed&type=Code&utf8=%E2%9C%93)
* [Packaging Ghostty](https://ghostty.org/docs/install/package)