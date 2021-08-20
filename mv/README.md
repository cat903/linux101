# mv Command
**mv stands for move**, we can use "mv" command to cut/move/rename files or group of files and folders.
<hr>

```console
mv file1.txt file2.txt
or
mv {file1.txt,file2.txt}
```
**above both command does exact samething**,
using mv command we can rename file1.txt to file2.txt, after executing this command there will be no file1.txt, if file2.txt already exists its contents will be overwritten and contents of file1.txt will be copied.
<hr>

```console
mv -i file1.txt file2.txt
```
 `mv -i` refers to interactive move, if file2.txt already exists, mv will seek user interaction to overwrite file2.txt's contents.
<hr>

```console
mv -n file1.txt file2.txt
```
`mv -n` refers to move-no-clobber, with `-n` option mv prevents file from being overwritten. if file2.txt already exists no changes will happen. but if file2.txt doesnt exist, file2.txt will be created and then content of file1.txt will be to file2.txt.
<hr>

```console
mv -b file1.txt file2.txt
```
`mv -b` refers to backup and move, this means before any changes backup will be made. in above case assuming file2.txt already exists, so using `-b` option file2.txt will be backed up first with the name of ~file2.txt and then contents of file1.txt will be copied into file2.txt and file1.txt will get vanished. **so the main purpose of -b option is protecting content of a file.**
<hr>

```console
mv src_dir1/subDir1/{test1.txt,test2.txt} src_dir2/subDir2 dest_Dir3/
```

above command will move file test1.txt,test2.txt and folder subDir2 to dest_Dir3
<hr>
To learn more about mv

```console
man mv 
```
