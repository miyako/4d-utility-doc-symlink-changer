4d-utility-doc-symlink-changer
==============================

Change local 4D documentation links to symbolic links, for 10.10 Yosemite.

Note
----

I think I found a workaround for this.

problem (v13, v14):

if you have static docs downloaded before Yosemite, you might see "web
page not found" instead of local documentation.

safari... file:///4D/13.4/ALERT.301-1218731.ja.html
chrome... file:///.file/id=6571367.64649051




solution:

re-downloaded static docs on your Yosemite (10.10.1).

**related tips**

by going to application preferences and enter a file URL instead of http,
you can force 4D to use local docs.

ex:

before

http://doc.4d.com/4dv13/help/command/ja/

http://doc.4d.com/4dv14/help/command/ja/


after

file:///Users/miyako/.../Documentation/v13/13.x/4Dv13.4/Help/Command/ja/

file:///Users/miyako/.../Documentation/v14/14.x/4Dv14/Help/Command/ja/


no need to create symlinks :)
