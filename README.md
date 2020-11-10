# Noos
Noos é proposta de projeto de sistema operacional baseada em linux usando tecnologia web 

## Objetivos
Objetivo seria criar um sistema operacional de codigo livre e de fácil usabilidade com interface com janelas, fosse focada no navegador assim como Chrome OS, porem também possibilitado a instalação de aplicações de terceiros.

## Gerenciador Sistema
O gerenciador do sistema seria feito em Node JS com biblioteca [shelljs](https://github.com/shelljs/shelljs) para execução dos comandos

## Gerenciador de Janelas 
A estrategia encontrada para gerenciamento das janelas seria atravez do projeto [vue-resizable](https://github.com/nikitasnv/vue-resizable) com as aplicações sendo carregada como componentes do Vue JS ou Webview do Eletron JS

## Aplicações base
No GitHub existe repositório com nome [electron-sample-apps](https://github.com/hokein/electron-sample-apps) com exemplos de plicações simples mais muito útil para sistema base.

## Aplicações de Terceiros
Teria que ser devolvido uma build específico para aplicações atuais em Electron js.
Como o Sistema é uma renderização do navegador as aplicações teriam duas possibilidades, roda como componentes ou como webview.



# Link
### [Server Dev](http://code-noos.brazilsouth.azurecontainer.io)
### Portas
 * 80: 
 * 81:
 * 8001: Vue UI
 * 8080: Front Dev
 * 8443: VS Code
