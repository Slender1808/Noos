# Noos
Noos é proposta de projeto de sistema operacional baseada em linux usando tecnologia web 

## Objetivos
Objetivo seria criar um sistema operacional de codigo livre e de fácil usabilidade com interface com janelas, fosse focada no navegador assim como Chrome OS , porem também possibilitado a instalação de aplicações de terceiros.

### Tecnologias

* Electron
* Node
* Vue
 * [vue-resizable](https://markdownlivepreview.com/)

## Gerenciador de Janelas 
A estrategia encontrada para gerenciamento das janelas seria atravez do projeto [vue-resizable](https://markdownlivepreview.com/) com as aplicações sendo carregada como componentes do Vue JS ou Webview do Eletron JS

## Aplicações base
No GitHub existe repositório com nome [electron-sample-apps](https://github.com/hokein/electron-sample-apps) com exemplos de plicações simples mais muito útil para sistema base.

## Aplicações de Terceiros
Teria que ser devolvido uma build específico para aplicações atuais em Electron js.
Como o Sistema é uma renderização do navegador as aplicações teriam duas possibilidades, roda como componentes ou como webview.
