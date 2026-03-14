# Painel NetBase - Firebase Edition

O Painel NetBase é um gerenciador de banco de dados em tempo real, integrado à infraestrutura do Firebase (Realtime Database).

## Configurações do Projeto
- **Projeto Firebase:** `netbase-cloud`
- **Database:** Realtime Database (Sincronização em tempo real)
- **Status do Banco:** Regras de Leitura/Escrita definidas como `true`.

## Segurança
- **Sistema de Login:** O acesso ao painel de geração de APIs está protegido pela chave de acesso: `netchaveapi`.
- **Validação:** Apenas usuários que inserirem o nome e a senha correta conseguem visualizar os campos de escrita no banco.

## Como fazer o deploy
Utilize os comandos no seu terminal para publicar as atualizações no Firebase Hosting:

1. **Definir alvo de deploy:**
   ```bash
   firebase target:apply hosting netbase netbase-cloud
