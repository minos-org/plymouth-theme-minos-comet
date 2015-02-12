## About

[Plymouth](http://en.wikipedia.org/wiki/Plymouth_(software)) is the application which provides the graphical "splash" screen when booting and shutting down a Minos system. 

<p align="center">
<img src="https://raw.githubusercontent.com/minos-org/plymouth-theme-minos-comet/master/plymouth-minos-comet.gif" alt="minos-comet-theme"/>
</p>

## Quick start

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```

2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install plymouth-theme-minos-comet
   ```

3. Enjoy ☺!

### On other Linux distributions

1. Type `sudo mkdir -p /lib/plymouth/themes/minos-comet/`

2. Copy files `sudo cp *png *.plymouth *.script /lib/plymouth/themes/minos-comet/`

3. Set the default theme and rebuild the initramfs file `plymouth-set-default-theme -R minos-comet`

## Feedback

Please drop me an [email](mailto:m@javier.io) with your suggestions or open [an issue](https://github.com/minos-org/plymouth-theme-minos-comet/issues) with your comments.
