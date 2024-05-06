### Branch, Merge e Conventional Commits usados no desenvolvimento

##### Nome de BRANCH
>Type / O que a branch faz / Task do JIRA

Exemplo:
>feat/lógica-entrada-saida/TGN-1


#### Merge da branch
```
git merge --no-ff --log feature/nova-funcionalidade/Task-JIRA
```
(Traz o histórico de commits da branch excluída)

--------------------------------------------------

Padrão de COMMITS do repositório:
>>> Conventional Commits

MODELO (Pular uma linha entre mensagens):

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional] - Descrição com mais detalhe

[rodapé opcional] - Nome - Status (Parcial/Conclusão) e código da tarefa na TASK (JIRA)
```

EXEMPLO:

Dar comando abaixo pra abrir o EDITOR:
```
git commit
```

NO EDITOR QUE ABRIR INFORMAR (Ex)

```
refactor: ajuste de resposta da IA

Agora a Data já vem no objeto com formato (Dia - Mês - Ano)

Rafael Cajé - Conclusão da Task TGN-1
```

Depois aperte ESC >>> :wq! >>> ENTER

---
#### Tipos (Type) de Commits

##### Os commits possuem os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

>fix - Commits do tipo fix indicam que seu trecho de código commitado está solucionando um problema (bug fix), (se relaciona com o PATCH do versionamento semântico).

>feat- Commits do tipo feat indicam que seu trecho de código está incluindo um novo recurso (se relaciona com o MINOR do versionamento semântico).

>docs - Commits do tipo docs indicam que houveram mudanças na documentação, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

>style - Commits do tipo style indicam que houveram alterações referentes a formatações de código, semicolons, trailing spaces, lint... (Não inclui alterações em código).

>refactor - Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

>build - Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.

>test - Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código).

>chore - Commits do tipo chore indicam atualizações de tarefas de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código).
