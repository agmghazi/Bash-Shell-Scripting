
 # **Bash Shell Scripting    :exclamation: 🚀
***
#  🚦  Bash Basic
## for get link your file
```
$ pwd
```
## for get all files in your directory
```
$ ls
```
## for make new file
```
$ mkdir
```
## for go to Desktop
```
$ cd Desktop
```
## to create file.anything
```
$ touch m.text
```
## to delete this file
```
$ rm m.text
$ rm -r ahmed
```
## to delete any directory (file)
```
$ rmdir ahmed
```
## to backend 
```
$cd ..
```
##  to move your file
```
$ mv l.text ahmed/l.text
```
## to get your files in this directory
```
$ ls ahmed 
```
## to rename this file
```
$ mv l.txt r.text
```
## to discover what is terminal to get description for this 
```
$ whatis terminal 
```
## to open this file in nano test editor in linux
```
$ nano m.text
```
## for get all files in your directory and hidden files 
```
$ ls -a
```
##  to create file but (.) this to make this file hidden
```
$ touch .m.text
```
## to get help from terminal for any thing
```
$ ls --help
```
## to get your files in this directory but with security bash
```
$ ls -l
```
## this security bash for administrator for this file
```
$ -rw-rw-r--
```
## for change security bash to administrator for this file 
```
$ chmod 755 new.text
```
## for make execute for any file
```
$ 755 file execute

owner  group	all
- rwx	 r-x    r-x
  111    101    101
   7      5      5
- (file)
d (folder)
r == read
w == write
x == execute 
```
## to open file in terminal 
```
$ cat long.text
```
##  to open file in terminal 
```
$ head long.text
```
## to open file in terminal 
```
$ tail long.text
```
## to get all code you  write in terminal
```
$ history
```
## to get hash security for file
```
$ wc long.text
```
##  to get hash security for file
```
$ wc -w long.text
```
## to get hash security for file
```
$ wc -l long.text
```
## to get hash security for file
```
$ wc -c long.text
```
## to edit  in file
```
$ ls --help | cut -d" " -f1 >firestworlds.text
firstworlds.text | grep "[a-Z]" >firstworldsmm.text
```
## for create file and write this inside
```
$ echo "hi from fedora" > hello.text
```
## for create file and write this inside
```
$ echo "hi from fedora" >> hello.text
```
#  🚦  Bash pro
## to get data from any website
```
$ wget www.cisco.com
cat index.html
cat index.html | grep "href=" | cut -d"/" -f3 | cut -d'"' -f1 | grep "cisco" | sort -u > cisco.txt
cat cisco.txt
 
////////////////////////////////
host www.cisco.com | grep "has address" | cut -d" " -f4
/////////////////////////////////////////
ciscoUrls=`cat cisco.txt`
for url in $ciscoUrls
do
      host $ciscoUrls | grep "has address" | cut -d" " -f4
done
```
## to create function 
```
$  function

print_my_name()
{
	echo "ahmed"
}

print_my_name()              

```
