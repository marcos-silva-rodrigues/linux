# Gerencia usuarios e grupos

+ adiciona usuarios
  ```bash
  useradd nome-do-usuario
  ```

+ adiciona usuarios pedindo info
  ```bash
  adduser nome-do-usuario
  ```

+ modifica a senha do usuario 
  ```bash
  passwd nome-do-usuario
  ```

+ adiciona usuarios impedindo ele de acessar o shell
  ```bash
  useradd nome-do-usuario -s /bin/false
  ```

+ alterar o diretorio home do usuario
  ```bash
  usermod -d /path nome-usuario
  ```

+ alterar a data de validade do usuario
  ```bash
  usermod -e 2022-04-28 nome-usuario
  ```

+ deleta usuario
  ```bash
  userdel nome-usuario
  ```

+ cria um grupo
  ```bash
  groupadd nome-grupo
  ```

+ cria uma senha para o grupo
  ```bash
  gpasswd nome-grupo
  ```

+ modifica o grupo
  ```bash
  groupmod nome-grupo
  ```

+ deleta o grupo
  ```bash
  groupdel nome-grupo
  ```

+ adiciona o usuario a um  grupo
  ```bash
  usermod -G nome-grupo nome-usuario
  ```

