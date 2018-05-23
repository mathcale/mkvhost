# mkvhost

Creates an Apache VirtualHost config file based on some input (URL and document root) and adds the informed URL to the local /etc/hosts file.

You must run this with `sudo` since the script will create/edit files not owned by your user (probably).

PS: the code is bad, but it **Just Works™** (at least on my machine ¯\\_(ツ)_/¯ )

### Usage

```bash
# Make it executable
$ sudo chmod +x mkvhost

# Fire!
$ sudo ./mkvhost
```
