# Financeiro Agro Bardin

Link do relatório de Fluxo de Caixa 2026 da Agro Bardin para a gerência.

O `index.html` traz o relatório **criptografado** (AES-256-GCM, chave derivada da senha por PBKDF2-SHA256, 600 mil iterações). Sem a senha, nenhum dado da empresa pode ser lido. O arquivo é gerado pelo botão **Gerar link do celular**, na versão do administrador (`fluxo-de-caixa-admin.html`).

Para atualizar: gere um novo `index.html` na versão do administrador, com a mesma senha, e envie para este repositório (Add file → Upload files → Commit changes).
