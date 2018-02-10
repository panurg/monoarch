# Monogentoo
Monogentoo is a theme for
[Plymouth](https://www.freedesktop.org/wiki/Software/Plymouth/) which exhibits
a monochrome white on black look and feel. It displays the Gentoo Linux logo and
a spinner.

# Installation
Files should be placed in the Plymouth themes directory,
which is usually `/usr/share/plymouth/themes`. You may install the theme by
simply cloning the repository:

    # cd /usr/share/plymouth/themes/
    # git clone https://github.com/panurg/monogentoo

Remember to change the Plymouth theme:

    # plymouth-set-default-theme monogentoo

# Removal
Simply remove the directory:

    # rm -rf /usr/share/plymouth/themes/monogentoo

Remember to change your theme again otherwise Plymouth will fall back to its
default one.

# Using with distributions other than Gentoo Linux
Nothing prevents you from doing that. If you want to replace the Gentoo Linux
logo with your favorite distribution's, you may want to change the
`images/logo.png` file to suit your liking.

# Credits
Monogentoo is a fork of [Monoarch](https://github.com/farsil/monoarch)

Gentoo Linux logo taken from
[rEFInd-Theme](https://github.com/initramfs/rEFInd-Theme).
