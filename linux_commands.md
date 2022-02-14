```shell
pwd
```

Shows you where you are

```shell
whoami
```

Tells you who you are signed in as.

Every user has a directory in `/home/`, except for the root user. Root is held at `/root/`

```shell
mkdir MLB
```

No news is good news for terminal.

```shell
ls
```

Provides a directory listing

```shell
cd
```

change directory

```shell
mkdir NL AL
```

Creates two directories `NL` and `AL` respective.

```shell
cd NL
```

```shell
mkdir East Central West
```

```shell
ls
```

```shell
cd ..
```

Move up to the parent directory


```shell
touch Mets
```

Creates a file

```shell
mv
```

In Linux, You should only use `mv` to rename a file. `mv` is dangerous. `mv` moves data to RAM, deletes from 
hard drive, and then writes back to hard drive. This is dangerous during power outage, etc. RAM is non-volatiale.

```shell
cp Mets /home/student/MLB/NL/East/
```

Copies.

```shell
cd ../../
```

Write relative 

```shell
cd ../NL
```

