# Atividade 4 - Scanner com Python

## Código
import re

codigo = "position = initial + rate * 60"

regexp = r'[a-zA-Z_][a-zA-Z0-9_]*|\d+|[=+\-*]'

tokens = re.findall(regexp, codigo)

print(tokens)

## Explicação
Utilizamos Python e expressões regulares para criar um mini scanner.
A regex identifica identificadores, números e operadores.
O programa retorna os tokens encontrados no código.
