#### How to build the Freifunk Helgoland Firmware

    git clone https://github.com/freifunk-gluon/gluon.git                  # Get the official Gluon repository
    cd gluon
    git clone https://github.com/freifunk-helgoland/site-helgo.git site    # Get the Freifunk Helgoland site repository
    make update                                                          # Get other repositories used by Gluon
    make                                                                 # Build Gluon

Please see [the official Gluon repository](https://github.com/freifunk-gluon/gluon) for an in-depth explanation of the build process.


#### Gluon versions used for specific Helgoland Freifunk Firmware builds

- 0.8.2:  v2016.2.7 new keys for new infrastructure
- 0.8.1:  v2016.2.3
- 0.8:    v2016.1.2
- 0.7.1:  v2015.1.1
- 0.7:    skipped
- 0.6:    v2014.4
