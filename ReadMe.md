# Team 3
## topics: Permissions, owner, group and other, setting Permission and seeing

#### Permission
  - how do they work - explain the binary
  - chmod with numbers? chmod with letters?
  - chmod with binary.

#### Demo task:
- show the Permission system
- create some files
- edit them
- change the Permission
- try to edit

- create a python file
- create hello world
- run it
- change Permission
- show that you can't run the file

## Permission

Permissions work by the user changing the Permissions for a file in which they can allow other users to access the file or not to have access to the file.

 - `-` sign removes Permission
 - `+` Grants the user Permission
 - `=` Sets Permission and removes other Permissions


## Binary

0: (`000`) No permission.
1: (`001`) Execute permission.
2: (`010`) Write permission.
3: (`011`) Write and execute permissions.
4: (`100`) Read permission.
5: (`101`) Read and execute permissions.
6: (`110`) Read and write permissions.
7: (`111`) Read, write, and execute permissions.
 
