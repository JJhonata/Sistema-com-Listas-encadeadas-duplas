📚 Sistema de Gerenciamento de Livros - Livraria Elegante

Este projeto é um sistema simples de gerenciamento de livros que utiliza uma lista encadeada dupla para armazenar as informações dos livros, e a biblioteca GTK para a interface gráfica.
O sistema permite:

➕ Adicionar novos livros.
🗑️ Remover livros da lista.
🔍 Buscar livros pelo título.
🖼️ Exibir os livros cadastrados em formato de "cards".

⚙️ Funcionalidades
Inserir Livro: Adicionar um novo livro com título, autor, preço e quantidade.
Remover Livro: Remover um livro da lista.
Buscar Livro: Buscar um livro pelo título e exibir suas informações.
Exibir Livros: Exibir todos os livros registrados em um layout de "cards".

🗂️ Arquivos do Projeto
livraria.c: Código principal com todas as funcionalidades e a interface gráfica.
style.css: (Opcional) Estilos customizados para a interface.
logo.png: (Opcional) Imagem de logo exibida na tela inicial.

🖥️ Video no youtube explicando o codigo: https://www.youtube.com/watch?v=ltJZ5JVjo0k

## Pré-requisitos

Antes de começar, você precisará das seguintes ferramentas:

- **MSYS2**: Ambiente Unix-like para Windows.
- **GTK**: Biblioteca para criação de interfaces gráficas.

### 1. Instalar MSYS2

Baixe e instale o [MSYS2](https://www.msys2.org/). Após a instalação, siga os passos abaixo:

1. Abra o terminal MSYS2 e atualize os pacotes:

   ```bash
   pacman -Syu

 - Reinicie o terminal e continue a atualização:
   
   ```bashh
   pacman -Su

2. Instalar GTK e Ferramentas de Desenvolvimento
No terminal MSYS2, instale o GTK3 e o conjunto de ferramentas de desenvolvimento:
   ```bash
   pacman -S mingw-w64-x86_64-gtk3 mingw-w64-x86_64-toolchain
   
   pacman -S mingw-w64-x86_64-toolchain mingw-w64-x86_64-pkg-config


3. Compilação e Execução
   Navegue até o seu diretorio ex:cd /c/Users/Aluno/Desktop/atividade

   1. Compile o código usando o GCC no terminal MSYS2:
    ```bash
    gcc -o livraria livraria.c `pkg-config --cflags --libs gtk+-3.0`

2. Execute o programa:
    ```bash
    ./livraria.exe

### Verificar o PATH

Se após a instalação houver problemas com os comandos `gcc` ou `pkg-config`, você pode verificar se o caminho `/mingw64/bin` foi adicionado ao `PATH` do MSYS2. Isso garante que os comandos sejam encontrados corretamente.

Você pode adicionar o caminho manualmente executando o seguinte comando no terminal do MSYS2:

    ```bash
    export PATH=/mingw64/bin:$PATH


👩‍💻 Desenvolvedores
[José Jhonata Vieira de Oliveira]
[Larissa Vieira de Oliveira]
