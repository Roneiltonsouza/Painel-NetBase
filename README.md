# NetBase API Manager 🛡️

Gerenciador de infraestrutura de banco de dados JSON para aplicativos de alta performance.

## 🔐 Acesso Seguro
O painel administrativo é protegido por uma camada de autenticação local via senha secreta, garantindo que apenas o proprietário do projeto possa gerar novas instâncias de banco de dados.

## ⚙️ Configuração
1. Obtenha sua **Master Key** no portal do JSONbin.io.
2. Insira a chave no campo `X_MASTER_KEY` no script do `index.html`.
3. A senha padrão de acesso ao painel é: `netchaveapi`.

## 🛰️ Estrutura da API
Cada banco gerado entrega um endpoint RESTful compatível com:
- **GET**: Leitura de dados.
- **PUT**: Atualização de informações.
- **DELETE**: Remoção de banco de dados (via painel JSONbin).

---
*Desenvolvido para ambientes mobile e integração rápida.*
