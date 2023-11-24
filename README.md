# redhat_track
## [lab 1]
## (q2)
cat : it's used for seeing the content of small files .

more : it's used for seeing the content of large files as it displays
the contents of file one screen at a time .

--------------------------------------------------------------------------------------------------------------------------------------------
## (q3)
rm : used to remove files or directories
![WhatsApp Image 2023-11-21 at 21 39 03(12)](https://github.com/mostafagh10/redhat_track/assets/41267238/bb09aca7-8026-4b22-82c3-136d99f317f8)

rmdir : used to remove only empty directories
![WhatsApp Image 2023-11-21 at 21 39 03(11)](https://github.com/mostafagh10/redhat_track/assets/41267238/9ab06b60-1461-43fa-8af9-c9203cfc784c)
----------------------------------------------------------------------------------------------------------------------------------------------
## (q4)
mkdir ~/dir1<br />
mkdir ~/dir1/{dir11,dir12}<br />
touch ~/dir1/dir11/file1<br />
cd ~/Documents<br />
touch mycv
![WhatsApp Image 2023-11-21 at 21 39 03(10)](https://github.com/mostafagh10/redhat_track/assets/41267238/5a456aa5-fbf1-4b28-85e9-c2c633b55c7f)
![WhatsApp Image 2023-11-21 at 21 39 03(9)](https://github.com/mostafagh10/redhat_track/assets/41267238/387330e9-1c7b-440b-a5b6-5b3fbd4db093)
![WhatsApp Image 2023-11-21 at 21 39 03(8)](https://github.com/mostafagh10/redhat_track/assets/41267238/1ef4a9d8-c8f5-49fe-aefa-e389165a9057)

A- 
cd ../<br />
rmdir ~/dir1/dir11<br />
notice : rmdir didn't remove the directory because it's not empty<br />
overcome with rm -r command : rm -r ~/dir1/dir11<br />
![WhatsApp Image 2023-11-21 at 21 39 03(7)](https://github.com/mostafagh10/redhat_track/assets/41267238/557b9103-7480-41a5-af02-759f684a5517)

B - 
rmdir -p ~/dir1/dir12<br />
notice in direcories : dir1 removed with dir12 but didn't remove the home directory<br />
notice in terminal : failed to remove home directory because of permission denied<br />
![WhatsApp Image 2023-11-21 at 21 39 03(6)](https://github.com/mostafagh10/redhat_track/assets/41267238/7a63ea4c-c7ec-412f-98b3-37d400da2007)

C - 
absolute : ~/Documents<br />
relative : ./Documents
-------------------------------------------------------------------------------------------------------------------------------------------------------
## (q5)
cp /etc/passwd ~/mypasswd

## (q6)
mv ~/mypasswd ~/oldpasswd
![WhatsApp Image 2023-11-21 at 21 39 03(5)](https://github.com/mostafagh10/redhat_track/assets/41267238/8b7e4e83-8553-4c52-9d50-e83d183617ac)
--------------------------------------------------------------------------------------------------------------------------------------------------------
## (q7)
cd /usr/bin<br />
way num 1 : cd ~/<br />
way num 2 : ../../home/mostafa<br />
way num 3 : cd<br />
way num 4 : cd $HOME<br />
![WhatsApp Image 2023-11-21 at 21 39 03(4)](https://github.com/mostafagh10/redhat_track/assets/41267238/51ba2d45-bccb-453c-ae4d-79a9bcee04c6)
--------------------------------------------------------------------------------------------------------------------------------------------------------
## (q8)
cd /usr/bin<br />
ls w*<br />
![WhatsApp Image 2023-11-21 at 21 39 03(3)](https://github.com/mostafagh10/redhat_track/assets/41267238/55b34120-83e5-4981-a351-5c3b81621204)
---------------------------------------------------------------------------------------------------------------------------------------------------------
## (q9)
cd /etc<br />
head -4 ./passwd<br />

## (q10)
head -7 ./passwd<br />
![WhatsApp Image 2023-11-21 at 21 39 03(2)](https://github.com/mostafagh10/redhat_track/assets/41267238/3dcee4e9-9a75-48d7-85cd-3b5f028d16e6)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q11)
man -a passwd<br />
![WhatsApp Image 2023-11-21 at 21 39 03(1)](https://github.com/mostafagh10/redhat_track/assets/41267238/d4a587f8-a676-41a9-b8b1-a4d93dbd4a9f)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q12)
man -s 5 passwd<br />
![WhatsApp Image 2023-11-21 at 21 39 03](https://github.com/mostafagh10/redhat_track/assets/41267238/fa45c0b0-f64d-4ec9-bb69-97c89f5046bd)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q13)
man -K passwd<br />
![Screenshot from 2023-11-22 08-23-45](https://github.com/mostafagh10/redhat_track/assets/41267238/831d3367-cfba-4f27-bf01-861d496de001)
----------------------------------------------------------------------------------------------------------------------------------------------------------
                                                        #[lab 2]
----------------------------------------------------------------------------------------------------------------------------------------------------------
## q1<br />
![Screenshot from 2023-11-22 01-08-39](https://github.com/mostafagh10/redhat_track/assets/41267238/efbde441-9eed-4b82-9160-b362348578ea)
------------------------------------------------------------------------------------
## q2<br />
![Screenshot from 2023-11-22 01-12-01](https://github.com/mostafagh10/redhat_track/assets/41267238/3ee386ef-e4fd-4895-9f4f-7b64b6b9228b)
------------------------------------------------------------------------------------
## q3<br />
![Screenshot from 2023-11-22 01-13-53](https://github.com/mostafagh10/redhat_track/assets/41267238/5ab4712f-947c-47cc-80a6-4f800d77db7a)
-----------------------------------------------------------------------------------
## q4<br />
![Screenshot from 2023-11-22 01-14-27](https://github.com/mostafagh10/redhat_track/assets/41267238/a42a71b3-190a-4353-a2ae-23c4c2290cd5)
-----------------------------------------------------------------------------------
## q5<br />
![Screenshot from 2023-11-22 01-18-59](https://github.com/mostafagh10/redhat_track/assets/41267238/cf7fd933-18c7-49ad-8f88-88c2cd200acb)
-----------------------------------------------------------------------------------
##q6<br />
![Screenshot from 2023-11-22 01-19-50](https://github.com/mostafagh10/redhat_track/assets/41267238/8df16241-08dd-4884-a192-9bff703ce878)
-----------------------------------------------------------------------------------
##q7<br />
![Screenshot from 2023-11-22 06-33-11](https://github.com/mostafagh10/redhat_track/assets/41267238/977a8e49-f176-46d6-8fa7-e6c816d2ade9)
-----------------------------------------------------------------------------------
##q8 <br />
![Screenshot from 2023-11-22 06-35-13](https://github.com/mostafagh10/redhat_track/assets/41267238/e62319c5-8ff4-4573-ab26-c2ac050cf7a2)
-----------------------------------------------------------------------------------
##q9 & q10 <br />
![Screenshot from 2023-11-22 06-36-58](https://github.com/mostafagh10/redhat_track/assets/41267238/3a5b74df-3272-4518-ac11-0bf18eb964ae)
------------------------------------------------------------------------------------
##q13 <br />
![Screenshot from 2023-11-22 13-37-59](https://github.com/mostafagh10/redhat_track/assets/41267238/e87f0751-fd03-40e9-a1c1-dfdfd5d5c81a)
------------------------------------------------------------------------------------
##q14 <br />
![Screenshot from 2023-11-22 13-43-23](https://github.com/mostafagh10/redhat_track/assets/41267238/e33e86e7-ccf8-4eb7-a0c8-228d2542e977)
------------------------------------------------------------------------------------
##q15 <br />
![Screenshot from 2023-11-22 13-48-50](https://github.com/mostafagh10/redhat_track/assets/41267238/4d52e86a-db00-4838-8c45-e536b5fcb607)
------------------------------------------------------------------------------------
##q16 <br />
point A : <br />
![Screenshot from 2023-11-22 13-59-36](https://github.com/mostafagh10/redhat_track/assets/41267238/51919d5c-7ff7-45ce-8160-4a78fca38221)
<br />
point B : <br />
![Screenshot from 2023-11-22 14-14-55](https://github.com/mostafagh10/redhat_track/assets/41267238/1f8fb21f-ee65-4b46-b8b7-ae5c71a717b0)
<br />
point C : <br />max permissions for file by default = 666<br />
max permissions for directory by default = 777
<br />
point D :
![Screenshot from 2023-11-22 14-43-00](https://github.com/mostafagh10/redhat_track/assets/41267238/8e066974-8111-44f4-b3fc-e71f4f3896d0)
--------------------------------------------------------------------------------------
##q17<br />
A - (min permissions to copy directory) :<br />
source directory permissions : 400 & destination direcory permissions : 300 <br />
B - (min permissions to copy file ) : <br />
file permessions : 400 & source dir permissions = 100 & destination dir permissions = 300 <br />
C - (min permissions to delete file) : <br />
source dir permissions = 300 <br />
D - (min permissions to change to directory ) : <br />
source dir permissions = 100 <br />
E - (min permissions to list the directory content )<br />
source dir permissions = 400 <br />
F - (min permissions to view file content) : <br />
source dir permissions = 400 <br />
G- (min permissions to modify the file content) : <br />
file permessions : 600 <br />
---------------------------------------------------------------------
##q18<br />
![Screenshot from 2023-11-22 20-57-35](https://github.com/mostafagh10/redhat_track/assets/41267238/5ee81143-46d4-4253-906b-ddb6450628fe)<br />
notice : when i want to remove the file he gave me the warning before removing it .<br />
----------------------------------------------------------------------
##q19<br />
the execution permission for file when be created = 0<br />
the execution permission for directory when be created = 1<br />
------------------------------------------------------------------------------------------------------------------------------
                                     #[LAB 3]
------------------------------------------------------------------------------------------------------------------------------
## q1
![Screenshot from 2023-11-24 18-57-32](https://github.com/mostafagh10/redhat_track/assets/41267238/b57aefd5-62d5-41c9-be5f-024b03d0302c)
--------------------------------------------------
## q2
A - by press J to move down one line <br />
B - by press K to move up one line <br />
C - <br />
![Screenshot from 2023-11-24 19-08-14](https://github.com/mostafagh10/redhat_track/assets/41267238/2e8cdeb1-2c1f-4a84-8b79-207cb41f5916)<br />
D - by press 5G<br />
E - by press dd,5d<br />
F - by press $i <br />
---------------------------------------------------
## q3
![Screenshot from 2023-11-24 19-21-37](https://github.com/mostafagh10/redhat_track/assets/41267238/ed07b757-eb7e-4179-b18b-57437ab9d3a4)<br />
-----------------------------------------------------
## q4
![Screenshot from 2023-11-24 19-42-28](https://github.com/mostafagh10/redhat_track/assets/41267238/e889ceb4-c82f-4d3d-b214-1b8eb3414ed4)
-----------------------------------------------------
## q5

---------------------------------------------------
## q6
by using printenv command
-----------------------------------------------------
## q7
![Screenshot from 2023-11-24 19-39-28](https://github.com/mostafagh10/redhat_track/assets/41267238/f6ecb65d-0d24-4b91-9863-501ae203b062)

-----------------------------------------------------
























                                                        



























