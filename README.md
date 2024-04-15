
<span id="topo">
<div align="center">
<img src="/Documentos/techguardian.png" width="350px" />
</div>
   
##  :space_invader:Projeto:
  O objetivo do projeto é desenvolver um sistema abrangente para controlar e monitorar a movimentação na RedZone, uma área específica onde a presença e o movimento de pessoas precisam ser gerenciados e monitorados com precisão. O sistema visa fornecer funcionalidades essenciais para administradores e usuários finais, controle de acesso e análise de dados eficazes, proporcionando segurança, transparência e facilidade de uso para todos os usuários envolvidos.


## :dart: Backlog Sprint 01


<img src="/Documentos/backlogsprint1.png" width="350px" />
  
## :dart: Backlog Total  
<p>
<img src="/Documentos/backlogsprint1.png" width="350px" />
</p>

<p>
<img src="/Documentos/backlogsprint2.png" width="350px" />
</p>
<img src="/Documentos/backlogsprint3.png" width="350px" />

### Critérios de Aceitação

<img src="/Documentos/criterioAceitação.png" width="1000px" />

##  :space_invader:Task details:

<img src="/Documentos/tasks.png" width="700px" />


<span id="project-scope">

## :dart: Escopo do Projeto

### Mockup

<img src="/Documentos/mockup.png" width="350px" />

### :bookmark_tabs: Modelo de Dados

<img src="/Documentos/modelagemDados.png" width="350px" />
<p>
end_id/sai_id: Identificador único de registro do movimento na RedZone. 
</p>
<p>
data_entrada/data_saida: Data do momento em que o movimento foi registrado. 
</p>
<p>
hora_entrada/hora_saida: Horário do momento em que o movimento foi registrado. 
  </p>
<p>
obs_entrada/obs_saida: Campo opcional para incluir observações adicionais sobre o movimento. 
</p>

### 📊Burndown

<img src="/Documentos/burndownSp1.png" width="700px" />

Veja mais detalhes das Tasks em nosso [JIRA](https://techguardian.atlassian.net/jira/software/projects/TGN/boards/3/backlog)

### 📹Sprint Review
<p>

</p>

### Requisitos Funcionais:
- ✅   Desenvolver uma interface web intuitiva, com autenticação;
- ✅   Desenvolver um Dashboard de indicadores por período;
- ✅   Filtros de período para análise de dados;
- ✅   Geração relatórios para compartilhamento.


### Requisitos Não Funcionais:
- ✅  Manual do usuário;
- ✅  Documentação do sistema;
- ✅  Guia de instalação;
- ✅  Acesso à organização de desenvolvimento.


## :dart: Tecnologias Utilizadas 

- ✅  Ferramentas: Figma, Visual Studio Code, Github, Whatsapp e Discord
- ✅  Programação Back-End : Java , Python, IA.
- ✅  Front-End Programming:  Vue.js.
- ✅  Database: MySql.

## :dart: Cronograma

|   Period     |     Dates       |
| ------------------------------ | ---- |
|  Kickoff     | 04/03 -  08/03  |
|  Sprint1     | 25/03 - 14/04   |
|  Sprint 2    | 15/04 - 05/05   |
|  Sprint 3    | 06/05 - 26/05   |
|  Sprint 4    | 27/05 - 16/06   |

Vídeo Sprint Review 


<hr>

<span id="team">

## 👨‍💻 Team


|    Name     | Function |      GitHub    |
|:-----------: |:------|:----------------------------|
| Eduardo Carvalho | Product Owner | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EduardoPereiraCarvalho) |
| Rafael Cajé | Scrum Master | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rafael-Caje) |
| Ana Paula | Dev | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnaPaulaSOliveira) |
| Carlos Henrique | Dev | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Carlos-Henrique39) |
| Thamires de Souza Barbosa | Dev | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Thamires-S0uza) |
| Vitor Yuri Santos | Dev | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vitor-y) |
| William Claudimar | Dev | [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/William2819) |

---

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


→ [Return the top](#returnthetop)
---

