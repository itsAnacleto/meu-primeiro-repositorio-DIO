# meu-primeiro-repositorio-DIO
repositório de testes

# Configuração Inicial

Configurar algumas informações básicas, como nome de usuário e endereço de e-mail:

```bash

git config --global user.name "Seu Nome"

git config --global user.email "seuemail@teste.com.br"

```

# Inicializando um Repositório

Pode ser feito no diretório raiz do projeto com o seguinte comando:

```bash

git init

```

Este comando cria um novo repositório Git no diretório atual.


# Adicionando Arquivos ao Repositório


Depois de inicializar um repositório Git, é possível começar a adicionar arquivos a ele:


```bash

git add .

```

# Realizando Commits

Uma vez que os arquivos estejam no index, é possível realizar um commit para salvar essas mudanças no repositório.

```bash

git commit -m "Mensagem do commit"

```

**Fornecer uma mensagem significativa para descrever as alterações realizadas no commit.**


Para visualizar o histórico de commits em um repositório Git:


```bash

git log

```

Exibe uma lista de commits, mostrando o hash do commit, autor, data e mensagem associada a cada commit.


# Ramificação e Fusão

 Permite que os desenvolvedores trabalhem em recursos ou correções de bugs sem interferir no código principal do projeto. O comando `git branch` é usado para listar, criar e excluir ramificações:

```bash

git branch          # lista todas as ramificações

git branch nome     # cria uma nova ramificação chamada "nome"

git branch -d nome  # deleta a ramificação "nome"

```

### Mudar para uma ramificação específica, comando `git checkout`:


```bash

git checkout nome_da_ramificação

```

### Para mesclar uma ramificação de volta para a ramificação principal.


```bash

git checkout master

git merge nome_da_ramificação

```

# Clonando Repositórios Remotos

Além de inicializar um novo repositório Git localmente, é possível clonar um repositório Git existente de um servidor remoto. Isso é útil ao colaborar com outros desenvolvedores ou ao trabalhar em projetos de código aberto. O comando `git clone` é usado para clonar um repositório:

```bash

git clone url_do_repositório

```

# Sincronizando com Repositórios Remotos

Depois de clonar um repositório ou fazer alterações locais, você pode sincronizar seu repositório local com um repositório remoto usando os comandos `git fetch`, `git pull` e `git push`:

- `git fetch`: Obtém todas as atualizações do repositório remoto, mas não aplica as alterações no seu repositório local.

- `git pull`: Obtém as atualizações do repositório remoto e as mescla automaticamente com seu repositório local.

- `git push`: Envia as alterações do seu repositório local para o repositório remoto.


# Resolvendo Conflitos de Mesclagem

Às vezes, ao mesclar uma ramificação com outra, podem ocorrer conflitos de mesclagem, onde o Git não pode determinar automaticamente como mesclar duas alterações. Nesses casos, é necessário resolver os conflitos manualmente, editando os arquivos afetados para incluir as alterações desejadas. Após resolver os conflitos, você pode usar o comando `git add` para adicionar os arquivos alterados ao index e, em seguida, realizar um commit para concluir a mesclagem.

### Comandos Avançados

Além dos comandos básicos mencionados acima, o Git oferece uma série de comandos avançados para gerenciar eficientemente o fluxo de trabalho de desenvolvimento. Alguns desses comandos incluem:

- `git rebase`: Reorganiza o histórico de commits, permitindo uma visualização mais limpa e linear do histórico do projeto.

- `git cherry-pick`: Seleciona e aplica commits específicos de uma ramificação para outra.

- `git reset`: Volta o HEAD para um commit específico, desfazendo commits indesejados.

- `git stash`: Salva temporariamente alterações locais não comprometidas, permitindo alternar rapidamente entre ramificações.



# TÍTULO 1
## TÍTULO 2
### TÍTULO 3
#### TÍTULO 4
##### TÍTULO 5

## Tipos de escrita
 *Italíco* ou _italíco_

**Negrito** ou __Negrito__

___negrito e italíco___

 ## Tipos de listas
 - Lista 1
 - Lista 2
   - sublista


1. lista
2. lista
   1. sublista

## Adicionando imagens
[Texto imagem](link imagem)
### LINK IMAGEM

[Estrada com áravores](https://burst.shopifycdn.com/photos/country-road-in-fall.jpg)

![Estrada com áravores](https://burst.shopifycdn.com/photos/country-road-in-fall.jpg)

### Blocos de código

'system.out.println();'


'''system.out.println();system.out.println();system.out.println();system.out.println();system.out.println();'''

### Citações

>texto citações

### Tabelas

| Cabeçalho 1 |Cabeçalho 2|
|-------------|-----------|
| Texto 1     | Texto 2   |
| Texto 3     | Texto 4   |
| Texto 5     |           |


### Checkout

- [X] Tarefa 1
- [ ] Tarefa 2

ou

[X] Tarefa 1 <br>
[ ] Tarefa 2
