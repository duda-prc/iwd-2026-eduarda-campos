# Do Caos ao Controle: Commits, PRs e contexto no Git

Uma apresentação interativa sobre Conventional Commits, Pull Requests com contexto e histórico Git legível.

## 📋 Conteúdo

37 slides cobrindo:
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
12. Comunicação clara nos commits (o que é Conventional Commits)
13. Conventional Commits — o padrão ouro (formato da mensagem)
14. Conventional Commits — tipos (`feat`/`fix` e Convenção Angular)
15. Exemplos de commits convencionais
16. Benefícios da adoção
17. Exemplos: Do Caos ao Controle
18. Gancho: padrão convencional + histórico limpo
19. Rebase interativo (`git rebase -i`)
20. `git commit --amend` (último commit)
21. Gancho — “Bora abrir um PR?”
22. Boas práticas de PR (introdução ao bloco de revisão)
23. Anatomia de um Pull Request eficaz
24. Contexto em PRs — ajude o revisor
25. Exemplo visual — PR fraco ou sem contexto (captura de tela)
26. Exemplo visual — PR com bom contexto (captura de tela)
27. Gancho — “Bora mergear?” (antes das estratégias na main)
28. Estratégias de merge na main — introdução (boas práticas 3/3)
29. Merge commit
30. Squash and merge
31. Rebase and merge (histórico linear)
32. Repositório real de exemplo (esta apresentação no GitHub)
33. Slide apenas com imagem (tela cheia)
34. Resumo: o que vimos (commits, PRs, merge)
35. Pequenas mudanças, grandes impactos
36. Frase de fechamento — por que escrevemos código?
37. Conclusão e Q&A

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
├── 12_comunicacao_clara_commits.html     # Slide 12: Comunicação clara / o que é CC
├── 13_conventional_commits_intro.html    # Slide 13: Formato Conventional Commits
├── 14_conventional_commits_tipos.html    # Slide 14: Tipos feat/fix e Angular
├── 15_conventional_commits_exemplos.html # Slide 15: Exemplos convencionais
├── 16_why_conventional_commits.html      # Slide 16: Benefícios
├── 17_comparison_examples.html           # Slide 17: Do Caos ao Controle
├── 18_gancho_commits_padrao_limpeza.html # Slide 18: Padrão + limpeza (gancho)
├── 19_git_rebase_interativo.html         # Slide 19: Rebase interativo
├── 20_git_commit_amend.html              # Slide 20: git commit --amend
├── 21_gancho_boas_praticas_mr_pr.html    # Slide 21: Gancho “Bora abrir um PR?”
├── 22_boas_praticas_mr_pr_intro.html     # Slide 22: Intro boas práticas de PR
├── 23_pr_anatomy.html                    # Slide 23: Anatomia de um PR
├── 24_pr_context.html                    # Slide 24: Contexto em PRs
├── 25_pr_exemplo_ruim.html               # Slide 25: Exemplo de PR sem contexto (imagem)
├── 26_pr_exemplo_bom.html                # Slide 26: Exemplo de PR com contexto (imagem)
├── 27_gancho_merge_strategies.html       # Slide 27: Gancho “Bora mergear?”
├── 28_merge_main_intro.html              # Slide 28: Merge na main (intro)
├── 29_merge_commit.html                  # Slide 29: Merge commit
├── 30_merge_squash.html                  # Slide 30: Squash and merge
├── 31_merge_rebase.html                  # Slide 31: Rebase and merge
├── 32_repo_exemplo_real.html             # Slide 32: Repositório real de exemplo
├── 33_slide_apenas_imagem.html           # Slide 33: Só imagem (veja 33_slide_imagem.png)
├── 34_resumo_o_que_vimos.html            # Slide 34: Resumo do que vimos
├── 35_call_to_action.html                # Slide 35: Chamada para ação
├── 36_final_phrase.html                  # Slide 36: Frase de fechamento
├── 37_conclusion_qna.html                # Slide 37: Conclusão / Q&A
├── repo-example.png                      # Captura do slide 32 (repositório no GitHub)
├── 33_slide_imagem.png                   # Imagem do slide 33 (adicione este arquivo)
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
