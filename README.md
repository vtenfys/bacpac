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
