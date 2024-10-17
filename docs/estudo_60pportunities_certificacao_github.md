O GitHub é uma plataforma baseada na nuvem onde você pode armazenar, compartilhar e trabalhar em conjunto com outras pessoas para escrever código.
Git é um sistema de controle de versão que rastreia mudanças em arquivos de forma inteligente.
Como o Git e o GitHub funcionam juntos?  Ao enviar arquivos para o GitHub, você os armazenará em um "repositório Git". Isso significa que quando você fizer alterações (ou "commits") nos seus arquivos no GitHub, o Git começará automaticamente a rastrear e gerenciar suas alterações.

| Tipo de Conta | Entenda |
| -----         | -----   |
Contas de usuário  | As contas de usuário são destinadas a humanos, mas você pode criar contas para automatizar atividades no GitHub. |
|               | Contas pessoais | conta pessoal usa o GitHub Free ou o GitHub Pro. Todas as contas pessoais podem ter um número ilimitado de repositórios públicos e privados, com um número ilimitado de colaboradores nesses repositórios. |
Contas da organização 
Contas empresariais

| Tipo de Conta | GitHub Free                                                  | GitHub Pro |
| -----         | -----                                                        | -----          |
| Pessoal       | Suporte da Comunidade GitHub                                 | Suporte do GitHub por e-mail   |
|               | Alertas Dependabot                                           | 3.000 minutos de GitHub Actions por mês   |
|               | Regras de proteção de implantação para repositórios públicos |    |
|               | Aplicação de autenticação de dois fatores                    |    |
|               | 500 MB de armazenamento de pacotes do GitHub                 | 2 GB de armazenamento de pacotes do GitHub   |
|               | 120 horas de núcleo do GitHub Codespaces por mês             | 180 horas de núcleo do GitHub Codespaces por mês   |
|               | 15 GB de armazenamento GitHub Codespaces por mês             |  20 GB de armazenamento GitHub Codespaces por mês  |
|               | Recursos do GitHub Actions:                                  | Ferramentas e insights avançados em repositórios privados:   |
|               | 2.000 minutos por mês                                        |  Revisores de solicitação de pull necessários  |
|               | Regras de proteção de implantação para repositórios públicos | Vários revisores de solicitação de pull,Ramos protegidos,Proprietários do código,Referências vinculadas automaticamente
   |
|               | Páginas do GitHub em repositórios públicos                   |  Páginas do GitHub  |
|               |                                                              | Wikis |
|               |           | Gráficos de insights do repositório: pulso, colaboradores, tráfego, confirmações, frequência de código, rede e bifurcações |
| Organização | = Pessoal Conta |   |
|             | Suporte da Comunidade GitHub
|             | Controles de acesso de equipe para gerenciamento de grupos
|             | 2.000 minutos de GitHub Actions por mês
|             | 500 MB de armazenamento de pacotes do GitHub
|             | = GitHub Team | GitHub Free for organizations, GitHub Team includes |
|             | GitHub Support via email | |
|             | 3,000 GitHub Actions minutes per month | |
|             | 2 GB GitHub Packages storage
|             | Advanced tools and insights in private repositories: Required pull request reviewers,Multiple pull request reviewers,Draft pull requests,Team pull request reviewers,Protected branches,Code owners, Scheduled reminders,GitHub Page, Wikis |  |
|             | GitHub Enterprise  | GitHub Enterprise Cloud ou GitHub Enterprise Server |
|             |  GitHub Enterprise Support |  |
|             |  Additional security, compliance, and deployment controls |  |
|             |  Authentication with SAML single sign-on|  |
|             |  Access provisioning with SAML or SCIM|  |
|             |  Deployment protection rules with GitHub Actions for private or internal |             |  repositories|  |
|             |  GitHub Connect|  |
|             |  GitHub Enterprise Cloud specifically includes:|  |
|             |  50,000 GitHub Actions minutes per month|  |
|             |  Included minutes can be used with standard GitHub-hosted runners only. |  |
|             |  50 GB GitHub Packages storage
|             |  A service level agreement for 99.9% monthly uptime

## Permissões de acesso no GitHub
Uma permissão é a capacidade de executar uma ação específica. 

| Tipo e Conta    | Entenda |
| -----           | ----    |
| Contas pessoais | o proprietário do repositório e os colaboradores. O GitHub limita o número de pessoas que podem ser convidadas para um repositório dentro de um período de 24 horas. Settings --> Colaboradores --> Adicionar pessoas |
|                 | Settings --> Opções de moderação --> clique em Limites de interação. |
|                 |  

