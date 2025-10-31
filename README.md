# EI-TRUCK

**EI-TRUCK** é um aplicativo voltado à **gestão inteligente de frotas**, capaz de armazenar dados de telemetria, identificar infrações cometidas por motoristas e correlacioná-las automaticamente com gravações de vídeo, gerando **recortes automáticos dos momentos de ocorrência**.

A plataforma fornece **relatórios completos e rankings de performance**, auxiliando na **redução de riscos**, **melhoria do comportamento ao volante** e **tomada de decisões estratégicas**. Além disso, facilita **auditorias e treinamentos contínuos**, promovendo uma gestão **proativa, segura e eficiente** da frota.

---

## Teste A/B — Interface e Funcionalidade

Com o objetivo de **melhorar a experiência do usuário**, foi realizado um **teste A/B** para comparar a interface original (A) com uma nova versão aprimorada (B).
Na versão **B**, foram introduzidas as seguintes funcionalidades e melhorias:

* **Chatbot interativo**
* **Tela dedicada para análise de viagens**
* **Acesso simplificado às configurações**
* **Sistema de filtragem de motoristas**

Essas mudanças buscaram tornar a navegação mais fluida, intuitiva e dinâmica, aumentando a eficiência das interações com o aplicativo.

---

## Coleta de Dados

### Fonte Inicial

A coleta inicial foi realizada através da plataforma [**Maze**](https://maze.co), responsável por monitorar e registrar os testes de usabilidade.

### Fonte Principal

A principal coleta de dados ocorreu em um **evento familiar** realizado em **03/11/2024**, onde foram obtidas **amostras de 9 participantes** para cada interface (A e B).
Além disso, **dois testes adicionais** foram aproveitados da plataforma Maze, ampliando a base amostral.

Os arquivos estão organizados na pasta **`/dados`**, contendo todos os registros utilizados nas análises.

---

## Descrição da Base de Dados

A base coletada contém diversas colunas, mas apenas duas foram utilizadas nas análises estatísticas:

1. **`Total duration (seconds)`** — Tempo total gasto pelo participante na execução das tarefas, em segundos.
2. **`Tester ID`** — Identificador único de cada testador.

Essas variáveis foram essenciais para medir e comparar o **tempo médio de conclusão** entre as duas interfaces.

---

## Análise Estatística — Teste t de Welch

As análises estatísticas foram conduzidas utilizando o **Teste t de Welch (A > B)**, com verificação de **normalidade, outliers e intervalos de confiança (95% e 99%)**.
Os resultados e gráficos detalhados encontram-se no notebook:
 **`teste_AB.ipynb`**

---

## Conclusão

Os testes e análises têm como objetivo **avaliar o impacto real das melhorias na interface B** sobre o desempenho e eficiência dos usuários do **EI-TRUCK**.
Com base nesses resultados, será possível direcionar futuras decisões de design e funcionalidade, garantindo uma experiência cada vez mais **efetiva, intuitiva e orientada por dados**.

---

## Criador

* **Miguel Araújo de Souza** — Desenvolvedor
   [GitHub](https://github.com/Gueguelas)
