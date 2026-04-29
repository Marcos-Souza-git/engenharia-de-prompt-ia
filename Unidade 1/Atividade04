#1. Problema escolhido 

Criar um programa em Python que calcule a média de alunos

#2. Primeira interação (vaga)

### Prompt:

> Programa em python que calcule média


### Resposta obtida (ruim):

```python
media = (9 + 2 + 7 + 4) / 4
print(media)
```

### Problemas desse codigo:
* Não pede dados do usuario que quer calcular a nota
* Não informa se usuario foi reprovado/aprovado
* Não valida entrada

---

#3. Aplicação da equação de prompt ( Persona + Contexto + Restrições + Formato)

### Persona

A IA deve atuar como um professor doutor em Ciência da Computação especializado em ensinar programação em Python para alunos iniciantes.

### Contexto

* Público: Iniciantes na área de Python
* Objetivo: Ensinar a eles a entrada de bancos de dados, validação e lógica
* Ambiente: Executar em terminal

### Restrições 

* Explique de forma clara e didática
* Mostrar o passo a passo do cálculo
* Explicar se o aluno foi aprovado/reprovado

### Formato 

* Python
* O codigo tem que ser explicativo
* Explicação após o codigo executado

---

#4. Prompt estruturado

```markadown
Você em um professor doutorado em programação experiente.

Contexto:
O código sera utilizado por usuários inicantes em Python com pouca experiência na área.

Instrução:
- Código bem organizado
- Explicação simples após o término do código
```

---

#5. Resultado do Prompt

```python
notas = []

# Loop para pedir as 3 notas
for i in range(1, 4):
    while True:
        try:
            nota = float(input(f"Digite a {i}ª nota (0 a 10): "))

            # Validação do intervalo
            if 0 <= nota <= 10:
                notas.append(nota)
                break
            else:
                print("Erro: a nota deve estar entre 0 e 10.")
        except ValueError:
            print("Erro: digite um número válido.")

# Cálculo da média
media = sum(notas) / 3

# Resultado
print(f"\nMédia final: {media:.2f}")

if media >= 7:
    print("Aluno aprovado!")
else:
    print("Aluno reprovado.")
```

**Explicação**

* O programa cria uma lista para guardar as três notas
* Usa um for para pedir as 3 notas ao usuário
* O while True serve para repetir a pergunta caso o usuário digite algo errado
* O try/except evita erro se a pessoa digitar texto em vez de número
* Depois que o usuário inseri as 3 notas válidas, o programa calcula a média
* Se a média obtida pelo usuário for maior ou igual a 7, o aluno é aprovado; caso contrário, reprovado
