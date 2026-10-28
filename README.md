# Manual de Uso da Calculadora Casio fx-82MS

Este repositório contém o código-fonte em LaTeX e o PDF final compilado do **Manual de Uso da Calculadora Científica Casio fx-82MS**. O documento foi estruturado seguindo o padrão de publicação da Sociedade Brasileira de Computação (SBC).

## Download do Manual (PDF)

Você pode baixar a versão pronta para leitura diretamente no link abaixo:

*  **pdf/Manual_Calculadora_FX82MS.pdf**

## Conteúdo do Manual

O manual abrange desde o uso básico até operações estatísticas avançadas da calculadora:

1. **Introdução**
2. **Conhecendo a Calculadora**
3. **Operações Básicas**
4. **Potências e Raízes**
5. **Memória**
6. **Cálculos Estatísticos**
7. **Regressão**
8. **Erros Comuns**
9. **Exemplos Práticos**

## Compilação a partir do Código-Fonte

Caso queira modificar o conteúdo ou compilar o documento por conta própria, siga as instruções abaixo:

### Pré-requisitos

Certifique-se de ter uma distribuição LaTeX instalada em seu sistema:
* **Windows:** https://miktex.org/ ou https://www.tug.org/texlive/
* **Linux:** TeX Live (`sudo apt install texlive-full`)

### Passos para Compilação

1. Clone o repositório:
   ```
     git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
     cd SEU-REPOSITORIO/src
   ```
  
2. Compile o arquivo principal via linha de comando ou pela sua IDE de preferência:
   ```
    pdflatex main.tex
    bibtex main
    pdflatex main.tex
    pdflatex main.tex
   ```
