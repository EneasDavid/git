# Mini-curso Git — Linhas do Tempo Perdidas

Você viajou pelas ramificações do tempo e agora há **várias versões da história** coexistindo no repositório.  
Mas cuidado: **nem todas deveriam continuar existindo...**

Seu objetivo é **encontrar a versão correta** e corrigir o rumo da história!

---

## Missão

Usando apenas os comandos Git aprendidos, encontre em qual branch está a versão final do arquivo `voce.txt`.

O conteúdo certo é:

```
ESSA É A VERSÃO FINAL!
```

---

## Contexto

Durante suas viagens temporais, você criou 6 possíveis linhas do tempo.  
Cada uma delas contém um arquivo `voce.txt`, mas só uma guarda o final verdadeiro.

### Branches existentes

| Branch       | Descrição |
|---------------|-----------|
| `agora`       | O presente nem sempre é o lugar certo. |
| `flamengo`    | Uma linha temporal animada, mas confusa. |
| `musica`      | Ecos de um som distante no tempo. |
| `possivel`    | Parece correta… mas não é. |
| `sorvete`     | Doce, porém temporária. |
| `talvez`      | Ambígua por natureza — ou será essa? ❓ |

---

## 💻 Comandos úteis

Use **apenas comandos Git** para navegar e investigar:

```bash
git branch               # listar as branches disponíveis
git switch <branch>      # mudar de branch
cat voce.txt             # visualizar o arquivo
git branch -d <branch>   # excluir uma linha do tempo incorreta
git push origin main     # enviar alterações finais
```

---

## Dica

Algumas linhas do tempo **não deveriam existir**.  
Quando encontrar a correta, **limpe o tempo** (remova as outras branches locais).

---

## Quando terminar

1. Verifique que `voce.txt` mostra “ESSA É A VERSÃO FINAL!”  
2. Garanta que apenas a branch certa permaneça.  
3. Envie sua linha do tempo restaurada para o repositório remoto.

Boa sorte, viajante do Git.