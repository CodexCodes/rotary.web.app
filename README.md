# Rotary Club Web Application

## Descrição do Projeto

A aplicação web desenvolvida tem como objetivo ajudar o **Rotary Club** de Campo Grande a gerenciar e divulgar suas campanhas de arrecadação de forma mais eficiente. Com foco em aumentar o impacto das ações sociais, a solução centraliza informações, possibilita o acompanhamento de metas de arrecadação e permite que os membros do Rotary criem novas campanhas.

O sistema é dividido em diferentes seções, permitindo que usuários comuns interajam com doações e campanhas, enquanto membros do Rotary têm acesso a funcionalidades adicionais para criar e gerenciar campanhas.

### Funcionalidades Principais

- **Página inicial**: Exibe uma visão geral das campanhas ativas e novas campanhas.
- **Campanhas**: Permite a visualização de campanhas existentes e informações detalhadas.
- **Nova Campanha**: Exclusiva para membros do Rotary para criar novas campanhas de arrecadação.
- **Doações**: Plataforma para usuários doarem via Pix ou cartão de crédito, acompanhando o progresso das campanhas.
- **Notificações**: Envio de atualizações sobre o andamento das campanhas e notificações de doações recebidas.
- **Login**: Sistema de autenticação para permitir diferentes acessos para membros do Rotary e usuários comuns.

## Tecnologias Utilizadas

- **Frontend**: React.js, Tailwind CSS, React Router
- **Backend**: Node.js (Express.js)
- **Banco de Dados**: MongoDB ou PostgreSQL (configurável)
- **Autenticação**: JWT (JSON Web Token)
- **API de Pagamentos**: Integração com Pix e opções de pagamento via cartão de crédito.
- **Hospedagem**: Deploy no Heroku ou outra plataforma de sua escolha.

## Estrutura de Pastas

A estrutura do projeto é organizada de forma a garantir uma manutenção fácil e a escalabilidade:


## Funcionalidades Detalhadas

- **Login e Autenticação**: O sistema oferece um controle de acesso para membros do Rotary e usuários comuns. Apenas membros do Rotary podem criar e gerenciar campanhas, enquanto os usuários comuns podem doar e acompanhar o progresso das campanhas.
  
- **Criação de Campanhas**: Exclusiva para membros do Rotary, permite que novos projetos de arrecadação sejam criados com detalhes como metas, descrição, datas e tipos de doação.

- **Doações**: Os usuários podem fazer doações para campanhas ativas. O sistema oferece a possibilidade de pagamentos por **Pix** ou **Cartão de Crédito**, com processamento de transações em tempo real.

- **Notificações e Progresso**: O sistema envia notificações para os usuários sobre o progresso das campanhas que eles estão acompanhando e para os membros do Rotary sobre novas doações.

## Como Rodar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/rotary-web-app.git
