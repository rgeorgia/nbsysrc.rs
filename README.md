# netbsd-sysrc
Very simple sysrc for NetBSD in rust.

### Why in Rust?

Because I am learning Rust and this is a self imposed, useful project

# nbsysrc
This started out to be a simple sysrc for NetBSD; however there may be some room to allow for FreeBSD, HardenedBSD and DragonflyBSD.

I am tired of opening rc.conf with vi(m) in order to add a service, or a flag. I don’t want to have to “cat” the rc.conf to see the rc status of a or flag.

I need a single application that does it for me, something similar to sysrc used by FreeBSD and it’s derivatives. Basically nbsysrc will take an argument from the command line and insert, append or change the value of an existing entry in the rc.conf file.

  #### Example:
  ```nbsysrc dbus=YES```

 Some Details
 ------------

 Check out our [wiki](https://github.com/rgeorgia/nbsysrc/wiki) for more details.

 Check out our [Roadmap wiki](https://github.com/rgeorgia/nbsysrc/wiki/Roadmap) for more details.
