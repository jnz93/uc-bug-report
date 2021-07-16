# Plugin UnityCode Bug Report

Uma ferramenta para reportar bugs e problemas em websites e sistemas wordpress. 
O sistema ficará "hibernado" a maior parte do tempo, podendo ser ativo por intermédio do atalho pré-configurado; Ao acionar o atalho o formulário de report aparecerá na tela; 
O formulário é composto pelos campo de descrição, um botão "tirar print-screen"([html2canvas](https://github.com/niklasvh/html2canvas)) e um campo para envio de arquivo de imagem; O arquivo gerado do print-screen ou o arquivo enviado do dispositvo serão "upados" na biblioteca wordpress;
O print-screen deve tirar uma "foto" do site completo em alta resolução e automaticamente fazer o upload para a biblioteca do wordpress;
Além da descrição do usuário o e-mail é acompanhado de especificações do dispositivo do usuário: Sistema operacional, navegador, tipo do dispositivo, IP, tipo da conexão, etc...
Os e-mails receptores podem ser configurados a partir da tela de configurações do plugin;

## Características do sistema
* Painel de Controle
  * Interface administrativa
  * Configuraçõe de e-mails receptores
* Atalho pré-configurado no teclado(F1, F2, etc...) para ativar a tela de report no site
* Vincular print-screen ou arquivo de imagem do dispositivo
* Formulário: Descrição e upload de arquivo
* Coletar: Tema e plugins ativos, IP, dispositivo, navegador, SO e versão de ambos
* Configuração de até 3 caixas de e-mails receptores
* html2canvas para capturar a tela


## Instalação
1) Faça o upload no diretório ou instale o plugin de forma comum pelo painel do wordpress

## Documentações
* [WP Plugin Handbook](https://developer.wordpress.org/plugins/)
* [html2canvas](https://github.com/niklasvh/html2canvas)

-----------

* Contributors: @jnz93
* Tags: #realstate, #importproperties
* Requires at least: 3.0.1
* Tested up to: 3.4
* Stable tag: 4.3
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html
