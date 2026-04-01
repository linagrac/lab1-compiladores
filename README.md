# LAB 1 - Compiladores

## Identificação

Faculdade: PUC-SP  
Curso: Ciência da Computação  
Disciplina: Compiladores  
LAB: Analisador Léxico  

Equipe:
- Carolina Olmos Gracio  
- Deborah Saad  

---

## Objetivo

O objetivo deste laboratório foi compreender o funcionamento de um analisador léxico (scanner), utilizando expressões regulares e autômatos finitos para reconhecimento de padrões em textos e códigos.

---

## Atividade 1 – Scanner em Bash

Foi realizada a simulação de um scanner simples utilizando script Bash, demonstrando como um código pode ser percorrido e dividido em tokens.

---

## Atividade 2 – Expressões Regulares

Utilizamos ferramentas online como regexr e regex101 para criar expressões regulares capazes de identificar:
- Identificadores  
- Números inteiros  
- Operadores  
- Espaços  

Isso demonstrou como tokens são definidos por padrões.

---

## Atividade 3 – Find/Replace com Regex

Aplicamos expressões regulares em arquivos reais, realizando substituições e limpeza de dados, como:
- Remoção de comentários  
- Alteração de operadores  
- Limpeza de arquivos CSV  

---

## Atividade 4 – Scanner em Python

Foi implementado um scanner em Python utilizando a biblioteca `re`, capaz de identificar tokens em uma string.

---

## Atividade 5 – Autômatos Finitos (JFLAP)

Criamos autômatos finitos determinísticos (DFA) e não determinísticos (NFA) para reconhecer padrões como:
- Números  
- Identificadores  
- Operadores  

Também realizamos a conversão de NFA para DFA.

---

## Atividade 6 – Tokenizer OpenAI

Comparação entre tokens de compiladores e tokens de IA:

- O tokenizer da OpenAI utiliza BPE (Byte Pair Encoding)
- Já o scanner de compiladores segue regras rígidas da linguagem

Exemplo:
A palavra "position" pode ser quebrada em partes menores pela IA, mas em compiladores ela é um único token.

---

## Atividade 7 – Scanner de Livro

Foi desenvolvido um scanner em Python para analisar um texto literário em português, utilizando expressões regulares para separar palavras e pontuações.

Entrada:
- Arquivo `.txt` contendo texto do livro

Saída:
- Lista de tokens (palavras e símbolos)

---

## Atividade Extra – IA como Analisador Léxico

Foi solicitado a uma IA a criação de um scanner capaz de identificar tipos de tokens (verbo, artigo, etc.).

### Resultado

A IA conseguiu gerar um código funcional, porém limitado.

### Discussão

Não é possível representar completamente a língua portuguesa com expressões regulares, pois ela possui estruturas complexas que exigem gramáticas mais avançadas (livres de contexto).

---

## Conclusão

O analisador léxico é responsável por transformar o código em tokens, sendo a primeira etapa de um compilador.

Os autômatos finitos são a base teórica desse processo, enquanto as expressões regulares definem os padrões reconhecidos.

---

## Reflexão 

Este laboratório foi importante para entender como linguagens de programação são interpretadas internamente.

Aprendemos que o scanner é uma etapa fundamental do compilador e que, apesar de parecer simples, envolve conceitos importantes como autômatos finitos e grmáticas formais.