GitHub Advanced Security: Varredura de código, CodeQL CLI , Escaneamento secreto , Regras de triagem automática personalizadas w Revisão de dependência.


### Gerenciando as configurações do seu tema
 Configurações --> Aparência --> Modo de tema
 <details>
<summary>My top languages</summary>

| Rank | Languages |
|-----:|-----------|
|     1| JavaScript|
|     2| Python    |
|     3| SQL       |

</details>

# Criando um link permanente para um snippet de código
No GitHub, navegue até a página principal do repositório.
Localize o código que você gostaria de vincular:
Escolha se deseja selecionar uma única linha ou um intervalo.
À esquerda da linha ou intervalo de linhas, clique em `...`. No menu suspenso, clique em Copiar permalink.
Navegue até a conversa onde você deseja criar um link para o snippet de código.
Cole seu permalink em um comentário e clique em Comentar .
Acrescente #Lo número da linha ou números no final da url. Por exemplo, github.com/<organization>/<repository>/blob/<branch_name>/README.md?plain=1#L14

### Usando palavras-chave em problemas e solicitações de pull
Para vincular uma solicitação de pull a um problema para mostrar que uma correção está em andamento e para fechar o problema automaticamente quando alguém mesclar a solicitação de pull, digite uma das seguintes palavras-chave seguidas por uma referência ao problema. Por exemplo, Closes #10ou Fixes octo-org/octo-repo#100.


| Problema vinculado | Sintaxe | Exemplo |
| ----               |  ----   |  ----   | 
| Problema no mesmo repositório	| PALAVRA-CHAVE #NÚMERO-DA-EDIÇÃO | Closes #10 |
| Problema em um repositório diferente	| PALAVRA-CHAVE PROPRIETÁRIO/REPOSITÓRIO#NÚMERO-DE-EDIÇÃO	| Fixes octo-org/octo-repo#100 |
|  Múltiplos problemas	| Use a sintaxe completa para cada problema | Resolves #10, resolves #123, resolves octo-org/octo-repo#100 |

<div class="mdx-columns3" markdown>
- [x] close
- [x] closes
- [x] closed
- [x] fix
- [x] fixes
- [x] fixed
- [x] resolve
- [x] resolves
- [x] resolved
</div>

### Comandos de barra
Os comandos de barra facilitam a digitação de Markdown mais complexos, como tabelas, listas de tarefas e blocos de código.


| Comando | Descrição |
| ----    | -----     |
| /code	  | Insere um bloco de código Markdown. Você escolhe o idioma. |
| /details | Insere uma área de detalhes recolhível. Você escolhe o título e o conteúdo. |
| /saved-replies | Insere uma resposta salva. Você escolhe entre as respostas salvas para sua conta de usuário. Se você adicionar %cursor%à sua resposta salva, o comando slash colocará o cursor naquele local. |
| /table | Insere uma tabela Markdown. Você escolhe o número de colunas e linhas. |
| /template | Mostra todos os modelos no repositório. Você escolhe o modelo para inserir. Este comando de barra funcionará para modelos de problemas e um modelo de solicitação de pull. |

No menu suspenso, clique em Copiar permalink .
### Fixando um problema no seu repositório
navegue até a página principal do repositório. --> Problemas (Issues) --> Fixar problema.
### Marcando problemas ou solicitações de pull como duplicados
Para marcar um problema ou solicitação de pull como duplicado, digite "Duplicate of #nnn"
### Desmarcando duplicatas
Você pode desmarcar problemas duplicados e solicitações de pull clicando em Desfazer na linha do tempo.
### Transferindo um problema aberto para outro repositório
principal do repositório --> Problemas --> Escolha o Problema -->  Problema de transferência --> Repositório para o qual deseja transferir o problema. -->  Transferir problema .
### Fechando um problema
Problemas  --> Opcionalmente, para alterar o motivo do encerramento do problema, ao lado de "Fechar problema", selecione e clique em um motivo --> Fechar Problema
### Excluir Problemas
o problema que você deseja excluir. --> "Notificações", clique em Excluir problema --> clique em Excluir este problema.
## Projetos 
É uma ferramenta adaptável e flexível para planejar e rastrear o trabalho no GitHub.

### Criando um projeto



