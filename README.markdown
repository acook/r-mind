r(mind)
=======

A little todo/reminder app that runs on the commandline and stores its reminders in a yaml file in your home directory.


Install
-------

If you already have ruby, then just link the script to the directory and name of your choice:

```ln -s `pwd`/r ~/bin/r```

It doesn't require anything outside of the Ruby stdlib!


TODO
----

When I originally wrote it - quite a while back - I had this idea of making unique hashes for each reminder for some reason.
Instead I want it to use basic auto incrementing IDs, and instead of deleting reminders by default, instead mark them as complete.

What I might end up doing is converting this to a gem and using sqlite as my backend.

**BUGS**

* Can't delete reminders right now, I broke them recently, oops
* probably other things, make an issue if you encounter another bug

Credits
-------

Anthony M. Cook 2010-2011
@anthony_m_cook
anthonymcook.com

