---
title: "Python para modelagem de sistemas físicos"
collection: teaching
type: "Tutorial"
permalink: /teaching/python
venue: "UNIFEI, Campus Itabira"
date: 2020-08-19
location: "Itabira, Brasil"
---

Tutorial Python para ser utilizado nas disciplinas de Física.

Python
======

## Instalando o Python

Esta seção explica como instalar o ambiente Python usando a distribuição Anaconda que utilizaremos ao longo da disciplina. A distribuição Anaconda é fornecida e mantida pela Continuum Analytics. Ela inclui o Python, muitas bibliotecas, e o ambiente de desenvolvimento integrado Spyder (IDE - integrated development environment) em um único pacote. O Anaconda também fornece um protocolo simples para atualizar e instalar pacotes. Há muitas alternativas disponíveis. Você pode e deve escolher uma mais adequada às suas próprias necessidades ou preferências. Um bom lugar para se conhecer as alternativas seria [www.python.org](https://www.python.org).

**A intenção não é promover uma distribuição particular de Python, mas promover o própria Python como uma ferramenta para a computação científica.**

### A.1 - INSTALAÇÃO DO PYTHON E SPYDER

Você pode baixar o Anaconda em [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual). O site detecta automaticamente seu sistema operacional (Windows, Mac OS X, ou Linux), mas não faça o download de nada ainda. Primeiro, certifique-se de que a versão de seu sistema operacional corresponde à exigência do instalador que lhe foi feita. (Por exemplo, o sistema operacional "Mac OS X - 64 Bit Python 2.7 Graphical Installer" requer atualmente o OS X 10.7 ou posterior). Segundo, certifique-se de que a versão de Python é o que você quer. As instruções abaixo descrevem como instalar o Python 3.4, que é a versão que usei para escrever este tutorial.

Se seu sistema operacional atende aos requisitos listados, prossiga para a Seção A.1.1. Se seu sistema operacional não atende a estes requisitos, a instalação padrão pode não ter sucesso em seu computador, ou a instalação pode ser bem sucedida, mas alguns pacotes podem não funcionar corretamente. A outra opção é tentar instalar a partir da linha de comando, conforme descrito na Seção A.1.2.

#### A.1.1 - Instalação gráfica

##### Windows

Este é um download grande que irá instalar muitos pacotes não utilizados neste tutorial; no entanto, a instalação é muito fácil. A menos que você esteja confortável trabalhando a partir da linha de comando, esta é a instalação que eu recomendo.

Uma vez terminado o download, encontre-o e abra-o. Provavelmente está em sua pasta Downloads. Clique duas vezes sobre o arquivo para iniciar a instalação. A menos que você queira personalizar a instalação, basta clicar em "Continuar" até chegar a "Destination Select". Selecione "Instalar somente para mim", a menos que você tenha uma boa razão para fazer o contrário. Isto criará uma pasta chamada anaconda em seu diretório pessoal que armazenará todos os arquivos associados. Clique em "Continuar" para abrir o diálogo "Tipo de Instalação". Clique em "Install" (Instalar) para iniciar uma instalação padrão. Você poderá ser solicitado a criar uma senha.

Após a instalação, você encontrará uma nova pasta chamada Anaconda ou Anaconda (64 bits) em Iniciar>Todos os Programas. Esta pasta contém um atalho para iniciar o Spyder.

### A.2 - CONFIGURAÇÃO DO SPYDER

Após a instalação do Spyder, há algumas configurações a serem feitas antes de iniciar a escrever e executar os scripts. Todas estas configurações são feitas usando o menu Preferências.

Depois de fazer as mudanças abaixo, talvez seja necessário reiniciar o Spyder.

#### A.2.1 - Diretório de trabalho

Você precisará manter um registro de seus arquivos. A maneira mais fácil de fazer isso de dentro do Spyder é dizer a ele para salvar todo o seu trabalho em uma pasta que você especificar. Escolha "Diretório de trabalho atual" a partir da lista de opções à esquerda do painel de Preferências. À direita, escolha o botão ao lado do seguinte e depois clique no ícone da pasta para selecionar um diretório, ou digite o caminho do diretório que você deseja usar. Talvez você deseje criar uma nova pasta chamada `rascunho` ou `atual` para trabalhar. Depois que você selecionou uma pasta, clique nos botões apropriados para que o "Abrir arquivo" e "Novo arquivo" utilizem este diretório. Você ainda pode acessar os arquivos em qualquer lugar em seu computador, mas a configuração destas opções é a maneira mais fácil para localizar os arquivos que você cria com Spyder.


<kbd>keyboard text</kbd>