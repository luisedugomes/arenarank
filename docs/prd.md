# 🎮 ArenaRank - Product Requirements Document (PRD)

## 📄1. Visão Geral e Objetivo

A ArenaRank é umma plataforma web onde jogadores amadores/semi-profissionais podem criar torneios, se inscrever em campeonatos, montar times e acompanhar rankings de equipes/jogadores;

A plataforma terá foco em jogos populares como LoL, Valorant e CS.

## 🎭 2. Atores do Sistema

- **Visitante:** Usuário não autenticado que acessa a página inicial e visualiza a interface principal da plataforma;
- **Jogador:** Usuário autenticado que pode criar ou participar de equipes (caso o jogador seje criador/líder do seu time, ele poderá inscrever os mesmos em campeonatos;
- **Moderador (Função alternativa do usuário autenticado):** Pode criar torneios e manipular os seus formatos;
- **Adiministrador:** Usuário com controle total da plataforma, pode gerenciar usuários, remover conteúdo indevido, moderar torneios, configurar o sistema e visualizar dados gerais;
- **ArenaRank (Sistema):** Ator ínvisível que permite que os torneios sejam criados com ferramentas especializadas para a construção de chaves dos jogos, também será possível visualizar rankings de times ou acompanhar torneios;

## 📋3. Histórias de Usuário e Escopo
   
Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

# 👤 Épico 1: Autenticação e Conta

- **USO1 - Abertura de conta:** O visitante irá preencher dados como Nome de Usuário, Senha e E-mail.
- **USO2 - Confirmação de E-mail:** O visitante irá precisar autenticar a conta acessando o E-mail de cadastro e confirmando através da mensagem enviada pela plataforma durante a finalização do processo de preenchimento de dados.

# 🕹️ Épico 2: Uso da Plataforma

- **US03 - Criação de torneios:** O usuário poderá criar campeonatos decidindo primeiro qual jogo será o tema dá competição (LoL, Valorant e CS), escolher o formato de chaves das equipes e irá preencher um formulário para deixer descrito as regras e premiações do torneio.
- **US04 - Criação de Equipes:** O usuário poderá criar equipes com um número máximo de 10 jogadores por equipes.
- **USO4 - Inscrição de Torneios:** O usuário que criou/é líder da equipe participante, poderá se registrar em campeonatos pré-definindo os seus jogadores (registrados na equipe escolhida).
- **USO05 - Inscrição em Equipes:** O usuário poderá se candidatar em equipes ou aceitar convites encaminhados por seus líderes/criadores.
