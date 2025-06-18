## CST 8254 Practical Mid Term

**Your Name:**
Quiel Andrew Castro
041167640
```

```

Answer directly in this .md file.



**1.**

```
scp C:/quielandrewcastro.txt pi@192.168.2.25:/home/pi
```



**2. What command do you use to see a directory listing that includes the permissions of the files?**

```
ls -l
```



**3.**

```
ls -l pr1.txt
```

**4. What are the permissions of the file you just created?**

```
-rw-r--r--
```

**5. What command do you use to display the folder you are currently working from?**

```
pwd
```



**6.**

```
chmod g=x pr1.txt
```



**7.**

```
mkdir midtermExam-301
```

**8. What are the permissions of this new folder  ?**

```
drwxr-xr-x
```

**9. What command do you use to list the ports your raspberry pi is listening to? Try it using the `-at` flag.**

```
netstat -at
```



**10.**

```
netstat -at > pr2.txt
```



**11.**

```
sftp pi@192.168.2.25
```



**12.**

```
put midtermPi.txt
```


```

**13.** What does the command do?

```
runs print working directory and outputs to mt.txt
tree lists directory structure and outputs it to pr.txt
```


**14.**

```
sudo useradd quielandrewcastro
```



 **15.**

```
sudo mkdir /home/quielandrewcastro
sudo chown quielandrewcastro:quielandrewcastro /home/quielandrewcastro
```



**16.**

```
sudo apt-get update
sudo apt-get install filezilla
```

**17.** issue the following command on your pi:

`cd /home`

`ls -als > /home/pi/pr3.txt`


