# lmv
1. проверяем наличие Vagrant plugins командой
2. ```yaml
3. vagrant plugin list
4. ```
4.  В выводе должен быть **vagrant-vbguest** если этого плагина нет, то устанавливаем **vagrant plugin install vagrant-vbguest**
5.  Далее из директории lvm поднимаем виртуальную машину **vagrant up**
6.  
