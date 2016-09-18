**Syncthing Snap**

*Notes*

 * A simple snap for Syncthing latest stable release

*Building*

On an up-to-date 16.04 system, install snapcraft and run `snapcraft` in the same directory as this README

*Things which work*

* Building the snap works

*Things which don't work*

 * Running the daemon when the snap installs doesn't work correctly. This can be checked with `systemctl status snap.syncthing.syncthing.service`. Output at this [paste](http://paste.ubuntu.com/23196930/)
