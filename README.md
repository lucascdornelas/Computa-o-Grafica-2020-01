# Computação Grafica 2020/01
<h4> Lucas Cota Dornelas <h4>

Tutorial: Como instalar e utilizar a biblioteca SOIL no Linux.
    Feito por Lucas Cota Dornelas. - 2020/01

Soil - Simple-OpenGL-Image-Library - é uma biblioteca utilizada para adicionar imagens em programas que usam OpenGL. GitHub

Instalando a biblioteca Soil:
        # apt-get install libsoil-dev
Adicionando a biblioteca no código:
include <SOIL.h>
Assim, a biblioteca já está referenciada e todas as suas funções já estão disponíveis no código. Contudo, para compilar o arquivo é necessário passar o parâmetro. 
# gcc main.c - o main - lSOIL


Para instalar as bibliotecas glew e  freeglut:
Instalando as bibliotecas:
# apt-get install freeglut3-dev
# apt-get install libglew-dev
Suas referências, respectivamente, para compilar é: 
-lglut e  -lGL   


