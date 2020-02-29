# Computação Grafica 2020/01
<h4> Lucas Cota Dornelas </h4>

<h1>Tutorial: Como instalar e utilizar a biblioteca SOIL no Linux.</h1>
    <h3>Feito por Lucas Cota Dornelas. - 2020/01</h3>

<p>Soil - Simple-OpenGL-Image-Library - é uma biblioteca utilizada para adicionar imagens em programas que usam OpenGL. GitHub</p>

<h2>Instalando a biblioteca Soil:</h2>
    apt-get install libsoil-dev
<h4>Adicionando a biblioteca no código:</h4>
    <p>include <SOIL.h></p>
<h4>Assim, a biblioteca já está referenciada e todas as suas funções já estão disponíveis no código. Contudo, para compilar o arquivo é necessário passar o parâmetro.</h4> 
    gcc main.c - o main - lSOIL


Para instalar as bibliotecas glew e  freeglut:
Instalando as bibliotecas:
    apt-get install freeglut3-dev
    apt-get install libglew-dev
Suas referências, respectivamente, para compilar é: 
-lglut e  -lGL   


