# Do Caos ao Controle: Commits, PRs e contexto no Git

Uma apresentação interativa sobre Conventional Commits, Pull Requests com contexto e histórico Git legível.

## 📋 Conteúdo

33 slides cobrindo:
1. Capa
2. Quem sou eu
3. Expectativa da Duda no mundo tech
4. Realidade da Duda no mundo tech
5. Por que escrevemos código? (título)
6. Por que escrevemos código? (negócio, regras voláteis e contexto)
7. O código é apenas metade da história
8. O "você do futuro" agradece
9. Árvore Git com mensagens genéricas (`git log --graph`)
10. Como controlar esse caos?
11. Boas práticas para colaboração de código
12. Conventional Commits — o padrão ouro (formato da mensagem)
13. Conventional Commits — tipos (`feat`/`fix` e Convenção Angular)
14. Exemplos de commits convencionais
15. Benefícios da adoção
16. Exemplos: Do Caos ao Controle
17. Gancho: padrão convencional + histórico limpo
18. Rebase interativo (`git rebase -i`)
19. `git commit --amend` (último commit)
20. Gancho — “Bora abrir um PR?”
21. Boas práticas de PR (introdução ao bloco de revisão)
22. Anatomia de um Pull Request eficaz
23. Contexto em PRs — ajude o revisor
24. Exemplo visual — PR com bom contexto (captura de tela)
25. Exemplo visual — PR fraco ou sem contexto (captura de tela)
26. Gancho — “Bora mergear?” (antes das estratégias na main)
27. Estratégias de merge na main — introdução (boas práticas 3/3)
28. Squash and merge
29. Merge commit
30. Rebase and merge (histórico linear)
31. Pequenas mudanças, grandes impactos
32. Frase de fechamento — por que escrevemos código?
33. Conclusão e Q&A

## 🚀 Como Usar Localmente

1. **Clone ou baixe este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/apresentacao-commits.git
   cd apresentacao-commits
   ```

2. **Abra o arquivo `index.html` no navegador:**
   - Duplo clique em `index.html`, ou
   - Use um servidor local (recomendado):
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (http-server)
     npx http-server
     ```
   - Acesse `http://localhost:8000`

3. **Navegue pelos slides:**
   - Use as **setas do teclado** (← →) para navegar
   - Ou clique nos botões "Anterior" e "Próximo"
   - Pressione **F11** para tela cheia

## 🌐 Deploy no GitHub Pages

