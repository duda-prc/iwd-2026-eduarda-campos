# Do Caos ao Controle: Padronização de Commits e Documentação

Uma apresentação interativa sobre padronização de commits, documentação e boas práticas de Git.

## 📋 Conteúdo

12 slides cobrindo:
1. Introdução ao tema
2. O problema: código sem contexto
3. O "você do futuro" agradece
4. O caos dos commits genéricos
5. Contexto em MR/PRs
6. Anatomia de um Pull Request eficaz
7. Conventional Commits - O padrão ouro
8. Benefícios da adoção
9. Exemplos: Do Caos ao Controle
10. Ferramentas que facilitam a jornada
11. Pequenas mudanças, grandes impactos
12. Conclusão e Q&A

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
├── index.html                      # Navegador de slides (abra este primeiro!)
├── title_slide.html               # Slide 1: Capa
├── the_problem.html               # Slide 2: O problema
├── future_self.html               # Slide 3: O "você do futuro"
├── commit_chaos.html              # Slide 4: Caos dos commits
├── pr_context.html                # Slide 5: Contexto em PRs
├── pr_anatomy.html                # Slide 6: Anatomia de um PR
├── conventional_commits_intro.html # Slide 7: Conventional Commits
├── why_conventional_commits.html  # Slide 8: Benefícios
├── comparison_examples.html       # Slide 9: Exemplos
├── tools_and_automation.html      # Slide 10: Ferramentas
├── call_to_action.html            # Slide 11: Chamada para ação
├── conclusion_qna.html            # Slide 12: Conclusão
└── README.md                       # Este arquivo
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