Recomendamos fortemente que você configure 2FA para sua conta. 2FA é uma camada extra de segurança que pode ajudar a manter sua conta segura. Para obter mais informações, consulte " Configurando autenticação de dois fatores ".

### Renomear uma branch
- [x] git branch -m OLD-BRANCH-NAME NEW-BRANCH-NAME
- [x] git fetch origin
- [x] git branch -u origin/NEW-BRANCH-NAME NEW-BRANCH-NAME
- [x] git remote set-head origin -a
- [x] git remote prune origin

Exigir revisões de solicitação de pull antes de mesclar
você pode exigir que o push revisável mais recente seja aprovado por alguém diferente da pessoa que o fez.
Descartar aprovações de pull request obsoletas quando novos commits forem enviados e/ou Exigir aprovação do push revisável mais recente , 


### Regras na Branch
Branches -->  Branch protection rules --> Add rule --> Branch name pattern"


| Tipo | Contexto | Requisitos de mesclagem	| Considerações |
| ---- | ----     | -----  | ------- |
| Strict | A caixa de seleção Exigir que as ramificações estejam atualizadas antes da mesclagem está marcada. |  O branch deve estar atualizado com o branch base antes da mesclagem. | Este é o comportamento padrão para verificações de status necessárias. Mais builds podem ser necessárias, pois você precisará atualizar o branch principal depois que outros colaboradores atualizarem o branch de destino. |
| Loose | A caixa de seleção Exigir que as ramificações estejam atualizadas antes da mesclagem não está marcada. | A ramificação não precisa estar atualizada com a ramificação base antes da mesclagem. | A ramificação não precisa estar atualizada com a ramificação base antes da mesclagem. |
| Disabled | A caixa de seleção Exigir que as verificações de status sejam aprovadas antes da mesclagem não está marcada. | A filial não tem restrições de mesclagem. | Se as verificações de status necessárias não estiverem habilitadas, os colaboradores podem mesclar o branch a qualquer momento, independentemente de ele estar atualizado com o branch base. Isso aumenta a possibilidade de alterações incompatíveis. |

Exigir confirmações assinadas: Usando GPG, SSH ou S/MIME,



## Perguntas e Respostas

1. **O que é Git?**
   - a) Um sistema de controle de versões.
   - b) Um serviço de armazenamento na nuvem.
   - c) Uma linguagem de programação.
   - **Resposta:** a) Um sistema de controle de versões.
2. **Como você cria um novo repositório no GitHub?**
   - a) `git new`
   - b) `git create`
   - c) Através da interface web do GitHub.
   - **Resposta:** c) Através da interface web do GitHub.
3. **Qual é o comando para adicionar todos os arquivos novos e modificados ao staging area?**
   - a) `git add .`
   - b) `git commit -m "Mensagem"`
   - c) `git push`
   - **Resposta:** a) `git add .`
4. **O que faz o comando `git status`?**
   - a) Mostra o histórico de commits.
   - b) Informa quais mudanças estão staged, unstaged ou untracked.
   - c) Faz push para o repositório remoto.
   - **Resposta:** b) Informa quais mudanças estão staged, unstaged ou untracked.
5. **Qual é a função do comando `git push`?**
   - a) Enviar suas mudanças locais para o repositório remoto.
   - b) Criar um novo branch.
   - c) Exibir o histórico de commits.
   - **Resposta:** a) Enviar suas mudanças locais para o repositório remoto.
6. **Como você reverte um commit no Git?**
   - a) `git reverse <commit-id>`
   - b) `git revert <commit-id>`
   - c) `git undo <commit-id>`
   - **Resposta:** b) `git revert <commit-id>`
7. **Qual comando é usado para criar uma nova branch no Git?**
   - a) `git checkout -b <branch-name>`
   - b) `git branch <branch-name>`
   - c) Ambos a e b.
   - **Resposta:** c) Ambos a e b.
8. **O que é um fork em GitHub?**
   - a) Uma cópia do repositório original que permite mudanças.
   - b) Uma forma de mesclar branches.
   - c) Um tipo de commit.
   - **Resposta:** a) Uma cópia do repositório original que permite mudanças.
9. **Como você mescla uma branch em outra?**
   - a) `git merge <branch-name>`
   - b) `git combine <branch-name>`
   - c) `git join <branch-name>`
   - **Resposta:** a) `git merge <branch-name>`
