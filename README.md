# AVANTECH---HACKATHON
Sistema web para gerenciamento de eventos com CRUD completo e integrado ao Firebase Realtime Database.
# Evantech 🚀

O Evantech é um sistema web completo e responsivo para o gerenciamento de inscrições em eventos de tecnologia. O projeto foi desenvolvido como um CRUD funcional integrado diretamente a um banco de dados real na nuvem.

## 👥 Integrantes da Equipe
* **[Isabella Tondim Lazarotti]** - Desenvolvedora / Pitch
* **[Isabella Tondim Lazarotti]** - Desenvolvedor Front-End
* **[Isabella Tondim Lazarotti]** - Desenvolvedor Back-End
* **[Isabella Tondim Lazarotti]** - Documentação / PO

 🛠️ Tecnologias Utilizadas

* **Front-End:** HTML5 e CSS3 (Design moderno e responsivo)
* **Lógica/Back-End:** JavaScript Vanilla (ES6+) usando programação assíncrona
* **Banco de Dados:** Firebase Realtime Database (Banco de dados NoSQL em nuvem do Google)
* **Comunicação com o Banco:** API Fetch utilizando o padrão arquitetural REST (métodos GET, POST, PUT e DELETE)

 📌 Funcionalidades do Sistema (CRUD)

* **Dashboard (Painel Geral):** Apresenta o status de lotação do evento em tempo real baseado nos dados da nuvem.
* **Novo Cadastro:** Formulário para registrar novos participantes.
* **Listagem de Participantes:** Tabela dinâmica que consome e renderiza os dados guardados no Firebase.
* **Edição e Exclusão:** Telas e comandos para atualizar informações ou remover registros diretamente do banco de dados.
⚙️ Regras de Negócio Implementadas

1. **Validação de CPF Único:** O sistema consulta o banco de dados antes de validar um novo cadastro, impedindo a inscrição duplicada do mesmo CPF.
2. **Status de Lotação Automático:** Caso o banco de dados atinja o limite de 5 ou mais inscritos, o painel principal (`index.html`) altera automaticamente seu status de "Aberto" para **"LOTADO"**.

## 📂 Estrutura do Projeto

```text
├── index.html       # Painel Geral (Dashboard)
├── cadastro.html    # Tela de Formulário de Inscrição
├── listagem.html    # Tela de Exibição dos Participantes
├── edicao.html      # Tela de Atualização de Dados
└── style.css        # Estilização Global do Sistema

## 💰 Modelo de Monetização (B2B + Premium)
O **Evantech** se sustenta através de dois pilares financeiros:
1. **Venda Direta para Empresas (B2B):** Licenciamento do software para organizadores de grandes eventos e corporações que precisam gerenciar suas listas de presença.
2. **Plano Premium (Features Extras):** Versão paga para organizadores independentes, liberando recursos como relatórios avançados de presença, exportação de planilhas e remoção do limite de vagas do painel.

## 🚀 Instruções para Execução Local

Para rodar o projeto localmente na sua máquina, não é necessário instalar dependências pesadas:

1. Faça o clone ou o download deste repositório.
2. Certifique-se de estar conectado à internet (necessário para a integração em tempo real com o Firebase).
3. Abra o arquivo `index.html` diretamente em qualquer navegador web moderno (Chrome, Edge, Firefox).
4. Prontinho! O sistema consumirá a API do banco de dados automaticamente.
