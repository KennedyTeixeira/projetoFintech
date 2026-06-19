# 🚀 OBsystem — Controle Financeiro

Este repositório contém o desenvolvimento do projeto **Fintech OBsystem**, uma aplicação robusta que possui um controle financeiro desenvolvida como parte das atividades práticas do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da **FIAP**. 

O objetivo principal é demonstrar a evolução de um projeto de software real, passando por todas as etapas cruciais da engenharia de software: **Engenharia de Requisitos (Casos de Uso)**, **Modelagem de Banco de Dados (Lógica e Física)** e **Desenvolvimento Front-end**.

---

## 📌 Evolução do Projeto

### 📑 Modelagem de Casos de Uso
Nesta primeira etapa, focamos no entendimento do negócio e no mapeamento do comportamento do sistema a partir da perspectiva do usuário.
* **Ator Principal:** Gestor Financeiro.
* **Casos de Uso Mapeados:**
  * *Cadastrar Conta:* Inclusão de agência, conta corrente e regras de negócio para conta poupança).
  * *Cadastrar Plano de Contas* e *Centro de Custos*.
  * *Registrar Receitas* e *Registrar Despesas*.
  * *Gerar Documento de Entrada e Saída do Financeiro*.
    
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/5860d3d0-a1d5-480a-9671-2f3a015da833" />

---

### 🗄️ Estruturação Lógica e Física do Banco de Dados
Com os requisitos definidos, estruturamos o armazenamento de dados do **OBsystem**, garantindo integridade e consistência através das seguintes entidades:
* **Fluxo Financeiro:** Tabelas de `TITULO`, `CLASSIFICACAO`, `CENTRO_CUSTO` e `PLANO_CONTA`.
* **Operações Comerciais:** Gerenciamento de `VENDA` e `COMPRA`.
* **Core de Cadastro:** Estrutura normalizada de `PESSOA` (especializada em *Pessoa Física/CPF*), além de amarrações para `ENDERECO`, `CONTATO`, `CLIENTE` e `FORNECEDOR`.
* **Integridade:** Definição rigorosa de Chaves Primárias (PKs), Chaves Estrangeiras (FKs) e tipos de dados otimizados para o ecossistema financeiro.
  
*Modelo Lógico de Dados:*
  
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/9b10b1e1-b2d2-4314-b604-4e24fd63b0f1" />

*Modelo Físico de Dados:*
  
<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/9350d0ad-e5d5-41b5-9f88-9453d02a0246" />

---

### 🎨 Desenvolvimento das Telas (Front-end)
A fase atual materializa as duas etapas anteriores em uma interface de usuário funcional, moderna e responsiva.
* **Tecnologias Utilizadas:** HTML5, CSS3 e **Tailwind CSS**.
* **Foco do Desafio:** Recriar com fidelidade os protótipos desenhados nas fases 1, 2 e 3 do curso, utilizando o poder das classes utilitárias do Tailwind para garantir um design limpo, componentes consistentes e total adaptabilidade a diferentes tamanhos de tela (responsividade).

<img width="1919" height="945" alt="image" src="https://github.com/user-attachments/assets/47f87f3c-f957-43bf-847e-5efc3dcb10ac" />

---

## 🛠️ Tecnologias e Ferramentas

* **Análise & Modelagem:** (Astah) | Diagramas de Caso de Uso e (SQL Developer Data Modeler) | Entidade-Relacionamento (DER).
* **Banco de Dados:** (PostgreSQL) | Linguagem SQL e Modelagem Lógica e Física.
* **Front-end:** (VS code) | HTML5, CSS3, Tailwind CSS.
* **Controle de Versão:** (Git Bash) | Git & GitHub.

---

## 🚀 Como Executar o Projeto Localmente

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
