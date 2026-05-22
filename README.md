# Calculadora Conversora Metalúrgica — Documentação Técnica

Este repositório contém os artefatos de modelagem, arquitetura e padronização visual desenvolvidos para o sistema **Calculadora Conversora Metalúrgica**. O objetivo desta etapa é garantir uma base sólida e padronizada para o desenvolvimento das próximas fases do projeto.

## Equipe
* Julia Nunes
* Matheus Luiz
* Miguel Pereira
* Nathalia Modesto
* Vinícius Paes

## Artefatos do Projeto

Abaixo estão listados e detalhados os artefatos obrigatórios da área de documentação do desenvolvedor:

### 1. Modelagem do Banco de Dados (DER)
A estrutura de dados foi modelada para suportar o fluxo de peças, processos de usinagem, parâmetros de corte e cálculo de custos.

* **Principais Entidades:** 
  * MaterialPeca, Peça Bruta e PecaFinal (Gestão de insumos e produtos)
  * maquina, operacao e parametroCorte (Fatores técnicos de fabricação)
  * processousinagem (Entidade central que unifica o processo)
  * custo (Cálculo financeiro indexado ao processo)

### 2. Diagrama de Classes
Mapeamento da estrutura dos componentes do sistema, contendo as classes, atributos, métodos e as relações de dependência/associação necessárias para a lógica de negócio da calculadora.

### 3. Design System (Padronização Visual)
Guia de estilo simplificado para garantir a consistência de interface (UI) e experiência do usuário (UX) do software.

* **Tipografia:**
  * **Títulos e Subtítulos:** Etna Sans Serif (H1: 40-60px | H2: 28-36px)
  * **Corpo de Texto:** Clear Sans (Mínimo de 18-24px)
* **Paleta de Cores (Diretriz 60-30-10):**
  * Vermelho (`#1e293b` ou correspondente do sistema)
  * Verde (`#14974f`)
  * Bege claro (`#fffaed`)
* **Ícones:** Divisão padronizada entre *Ícones de Sistema* (ações gerais como fechar/voltar) e *Ícones de Produto* (representação de ferramentas específicas do setor metalúrgico).

## Próximos Passos
Com a base de dados modelada, a arquitetura de classes desenhada e a identidade visual definida, o projeto avançará para a fase de desenvolvimento do backend (regras de negócio e persistência de dados) e construção das telas do protótipo funcional.