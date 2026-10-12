# Política de Segurança

O software da **Bubble Studio 3D** é **proprietário** e de uso interno. Ele lida com dados
de clientes (inclusive CPF) e com credenciais de integração com marketplaces, por isso levamos
a segurança a sério.

## 🔒 Como reportar uma vulnerabilidade

Se você encontrou uma falha de segurança em qualquer repositório da organização:

1. **Não abra uma issue pública** nem comente em PRs.
2. Envie um e-mail para **[e-mail de segurança]** com o assunto `[SEGURANÇA] <resumo curto>`.
3. Descreva o que encontrou, onde (repositório, arquivo ou rota), como reproduzir e o impacto
   que você imagina.

Responderemos em até **7 dias corridos** confirmando o recebimento e, depois da análise,
informaremos o plano de correção.

> Você também pode usar o relato privado do GitHub, em **Security → Report a vulnerability**,
> no repositório afetado, quando essa opção estiver disponível.

## ⚠️ Se você encontrar uma credencial exposta

Tokens, chaves de API ou senhas (Mercado Livre, Shopee, Meta, TikTok, banco de dados) visíveis
em código, histórico de commits, logs ou imagens:

1. **Revogue ou gere uma nova credencial imediatamente** no serviço de origem.
2. Só depois remova o segredo do repositório.
3. Avise pelo e-mail acima, para que o histórico seja revisado.

Apagar o arquivo **não basta**: o segredo continua no histórico do Git.

## 🧾 Dados pessoais (LGPD)

- O CPF só é guardado para emissão de nota fiscal e não deve ser usado para outra finalidade.
- Dados de clientes **nunca** entram em commits, issues, capturas de tela ou logs.
- Pedidos de exclusão de dados são tratados por **anonimização**, conforme o modelo de dados.

## 🛡️ Boas práticas do projeto

- Segredos ficam em variáveis de ambiente ou **GitHub Secrets**, nunca no código.
- O arquivo `.env` está sempre no `.gitignore`.
- Autenticação em duas etapas obrigatória para todos os membros da organização.
- Dependabot e verificação de segredos ativos nos repositórios.

## 📌 Escopo

Esta política vale para todos os repositórios da organização **Bubble-Studio3D**.
Não há programa de recompensas (*bug bounty*).
