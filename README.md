# 🐝 Beebop · Trilha de Conhecimento Front-end

Roadmap simples e interativo para quem está começando no projeto **Beebop**. Ele reúne, em quatro fases, o que é preciso estudar para chegar ao primeiro portfólio: do controle de versão ao ecossistema front-end.

Feito com *vibe coding*: um único arquivo HTML, sem dependências, sem build e sem framework.

🔗 **Acesse online:** `https://SEU-USUARIO.github.io/NOME-DO-REPO/`

---

## ✨ O que tem aqui

- **4 fases sequenciais**, cada uma com descrição, lista de tarefas e duração sugerida.
- **Checklist clicável**: marque o que já concluiu e acompanhe o avanço por fase e no geral.
- **Progresso salvo no navegador** (`localStorage`): fechou a aba, voltou, está tudo lá.
- **Links para cursos e materiais gratuitos** em cada fase.
- **Responsivo**: funciona no celular e no computador.
- **Pronto para imprimir**: layout A4 com regras `@media print`, ideal para exportar em PDF.

## 🗺️ As fases

| Fase | Foco | Duração sugerida | Material |
|------|------|------------------|----------|
| 1 | Ferramentas e fundamentos (Git e GitHub) | 1 a 2 semanas | [Introdução ao Git e GitHub (FGV)](https://cursosgratuitos.fgv.br/curso/introducao-ao-git-e-github) |
| 2 | Prática com HTML, CSS e JavaScript | 6 a 10 semanas | [Web Development (NetAcad)](https://www.netacad.com/learning-collections/web-development?courseLang=en-US) |
| 3 | Avançado: ecossistema front-end | 2 a 4 meses | [Roadmap Front-end (roadmap.sh)](https://roadmap.sh/frontend) |
| 4 | Portfólio e carreira | Contínuo | Seus próprios projetos |

## 🚀 Como usar

1. Abra o `index.html` no navegador (dois cliques bastam).
2. Siga as fases em ordem e marque cada item ao concluir.
3. Use o botão **Limpar progresso** se quiser recomeçar.

> O progresso é individual e fica guardado só no navegador de quem usa. Quem abrir o link terá o próprio roadmap em branco.

## 🖨️ Exportar para PDF

1. Abra a página e pressione `Ctrl + P` (ou `Cmd + P` no Mac).
2. Em **Destino**, escolha **Salvar como PDF**.
3. Confirme o papel em **A4** e marque **Gráficos de plano de fundo** para manter as cores.
4. Clique em **Salvar**.

No PDF, os botões viram links sublinhados com a URL visível, e os itens concluídos continuam marcados.

## 🌐 Publicar no GitHub Pages

1. Envie o projeto para um repositório no GitHub (o arquivo precisa se chamar `index.html`).
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save** e aguarde alguns minutos. O endereço aparece na mesma tela.

## 🛠️ Como editar

Tudo está em um único arquivo, o `index.html`:

- **Textos e links:** edite direto no HTML, dentro de cada `<article class="card">`.
- **Adicionar um item:** copie uma linha `<li><label>...</label></li>` dentro da lista da fase. O contador e a barra de progresso se ajustam sozinhos.
- **Adicionar uma fase:** copie um bloco `<section class="step">` inteiro e altere o número, o título e os itens.
- **Cores:** mude as variáveis no topo do CSS, em `:root`.

⚠️ O progresso salvo é associado à **posição** de cada item (fase e ordem na lista). Se você reordenar ou inserir itens no meio de uma lista, as marcações de quem já usa o roadmap podem se deslocar. Prefira adicionar novos itens ao final da lista.

## 📁 Estrutura

```
.
├── index.html   # roadmap completo (HTML + CSS + JS)
└── README.md    # este arquivo
```

## 🤝 Contribuindo

Sugestões de cursos, correções e novos tópicos são bem-vindas. Abra uma *issue* ou envie um *pull request* com a mudança.

---

<sub>Trilha inicial do projeto Beebop · uso livre para estudo e compartilhamento.</sub>