10. **O que são issues no GitHub?**
    - a) Problemas técnicos a serem resolvidos.
    - b) Relatórios de bugs e sugestões.
    - c) Ambos a e b.
    - **Resposta:** c) Ambos a e b.
11. **O que faz o comando `git blame`?**
    - a) Mostra quem fez cada mudança em uma linha de um arquivo.
    - b) Mostra o histórico de branches.
    - c) Apaga o histórico de mudanças.
    - **Resposta:** a) Mostra quem fez cada mudança em uma linha de um arquivo.
12. **Para que serve um README.md?**
    - a) Para documentar o projeto.
    - b) Para armazenar arquivos binários.
    - c) Não tem uso específico.
    - **Resposta:** a) Para documentar o projeto.
13. **Qual é o formato padrão para mensagens de commit?**
    - a) Qualquer formato é aceitável.
    - b) Uma linha curta com um resumo e uma descrição mais longa embaixo.
    - c) Apenas uma linha curta.
    - **Resposta:** b) Uma linha curta com um resumo e uma descrição mais longa embaixo.
14. **O que significa "merge conflict"?**
    - a) Quando duas branches têm mudanças que não podem ser mescladas automaticamente.
    - b) Quando o repositório está corrompido.
    - c) Quando um commit é revertido.
    - **Resposta:** a) Quando duas branches têm mudanças que não podem ser mescladas automaticamente.
15. **O que é GitHub Actions?**
    - a) Uma ferramenta para automatizar fluxos de trabalho.
    - b) Um método de revisão de código.
    - c) Um tipo de branching.
    - **Resposta:** a) Uma ferramenta para automatizar fluxos de trabalho.
16. **Como você pode comentar em um pull request?**
    - a) Somente através de email.
    - b) Usando a aba 'Comments' no pull request.
    - c) Não é possível comentar.
    - **Resposta:** b) Usando a aba 'Comments' no pull request.
17. **Qual comando pode ser usado para atualizar seu branch local com as alterações do repositório remoto?**
    - a) `git fetch`
    - b) `git pull`
    - c) Ambos a e b.
    - **Resposta:** c) Ambos a e b.
18. **Como você exclui uma branch local?**
    - a) `git delete <branch-name>`
    - b) `git branch -d <branch-name>`
    - c) `git remove <branch-name>`
    - **Resposta:** b) `git branch -d <branch-name>`
19. **O que é um "remote" no Git?**
    - a) Uma branch local.
    - b) Um repositório no servidor remoto.
    - c) Um commit específico.
    - **Resposta:** b) Um repositório no servidor remoto.
20. **Como você adiciona um repositório remoto ao seu repositório local?**
    - a) `git remote add origin <URL>`
    - b) `git fetch <URL>`
    - c) `git push <URL>`
    - **Resposta:** a) `git remote add origin <URL>`
21. **Qual comando você usaria para cancelar um commit local que ainda não foi enviado ao repositório remoto?**
    - a) `git restore --staged <file>`
    - b) `git reset --soft HEAD~1`
    - c) `git delete <commit-id>`
    - **Resposta:** b) `git reset --soft HEAD~1`
22. **Qual é a vantagem de usar branches no Git?**
    - a) Permite que várias pessoas trabalhem em recursos diferentes simultaneamente.
    - b) Mantém o repositório limpo e organizado.
    - c) Ambas a e b.
    - **Resposta:** c) Ambas a e b.
23. **O que o comando `git checkout <branch-name>` faz?**
    - a) Apaga uma branch.
    - b) Alterna o trabalho para a branch especificada.
    - c) Copia um arquivo específico.
    - **Resposta:** b) Alterna o trabalho para a branch especificada.
24. **O que é um commit "orphan" no Git?**
    - a) Um commit sem um pai.
    - b) Um commit que não é parte da árvore de commits.
    - c) Ambos a e b.
    - **Resposta:** c) Ambos a e b.
25. **Qual das opções abaixo é uma boa prática ao escrever mensagens de commit?**
    - a) Mensagens longas e detalhadas sem formatação.
    - b) Uma linha resumindo as mudanças, seguida de uma linha em branco e uma descrição detalhada, se necessário.
    - c) Usar apenas emojis.
    - **Resposta:** b) Uma linha resumindo as mudanças, seguida de uma linha em branco e uma descrição detalhada, se necessário.
