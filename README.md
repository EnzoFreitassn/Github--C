# 📋 Mural de Recados

Um projetinho simples para aprender Git e GitHub na prática.

A ideia é fácil: cada pessoa adiciona o nome e um recado na lista do arquivo
[`participantes.md`](participantes.md), e a página [`index.html`](index.html)
mostra o mural.

---

## 🎯 Para que serve este repositório

Este projeto existe para treinar o fluxo básico do GitHub:

1. **Clonar** o repositório
2. Criar uma **branch** (galho) com suas mudanças
3. Fazer um **commit** (salvar um ponto no histórico)
4. Dar **push** (subir para o GitHub)
5. Abrir um **Pull Request** (pedir para juntar suas mudanças)

---

## 🧑‍💻 Guia rápido de comandos (cola aqui!)

### 1. Clonar o repositório (só na primeira vez)
```bash
git clone https://github.com/USUARIO/mural-de-recados.git
cd mural-de-recados
```

### 2. Criar uma branch sua
Sempre trabalhe numa branch separada, nunca direto na `main`.
```bash
git checkout -b minha-branch
```
Dica: dê um nome que explique o que você vai fazer, ex.: `adiciona-nome-joao`.

### 3. Fazer suas mudanças
Edite o arquivo `participantes.md` e adicione sua linha.

### 4. Ver o que você mudou
```bash
git status        # mostra quais arquivos mudaram
git diff          # mostra as mudanças linha por linha
```

### 5. Salvar as mudanças (commit)
```bash
git add participantes.md       # escolhe o que vai no commit
git commit -m "Adiciona recado do João"
```

### 6. Subir para o GitHub (push)
```bash
git push origin minha-branch
```

### 7. Abrir um Pull Request
Vá até a página do repositório no GitHub. Vai aparecer um botão
**"Compare & pull request"**. Clique, escreva uma descrição e confirme.

---

## 🔁 Comandos do dia a dia

| O que você quer | Comando |
|---|---|
| Ver em qual branch está | `git branch` |
| Trocar de branch | `git checkout nome-da-branch` |
| Atualizar sua cópia com o que mudou no GitHub | `git pull` |
| Ver o histórico de commits | `git log --oneline` |

---

## 💡 Observação

Para conseguir dar `push` direto neste repositório, você precisa ser
**colaborador**. O dono do repositório te adiciona em
`Settings → Collaborators`.
