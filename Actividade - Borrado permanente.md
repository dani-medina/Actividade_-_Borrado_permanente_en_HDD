# Actividade - Borrado permanente en HDD



## Obxectivos:

- Diferenciar entre eliminación estándar e borrado permanente.
- Empregar ferramentas de borrado seguro para destruír ficheiros de xeito irreversible.
- Reflexionar sobre implicacións éticas e legais do borrado permanente.

## Precacución

Confirma o disco é realmente o que queres borrar.
Todo dato se perderá permanentemente.
Non interrumpas o proceso unha vez iniciado.
Fai backup de cualquier dato importante antes de continuar.

## Modo de traballo

Cada exercicio pode facerse en paralelo con outros.


## Exercicio 1 - Data Craving básico con Photorec

- [ ] Clona unha máquina Windows. Chama á maquina Ac-BorradoPermanente-Ex1
- [ ] Crea  un directorio chamado DatosConfidenciais no Escritorio.
- [ ] Copia os arquivos deste repo [Github - Arquivos](https://github.com/dani-medina/Actividade_-_Borrado_permanente_en_HDD/tree/main/Arquivos) ao cartafol DatosConfidenciais, e botalles un ollo para ver o que conteñen.
- [ ] Borra os arquivos como faría calquera usuario (baleira a papeleira de reciclaxe)
- [ ] Utiliza a ferramenta PhotoRec para recuperar os datos borrados.
- [ ] Fai un resumo cos problemas que te atopaches coa ferramenta, os pros e os contras.

## Exercicio 2 - Data Craving básico con Recuva

- [ ] Clona unha máquina Windows. Chama á maquina Ac-BorradoPermanente-Ex2
- [ ] Crea  un directorio chamado DatosConfidenciais no Escritorio.
- [ ] Copia os arquivos deste repo [Github - Arquivos](https://github.com/dani-medina/Actividade_-_Borrado_permanente_en_HDD/tree/main/Arquivos) ao cartafol DatosConfidenciais, e botalles un ollo para ver o que conteñen.
- [ ] Borra os arquivos como faría calquera usuario (baleira a papeleira de reciclaxe)
- [ ] Utiliza a ferramenta PhotoRec para recuperar os datos borrados.
- [ ] Fai un resumo cos problemas que te atopaches coa ferramenta, os pros e os contras.

## Exercicio 3

- [ ] Clona unha máquina Windows. Chama á maquina Ac-BorradoPermanente-Ex3
- [ ] Engade un disco virxe SATA de tamaño 1 GB á máquina. Se tes dúbidas aquí tes unha guía [Adding and removing disk drive in VirtualBox](https://progmar.net.pl/en/knowledge-base/virtualbox-adding-removing-disk-drive)
- [ ] Prepárao para gardar información cun sistema de arquivos NTFS. Se tes dúbidas de como facelo aquí tes unha guía de Seaguete: [Cómo formatear su unidad en Windows | Seagate España](https://www.seagate.com/es/es/support/kb/how-to-format-your-drive-on-windows/) 
- [ ] Crea no novo disco un cartafol chamado DatosConfidenciais.
- [ ] Copia os arquivos deste repo [Github - Arquivos](https://github.com/dani-medina/Actividade_-_Borrado_permanente_en_HDD/tree/main/Arquivos) ao cartafol DatosConfidenciais.
- [ ] Documéntate sobre  sdelete de sysinternals.
- [ ] Borra os arquivos de xeito permanente.
- [ ] Utiliza a ferramenta PhotoRec e Recuva para recuperar os datos borrados. Foi posible?





## Exercicio 4

- [ ] Clona Debian Server. Chama á máquina Ac-BorradoPermanente-Ex4.
- [ ] A máquina debe ter dúas tarxetas de rede: unha en NAT e outra en Host-Only. Se tes dúbidas de como crear unha interface hostonly sigue esta guía: [Host-only Networking in VirtualBox
](https://condor.depaul.edu/glancast/443class/docs/vbox_host-only_setup.html)
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Crea un directorio chamado DatosConfidenciais no cartafol home do usuario *adminsitrador*.
- [ ] Copia os arquivos deste repo [Github - Arquivos](https://github.com/dani-medina/Actividade_-_Borrado_permanente_en_HDD/tree/main/Arquivos) ao cartafol DatosConfidenciais. Podes facelo por SSH e SCP ou con curl/wget.
- [ ] Borra os arquivos como faría calquera usuario (rm -fr).
- [ ] Utiliza a ferramenta PhotoRec para recuperar os datos borrados.
- [ ] Fai un resumo cos problemas que te atopaches.


## Exercicio 5
- [ ] Inicia a máquina do exercicio 3. 
- [ ] Volve a copiar os arquivos ao disco de 1 GB.
- [ ] Apaga a máquina.
- [ ] Clona Debian Server. Chama á máquina Ac-BorradoPermanente-Ex5.
- [ ] A máquina debe ter dúas tarxetas de rede: unha en NAT e outra en Host-Only. Se tes dúbidas de como crear unha interface hostonly.
- [ ] Vincula o disco anterior dun 1 GB á máquina Ac-BorradoPermanente-Ex5. Se non sabes como facelo: [How to add a virtual hard disk in VirtualBox virtual machine](https://www.simplified.guide/virtualbox/disk-add)
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Monta o sistema de arquivos NFTS de 1 GB. Se non tes claro como facerlo: [How to Mount NTFS Partition in Linux {Read-only & Read-and-Write}](https://phoenixnap.com/kb/mount-ntfs-linux)
- [ ] Verifica que podes ver os arquivos.
- [ ] Saca un snapshot da máquina. Aquí tes unha guía de como facelo: [Instantáneas (snapshot) | Tutorial de VirtualBox](https://www.fpgenred.es/VirtualBox/instantneas_snapshot.html)
- [ ] Borra os arquivos como faría calquera usuario (rm -fr).
- [ ] Utiliza a ferramenta Foremost para recuperar os datos borrados.

## Exercicio 6

- [ ] Recupera o snapshot da máquina Debian Server. Ac-BorradoPermanente-Ex5.
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Monta o sistema de arquivos NFTS de 1 GB
- [ ] Verás o directorio chamado DatosConfidencias e os arquivos que borramos no exercicio anterior.
- [ ] Borra os arquivos como faría calquera usuario (rm -fr).
- [ ] Utiliza a ferramenta Scalpel para recuperar os datos borrados.

## Exercicio 7

- [ ] Recupera o snapshot da máquina Debian Server. Ac-BorradoPermanente-Ex5.
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Monta o sistema de arquivos NFTS de 1 GB
- [ ] Verás o directorio chamado DatosConfidencias e os arquivos que borramos no exercicio anterior.
- [ ] Documéntate sobre  shred.
- [ ] Borra os arquivos de xeito permanente.
- [ ] Utiliza as ferramentas PhotoRec, foremost e scalpel para recuperar os datos borrados. Foi posible?



## Exercicio 8

- [ ] Recupera o snapshot da máquina Debian Server. Ac-BorradoPermanente-Ex5.
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Monta o sistema de arquivos NFTS de 1 GB
- [ ] Verás o directorio chamado DatosConfidencias e os arquivos que borramos no exercicio anterior.
- [ ] Documéntate sobre  wipe.
- [ ] Borra os arquivos de xeito permanente.
- [ ] Utiliza as ferramentas PhotoRec, foremost e scalpel para recuperar os datos borrados. Foi posible?



## Exercicio 9
- [ ] Recupera o snapshot da máquina Debian Server. Ac-BorradoPermanente-Ex5.
- [ ] Conéctate por SSH a través da IP hostonly (192.168.56.X).
- [ ] Monta o sistema de arquivos NFTS de 1 GB
- [ ] Verás o directorio chamado DatosConfidencias e os arquivos que borramos no exercicio anterior.
- [ ] Apaga a máquina. Inicia a máquina con ISO de CAINE 12.
- [ ] Encende a máquina coa distro CAINE en modo live.
- [ ] Consegue destruír a información de todo o disco de 1 GB e que non sexa recuperable utilizando o comando scrub.
- [ ] Utiliza as ferramentas PhotoRec, foremost e scalpel para recuperar os datos borrados. Foi posible?



## Exercicio 10

- [ ] Explica a diferenza entre eliminar e borrar permanentemente.
- [ ] Describe cal foi a ferramenta que usaches e por que é efectiva para borrado antiforense.
- [ ] Reflexiona sobre os posibles riscos éticos e legais de usar borrado permanente en entornos reais.
- [ ] Elabora un protocolo e os documentos necesarios (por exemplo, formularios) para proceder a destrución da información relevante dunha organización.





## Autor

Daniel Medina Méndez

[www.linkedin.com/in/daniel-medina-méndez](www.linkedin.com/in/daniel-medina-méndez)

## Licenza do documento

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
