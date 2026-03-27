# Do Caos ao Controle: Commits, PRs e contexto no Git

Uma apresentação interativa sobre Conventional Commits, Pull Requests com contexto e histórico Git legível.

## 📋 Conteúdo

18 slides cobrindo:
1. Capa
2. Quem sou eu
3. Expectativa da Duda no mundo tech
4. Realidade da Duda no mundo tech
5. Por que escrevemos código? (negócio, regras voláteis e contexto)
6. Além do código (fechamento: história vs. implementação)
7. O código é apenas metade da história
8. O "você do futuro" agradece
9. Árvore Git com mensagens genéricas (`git log --graph`)
10. O caos dos commits genéricos
11. Conventional Commits — o padrão ouro (solução: histórico)
12. Benefícios da adoção
13. Exemplos: Do Caos ao Controle
14. Ferramentas que facilitam a jornada
15. Anatomia de um Pull Request eficaz (solução: MR/PR)
16. Contexto em MR/PRs — ajude o revisor
17. Pequenas mudanças, grandes impactos
18. Conclusão e Q&A

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
├── 05_por_que_escrevemos_codigo.html     # Slide 5: Negócio, volatilidade e contexto
├── 06_alem_do_codigo.html                # Slide 6: História vs. implementação
├── 07_the_problem.html                   # Slide 7: O código é metade da história
├── 08_future_self.html                   # Slide 8: O "você do futuro"
├── 09_git_tree_chaos.html                # Slide 9: Árvore git / mensagens vazias
├── 10_commit_chaos.html                  # Slide 10: Caos dos commits
├── 11_conventional_commits_intro.html    # Slide 11: Conventional Commits
├── 12_why_conventional_commits.html     # Slide 12: Benefícios
├── 13_comparison_examples.html           # Slide 13: Exemplos
├── 14_tools_and_automation.html          # Slide 14: Ferramentas
├── 15_pr_anatomy.html                    # Slide 15: Anatomia de um PR
├── 16_pr_context.html                    # Slide 16: Contexto em PRs
├── 17_call_to_action.html                # Slide 17: Chamada para ação
├── 18_conclusion_qna.html                # Slide 18: Conclusão / Q&A
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
