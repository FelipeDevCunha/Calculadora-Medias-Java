🎓 Calculadora de Médias Escolares

Este é um projeto simples desenvolvido em Java para consolidar conhecimentos sobre tipos de dados primitivos, operadores aritméticos e estruturas condicionais (if/else). O programa recebe quatro notas de um aluno, calcula a média aritmética e informa a situação acadêmica.

🚀 Funcionalidades

Entrada de dados via terminal (quatro notas).

Cálculo automático da média aritmética.

Classificação do aluno baseada na média:

Aprovado: Média $\ge 7.0$

Exame: Média entre $5.0$ e $6.9$

Reprovado: Média $< 5.0$

🛠️ Tecnologias Utilizadas

Linguagem: Java

IDE: IntelliJ IDEA

Entrada de dados: java.util.Scanner

📋 Como Executar o Projeto

Certifique-se de ter o JDK (Java Development Kit) instalado em sua máquina.

Clone este repositório:

Bash

git clone https://github.com/SEU_USUARIO/calculadora-medias-java.git

Abra o projeto no IntelliJ IDEA ou em sua IDE de preferência.

Localize o arquivo CalculadoraMedia.java dentro da pasta src.

Execute o método main.

💻 Exemplo de Código

Java

// Trecho principal da lógica condicional

if (media >= 7.0) {

    System.out.println("Status: APROVADO");

} else if (media >= 5.0 && media < 7.0) {
    
    System.out.println("Status: EXAME");

} else {
    
    System.out.println("Status: REPROVADO");
}<img width="1807" height="287" alt="Captura de tela terminal" src="https://github.com/user-attachments/assets/7db8aec1-5140-46d8-b4c5-69a65d097c41" />
