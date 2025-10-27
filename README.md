# EI-TRUCK
**EI-TRUCK** O Ei-truck é um app que ...

## Teste A/B - Interface e Funcionalidade

Para aprimorar a experiência do usuário, realizamos um teste A/B em que foram feitas as seguintes alterações na interface B:

- **Chat-bot** 
- **Tela de fazer uma analise de uma viagem**
- **Acesso as configurações** 
- **Filtragem de motoristas**


## Coleta de Dados

### Fonte Inicial
Inicialmente, usamos a plataforma [Maze](https://maze.co) para realizar e monitorar os testes.

### Fonte Principal
A principal coleta de dados foi realizada em um evento familiar em 03/11/2024, onde conseguimos coletar amostras de 9 participantes para cada interface (A e B). Além disso, dois testes foram aproveitados da plataforma Maze.

Os dados estão armazenados na pasta de `dados`

## Descrição da Base de Dados

A base de dados coletada para análise do Teste A/B contém muitas colunas, mas as necessárias usadas para analise são:

1. **Total duration (seconds)** Tempo total de execução das tarefas para cada usuário em uma interface específica.
2. **Tester ID** Indica o ID do usuario.


## Análise de Teste-T

As análises do teste-t podem ser encontradas nos notebooks:
- `teste_AB.ipynb`


Esperamos que o resultado deste teste nos ajude a identificar melhorias na interface do EI-TRUCK, proporcionando uma experiência ainda mais eficiente para nossos usuários.

<h2>Criador:</h2>
<ul>
<li><strong>Miguel Araújo de Souza</strong> - <a href="https://github.com/Gueguelas">GitHub</a></li>
</ul>