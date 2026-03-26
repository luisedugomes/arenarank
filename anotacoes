```mermaid
flowchart TD

%% Atores
Visitante[Visitante]
Jogador[Jogador]
Moderador[Moderador]
Admin[Administrador]
Sistema[ArenaRank Sistema]

%% Autenticação
Visitante -->|Criar conta| CriarConta[US01 - Abertura de Conta]
CriarConta --> ConfirmarEmail[US02 - Confirmação de Email]
ConfirmarEmail --> Jogador

%% Uso da Plataforma - Jogador
Jogador --> CriarEquipe[US04 - Criar Equipe]
Jogador --> CandidatarEquipe[US06 - Candidatar-se / Aceitar Convite]
Jogador --> InscreverTorneio[US05 - Inscrição em Torneios]

%% Moderador
Moderador --> CriarTorneio[US03 - Criar Torneio]
CriarTorneio --> DefinirJogo[Selecionar Jogo LoL, Valorant, CS]
CriarTorneio --> DefinirFormato[Definir Formato de Chaves]
CriarTorneio --> DefinirRegras[Definir Regras e Premiação]

%% Sistema
Sistema --> GerarChaves[Gerar Chaves de Torneio]
Sistema --> Ranking[Atualizar Rankings]
Sistema --> Acompanhar[Acompanhar Torneios]

%% Admin
Admin --> GerenciarUsuarios[Gerenciar Usuários]
Admin --> ModerarConteudo[Remover Conteúdo Indevido]
Admin --> ModerarTorneios[Moderar Torneios]
Admin --> ConfigSistema[Configurar Sistema]
Admin --> VisualizarDados[Visualizar Dados Gerais]

%% Relações adicionais
CriarEquipe --> InscreverTorneio
CriarTorneio --> GerarChaves
GerarChaves --> Acompanhar
Acompanhar --> Ranking
```
