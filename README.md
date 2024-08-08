Repositórios oficiais do programa "Parcellite":

http://parcellite.sourceforge.net/
https://github.com/rickyrockrat/parcellite/blob/master/po/pt_BR.po

- - - - -

Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/Parcellite_pt_BR/blob/main/parcellite_pt_BR_13-01-2022.po

Para utilizar o arquivo "parcellite_pt_BR_13-01-2022.po", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"parcellite_pt_BR_13-01-2022.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt parcellite_pt_BR_13-01-2022.po -o parcellite.mo

Comando para renomear o arquivo antigo da tradução com a extensão ".mo" que está na pasta do idioma "pt_BR".

$ sudo mv /usr/share/locale/pt_BR/LC_MESSAGES/parcellite.mo /usr/share/locale/pt_BR/LC_MESSAGES/parcellite_antigo.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp parcellite.mo /usr/share/locale/pt_BR/LC_MESSAGES
