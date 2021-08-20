# touch Command
 we use touch command to create empty file/files
 ```console
 touch  test.txt
 ```
 will create a empty file named test.txt
<hr>

```console
touch test1.txt test2.txt test3.txt
or
touch test{1,2,3}.txt
```

To create multiple files using touch we can use above command
<hr>

touch command options are-
```
-a, change the access time only
-m, change the modification time only
-d, update access & modification time using specified time string
-r, use the acccess & modification time of another file
-t, update the access & modification times using specified time format
-c, if the file doesn't exist, don't create it
```

# Timestamp
* Every linux file has three timestamp
   * Access-time: The access timestamp is the last time a file was read.
   * Modification-time: A modified timestamp signifies the last time the contents of a file were modified. 
   * Change-time: Time at which the metadata related to a file was changed.
 <hr>

 To view all timestamp of a file we use
```
 stat filename
```
 ![stat filename](statfile.png) 

 # Change or Update Timestamp
 