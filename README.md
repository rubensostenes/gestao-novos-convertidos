# ⛪ Sistema de Cadastro de Novos Convertidos

Este projeto é uma ferramenta de gestão desenvolvida para facilitar o acolhimento e o registro de novos membros em congregações. O sistema permite o cadastro detalhado, armazenamento em nuvem e uma ponte direta de comunicação via WhatsApp.

## ✨ Funcionalidades

- **📋 Cadastro Detalhado:** Coleta de dados pessoais, informações familiares e congregação de destino (incluindo Acaraú e outras).
- **📲 Integração com WhatsApp:** Ao cadastrar, o sistema gera automaticamente um link para iniciar uma conversa com o novo convertido, já incluindo o prefixo +55 e mensagem personalizada.
- **🗄️ Banco de Dados em Tempo Real:** Utiliza Firebase para sincronização instantânea entre diferentes dispositivos.
- **🔍 Gestão de Dados:** Área administrativa para visualizar detalhes, atualizar informações ou deletar registros com interface intuitiva.
- **🌐 Modo Online/Offline:** Sincronização automática dos dados salvos localmente assim que a conexão é restabelecida.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** Tailwind CSS (Interface Moderna e Responsiva), HTML5, JavaScript Vanilla.
- **Backend:** Firebase Realtime Database.
- **Ícones:** Font Awesome.

## 🚀 Como Usar

1.  **Configuração:** Insira suas credenciais do Firebase no script principal dentro do `index.html`.
2.  **Uso:** Abra o arquivo `index.html` em qualquer navegador ou hospede em plataformas como Netlify/Vercel.
3.  **Fluxo:** Preencha os dados do novo membro -> Clique em Cadastrar -> O sistema salva no banco e abre o WhatsApp para o primeiro contato.

## 📂 Estrutura do Projeto

- `index.html`: Interface principal e lógica de negócio.
- `style.css`: Estilizações específicas e correções de layout.
- `Firebase Integration`: Persistência de dados em nuvem.

## 📄 Licença

Projeto desenvolvido para fins de organização eclesiástica e gestão de membros.