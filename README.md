# COMANDOS USADOS

## AULA 1

- git config --global user.name "Adriano Matos"
- git config --global user.email "adrianotaua@hotmail.com"

- git commit --amend --reset-author
  (pra dizer que foi eu quem fiz os commits anteriores)

- git clone linkDoGitHub............
- git add nomeDoArquivo
- git add . (adiciona todos os arquivos)
- git status
- git reset (Remove tudo da lista de arquivos rastreados)
- git commit -M "Msg de Descrição do Commit"
- git push origin main (enviar para GitHub 1ª vez)
- git push

## AULA 2

- git checkout nomeNovaBranch (cria NovaBranch)
- checkout nomeNovaBranch (muda p/ NovaBranch)
- git checkout -b dell_novo (cria NovaBranch e muda p/ ela)
- git branch (visualiza branchs)
- git add . (após alterar oq quer TESTAR)
- git commit -M "Msg"
- git push -u origin NovaBranch (-u define que nas próximas vezes que você executar comandos como git push ou git pull sem especificar o nome da branch, o Git saberá automaticamente a qual branch remota você está se referindo).
- git push origin dell_novo (sem configurar o rastreamento da branch remota)

### APÓS COMPROVAR EFICÁCIA DA NOVA BRACH, É SÓ UNIR

- git checkout main (voltar à branch principal)
- git merge NovaBranch (mesclando)
- git push origin main (enviando branch main atualizada)

## AULA 03

- git fetch (trás branches remotas p/ local)
- git branch (mostra todas as branches, geralmente não mostra a branch recém baixada, mas se mudar para ela vai verificar que ela veio do GitHub)
- OBS: É preciso estar dentro da branch que vai receber o código da branch que modificou o código, isso significa que vc vai "aceitar" as alterações daquela branch.

### BAIXAR ALTERAÇÕES DO GITHUB P/ LOCAL E MESCLA DIRETAMENTE

- git pull origin main (trás da main remota, já feito merge, para main local)
- git pull origin alternativa_b (Este comando trará as alterações de alternativa_b do repositório remoto e as mesclará diretamente na branch main do repositório local. Após isso, só enviar para o github, dessa vez diretamente da MAIN)
