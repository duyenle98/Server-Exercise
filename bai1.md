# bài thực hành về user, group, file

1. Tạo 3 user(user-1, user-2, user-3), 2 group(groupA, groupB)

   #### Create user:

   sudo useradd -d /home/user-1 -m user-1
   sudo passwd user-1

   sudo useradd -d /home/user-2 -m user-2
   sudo passwd user-2

   sudo useradd -d /home/user-3 -m user-3
   sudo passwd user-3

   ![User-b1](./images/user-b1.png)

   #### Create group:

   sudo groupadd groupA
   sudo groupadd groupB
