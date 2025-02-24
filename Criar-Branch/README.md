# **Criar uma Branch pelo Terminal (Zsh)**  

## 📌 1. Verificar se você está em um repositório Git  

Primeiro, abra o terminal **Zsh** e navegue até o diretório do seu repositório:  

```sh
cd /caminho/do/seu/repo
```

Para garantir que voce está em um repositório Git, execute:
```sh
git status
```

Se não estiver em um repositório Git, inicialize um novo com:
```sh
git init
```

## 🌱 2. Criar uma nova Branch
```sh
git checkout -b nome-da-branch
```
- Substitua nome-da-branch pelo nome desejado para sua branch.

Para verificar se a branch foi criada, execute:
```sh
git branch
```
Isso listará todas as branches do repositório. A branch atual estará marcada com um *. Se caso a branch não estiver sido selecionada automaticamente no seu terminal, execute:
```sh
git checkout nome-da-branch
```

## ✏️ 3. Fazer alterações na nova Branch
Agora que você está na nova branch, faça as alterações necessárias nos arquivos do projeto.

Uma boa prática seria adicionar cada alteração que for feita e dar um commitar(comentar). Por exemplo:

🔍 Esse comando irá listar o que foi modificado.

```sh
git status
```

📂 Adicionar arquivos ao commit

```sh
git add nome-do-arquivo
```

Ou adicione todos os arquivos modificados:
```sh
git add .
```

📝 Criar um commit com uma mensagem descritiva
```sh
git commit -m "Descrição do commit"
```
Sempre escreva mensagens de commit claras e objetivas.

## 🚀 4. Enviar a branch para o repositório remoto(No GitHub)
Se vai enviar a branch para o GitHub execute:
```sh
git push origin nome-da-branch
```

## 🔄 5. Alternar entre branches
Se precisar voltar para a branch principal (main), use:

```sh
git checkout main
```

Ou, em versões mais recentes do Git:
```sh
git switch main
```

---

## 🎉 **Conclusão**  

Com esses passos, você agora tem o conhecimento necessário para criar, alternar e gerenciar suas branches de forma eficiente no Git usando o terminal **Zsh**! 🔧💻  

Lembre-se de sempre manter suas mensagens de commit claras, realizar commits frequentemente e manter o repositório organizado para facilitar o trabalho em equipe. 🌟  

Se precisar de mais ajuda, estarei por aqui. Boa sorte no seu projeto e até a próxima! 🚀👋  

