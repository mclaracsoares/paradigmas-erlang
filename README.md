# Projeto com Linguagem Erlang

<img width="1992" height="1186" alt="image" src="https://github.com/user-attachments/assets/bc81d4ec-9ba8-448f-a7ba-d5118dffb841" />

# 🧠 Projeto Erlang — Paradigma Funcional

## 📘 Descrição

Este projeto foi desenvolvido como parte da disciplina de **Paradigmas de Linguagens de Programação**, com o objetivo de demonstrar os conceitos do **paradigma funcional** aplicados em **Erlang**.

A aplicação, executada via terminal (CLI), apresenta três funcionalidades principais:

- **Conversões monetárias:** Real ↔ Dólar, Real ↔ Euro
- **Estatísticas:** cálculo de média, mediana, mínimo e máximo de um vetor
- **Validação:** verificação de CPF e e-mail

O sistema foi estruturado em **módulos independentes**, destacando a **modularidade e clareza do código** — princípios fundamentais da programação funcional.

---

## ⚙️ Como compilar e executar

### 🔹 Compilação

1️⃣ **Instalar o Erlang**

- Faça o download em: [https://www.erlang.org/downloads](https://www.erlang.org/downloads)

2️⃣ **Abrir o terminal Erlang**  
Abra o terminal na pasta do projeto e digite:

```
erl
```

3️⃣ **Verificar se está na pasta correta**  
Dentro do shell Erlang, use os comandos:

```
pwd().   % mostra o caminho atual
ls().    % lista os arquivos na pasta
```

Certifique-se de que os arquivos `main.erl`, `conversion.erl`, `stats.erl` e `validate.erl` estão listados.

4️⃣ **Compilar os módulos**

```
c(conversion).
c(stats).
c(validate).
c(main).
```

5️⃣ **Executar o programa principal**

```
main:start().
```

O menu principal será exibido com as opções:

```
1 - Conversões monetárias
2 - Estatísticas
3 - Validações
4 - Sair
```

Após isso, todas as funcionalidades estarão disponíveis para teste. 🎯

---

## 💡 Funcionalidades

### 🔹 Conversões monetárias

- Real ↔ Dólar
- Real ↔ Euro

Os valores de conversão são fixos e definidos no código.

---

### 🔹 Estatísticas

Recebe um vetor numérico e calcula:

- Média
- Mediana
- Valor mínimo
- Valor máximo

---

### 🔹 Validação

Realiza a verificação de:

- **CPF:** valida formato e dígitos verificadores
- **E-mail:** valida estrutura básica (ex: nome@dominio.com)

Caso a entrada seja inválida, o sistema exibe **mensagens de erro amigáveis**.

---

## 💬 Aprendizados e Reflexões

Durante o desenvolvimento, enfrentamos **dificuldades iniciais** com a **sintaxe de Erlang**, que exige atenção a detalhes como pontos finais, colchetes e vírgulas — o que pode causar erros facilmente se não houver cuidado.

Para tornar o código mais acessível, buscamos **simplificar a estrutura e minimizar erros de digitação**, sem perder a lógica funcional.

Com o avanço do projeto, foi possível compreender e aplicar conceitos importantes, como:

- Modularidade
- Recursão
- Funções puras
- Imutabilidade

Esses princípios reforçaram a importância de pensar em termos de **composição funcional** e **clareza de código**, evitando efeitos colaterais e promovendo estabilidade.

---

## ⚖️ Conclusões

O estudo e desenvolvimento em Erlang proporcionaram uma compreensão mais profunda do **paradigma funcional**.

Entre as **vantagens observadas**, destacam-se:

- Estabilidade e previsibilidade do comportamento
- Simplicidade conceitual
- Clareza na separação das funções

Entretanto, também percebemos **limitações**, como:

- Menor suporte a bibliotecas modernas
- Curva de aprendizado mais acentuada para iniciantes

Mesmo assim, a experiência reforçou o valor da **linguagem funcional** para sistemas confiáveis e tolerantes a falhas, como os utilizados em telecomunicações e aplicações distribuídas.

---

## 👥 Integrantes
- Maria Clara C. Soares 
- Pedro Filipe Macedo
- Artur Camara
- José Clayton
- Igor Carvalheira
- Marco Antonio Arcoverde
- Pedro Henrique Bezerra
- Lucas E. Gurgel

## Professor
- Paulo Henrique Rocha