1. **Crie um repositório no GitHub:**
   - Vá para [github.com/new](https://github.com/new)
   - Nome: `apresentacao-commits` (ou o nome que preferir)
   - Marque "Public"
   - Clique "Create repository"

2. **Faça push dos arquivos:**
   ```bash
   git init
   git add .
   git commit -m "feat: adicionar apresentação sobre Conventional Commits"
   git branch -M main
   git remote add origin https://github.com/seu-usuario/apresentacao-commits.git
   git push -u origin main
   ```

3. **Ative o GitHub Pages:**
   - Vá para **Settings** do repositório
   - Procure por **Pages** (no menu lateral esquerdo)
   - Em "Source", selecione **main** (ou a branch que você usou)
   - Clique **Save**

4. **Acesse sua apresentação:**
   - Após alguns segundos, você verá um link como:
   - `https://seu-usuario.github.io/apresentacao-commits`

## 📁 Estrutura de Arquivos

```
apresentacao-commits/
├── index.html                         # Navegador de slides (abra este primeiro!)
├── slides.css                         # Estilos compartilhados dos slides
├── 01_title_slide.html                   # Slide 1: Capa
├── 02_about_me.html                      # Slide 2: Quem sou eu
├── 03_expectativa_duda_mundo_tech.html   # Slide 3: Expectativa (imagem grande)
├── 04_realidade_duda_mundo_tech.html     # Slide 4: Realidade (imagem grande)
├── 05_intro_por_que_escrevemos_codigo.html # Slide 5: Título "Por que escrevemos código?"
├── 05_por_que_escrevemos_codigo.html     # Slide 6: Negócio, volatilidade e contexto
├── 07_the_problem.html                   # Slide 7: O código é metade da história
├── 08_future_self.html                   # Slide 8: O "você do futuro"
├── 09_git_tree_chaos.html                # Slide 9: Árvore git / mensagens vazias
├── 10_commit_chaos.html                  # Slide 10: Como controlar esse caos?
├── 11_boas_praticas_colaboracao_codigo.html # Slide 11: Boas práticas colaboração
├── 12_conventional_commits_intro.html    # Slide 12: Formato Conventional Commits
├── 13_conventional_commits_tipos.html    # Slide 13: Tipos feat/fix e Angular
├── 14_conventional_commits_exemplos.html # Slide 14: Exemplos convencionais
├── 15_why_conventional_commits.html      # Slide 15: Benefícios
├── 16_comparison_examples.html           # Slide 16: Do Caos ao Controle
├── 17_gancho_commits_padrao_limpeza.html # Slide 17: Padrão + limpeza (gancho)
├── 18_git_rebase_interativo.html         # Slide 18: Rebase interativo
├── 19_git_commit_amend.html              # Slide 19: git commit --amend
├── 20_gancho_boas_praticas_mr_pr.html    # Slide 20: Gancho “Bora abrir um PR?”
├── 21_boas_praticas_mr_pr_intro.html     # Slide 21: Intro boas práticas de PR
├── 22_pr_anatomy.html                    # Slide 22: Anatomia de um PR
├── 23_pr_context.html                    # Slide 23: Contexto em PRs
├── 24_pr_exemplo_bom.html                # Slide 24: Exemplo de PR com contexto (imagem)
├── 25_pr_exemplo_ruim.html               # Slide 25: Exemplo de PR sem contexto (imagem)
├── 26_gancho_merge_strategies.html       # Slide 26: Gancho “Bora mergear?”
├── 27_merge_main_intro.html              # Slide 27: Merge na main (intro)
├── 28_merge_squash.html                  # Slide 28: Squash and merge
├── 29_merge_commit.html                  # Slide 29: Merge commit
├── 30_merge_rebase.html                  # Slide 30: Rebase and merge
├── 31_call_to_action.html                # Slide 31: Chamada para ação
├── 32_final_phrase.html                  # Slide 32: Frase de fechamento
├── 33_conclusion_qna.html                # Slide 33: Conclusão / Q&A
└── README.md                          # Este arquivo
```

## 🎨 Estilo

- **Tema:** Terminal minimalista
- **Cores:** Fundo escuro (#1E1E1E), texto claro, destaque em verde (#4ADE80)
- **Fontes:** Space Grotesk (títulos), IBM Plex Mono (corpo)
- **Resolução:** 1280x720px (16:9)

## ⌨️ Atalhos de Teclado

| Tecla | Ação |
|-------|------|
| `→` (Seta Direita) | Próximo slide |
| `←` (Seta Esquerda) | Slide anterior |
| `F11` | Tela cheia |

## 📝 Personalizações

Você pode editar os arquivos HTML diretamente:
- Alterar cores: procure por `#4ADE80` (verde), `#1E1E1E` (fundo), `#E0E0E0` (texto)
- Modificar conteúdo: edite o texto dentro das tags HTML
- Adicionar novos slides: crie um novo arquivo `.html` e adicione à lista em `index.html`

## 🔗 Referências

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Atlassian Git Tutorials](https://www.atlassian.com/git)
- [Commitizen](http://commitizen.github.io/cz-cli/)
- [Husky](https://typicode.github.io/husky/)

## 📄 Licença

Livre para uso pessoal e educacional.

---

**Dica:** Esta apresentação é um ótimo exemplo de como usar Git e GitHub de forma prática. Considere fazer commits bem estruturados enquanto trabalha nela! 😉
