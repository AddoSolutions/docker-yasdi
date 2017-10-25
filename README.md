# SMA SunnyBoy YASDI Docker

This is just a docker file with the latest (at this time) compiled yasdi interface.

You can run:

```
yasdishell
```

And that should run whatever you need, though it does look for a `yasdi.ini` file.


From there you will want to do a volume mapping of whatever your serial device is, `--device=/dev/ttyS0:/dev/ttyS0`.  From there, you should be able to manage the rest!
