<!-- Título -->
# Configurando Usuário no Git

***Conteúdo da Aula:***

Para que os commits feitos possuam nosso nome e e-mail em seu escopo, precisamos realizar esta configuração.

Para isso, no terminal (macOS ou Linux) ou Git Bash (Windows), digite os seguintes comandos:

```powershell
git config --global user.name "SEU NOME"
```

> Para configurar o nome do usuário.

```powershell
git config --global user.email "SEU EMAIL"
```

> Para configurar o e-mail.

Com isso, todos os commits feitos no computador terão nosso e-mail e nome como autores.

## :memo: Explicação do Processo

**O que este código faz?**  

Configura o nome e e-mail do usuário globalmente no Git, para identificar quem está fazendo alterações nos repositórios.

**Vocabulário Básico:**

- `git config` &#8594; Comando para configurar preferências do Git.
- `--global` &#8594; Aplica a configuração para todos os repositórios do computador.
- `user.name` &#8594; Identifica o nome do usuário nos commits.
- `user.email` &#8594; Identifica o e-mail do usuário nos commits.

**Explicação Passo a Passo:**

1. `Linha 1`: `git config --global user.name "SEU NOME"`
   &#8594; Cria uma "etiqueta" com seu nome que será usada em todos os seus projetos Git, como assinar um quadro.

2. `Linha 2`: `git config --global user.email "SEU EMAIL"`
   &#8594; Adiciona seu "endereço digital" que identifica você em todos os repositórios, como um carimbo pessoal.

**Cuidado!**

- Use seu nome real e e-mail verdadeiro.
- Coloque o nome entre aspas se tiver espaços.
- O e-mail deve ser o mesmo da sua conta no GitHub/GitLab.

**Dica Prática:**

Pense nisso como assinar um caderno: cada vez que você fizer uma alteração (commit), seu nome e e-mail estarão junto, como uma assinatura.

**Exemplo Concreto:**

```powershell
git config --global user.name "Marta Silva"
git config --global user.email "marta.silva@email.com"
```

Agora todos os seus projetos saberão que foi você quem fez as alterações!

> [!IMPORTANT]\
> **Boas práticas**:
>
> - Usar nome real e e-mail profissional.
> - Manter consistência entre nome/e-mail.
> - Verificar configuração antes de iniciar trabalho.

---

> [!WARNING]\
> **Recomendações**:
>
> - Adicionar verificação de configuração:
>
> ```powershell
> git config --global --list
> ```
>
> Para listar todas as configurações globais do Git.

---

> [!NOTE]\
> **Observações**:
>
> - Configuração `--global` aplica-se a todos os repositórios.
> - Possível sobrescrever configuração por repositório específico.
> - Recomendado usar e-mail associado à conta GitHub/GitLab.

---

## :clipboard: Próximos Passos

- Configurar identidade no Git.
- Verificar configurações.
- Iniciar trabalho em repositórios.

## :bookmark: Tags

`#Git` `#Configuração` `#DevOps` `#ControleDeVersão` `#Iniciantes`

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-con-usu-git-com-git-fun-fun&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-con-usu-git-com-git-fun-fun?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-con-usu-git-com-git-fun-fun?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-con-usu-git-com-git-fun-fun?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-con-usu-git-com-git-fun-fun?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-con-usu-git-com-git-fun-fun?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
