THis is the first file created to practise the GIT.
git init   [ This is to initiate the git local ]
you can create/start your development post that you can use the below command to add the files for tracking.
git add file_name  [ it adds the file name ie it stages the file for the commit ]
git commit -m "THis is the first file" [ this is to commit the changes and have a history of the changes]
##################################
Here I have tested removing the file which I committed and with the below command I have restored the file
git restore file1.txt
2. Now I need to test how the behaviour is if we add and then restore without comitting the file and only by adding the file [ git add file1.txt]
