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

### License

Just in case, here's the Don't Be A Dick Public License

DON'T BE A DICK PUBLIC LICENSE

> Version 1.1, December 2016

> Copyright (C) 2017 Matheus Calegaro <eu@mathcale.com>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document.

> DON'T BE A DICK PUBLIC LICENSE
> TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

1. Do whatever you like with the original work, just don't be a dick.

   Being a dick includes - but is not limited to - the following instances:

 1a. Outright copyright infringement - Don't just copy this and change the name.
 1b. Selling the unmodified original with no work done what-so-ever, that's REALLY being a dick.
 1c. Modifying the original work to contain hidden harmful content. That would make you a PROPER dick.

2. If you become rich through modifications, related works/services, or supporting the original work,
share the love. Only a dick would make loads off this work and not buy the original work's
creator(s) a pint.

3. Code is provided with no warranty. Using somebody else's code and bitching when it goes wrong makes
you a DONKEY dick. Fix the problem yourself. A non-dick would submit the fix back.