26. **O que faz o comando `git stash`?**
    - a) Salva temporariamente mudanças não commitadas.
    - b) Realiza um commit sem mensagem.
    - c) Restaura uma versão anterior do repositório.
    - **Resposta:** a) Salva temporariamente mudanças não commitadas.
27. **Como você aplica as mudanças guardadas em um stash?**
    - a) `git apply stash`
    - b) `git stash apply`
    - c) `git pop stash`
    - **Resposta:** b) `git stash apply`
28. **Qual é a função do comando `git reset`?**
    - a) Reverter o repositório a um commit anterior.
    - b) Excluir um branch não utilizado.
    - c) Alterar a configuração do repositório.
    - **Resposta:** a) Reverter o repositório a um commit anterior.
29. **Qual é a finalidade do arquivo `.gitignore`?**
    - a) Listar arquivos que devem ser incluídos no repositório.
    - b) Listar arquivos que devem ser ignorados pelo Git.
    - c) Armazenar mensagens de commit.
    - **Resposta:** b) Listar arquivos que devem ser ignorados pelo Git.
30. **Como você compara diferenças entre duas branches?**
    - a) `git diff <branch1> <branch2>`
    - b) `git compare <branch1> <branch2>`
    - c) `git merge <branch1> <branch2>`
    - **Resposta:** a) `git diff <branch1> <branch2>`
31. **O que um pull request permite?**
    - a) Mesclar automaticamente duas branches.
    - b) Discutir mudanças antes de mesclá-las.
    - c) Criar novos branches.
    - **Resposta:** b) Discutir mudanças antes de mesclá-las.
32. **Qual comando é usado para visualizar o histórico de commits?**
    - a) `git show`
    - b) `git log`
    - c) `git history`
    - **Resposta:** b) `git log`
33. **O que é um repositório "bare"?**
    - a) Um repositório que possui apenas branches.
    - b) Um repositório sem arquivos de trabalho.
    - c) Um repositório que não possui histórico.
    - **Resposta:** b) Um repositório sem arquivos de trabalho.
34. **Qual comando é usado para listar as branches em seu repositório?**
    - a) `git show-branches`
    - b) `git branches`
    - c) `git branch`
    - **Resposta:** c) `git branch`
35. **O que acontece se você fizer um commit sem ter adicionado mudanças primeiro?**
    - a) Git retorna um erro.
    - b) O commit será vazio.
    - c) Git sobrescreve o último commit.
    - **Resposta:** b) O commit será vazio.
36. **Qual é a função do comando `git tag`?**
    - a) Criar versões de um projeto.
    - b) Adicionar um branch ao repositório.
    - c) Remover arquivos.
    - **Resposta:** a) Criar versões de um projeto.
37. **O que faz o `git cherry-pick <commit-id>`?**
    - a) Aplica mudanças de um commit específico a outra branch.
    - b) Mescla dois branches.
    - c) Exclui um commit.
    - **Resposta:** a) Aplica mudanças de um commit específico a outra branch.
38. **Como você exclui um repositório no GitHub?**
    - a) Usando a linha de comando.
    - b) Através das configurações do repositório na interface web do GitHub.
    - c) Não é possível excluir um repositório.
    - **Resposta:** b) Através das configurações do repositório na interface web do GitHub.
39. **O que é uma branch "main"?**
    - a) Uma branch que armazena o código mais estável.
    - b) Uma branch temporária.
    - c) Um tipo de commit.
    - **Resposta:** a) Uma branch que armazena o código mais estável.
40. **Qual comando você usaria para renomear uma branch?**
    - a) `git rename <old-name> <new-name>`
    - b) `git branch -m <new-name>`
    - c) `git move <old-name> <new-name>`
    - **Resposta:** b) `git branch -m <new-name>`
41. **O que faz o comando `git revert <commit-id>`?**
    - a) Apaga o commit especificado.
    - b) Cria um novo commit que desfaz as mudanças do commit especificado.
    - c) Muda a configuração do repositório.
    - **Resposta:** b) Cria um novo commit que desfaz as mudanças do commit especificado.
42. **O que o comando `git pull --rebase` faz?**
    - a) Faz uma atualização normal das mudanças.
    - b) Reaplica suas alterações sobre as últimas mudanças da branch remota.
    - c) Exclui a branch local.
    - **Resposta:** b) Reaplica suas alterações sobre as últimas mudanças da branch remota.
