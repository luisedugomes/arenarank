# 🛠️ Especificação Técnica (Tech Spec) - ArenaRank

Este documento detalha arquitetura técnica, o modelo de dados e os contratos de API (via JSON Server) necessárias para o funcionamento da plataforma de torneios e-sports amadores ArenaRank.

## 1. Modelo de Dados (Diagrama ER)

Abaixo está o Diagrama Entidade-Relacionamento (DER) que representa a estrutura do nosso "banco de dados" (`db.json`) e como as informações se conectam.

```mermaid
erDiagram
Usuario ||--o{ Torneio : "se inscreve no torneio"
Usuário {
string id PK "Gerado automaticamente"
string nome
string usuário "Usado para o login"
string senha
string torneio
}
