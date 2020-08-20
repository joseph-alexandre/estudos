Esse espaço destina-se para documentar todo meu conhecimento (ou a maior parte dele) a respeito de Node.js, desde o começo. Este documento será atualizando conforme meu conhecimento na tecnologia progrida.

## Sumário
1. [Instalação do Node.js](#instalação-do-node.js)
    1. [Gerenciador de pacote](#1.-gerenciador-de-pacote)
    2. [Instalação manual](#2.-instalação-manual)
    
    
## Instalação do Node.js

Existem duas maneiras de se instalar o Node.js na máquina, estas são:

### 1. Gerenciador de pacote

#### Windows

Utilizando **Chocolatey:**

`choco install nodejs-lts`

#### Ubuntu

Utilizando **APT**:

`sudo apt install nodejs`

### 2. Instalação manual

Nesse caso, é necessário acessar o site oficial do [Node.js](https://nodejs.org/en/) para obter os intaladores e/ou arquivos necessários.

Após baixar os arquivos, é preciso definir a variável de ambiente para o correto funcionamento do Node.js no sistema.

#### Windows

Abra o prompt de comando e insira o comando:

`setx PATH "%PATH%;[pasta_raiz_do_node]\bin";`

#### Ubuntu

Abra o terminal e insira o comando:

`export PATH=$PATH:/usr/local/[pasta_raiz_do_node]/bin`

Ao utilizar um gerenciador de pacote para realizar a instalação, a variável de ambiente é definida automaticamente.s
