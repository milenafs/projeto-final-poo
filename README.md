# 📚 Gerenciador Acadêmico

## 🛠️ Comandos Chave do Git

**📥 Pega as alterações da sua branch da nuvem e joga pra local**

```bash
git pull
```

**➕ Salva todas suas alterções no código pra commitar**

```bash
git add .
```

**✅ Cria um commit**

```bash
git commit -m "Descrição do commit"
```

**⬆️ Sobe as atualizações da sua branch local pra nuvem**

```bash
git push
```

## 🌿 **Mudar de branch**

**🔀 Para mudar de branch, use o comando:**

```bash
git checkout -b nome-da-nova-branch
```

**↩️ Voltar pra main:**

```bash
git checkout main
```

## 🔄 Atualizar sua branch com as mudanças da main

**1. Esteja na sua branch**

> Não sabe em que branch está? Roda um `git status`

**2. Pegue as atualizações gerais do projeto da nuvem para seu projeto local**

```bash
git fetch
```

**3. Atualize sua branch com a main**

```bash
git rebase origin/main
```

**4. Suba a atualização da sua branch pra nuvem**

```bash
git push --force-with-lease
```

## 📌 Mergear sua branch na main

**1. Faça a [atualização da sua branch com a main](https://github.com/mrRiqueRique/projeto-final-poo/tree/main?tab=readme-ov-file#-atualizar-sua-branch-com-as-mudan%C3%A7as-da-main) do tópico anterior**

**2. No github vá em [`Pull requests`](https://github.com/mrRiqueRique/projeto-final-poo/pulls)**

**3. Crie seu PR e clique no botão de mergear caso não tenha conflito**

> Se deu conflito é porque o passo **1** não aconteceu

![image](https://github.com/user-attachments/assets/c78b3ec7-3e50-4af9-b6e2-b592d8594bf7)
