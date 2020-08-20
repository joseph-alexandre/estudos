# Instalação do Node.js

Existem duas maneiras de se instalar o Node.js na máquina, estas são:

### 1. Gerenciadores de pacotes.

##### Windows
Utilizando **Chocolatey:**

`choco install nodejs-lts`

##### Ubuntu
Utilizando **APT**:

`sudo apt install nodejs`


### 2. Instalação manual.

Nesse caso, é necessário acessar o site oficial do [Node.js](https://nodejs.org/en/) para obter os intaladores e/ou arquivos necessários.

Após baixar os arquivos, é preciso definir a variável de ambiente para o correto funcionamento do Node.js no sistema.

##### Windows 
Abra o prompt de comando e insira o comando:

`setx PATH "%PATH%;[pasta_raiz_do_node]\bin";
`
#### Ubuntu
Abra o terminal e insira o comando:

`export PATH=$PATH:/usr/local/[pasta_raiz_do_node]/bin`

Ao utilizar um gerenciador de pacote para realizar a instalação, a variável de ambiente é definida automaticamente.s 
