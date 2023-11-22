# Lab 2

## Q.1: Create user account *islam*? 

![](./imgs/lab2-1.png)

## Q.2: Create user account *baduser*?

![](./imgs/lab2-2.png)

## Q.3: Create secondary group "*pgroup*" with *gid* 30000?

![](./imgs/lab2-3.png)

## Q.4: Create secondary group "*badgroup*"?

![](./imgs/lab2-4.png)

## Q.5: Add *islam* to "*pgroup*"?

![](./imgs/lab2-5.png)

## Q.6: Modify *islam*'s password to "*password*"?

![](./imgs/lab2-6.png)
M
## Q.7: Modify *islam*'s password to expires in 30 days?

![](./imgs/lab2-7.png)

## Q.8: Lock "*baduser*" account?

![](./imgs/lab2-8.png)

## Q.9: Delete "*baduser*" account?

![](./imgs/lab2-9.png)

## Q.10: Delete supplementary group "*badgroup*"?

![](./imgs/lab2-10.png)

## Q.11: Create folder *myteam* and change permission to read only for owner?

![](./imgs/lab2-11.png)

## Q.12: Log out and log in by another user?

![](./imgs/lab2-12.png)

## Q.13: Try to access (by *cd* command) folder *myteam* ?

![](./imgs/lab2-13.png)

## Q.14

1. Change *oldpasswd* file permissions to u=rw,g=wx,o=x
		![](./imgs/lab2-14-a-1.png) ![](./imgs/lab2-14-a-1.png)

1. Change your default permissions to be as above
	![](./imgs/lab2-14-b.png) 

1. What is the max permission a file and a directory can have by default?
	* **File** : 666
	* **Directory** : 777

1. Change default permission to be no permission for everyone?
	![](./imgs/lab2-14-d.png)

## Q.15: What are the minimum permisson needed for?

1. Copy a directory

	|min permissions needed for	|Source Dir|Dest Dir |
	|---------------------------|----------|---------|
	|Copy Dir                   | r        | w,x     |

1. Copy a file

	|min permissions needed for	    |Source File|Dest Dir|
	|-------------------------------|-----------|---------|
	|Copy File                      | r         | w,x     |

1. Delete a file

    |min permissions needed for	    |Source File|Parent Dir|
	|-------------------------------|-----------|----------|
	|Delete File                    |      _    | w,x      |

1. Change to a directory

    |min permissions needed for	    |Target Directory|
	|-------------------------------|----------------|
	|Change into Directory          |x               |

1. List a directory content

    |min permissions needed for	    |Target Directory|
	|-------------------------------|----------------|
	|List Directory Content         |r               |

1. View a file content

    |min permissions needed for	    |Target File|
	|-------------------------------|-----------|
	|View File Content              |r          |

1. Modify a file

    |min permissions needed for	    |Target File|
	|-------------------------------|-----------|
	|Modify File                    |w          |

## Q.16: Create a file with permission 444? try edit && remove it?

![](./imgs/lab2-16.png)

## Q.17: What is the difference between ***x*** permission for a file and a directory?

|permission|File                          |Directory                         |
|----------|------------------------------|----------------------------------|
|**X**     |Can run the file as executable (e.g bash scripts, python scripts, linux executables,...)|Can access the directory     |
