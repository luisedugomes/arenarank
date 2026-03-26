# 🛠️ Especificação Técnica (Tech Spec) - ArenaRank

Este documento detalha arquitetura técnica, o modelo de dados e os contratos de API (via JSON Server) necessárias para o funcionamento da plataforma de torneios e-sports amadores ArenaRank.

## 1. Modelo de Dados (Diagrama ER)

Abaixo está o Diagrama Entidade-Relacionamento (DER) que representa a estrutura do nosso "banco de dados" (`db.json`) e como as informações se conectam.

```mermaid
erDiagram
Usuário ||--o{ Jogador : "se inscreve/cria uma equipe"
Usuário ||--o{ Moderador : "cria o torneio"
Jogador ||--o{ Torneio : "se inscreve no torneio"
Moderador ||--o{ Torneio : "administra o torneio"
Usuário {
string id PK "Gerado automaticamente"
string nome
string usuário "Usado para o login"
string senha
string equipe "Se registra/cria"
string torneio "Se registra/cria"
}
Jogador{
string id PK
string usuário
string equipe "Equipe selecionada/registrada"
string conta 
}
Moderador {
string id PK
string equipes
string chaves "Tipos de chaves do sistema para o jogo escolhido"
string descrição
string regulamento
}
Torneio {
string id PK
string equipes "Nome da equipes"
string jogo
string horário "Hora do começo/fim do torneio"
string posição "Colocação da equipe nas chaves"
}
```
## 2. Dicionário de Dados

Breve explicação das tabelas principais:

- **Usuário:** Responsável pelo registro de equipes, pela criação ou participação de torneios podendo
