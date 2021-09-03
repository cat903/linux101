# **cp Command**
**cp stands for copy.** "cp" command is used **to copy file or group of files and folders**
<hr>

```console
cp  src_file1.txt  dest_file2.txt

```     
copies file1 to file2, **if file2 exists it overwrites**
<hr>

```console
cp  src_file1.txt  src_file2.txt  dest_folder
```
copies source files to a destination folder
<hr>
 
```console
cp  src_file1.txt   dest_folder/desired_named_.txt
``` 

copies source file with desired name to a destination folder, if file with same desired name already exist it will overwrite its content without warning.
<hr>

```console
cp  -i  filename1.txt  filename2.txt
```
`cp -i`  refers to interactive copy , if cp had to overwrit
e somefile it will prompt and ask user to press y to overwrite the file.
<hr>

```console
cp -b file1.txt file2.txt
```

`cp -b`  refers to backup and copy, if file2.txt exist already cp will backup file2.txt as ~file2.txt and then it will overwrite its content
with file1.txt's content. 
<hr>

```console
cp -r folderA file1.txt folderB
```

`cp -r`  is **used to copy directory**, above command makes a copy of  folderA and file1.txt inside folderB
<hr>

For More Options press Ctrl+Alt+t to open up terminal & type

```console
man cp
```
