# 🌐 Criando um Monitoramento de Custos no Data Factory: Microsoft Azure com Conta Gratuita de Estudante
Microsoft AI for Tech - Azure Databricks: Este repositório faz parte do Desafio de Projeto da DIO "Criando um Monitoramento de Custos no Data Factory".

## 📘 Introdução

Este projeto tem como objetivo oferecer uma abordagem prática e acessível ao ambiente da Microsoft Azure, utilizando uma conta gratuita de estudante. A proposta é guiar o usuário desde os primeiros passos na plataforma até a criação de recursos completos, com foco especial na implantação e configuração do **Azure Data Factory (ADF)**.

---

## ☁️ Visão Geral da Microsoft Azure

A Microsoft Azure é uma plataforma de computação em nuvem que oferece uma ampla variedade de serviços para desenvolvimento, armazenamento, análise, inteligência artificial, redes, segurança e muito mais. Esses serviços permitem que empresas e desenvolvedores criem, testem, implantem e gerenciem aplicações em escala global.

---

## 📊 Meu Dashboard

O dashboard personalizado no Azure é uma ferramenta visual que centraliza as principais informações e recursos da conta em uma única tela. Ele permite ao usuário:

- Fixar recursos importantes, como bancos de dados, máquinas virtuais ou pipelines;
- Acompanhar métricas em tempo real;
- Visualizar alertas, consumo de recursos e monitoramento de performance;
- Criar diferentes dashboards para diferentes propósitos (ex: um para desenvolvimento, outro para produção).

Essa personalização é ideal para manter o controle sobre o ambiente, oferecendo agilidade na tomada de decisões e melhor organização visual. É possível “pinar” qualquer recurso diretamente ao dashboard com um simples clique.

---

## ⚙️ Criação de Recursos no Azure – Data Factory

### 1. Início da Criação de Recursos

- Todo recurso no Azure deve estar associado a um **Grupo de Recursos**, que serve para organizar serviços relacionados ao mesmo projeto.

#### Importância do Grupo de Recursos

- Essencial para **gestão, manutenção, controle de custos e organização**.
- Cada recurso deve obrigatoriamente pertencer a **um único grupo de recursos**.

---

### 2. Padrão de Nomenclatura no Azure

- Uso de **abreviações padronizadas**:
  - `adf` → Azure Data Factory  
  - `cosmos` → Azure Cosmos DB database
  - `vm` → Virtual machine  
  - `sqldb` → Azure SQL database

- O sistema faz **validação automática** dos nomes durante a criação.

---

### 3. Escolha da Localização (Region/Location)

- A escolha da região depende de:
  - Requisitos de latência;
  - Normas de compliance;
  - Exigências do cliente.

- Regiões comuns:
  - `Brazil South` → hospedagem nacional, para clientes com essa exigência;
  - `East US` ou `West Europe` → melhor custo-benefício.

---

### 4. Configurações Avançadas na Criação

- **Integração com DevOps** (GitHub, Azure Repos);
- Configurações de **rede, segurança e criptografia**;
- Uso de **Tags** para organização:
  - Ex: `projeto = financeiro`, `ambiente = produção`.

---

### 5. Validação e Implantação do Recurso

- Validação automática feita pelo Azure;
- Resumo final da configuração exibido antes da criação.

---

### 6. Templates e Automação (ARM Templates)

- Geração de templates JSON com base na interface gráfica;
- Ideal para replicação e padronização de configurações.

---

### 7. Acompanhamento da Implantação

- Notificações em tempo real do progresso da criação;
- Detalhamento dos passos e provisionamentos executados.

---

### 8. Acesso ao Recurso Criado

- Após a criação, o recurso já pode ser acessado e gerenciado diretamente.

---

## 🛠️ Gerenciamento do Recurso Azure Data Factory

Após a criação, é possível gerenciar diversas funcionalidades:

---

### 1. Ver Informações do Recurso

- Acesse a **visão geral** para consultar:
  - Nome;
  - Tipo;
  - Localização;
  - Status;
  - Logs de atividade.

---

### 2. Configurar Controle de Acesso (IAM)

- Vá até **"Controle de Acesso (IAM)"**;
- Atribua funções como `Leitor`, `Contribuidor`;
- Selecione o usuário e aplique a permissão.

---

### 3. Gerenciar Marcações (Tags)

- Crie ou edite tags para organização:
  - Exemplo: `Ambiente = Produção`, `Dono = Equipe X`.

---

### 4. Aplicar Bloqueios (Locks)

- Bloqueios disponíveis:
  - **Somente leitura**;
  - **Impedir exclusão**.

---

### 5. Personalizar o Dashboard

- Fixe gráficos e recursos no painel;
- Crie dashboards separados por equipe ou projeto;
- Edite visualmente tamanho, posição e cores.

---

### 6. Utilizar Notificações

- Acompanhe notificações como:
  - Sucesso na criação;
  - Erros;
  - Alertas de uso e performance.

---

### 7. Acessar Configurações Gerais

- Ajuste:
  - Idioma;
  - Tema (claro/escuro);
  - Região;
  - Preferências de notificação.

---

### 8. Usar Suporte e Feedback

- Acesse o centro de ajuda;
- Abra chamados;
- Envie sugestões e feedbacks para a Microsoft.

---

### 9. Utilizar o Cloud Shell

- Execute comandos com:
  - PowerShell;
  - Bash;
  - Python;

- Ideal para automações e práticas de IaC (Infraestrutura como Código).

---

### 10. Explorar Documentação Integrada

- Acesse a documentação oficial diretamente pelo portal;
- Excelente para aprofundamento e aprendizado contínuo.

---

### 11. Usar o Assistente com IA (Copilot)

- Use o Copilot para:
  - Criar recursos;
  - Gerar códigos;
  - Entender configurações;
  - Obter sugestões automatizadas e inteligentes.

---
