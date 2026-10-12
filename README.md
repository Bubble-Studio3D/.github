# 🫧 .github — Bubble Studio 3D

Repositório de configuração da organização **Bubble-Studio3D** no GitHub.
Ele guarda o perfil público da organização e os arquivos padrão que todos os
repositórios herdam automaticamente.

> ℹ️ Este repositório é **público** por exigência do GitHub (é isso que exibe o perfil e
> distribui os arquivos padrão). Por isso, **nada interno** deve ser colocado aqui:
> sem segredos, preços, margens, dados de clientes ou documentação operacional.

---

## 📁 Estrutura

```
.github/
├── profile/
│   └── README.md              # Página pública da organização
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml         # Formulário de relato de bug
│   ├── tarefa.yml             # Formulário de tarefa / funcionalidade
│   └── config.yml             # Desativa issues em branco e aponta para a política de segurança
├── PULL_REQUEST_TEMPLATE.md   # Checklist padrão de Pull Request
├── SECURITY.md                # Política de segurança e contato para vulnerabilidades
└── README.md                  # Este arquivo
```

## 🧭 O que cada arquivo faz

| Arquivo | Efeito |
|---|---|
| `profile/README.md` | Vira a página inicial em `github.com/Bubble-Studio3D` |
| `ISSUE_TEMPLATE/` | Formulários padrão de issue em todo repositório da organização que não tiver os seus |
| `PULL_REQUEST_TEMPLATE.md` | Checklist padrão em todo PR (segredos, LGPD, regras do projeto) |
| `SECURITY.md` | Exibido na aba **Security** dos repositórios; diz como reportar uma falha em privado |

Um repositório pode substituir qualquer um desses arquivos criando o seu próprio
(por exemplo, `.github/PULL_REQUEST_TEMPLATE.md` dentro dele). O arquivo local tem prioridade.

## ➕ O que **não** é herdado daqui

Estes itens precisam existir em **cada repositório** de código:

- `dependabot.yml` — atualização automática de dependências
- `CODEOWNERS`
- Workflows do GitHub Actions (CI)
- `.gitignore` com `.env`
- Aviso de licença: o software é **proprietário**, todos os direitos reservados

## ✏️ Como alterar

1. Crie uma branch a partir da `main`.
2. Edite o arquivo e abra um Pull Request.
3. Confira que não há dado sensível na mudança.
4. Faça o merge. A alteração vale para os demais repositórios assim que for para a `main`.

## 🔗 Links

- Organização: [github.com/Bubble-Studio3D](https://github.com/Bubble-Studio3D)
- Política de segurança: [SECURITY.md](SECURITY.md)

---

<sub>Bubble Studio 3D · Software e materiais proprietários · Todos os direitos reservados</sub>
