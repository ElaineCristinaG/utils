## inicializar o linux com um pendrive bootável 

## identificar partições de armazenamento no linux ubuntu
```sudo fdisk -l ou lsblk 
```
## criar uma partição, identifique qual é o sitema de aruivos e crie uma partição , se a partição fosse : /dev/sda1 
```sudo mount /dev/sda1 /mnt/
```
## desmontar uma partição:
```sudo umount <nome da partição criada>
```
## copia de diretorios para uma pendrive por exemplo
```cp -r /mnt/home/user/diretorioXPTO /dev/sdb1/
```
## copia de arquivos par um pendrive por exemplo
```cp /mnt/home/user/arquivoXPTO /dev/sdb1/
