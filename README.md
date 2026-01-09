# 🎮 Jogo Queah em C++

Este projeto consiste na implementação do jogo **Queah**, desenvolvido em **C++**, utilizando a biblioteca gráfica **raylib**.  
O jogo foi criado com foco em lógica de programação, organização de código e persistência de dados em arquivos.

---

## 🎯 Objetivo do Projeto
Desenvolver um jogo funcional em C++ que:
- Utilize interface gráfica
- Armazene informações de jogadores e vencedores
- Aplique conceitos fundamentais da linguagem C++

---

## 🛠️ Tecnologias Utilizadas
- **C++**
- **Raylib** (biblioteca gráfica)
- **Manipulação de arquivos**
- **Programação estruturada**
- **Funções e sobrecarga**

---

## 🧠 Conceitos Aplicados
- Uso de **funções** para modularização do código
- **Sobrecarga de funções**
- Leitura e escrita em **arquivos** para:
  - Histórico de jogadores
  - Registro de vencedores
- Estruturas de controle e lógica de jogo
- Interface gráfica com **raylib**

---

## ▶️ Como Executar

### Pré-requisitos
- Compilador C++ (g++, clang, etc.)
- Biblioteca **raylib** instalada

### Compilação (Windows)
```bash
g++ main.cpp jogo.cpp -o jogo -lraylib -lopengl32 -lgdi32 -lwinmm
