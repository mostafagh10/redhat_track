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
ls w*
![WhatsApp Image 2023-11-21 at 21 39 03(3)](https://github.com/mostafagh10/redhat_track/assets/41267238/55b34120-83e5-4981-a351-5c3b81621204)
---------------------------------------------------------------------------------------------------------------------------------------------------------
## (q9)
cd /etc<br />
head -4 ./passwd

## (q10)
head -7 ./passwd
![WhatsApp Image 2023-11-21 at 21 39 03(2)](https://github.com/mostafagh10/redhat_track/assets/41267238/3dcee4e9-9a75-48d7-85cd-3b5f028d16e6)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q11)
man -a passwd
![WhatsApp Image 2023-11-21 at 21 39 03(1)](https://github.com/mostafagh10/redhat_track/assets/41267238/d4a587f8-a676-41a9-b8b1-a4d93dbd4a9f)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q12)
man -s 5 passwd
![WhatsApp Image 2023-11-21 at 21 39 03](https://github.com/mostafagh10/redhat_track/assets/41267238/fa45c0b0-f64d-4ec9-bb69-97c89f5046bd)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
(q13)
man -K passwd
![Screenshot from 2023-11-22 08-23-45](https://github.com/mostafagh10/redhat_track/assets/41267238/831d3367-cfba-4f27-bf01-861d496de001)
----------------------------------------------------------------------------------------------------------------------------------------------------------





























