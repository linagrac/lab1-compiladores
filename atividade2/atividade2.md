# Atividade 2 - Expressões Regulares

## Texto analisado
position = initial + rate * 60

## Regex utilizadas
[a-zA-Z_][a-zA-Z0-9_]*
\d+
[=+\-*]
\s+

## Explicação
Utilizamos expressões regulares para identificar tokens em um texto.
Cada regex reconhece padrões como identificadores, números e operadores.
Isso simula o funcionamento de um analisador léxico.
