# 🔐 Política de Segurança

Este repositório segue boas práticas de segurança, mesmo sendo voltado a configurações pessoais de terminal. As diretrizes abaixo descrevem os mecanismos adotados para garantir integridade e evitar vazamentos acidentais.

---

## 🔏 Commits Assinados (GPG)

Todos os commits deste repositório são assinados digitalmente com a chave GPG:

- 🆔 Chave pública: `9FD1479F341442C2`
- 📦 Assinatura configurada localmente por repositório (não afeta Git global)
- ✅ GitHub exibe `Verified` ao lado de cada commit válido

---

## 🛡️ Hook de Segurança (Pre-commit)

Um hook de pre-commit é utilizado para evitar vazamento de dados sensíveis:

- 🚫 Impede commits contendo o domínio corporativos
- 🔐 Validação automática via script antes de cada commit
- ⚙️ Local: `.git/hooks/pre-commit`

> Este mecanismo atua como camada de proteção contra vazamento de e-mails corporativos em repositórios públicos.

---

## ⚠️ Escopo e Responsabilidade

Este repositório é de uso **pessoal**, mas aplica:

- Padrões consistentes de versionamento
- Boas práticas de segurança em shell
- Isolamento completo por branch (`bash` / `powershell`)
- Commits rastreáveis e autenticados

---

## 📫 Relato de Problemas

Este repositório é mantido por [@rtsantanna](https://github.com/rtsantanna).  
Caso identifique algum comportamento inseguro, entre em contato via GitHub Issues ou pull request.

---

## 📝 Licença

Este repositório está sob a Licença MIT.  
Consulte o arquivo [LICENSE](./LICENSE) para mais informações.
