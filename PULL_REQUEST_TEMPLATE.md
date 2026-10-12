## 📝 O que muda

<!-- Resumo em 1 ou 2 frases. -->

## 🎯 Por que

<!-- Qual problema resolve ou qual tarefa/issue atende? Ex.: Closes #12 -->

## 🧩 Módulo afetado

- [ ] Produtos
- [ ] Pedidos
- [ ] Financeiro
- [ ] Marketing (coleta Instagram / TikTok / Shopee / Mercado Livre)
- [ ] Jurídico
- [ ] Banco de dados
- [ ] Infra / CI / Configuração
- [ ] Documentação

## ✅ Checklist

**Segurança e dados**
- [ ] Não há tokens, chaves, senhas ou `.env` neste PR
- [ ] Não há dados reais de clientes (CPF, nome, endereço) em código, testes, logs ou prints
- [ ] Nenhuma rota `DELETE` nova: desativação é feita por `PATCH` de status

**Regras do projeto**
- [ ] Métricas (margem, custo, lucro/hora) são calculadas no back-end, não gravadas no banco
- [ ] Categoria, canal e status usam os valores fixos definidos na aplicação
- [ ] Histórico e relatórios incluem registros inativos; catálogo mostra só `ativo`

**Qualidade**
- [ ] Testei localmente
- [ ] Migração de banco testada (se houver) e reversível
- [ ] Atualizei a documentação (se necessário)

## 🧪 Como testar

<!-- Passos para conferir a mudança. -->

## 📸 Capturas de tela (se houver mudança visual)

<!-- Use apenas dados fictícios. -->
