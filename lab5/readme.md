# Lab 5

## Q.1: Compress and decompress a file by `compress`, `gzip` and `zip`?

1. **Compress**

    ![](./imgs/lab5-1-a.png)

1. **gzip**

    ![](./imgs/lab5-1-b.png)

1. **zip**

    ![](./imgs/lab5-1-c.png)

## Q.2: What is the command used to view the content of a compressed file?

1. **`zcat` to view contents of files compressed with `compress`, `gzip` and `zip`**

    ![](./imgs/lab5-2-a.png)

1. **`bzcat` to view contents fo files compressed with `bzip2`**

    ![](./imgs/lab5-2-b.png)

## Q.3: Backup `/etc` director using `tar` utility?

![](./imgs/lab5-3-a.png)
![](./imgs/lab5-3-b.png)

## Q.4: Starting fromyour home directory, find all files that were modified in the last two days?

![](./imgs/lab5-4-a.png)
![](./imgs/lab5-4-b.png)

## Q.5: Starting from `/etc`, find filew owned by `root` user?

![](./imgs/lab5-5.png)

## Q.6: Find all directories in your home directory?

![](./imgs/lab5-6-a.png)
![](./imgs/lab5-6-b.png)

## Q.7: Write a command to search for all files on the system that, its name is `.profile`?

1. Using `find` command

    ![](./imgs/lab5-7-a.png)

1. Using `locate` command

    ![](./imgs/lab5-7-b.png)

## Q.8: Identify the file types of the following: `/etc/passwd`, `/dev/pts/0`, `/etc` and `/dev/sda`?

![](./imgs/lab5-8.png)

## Q.9: List the `inode` numbers of `/`, `/etc` and `/etc/hosts`?

![](./imgs/lab5-9.png)

## Q.10: Copy `/etc/passwd` to your home directory, use the commands `diff` and `cmp` and edit in the file you copied, and then use these commands again, and check the output?

1. **Using `diff`**

    ![](./imgs/lab5-10-a.png)

1. **Using `cmp`**

    ![](./imgs/lab5-10-b.png)

## Q.11: Create a symbolic link of `/etc/passwd` in `/boot`?

![](./imgs/lab5-11.png)

## Q.12: Create a hard link of `/etc/passwd` in `/boot`. Could you? Why?

![](./imgs/lab5-12.png)

* **Couldn't add a hard link**
* **Why?** because the `/etc/passwd` and `/boot` exists of 2 different partitions and hard links need to exist on the same partition of the file it points to it.
