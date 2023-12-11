# Lab 7

## Q.1: Add the following users (user1, user2, user3, user4, user5, user6, user7) to the system?

![](./imgs/linux-lab7-1-a.png)

![](./imgs/linux-lab7-1-b.png)

![](./imgs/linux-lab7-1-c.png)

## Q.2: Using `groupadd` add the following groups (`sales gid=10000`, `hr gid=10001`, `web gid=10002`)?

![](./imgs/linux-lab7-2-a.png)

![](./imgs/linux-lab7-2-b.png)

### Why should we set `GID` in this manner instead of allowing the system to set the `GID` by default?

Useful in case where we need to maintain consistency across systems

## Q.3: Using `usermod` add `user1, user2` to sales group, `user3, user4` to hr group, `user5, user6` to web group, and `user7` to all groups?

![](./imgs/linux-lab7-3-a.png)

![](./imgs/linux-lab7-3-b.png)

## Q.4: Login as each user and use `id` command to verify the above question?

![](./imgs/linux-lab7-4.png)

## Q.5: Create `/depts/sales/` `/depts/hr/` `/depts/web/`?

![](./imgs/linux-lab7-5.png)

## Q.6: Using `chgrp`, setthe group ownership of each directory to the respective group?

![](./imgs/linux-lab7-6.png)

## Q.7: Set the permissions on the `/depts` to `755`, and each sub-dir to `770`?

![](./imgs/linux-lab7-7.png)

## Q.8: Set the `SGID` on each sub-dir inside `/depts/`?

![](./imgs/linux-lab7-8.png)

## Q.9: Switch to `user2` and attempt to create file inside each sub-dir of `/depts`?

![](./imgs/linux-lab7-9.png)

### What is the group ownership of the newly created file?

![](./imgs/linux-lab7-9-extra.png)

## Q.10: Configure `sudoers` to allow `user3` and `user4` to user `/bin/mount` and `/bin/umount, while allowing`user5` only to user `fdisk` command?

![](./imgs/linux-lab7-10.png)

## Q.11: Login as `user3` and try to unmount `/boot`?

![](./imgs/linux-lab7-11.png)

## Q.12: Long as `user4` and remount `/boot`?

![](./imgs/linux-lab7-12-a.png)

### Try to view partition table using `fdisk`?

![](./imgs/linux-lab7-12-b.png)

## Q.13: Create dir with permissions `rwxrwx---`, grant second group (sales) `r-x`?

![](./imgs/linux-lab7-13.png)

## Q.14: Create a file on the dir and grant `rw` access to second group (sales)?

![](./imgs/linux-lab7-14.png)

## Q.15: Set the owning group as the owning group of any newly created file in that dir?

![](./imgs/linux-lab7-15.png)
