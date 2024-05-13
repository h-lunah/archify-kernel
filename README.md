# archify-kernel
A tool to convert your Linux kernel trees into Arch Build System (AUR) compliant Linux kernel trees.

## How to use?
1. Run `./archify-kernel path/to/linux suffix` to apply the Arch treatment to a Linux kernel tree.
2. Go into the newly created Linux kernel tree.
3. Put in your `.config` and run `make oldconfig` to populate any new options.
4. Run `makepkg -rsi` to compile the kernel.

Now you can have the latest kernel before Arch maintainers do it for you!
