# Vagrant Virtualbox Templates
===

Contained within are various virtualbox templates I've created using [veewee](https://github.com/jedi4ever/veewee).

If you actually decide to depend on these images, please remember to visit this page again if the image suddenly goes missing so that you can update versions/download locations, etc.

Note: In the future I may move these images to S3, or decide to not host them at all because of bandwidth costs. I doubt these will become popular, but just putting that out there.

## Current Templates

### ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15
#### Hardware Specs
- 60 GB HD
- 3 GB RAM

Basically this is a template based on Ubuntu 12.10 with the latest patches applied, Python 2.7, and some other basic server utils that are useful.  I was tired of using existing images having such small hard drives, and also tired of waiting for updates to be applied.

#### Download URL

[https://dl.dropboxusercontent.com/u/124591/dist/vagrant-boxes/ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15.box](https://dl.dropboxusercontent.com/u/124591/dist/vagrant-boxes/ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15.box)

## Simple Instructions

To build one of these images yourself, run these commands from the root of the project:

```
$ veewee vbox build ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15
$ veewee vbox validate ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15
$ veewee vbox export ubuntu-12.10-server-i386-devnulled-60GB-3GB-2013-11-15
```

## License

Please see the LICENSE file for this project.