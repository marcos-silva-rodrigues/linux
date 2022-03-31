# Permissoes de arquivos

usuario -> grupo -> outros
r -> 4
w -> 2
x -> 1


+ mudar a permissão do arquivo com numero
  ```bash
    sudo chmod 664 arquivo.txt
  ```

+ mudar a permissão do usuario arquivo
  ```bash
    sudo chmod u+x arquivo.txt
  ```

+ mudar a permissão do grupo arquivo
  ```bash
    sudo chmod g+x arquivo.txt
  ```

+ mudar a permissão arquivo para outros 
  ```bash
    sudo chmod o+x arquivo.txt
  ```

+ mudar o usuario e o grupo do arquivo
  ```bash
    sudo chown user:group arquivo.txt
  ```

+ mudar o usuario e o grupo do diretorio
  ```bash
    sudo chown -R user:group arquivo.txt
  ```