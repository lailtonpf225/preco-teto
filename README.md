# 📈 TetoInvest Pro — Gestão de Preço Teto & Ações Favoritas

Aplicação web para cálculo automático de **Preço Teto** de ações da B3 (pelos métodos **Décio Bazin**, **Benjamin Graham** com margem de segurança, **Híbrido** e **Teto Projetivo por Payout**), com proteção por senha criptografada (`SHA-256`) e sincronização opcional em nuvem via GitHub Gist.

## 🚀 Como acessar
1. Acesse o link do seu GitHub Pages.
2. Digite sua senha de acesso (a senha padrão inicial é `123456`).
3. No menu superior, clique em **GitHub & Senha** para alterar sua senha mestra e configurar backup ou sincronização entre dispositivos.

## 🔒 Segurança & Persistência de Dados
- **Senha Criptografada:** Sua senha nunca fica salva em texto puro, apenas o hash `SHA-256`.
- **Armazenamento Local (`localStorage`):** Suas ações favoritas e preços tetos ficam salvos automaticamente no navegador.
- **Sincronização entre PC e Celular (Opcional):** Dentro do botão **GitHub & Senha**, você pode conectar um *Personal Access Token* (escopo `gist`) para salvar e carregar sua carteira de um GitHub Gist secreto.
