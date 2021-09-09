![pol](https://user-images.githubusercontent.com/73176377/132608949-b5ac7a7e-d211-4e5f-9778-cf17e3383b5c.jpg)

# Node Kurulum Adımları

#Kullanıcı Oluşturma

sudo adduser kullaniciadiniz

sudo visudo
root    ALL=(ALL:ALL) ALL 
kullaniciadiniz ALL=(ALL:ALL) ALL #root altına bu satırı ekle
CTRL+X Y Enter

#Kullanıcıya Yetki Ver/Authorize User
sudo usermod -a -G sudo kullaniciadiniz

sudo su - kullaniciadiniz
