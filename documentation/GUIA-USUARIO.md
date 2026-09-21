# Guia do usuário — Ripper Search

## Primeiros passos

1. Instale a extensão (veja [README](../README.md))
2. Faça login em [forum.ripper.store](https://forum.ripper.store/login)
3. Abra uma página de produto em uma loja suportada (ex.: Booth)
4. Clique no ícone **Ripper Search** na barra do Chrome para abrir o painel

Se aparecer o banner "Faça login no fórum", clique em **Abrir login** e entre na sua conta.

---

## Aba Buscar

### Busca automática

Por padrão, a extensão busca automaticamente ao abrir o painel na página do item. Desative em **Configurações → Busca automática ao carregar**.

### Modos de busca

- **Buscar por nome** — usa o título do produto
- **Buscar por URL** — usa o link da página atual
- **Qualquer palavra / Todas as palavras** — controla como o fórum interpreta o termo

### Resultados

Os resultados são divididos em:

- **Downloads encontrados** — posts com link de download (DL)
- **Discussões** — tópicos sem DL detectado

Em cada card você vê:

- Status (Resolvido / Não resolvido)
- Categoria, autor, data/hora
- Comentários e visualizações
- **Curtidas** — clique no ♡ para dar upvote (precisa estar logado)
- **★ Favoritar** — monitora o tópico na aba Pedidos

### Ações nos cards

| Botão | Quando aparece | O que faz |
|-------|----------------|-----------|
| **Baixar** | Posts com DL | Extrai links do tópico e inicia download ou abre hidelink |
| **Bump** | Discussões | Posta "bump" no tópico para subir visibilidade |
| **Postar pedido LF** | Sem resultados ou no rodapé | Abre formulário de pedido Looking For |

### Downloads em posts

- Links diretos (mega, mediafire, etc.) iniciam download pelo Chrome
- Links **hidelink** do fórum abrem em nova aba — clique no link lá para baixar
- Sites como workupload podem pedir verificação "você é humano"

---

## Aba Pedidos

Monitora tópicos que você favoritou ou pedidos LF que você publicou.

### Status dos pedidos LF

| Status | Significado |
|--------|-------------|
| Na fila de moderação | Post enviado, aguardando aprovação dos mods |
| Em análise | Tópico aprovado, aguardando resposta |
| Monitorando | Sem novidades ainda |
| Novo DL! | Alguém postou download no tópico |
| Resolvido | Pedido marcado como resolvido |

### Ações

- **Atualizar scan** — verifica novos downloads nos tópicos monitorados
- **Adicionar pedido existente** — cole o link de um tópico LF já aprovado
- **Marcar como visto** — remove alerta sem parar o monitoramento

Notificações do browser podem ser ativadas em **Configurações**.

---

## Aba Downloads

- **Campo de URL** — cole um link (workupload, mega, etc.) e clique **Baixar**
- **Botão Baixar nos resultados** — na aba Buscar, nos cards com DL
- Lista mostra progresso, cancelar ou abrir arquivo concluído

---

## Aba Histórico

Registra suas buscas automaticamente. Use **Repetir** para buscar o mesmo termo de novo.

---

## Aba Configurações

- **Idioma** — interface em 6 idiomas
- **Tags padrão** — usadas em pedidos LF
- **Mensagem de bump** — texto postado ao dar bump (padrão: `bump`)
- **Exportar / Importar** — backup das configurações
- **Sites habilitados** — ative ou desative lojas específicas

---

## FAQ

### "Faça login em forum.ripper.store primeiro"

Você precisa estar logado no fórum. Abra o login pelo banner ou em [forum.ripper.store/login](https://forum.ripper.store/login).

### Pedido LF não aparece no fórum imediatamente

Posts novos vão para a **fila de moderação**. Acompanhe na aba **Pedidos** com status "Na fila de moderação". Quando aprovado, o status muda para "Em análise".

### "Nenhum link de download encontrado neste tópico"

O fórum detectou DL, mas o link pode estar em formato protegido (hidelink). O tópico será aberto — clique no link de download dentro do post.

### Chrome mostra "Extensão não verificada"

Normal em instalação manual (ZIP). A Chrome Web Store remove esse aviso após publicação oficial.

### Como atualizar a extensão

- **ZIP manual:** baixe o Release novo, remova a extensão antiga e carregue a pasta nova
- **Chrome Web Store:** atualiza automaticamente (quando disponível)

---

## Suporte

Abra uma [issue no GitHub](https://github.com/T1NG4/ripper-search/issues) com descrição do problema, loja usada e prints se possível.
