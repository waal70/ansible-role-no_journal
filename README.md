Role Name
=========

This role will turn the journaling filesystem ext4 into a non-journaling filesystem.
It does so, by removing the "has_journal" flag on the drive.
Because it affects the root filesystem, it includes some wizardry for making it so.

Requirements
------------

Debian-based. The role will figure out the device where "/" is mounted

Role Variables
--------------

None

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html#license-text)

Author Information
------------------

Unless otherwise noted, this entire repository is (c) 2024 by André (waal70). [See github profile](https://github.com/waal70)

Please contact me if you need a commercial license for any of these files
