# git

## Comandos básicos


```bash
git clone
```

Serve para copiar o repositório, sem esse comando não 
é possível criar ou editar o seu repositório.*


*Adiciona o arquivo editado ou criado ao repositório. 
O git add ponto serve para salvar todos os arquivos da pasta existente no seu repositório.É necessário para preparar todas as alterações no diretório atual para o próximo commit, permitindo um controle organizado sobre as mudanças que serão incluídas.*

git add . 

git add (serve para adicionar arquivos específicos, mas é usado em poucos casos porque geralmente é o arquivo todo que é editado)

*Mostra as atualizações feitas, exibindo informações detalhadas sobre as alterações que foram feitas.
O git status é essencial para saber o que está acontecendo no seu repositório antes de fazer qualquer commit.*

git status

*Cria um commit com uma mensagem especificada, deixando registrado as alterações feitas no código.
 A mensagem descreve as mudanças feitas. Isso facilita no rastreamento do histórico do projeto feito.
 Sem esse comando as alterações feitas não são definitivamente salvas.*

git commit -m "mensagem"

*Atualiza o repositório local com as mudanças do branch principal (main) do repositório remoto (origin), obtendo essas atualizações, junta essas mudanças na branch local(main), mantendo o código atualizado e sincronizado.*  

git pull origin main


*Envia as atualizações para a branch principal (main).
 Esse comando transfere as alterações feitas localmente para o repositório compartilhado, mantendo  a sincronização do código.*
git push origin main

## Trabalhando sozinho em um computador


```mermaid
flowchart TD
  A["Criar repositório"]
  B["Clonar repositório
  (git clone + url do repositório)"]
  C["Adicionar arquivo
  (git add .)"]
  D["Mostrar atualizações
  (git status)"]
  E["Criar commit
  (git commit -m mensgem)"]
  F["Atualizar
  (git pull origin main)"]
  G["Finalizar
  (git push origin main)"]

  A --> B
  B --> C
  C --> D
  D --> E
  E --> F
  F --> G

```

## Trabalhando sozinho em dois computadores

```mermaid
```

## Trabalhando em grupo em um computador cada um

```mermaid
```

## Trabalhando em grupo em múltiplos computadores

```mermaid
```