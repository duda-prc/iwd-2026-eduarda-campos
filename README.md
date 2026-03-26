# Do Caos ao Controle: Commits, PRs e contexto no Git

Uma apresentação interativa sobre Conventional Commits, Pull Requests com contexto e histórico Git legível.

## 📋 Conteúdo

16 slides cobrindo:
1. Capa
2. Quem sou eu
3. Por que escrevemos código? (negócio, regras voláteis e contexto)
4. Além do código (fechamento: história vs. implementação)
5. O código é apenas metade da história
6. O "você do futuro" agradece
7. Árvore Git com mensagens genéricas (`git log --graph`)
8. O caos dos commits genéricos
9. Conventional Commits — o padrão ouro (solução: histórico)
10. Benefícios da adoção
11. Exemplos: Do Caos ao Controle
12. Ferramentas que facilitam a jornada
13. Anatomia de um Pull Request eficaz (solução: MR/PR)
14. Contexto em MR/PRs — ajude o revisor
15. Pequenas mudanças, grandes impactos
16. Conclusão e Q&A

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
├── 03_por_que_escrevemos_codigo.html     # Slide 3: Negócio, volatilidade e contexto
├── 04_alem_do_codigo.html                # Slide 4: História vs. implementação
├── 05_the_problem.html                   # Slide 5: O código é metade da história
├── 06_future_self.html                   # Slide 6: O "você do futuro"
├── 07_git_tree_chaos.html                # Slide 7: Árvore git / mensagens vazias
├── 08_commit_chaos.html                  # Slide 8: Caos dos commits
├── 09_conventional_commits_intro.html    # Slide 9: Conventional Commits
├── 10_why_conventional_commits.html     # Slide 10: Benefícios
├── 11_comparison_examples.html           # Slide 11: Exemplos
├── 12_tools_and_automation.html          # Slide 12: Ferramentas
├── 13_pr_anatomy.html                    # Slide 13: Anatomia de um PR
├── 14_pr_context.html                    # Slide 14: Contexto em PRs
├── 15_call_to_action.html                # Slide 15: Chamada para ação
├── 16_conclusion_qna.html                # Slide 16: Conclusão / Q&A
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
