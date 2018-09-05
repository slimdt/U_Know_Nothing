## Problem: 
I do not want to create python virtualenv in dropbox, instead, I create the virturalenv in another place and only sync some important files in a Dropbox folder

## Solution:
ln command

### create soft link
ln -s absolute_path_of_folder1 absolute_path_of_folder2
e.g. ln -s /home/sliM/code/    /home/sliM/codesoft  
then, /home/sliM/codesoft is the softlink of /home/sliM/code/, any change in /home/sliM/code/ will also happen in /home/sliM/codesoft

### delete soft link
rm -rf /home/sliM/codesoft 
not
rm -rf /home/sliM/codesoft/
