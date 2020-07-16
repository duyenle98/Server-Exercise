3. Tạo file-a cho user-1 được 3 quyền (read write execute) và groupA chỉ có quyền read

#### Create file-a.txt

touch file-a.txt

![Create-file](./images/create-file.png)

#### Doi chu so huu cua file-a.txt thanh user-1:groupA

sudo chown user-1:groupA file-a.txt

![Change-own](./images/change-own.png)

#### Cap quyen

sudo chmod 740 file-a.txt

![Add-per](./images/add-per.png)

#### Xem quyen

![Show-per](./images/show-per.png)
