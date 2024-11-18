# OpenGL object loader

Este repositório tem o intuito de demonstrar o carregamento de um objeto feio no programa blender sendo carregado com uso da interface OpenGL na linguagem de programação C++. 

### Bibliotecas utilizadas:
- glew
- glfw
- assimp
- glm

<div align="center">
    <img src="https://github.com/user-attachments/assets/2edf8527-0b2f-4f61-a357-8a4ab645724c" alt="OpenGL object loader">
</div>

O objeto utilizado pode ser encontrado [aqui](https://www.fab.com/listings/b0fc635c-325c-424b-be27-a9efb0911bf8).

https://github.com/user-attachments/assets/fc97d24c-08b5-4134-a051-9a95e61e8d4c

As Dependencias não estão incluidas no repositorio

Como rodar:
1. Se estiver utilizando linux e tiver as bibliotecas necessárias instaladas, pode utilizar o script run.sh
2. Se não:
```
mkdir build
cd build
cmake ..
make
```
para compilar o projeto
```
./build/main.run
```
para rodar o programa compilado

talvez o cmake não funcione no seu sistema.
