# Compressor-De-Videos-Node-FFMPEG
Um compressor de videos capaz de reduzir a qualidade da imagem.

PARA FAZER O USO DO PROGRAMA, VOCÊ TERÁ QUE FAZER O DOWNLOAD DO FFMPEG VERSÃO 2019-12-01, DISPONÍVEL NO LINK:
https://www.videohelp.com/software/ffmpeg/old-versions

APÓS FAZER O DOWNLOAD, EXTRAIA O ARQUIVO ZIP E COLOQUE A PASTA JUNTO A PASTA RAIZ DO PROJETO.
RENOMEIE A PASTA DO ARQUIVO PARA "ffmpeg", E RETIRE AS DEMAIS PASTAS, DE FORMA QUE O CAMINHO PARA ACESSAR O .exe SEJA: "Compressor-De-Videos\ffmpeg\bin"

O VÍDEO QUE SERÁ COMPRIMIDO, DEVERÁ SER COLOCADO DENTRO DA PASTA "src";
O COMANDO PARA COMEÇAR A EXECUÇÃO DEVERÁ SER: "node videos ./src 1 1", ONDE ./src É A PASTA ONDE O VIDEO SE ENCONTRA, 1 SIGNIFICA O PRIMEIRO ARQUIVO A SER COMPRIMIDO,
E 1 SIGNIFICA O ÚLTIMO ARQUIVO A SER COMPRIMIDO.

O NOME DOS VIDEOS A SEREM COMPRIMIDOS, DEVERÃO SER 1, 2, 3, 4, ... ASSIM POR DIANTE.
