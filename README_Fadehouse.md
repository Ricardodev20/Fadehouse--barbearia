# 💈 FadeHouse — Sistema de Gestão para Barbearia

Sistema web desenvolvido para a **FadeHouse**, com foco em facilitar o agendamento de serviços pelos clientes e apoiar a gestão da barbearia.

O projeto reúne uma interface pública para apresentação da barbearia, área de clientes para agendamentos e um painel administrativo com recursos de gerenciamento e acompanhamento das operações.

> 📚 **Projeto acadêmico / portfólio** — desenvolvido como aplicação web demonstrativa.

---

## 🎯 Objetivo

O objetivo do projeto é criar uma solução digital para uma barbearia, centralizando o atendimento ao cliente e algumas rotinas administrativas em uma única aplicação.

Entre as principais propostas estão:

- facilitar o agendamento de horários;
- apresentar serviços, preços e barbeiros;
- permitir acompanhamento dos agendamentos;
- organizar informações de clientes;
- auxiliar no controle de estoque;
- acompanhar informações financeiras;
- disponibilizar relatórios e indicadores para gestão.

---

## ✨ Funcionalidades

### 👤 Área do cliente

- Cadastro/login de cliente;
- Escolha do barbeiro;
- Escolha do serviço;
- Seleção de data e horário;
- Confirmação do agendamento;
- Visualização dos próprios agendamentos.

O fluxo de agendamento é dividido em etapas para facilitar a escolha do barbeiro, serviço, data e horário. fileciteturn1file0L583-L619

### 💈 Serviços e barbeiros

A aplicação apresenta serviços como:

- Corte Clássico;
- Degradê / Fade;
- Barba Completa;
- Combo Completo;
- Skin Fade.

Também possui cadastro e gerenciamento de barbeiros, incluindo nome e especialidade. fileciteturn2file4

### 📊 Painel administrativo

O projeto possui uma área administrativa para gerenciamento das informações da barbearia, incluindo:

- Agendamentos;
- Clientes;
- Barbeiros;
- Estoque;
- Caixa;
- Relatórios;
- Configurações;
- Indicadores e gráficos.

O painel também possui recursos de busca, filtros, tabelas, gráficos e gerenciamento dos dados. fileciteturn3file5

### 📦 Controle de estoque

O sistema permite:

- adicionar produtos;
- editar produtos;
- remover produtos;
- informar quantidade disponível;
- definir estoque mínimo;
- registrar custo;
- identificar produtos esgotados ou com estoque baixo;
- acompanhar produtos mais vendidos e giro do estoque. fileciteturn3file6

### 💰 Controle financeiro

A aplicação possui recursos relacionados ao caixa e ao acompanhamento de faturamento, incluindo métricas, movimentações e relatórios. Os dados de faturamento podem ser utilizados para calcular total, quantidade de atendimentos, ticket médio e cancelamentos. fileciteturn3file7

### 📈 Relatórios

O sistema possui relatórios relacionados a:

- faturamento;
- agendamentos;
- estoque;
- produtos mais vendidos;
- giro de estoque;
- valor do estoque.

Também existe uma função para exportação de informações em formato CSV. fileciteturn2file5

### 📝 Persistência de dados

O projeto utiliza **LocalStorage do navegador** para manter dados como:

- agendamentos;
- estoque;
- barbeiros;
- clientes;
- configurações;
- caixa;
- registros de auditoria.

Os dados são salvos localmente no navegador e possuem mecanismos de salvamento automático. fileciteturn3file0turn3file7

---

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando principalmente:

- **HTML5** — estrutura da aplicação;
- **CSS3** — estilização, layout, animações e responsividade;
- **JavaScript** — lógica da aplicação, interações e gerenciamento dos dados;
- **LocalStorage** — persistência local dos dados no navegador;
- **Google Fonts** — fontes utilizadas na interface.

O arquivo principal contém a estrutura HTML, estilos CSS e código JavaScript da aplicação. A interface utiliza as fontes **Cormorant Garamond** e **Jost**. fileciteturn1file0L1-L7

---

## 🎨 Interface

A identidade visual do projeto utiliza uma proposta de **dark luxury**, com predominância de tons escuros e detalhes dourados.

O layout também possui comportamento responsivo para diferentes tamanhos de tela, incluindo adaptações para dispositivos móveis. fileciteturn1file0L108-L119

---

## 🚀 Como executar

Como o projeto é composto por HTML, CSS e JavaScript no mesmo arquivo, não é necessário instalar dependências ou configurar um servidor para executar a versão atual.

### 1. Clone o repositório

```bash
git clone https://github.com/Ricardodev20/Fadehouse--barbearia.git
```

### 2. Entre na pasta

```bash
cd Fadehouse--barbearia
```

### 3. Abra o arquivo HTML

Abra o arquivo principal do projeto no navegador.

Também é possível utilizar o **Live Server** no VS Code para executar o projeto durante o desenvolvimento.

---

## 📁 Estrutura atual

```text
Fadehouse--barbearia/
│
├── fadehouse_final.html
└── README.md
```

> A estrutura acima representa a versão atual baseada no arquivo HTML enviado para análise.

---

## 🔐 Observação sobre dados e autenticação

Esta versão do projeto funciona no lado do cliente e utiliza **LocalStorage** para persistência.

Portanto, os dados não estão armazenados em um banco de dados externo e não existe, nesta versão, um backend responsável pela autenticação ou armazenamento centralizado.

Isso significa que o projeto deve ser considerado uma **aplicação demonstrativa/protótipo**, e não um sistema pronto para produção.

---

## 📚 Aprendizados do projeto

Durante o desenvolvimento do FadeHouse, foram trabalhados conceitos como:

- Estruturação de páginas web;
- HTML semântico;
- CSS e design responsivo;
- JavaScript;
- Manipulação do DOM;
- Eventos e interações;
- Formulários;
- Fluxos de agendamento;
- Persistência com LocalStorage;
- Organização de dados;
- Construção de dashboards;
- Gráficos e indicadores;
- Exportação de dados;
- Responsividade para dispositivos móveis.

---

## 👨‍💻 Autor

**Ricardo Grisoste Costa**

🎓 Estudante de Engenharia de Software — Faculdade Positivo  
💻 Desenvolvedor Full Stack em formação

### 🔗 Links

- GitHub: [@Ricardodev20](https://github.com/Ricardodev20)
- LinkedIn: **adicione seu LinkedIn aqui**

---

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
