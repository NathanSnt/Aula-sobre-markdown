
# Como usar o **markdown**

## TÍTULOS
```
# Exemplo
## Exemplo
### Exemplo
#### Exemplo
##### Exemplo
```
# Exemplo
## Exemplo
### Exemplo
#### Exemplo
##### Exemplo

## NEGRITO
```
**Frase em negrito**
ou
__Frase em negrito__
```
**Essa é uma frase em negrito**

## ITÁLICO
```
*Frase em itálico*
ou
_Frase em itálico_
```
*Essa é uma frase em itálico*

## ITÁLICO E NEGRITO
```
**_Frase em Negrito e Itálico_**
ou
__*Frase emNegrito e Itáliso*__
```
**_Essa é uma frase em Negrito e Itálico_**

## FRASE RASURADA
```
##Frase rasurada##
ou
~~Frase rasurada~~
```
~~Essa é uma frase rasurada~~

## LINHA HORIZONTAL
```
--- OU ***
```
---

## LISTA NUMÉRICA
```
1. Item
1. Item
1. Item
```
1. Item 1
1. Item 2
1. Item 3

## LISTA ANINHADA
```
1. Item
1. Item
   2. Item
   2. Item
      3. Item
      3. Item
   2. Item
1. Item
1. Item
```
1. Item 1
1. Item 2
   1. Item a
   1. Item b
      1. Item 1
      1. Item 2
   2. Item c
1. Item 3  
1. Item 4

## LISTA DEMARCADA COM PONTO
```
- item
OU
* item
```
- Exemplo 1
- Exemplo 2
   - Exemplo a
   - Exemplo b
      - Exemplo 1
      - Exemplo 2
   - Exemplo c
- Exemplo 3
- Exemplo 4

## LISTA DE TAREFA
```
- [ ] Nome da tarefa
- [x] Tarefa concluida
```
- [x] Estudar para a prova
- [x] Limpar a casa
- [ ] Levar o cachorro para passear
- [ ] Preparar a janta

## IMAGEM
- ### arrastar a imagem para o campo de texto ou  
```![Descrição da imagem](Link da imagem)```  

![baa41a0eb413a4798803a4dbb1cffc4a](https://user-images.githubusercontent.com/79227411/125203376-81ec3700-e24e-11eb-9a6c-822358a125ff.jpg)  

## LINK
```[Descrição do link](Link)```  
[Exemplo](https://github.com/NathanSnt)  

## IMAGEM COM LINK 
```[![Descrição da imagem](link da imagem)](link)```  

[![alguma coisa](https://user-images.githubusercontent.com/79227411/125203376-81ec3700-e24e-11eb-9a6c-822358a125ff.jpg)](https://github.com/NathanSnt)  

## TABELA
```
coluna 1 | coluna 2 | coluna 3
---|---|---
valor 1 | valor 2 | valor 3
```
### resultado:  
coluna 1 | coluna 2 | coluna 3
---|---|---
valor 1 | valor 2 | valor 3

## LINHA DE COMANDOS

- ###  coloque o comando entre crases ``` ` código vai aqui ` ```  
`print(Exemplo)`

## TRECHO DE CÓDIGO
- ### Coloque o código entre três crease \```

```
num = int(input('Digite um número: '))
if num % 2 == 0:
    print(f'O número {num} é PAR')
else:
    print(f'O número {num} é ÍMPAR')
```

## EMOJI

` :NomeDoEmoji: `  
:monkey:
## CITAR PESSOAS

` @NomeDaPessoa `  
@NathanSnt

`>Texto qualquer`  
 >Texto qualquer

Como o @NathanSnt havia dito anteriormente:
> Estudem! Se a vida já é dificil com conhecimento...  
> Imaginem como será sem ele.

## MENCIONAR ISSUES
` Seu problema foi resolvida na issue #4` 

## ESCAPE DE CÓDIGO
- ### para conseguir escrever algum código do markdown coloque uma contra-barra antes do código
```\!\[Qualquer coisa]\(youtube.com)```
- \!\[Qualquer coisa]\(youtube.com)
