# lmv
1. проверяем наличие Vagrant plugins командой ``` vagrant plugin list ```
2. В выводе должен быть ``` vagrant-vbguest ``` если этого плагина нет, то устанавливаем ``` vagrant plugin install vagrant-vbguest ```
3. Далее из директории **lvm** поднимаем виртуальную машину ``` vagrant up ```
4.  Далее создали PV, VG 'dzeh', LV 'test' и 'small'
5.  ![alt text](./Pictures/1vgs-lvs.png)
6.  
