# Arquivos e Diretorios

+ criar um diretorio
  ```bash
  mkdir teste
  ```

+ criar um arquivo
  ```bash
  touch arquivo.txt
  ```

+ copia um arquivo
  ```bash
  cp arquivo.txt outroarquivo.txt
  ```

+ copia o conteudo de um diretorio
  ```bash
  cp -a diretorio ./outrodiretorio
  ```

+ copia o conteudo de um diretorio e subdiretorios
  ```bash
  cp -R diretorio ./outrodiretorio
  ```

+ remove um arquivo
  ```bash
  rm arquivo.txt
  ```
+ remove um diretorio e seus arquivos e subdiretorios
  ```bash
  rm  -rf arquivo.txt
  ```

+ remove um diretorio e seus arquivos e subdiretorios com descrição
  ```bash
  rm  -rfv arquivo.txt
  ```

+ move arquivo entre diretorios
  ```bash
  mv  ./origem ./destino
  ```