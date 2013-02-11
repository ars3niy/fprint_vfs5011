If you would like to test the driver, which you will probably do by running
fprint_demo, please set the VFS5011_DEBUGPATH environment variable to a
directory where lots of debug files will be created (the directory must already
exist), like this:
VFS5011_DEBUGPATH=~/.fprint/index_finger fprint_demo

These debug files will provide valuable feedback that can help developing the
driver. But I would like to mention that the .pgm images that will be created
this way will contain images of scanned fingerprints. So, if you have access to
some top security military base where fingerprints are used for authentication,
don't send me these images :-)

Arseniy Lartsev, 2013-02-11
