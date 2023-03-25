# Day 6 Task: File Permissions and Access Control Lists

1) Create a simple file and do `ls -ltr` to see the details of the files.
   As a task, change the user permissions of the file and note the changes after `ls -ltr`
   
    File name : file1.txt
    
    Before Changing permissions :
  
    ![Q1 a](https://user-images.githubusercontent.com/77112379/227739186-53636bc4-be9c-44d9-a432-a4e8631c2a66.jpg)
    
    After Changing permissions :
  
    ![Q1 b](https://user-images.githubusercontent.com/77112379/227739188-9a3c85ca-efaa-46fc-b694-4981e62e57ff.jpg)

 2) Write an article about File Permissions based on your understanding.
    
    Link to my Blog :
    https://nishantsharma.hashnode.dev/file-permissions-in-linux#heading-changing-ownership-using-the-chown-command

 3) Read about ACL and try out the commands `getfacl` and `setfacl`
    
    `getfacl` Command : Permission of file1.txt
    
    ![Q3 a](https://user-images.githubusercontent.com/77112379/227740396-bf82c18e-56f6-4927-b125-26591c8e74d8.jpg)

    `setfacl` Command : Changed permission of file1.txt to read only for user osboxes
    
    ![Q3 b](https://user-images.githubusercontent.com/77112379/227740430-710e117c-ce86-473b-acd6-c19fb997b414.jpg)

    READY FOR DAY 07
