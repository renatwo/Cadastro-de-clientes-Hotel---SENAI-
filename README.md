# Cadastro de Cliente - Hotel SENAI

Projeto desenvolvido em Python durante os estudos no SENAI, com o objetivo de praticar lógica de programação por meio de um sistema simples de cadastro de hóspedes para um hotel.

O sistema permite informar a quantidade de hóspedes, cadastrar nome e idade, escolher o tipo de quarto e calcular o valor total da hospedagem com base na quantidade de dias.

---

## Objetivo do projeto

O objetivo deste projeto é simular um sistema básico de atendimento para hotel, onde é possível:

- Cadastrar hóspedes
- Informar idade dos hóspedes
- Escolher o tipo de quarto
- Definir a quantidade de dias de hospedagem
- Calcular o valor total da estadia
- Exibir um resumo da escolha de cada hóspede

---

## Funcionalidades

O sistema permite cadastrar até 3 hóspedes diretamente pelo terminal.

Para cada hóspede, o programa solicita:

- Nome
- Idade
- Tipo de quarto
- Quantidade de dias de hospedagem

Após isso, o sistema calcula e exibe o valor total da hospedagem.

---

## Tipos de quartos disponíveis

| Código | Tipo de quarto | Valor por dia |
|------:|----------------|--------------:|
| 1 | Simples | R$ 100,00 |
| 2 | Duplo | R$ 150,00 |
| 3 | Luxo | R$ 250,00 |

---

## Tecnologias utilizadas

- Python
- Lógica de programação
- Entrada de dados com `input`
- Condicionais com `if`, `elif` e `else`
- Listas
- Dicionários
- Cálculos matemáticos
- Formatação de valores monetários

---

## Estrutura do projeto

```text
.
├── main.py
└── README.md
```

---

## Como executar o projeto

### 1. Clone o repositório

```bash
git clone URL_DO_SEU_REPOSITORIO
```

### 2. Entre na pasta do projeto

```bash
cd nome-da-pasta-do-projeto
```

### 3. Execute o arquivo Python

```bash
python main.py
```

---

## Exemplo de uso

Ao executar o programa, o sistema pergunta a quantidade de pessoas:

```text
Quantidade pessoas:
```

Depois solicita os dados do hóspede:

```text
Nome:
Idade:
```

Em seguida, apresenta as opções de quarto:

```text
1 - simples R$ 100.0
2 - duplo R$ 150.0
3 - luxo R$ 250.0
```

Após a escolha, o sistema pergunta a quantidade de dias:

```text
Dias:
```

E retorna o valor total da hospedagem:

```text
O hospede Renato escolheu o quarto: luxo
R$ 500.00
Quantidade de dias do hospede Renato -> 2
```

---

## Conceitos praticados

Neste projeto foram praticados conceitos fundamentais de programação, como:

- Criação de variáveis
- Uso de listas
- Uso de dicionários
- Estruturas condicionais
- Entrada e saída de dados
- Conversão de tipos com `int`
- Cálculos com valores numéricos
- Organização de fluxo de execução
- Formatação de valores com `f-string`

---

## Regra de funcionamento

O programa possui tratamento para as seguintes quantidades de hóspedes:

- 1 hóspede
- 2 hóspedes
- 3 hóspedes

Caso seja informado um número maior que 3, o sistema exibe a mensagem:

```text
Para mais hospedes chame o coord.
```

---

## Aprendizados

Com este projeto, foi possível praticar a construção de um sistema simples usando Python, simulando um cenário real de cadastro e cobrança em um hotel.

O projeto reforça a importância de organizar dados, trabalhar com condições e realizar cálculos de forma automatizada.

---

## Possíveis melhorias futuras

Algumas melhorias que podem ser adicionadas futuramente:

- Usar laço de repetição `for` para evitar repetição de código
- Permitir cadastro de qualquer quantidade de hóspedes
- Validar se o usuário escolheu um quarto válido
- Calcular o valor total geral de todos os hóspedes
- Salvar os dados em arquivo `.txt` ou `.csv`
- Criar uma interface gráfica simples
- Organizar o código em funções
- Melhorar a apresentação dos valores em reais

---

## Autor

Desenvolvido por Renato Alves Queiroz.

Projeto acadêmico desenvolvido durante os estudos no SENAI, com foco em lógica de programação e fundamentos da linguagem Python.