43. **Qual é a finalidade do comando `git reflog`?**
    - a) Mostrar os logs de pull requests.
    - b) Exibir o histórico dos movimentos de HEAD.
    - c) Excluir branches remotas.
    - **Resposta:** b) Exibir o histórico dos movimentos de HEAD.
44. **Como você pode ignorar um arquivo específico por meio do arquivo `.gitignore`?**
    - a) Adicionando o nome do arquivo diretamente.
    - b) Usando a palavra-chave "ignore".
    - c) Criando um novo arquivo de configuração.
    - **Resposta:** a) Adicionando o nome do arquivo diretamente.
45. **O que significa "force push"?**
    - a) Enviar todas as branches para o repositório remoto.
    - b) Sobrescrever a branch remota com as mudanças locais, mesmo que haja divergências.
    - c) Enviar um commit específico.
    - **Resposta:** b) Sobrescrever a branch remota com as mudanças locais, mesmo que haja divergências.
46. **O que faz o comando `git clean`?**
    - a) Remove branches não utilizadas.
    - b) Remove arquivos não rastreados do diretório de trabalho.
    - c) Limpa o histórico de commits.
    - **Resposta:** b) Remove arquivos não rastreados do diretório de trabalho.
47. **Qual é o significado de "fork" no GitHub?**
    - a) Criar uma cópia do repositório para modificar como desejar.
    - b) Mesclar duas branches.
    - c) Enviar um commit.
    - **Resposta:** a) Criar uma cópia do repositório para modificar como desejar.
48. **O que acontece se você fizer um `git pull` enquanto estiver em uma branch diverge?**
    - a) O Git tenta mesclar automaticamente as mudanças.
    - b) Você receberá um erro e precisará resolver manualmente.
    - c) O branch será excluído.
    - **Resposta:** a) O Git tenta mesclar automaticamente as mudanças.
49. **Como você pode verificar a diferença entre o repositório local e o remoto?**
    - a) `git compare`
    - b) `git diff origin/<branch>`
    - c) `git log`
    - **Resposta:** b) `git diff origin/<branch>`
50. **Qual comando é usado para mostrar o conteúdo de um arquivo em um commit específico?**
    - a) `git cat <commit-id>:<file-path>`
    - b) `git show <commit-id>:<file-path>`
    - c) `git log <commit-id>:<file-path>`
    - **Resposta:** b) `git show <commit-id>:<file-path>`
51. **O que é "pull request" no GitHub?**
    - a) Uma solicitação para mesclar seus commits em outra branch.
    - b) Um novo branch criado automaticamente.
    - cClaro! Abaixo estão 60 perguntas e respostas que você pode usar para simular um teste de certificação GitHub Foundation.





Passo 1: Gere um Token de Acesso Pessoal

    Acesse Configurações do GitHub.
    Clique em "Generate new token".
    Dê um nome ao token e selecione as permissões necessárias (para criar repositórios, você precisará da permissão repo).
    Copie o token gerado. Guarde-o em um lugar seguro, pois você não poderá vê-lo novamente.

Passo 2: Crie um Repositório Usando curl

Com o token em mãos, você pode usar o seguinte comando curl para criar um repositório. Substitua YOUR_GITHUB_TOKEN pelo seu token e REPO_NAME pelo nome do repositório que você deseja criar.

bash

curl -H "Authorization: token YOUR_GITHUB_TOKEN" \
     -d '{"name":"REPO_NAME", "private":false}' \
     https://api.github.com/user/repos

Explicação do Comando

    -H "Authorization: token YOUR_GITHUB_TOKEN": Define o cabeçalho de autorização com seu token.
    -d '{"name":"REPO_NAME", "private":false}': Define os dados do repositório. Você pode mudar "private":false para true se quiser que o repositório seja privado.
    https://api.github.com/user/repos: URL da API para criar um repositório.

Passo 3: Verifique se o Repositório Foi Criado

Você pode verificar se o repositório foi criado acessando sua conta do GitHub ou usando um comando curl para listar seus repositórios:

bash

curl -H "Authorization: token YOUR_GITHUB_TOKEN" https://api.github.com/user/repos

Isso deve listar todos os repositórios que você criou.
Dicas Adicionais

    Certifique-se de que o curl está instalado no seu sistema.
    Se precisar de mais informações sobre a API do GitHub, você pode consultar a documentação oficial.

Se tiver mais perguntas ou precisar de ajuda com algo específico, sinta-se à vontade para perguntar!