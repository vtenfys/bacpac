bacpac
======

bacpac is a backup and restore script for [Arch Linux]'s pacman configuration
data and manually installed packages.

[Arch Linux]: https://www.archlinux.org/

Dependencies
------------

* [bash] for the script itself
* [git] and [diffutils] for backing up current packages and configuration
* [sudo] and [grep] for restoring packages and configuration
* ...that's all!

[bash]: https://www.archlinux.org/packages/core/x86_64/bash/
[git]: https://www.archlinux.org/packages/extra/x86_64/git/
[diffutils]: https://www.archlinux.org/packages/core/x86_64/diffutils/
[sudo]: https://www.archlinux.org/packages/core/x86_64/sudo/
[grep]: https://www.archlinux.org/packages/core/x86_64/grep/

Getting started
---------------

Setting up bacpac for the first time is super-easy; the only requirement is a
GitHub account to sync your packages. To get started, read the following
instructions:

1. [Create a GitHub account] if you don't already have one.

1. Fire up a terminal.

2. `git clone https://github.com/tech4david/bacpac`

3. `cd bacpac`

4. `./bacpac init`

5. Follow the instructions displayed on the terminal.

Please report any issues you find with bacpac [here].

[Create a GitHub account]: https://github.com/join
[here]: https://github.com/tech4david/bacpac/issues
