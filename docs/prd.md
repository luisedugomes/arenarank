# 🎮 ArenaRank - Product Requirements Document (PRD)

## 📄1. Visão Geral e Objetivo

A ArenaRank é umma plataforma web onde jogadores amadores/semi-profissionais podem criar torneios, se inscrever em campeonatos, montar times e acompanhar rankings de equipes/jogadores;

A plataforma terá foco em jogos populares como LoL, Valorant e CS.

## 🎭 2. Atores do Sistema

- **Visitante:** Usuário não autenticado que acessa a página inicial e visualiza a interface principal da plataforma;
- **Jogador:** Usuário autenticado que pode criar ou participar de equipes (caso o jogador seje criador/líder do seu time, ele poderá inscrever os mesmos em campeonatos;
- **Moderador (Função alternativa do usuário autenticado):** Pode criar torneios e manipular os seus formatos;
- **ArenaRank (Sistema):** Ator ínvisível que permite que os torneios sejam criados

Criar conta / login
Editar perfil
Se inscrever em torneios
Participar de times
Visualizar rankings
Acompanhar torneios

💡 É o ator mais importante — praticamente todas as funcionalidades passam por ele.

## 🧑‍💼  Organizador de Torneio

👉 Pode ser um jogador com permissões extras

O que faz:

Criar torneios
Definir regras
Gerenciar participantes
Atualizar resultados
Encerrar torneios

💡 Em muitos sistemas, esse papel é um “upgrade” do jogador.

## 🛡️  Administrador do Sistema

👉 Controle total da plataforma

O que faz:

Gerenciar usuários
Remover conteúdo indevido
Moderar torneios
Configurar sistema
Visualizar dados gerais

💡 Papel importante pra segurança e organização.

## 3. Histórias de Usuário e Escopo
   
Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

# 👤 Épico 1: Autenticação e Conta

- **USO1 - Abertura de conta:** O visitante irá preencher dados como Nome de Usuário, Senha e E-mail.
- **USO2 - Confirmação de E-mail:** O visitante irá precisar autenticar a conta acessando o E-mail de cadastro e confirmando através da mensagem enviada pela plataforma durante a finalização do processo de preenchimento de dados.

# 🕹️ Épico 2: Uso da Plataforma

- **US03 - Criação de torneios:** O usuário poderá criar campeonatos decidindo primeiro qual jogo será o tema dá competição (LoL, Valorant e CS), escolher o formato de chaves das equipes e irá preencher um formulário para deixer descrito as regras e premiações do torneio.
- **US04 - Inscrição em torneios:**
