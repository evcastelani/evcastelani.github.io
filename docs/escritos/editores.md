# Editores de texto


*Publicado em 20/03/2020* 

*Última edição em 20/03/2020*

Em minhas atividades rotineiras, como por exemplo, escrever notas de aula ou implementar algum algoritmo, tenho uma forte dependência de editores de texto. Dessa forma, já testei várias ferramentas que gostaria de listar aqui, onde tentei (ainda que não seja um expert) utilizar cada uma delas com algum nível aceitável de produtividade. Claramente, não são as únicas ferramentas existentes no mercado e muito do que está associado aqui são apenas impressões pessoais. Mas vamos lá. Antes de ler o texto, atente-se ao fato de que em meu uso diário trabalho fortemente com LaTeX e com programação em linguagem Julia, além de esporádicamente, escrever algumas coisas para estes documentos. 

## Atom

Este editor pode ser obtido acessando este [link](https://atom.io). Em minha singela opinião, acho editor lindissímo e ele me abriu a cabeça para funcionalidades que antes eu não dava a mínima, como por exemplo, seleção vertical através dos múltiplos cursores, identanção automatizada, auto-completar e, principalmente, ser "hackeavel". Até meu primeiro contato com ele, costumava utilizar IDE's dedicadas. Por exemplo, ao utilizar LaTeX, utilizava uma IDE chamada TexStudio. Quando utilizava Matlab, recorria a própria interface do Matlab. Quando trabalhava com Fortran (isso mesmo, trabalhei com Fortran!) utiliza o Force. Ao utilizar o Atom, em um primeiro momento como IDE da linguagem Julia, observei que facilmente poderia customizar o visual e instalar extensões que me permitiam trabalhar com tudo que precisava.

Contudo, é importante destacar que algo que incomoda, e muito, é lentidão para carregar o programa e o alto consumo de memória RAM. Evidentemente, isso acontecia (ou acontece) pois este software é forjado utilizando a plataforma [Electron](https://www.electronjs.org) que, embora seja muito prática e bastante estável, sofre com recorrente reclamações sobre recursos do sistema. De qualquer forma, vale a pena testar o Atom. É bonito, funcional e bem simples de customizar. 

## VSCode

Este [editor](https://code.visualstudio.com) é fruto da guerra de editores que estamos vivendo. Ele foi desenvolvido pela Microsoft e foi disponibilizado no GitHub com código aberto (isso mesmo! software da Microsoft com código aberto). Este programa conta com uma grande biblioteca de extensões que dão as mesmas ou até mais funcionalidades do que o programa Atom, seu concorrente direto no primeiro momento. Particularmente, tive num primeiro momento mais dificuldades para me adapatar a este do que me adaptar ao Atom, mas ele mostra algumas vantagens substanciais em relação ao Atom. Em primeiro lugar, o recurso chamado `Intellisense`. Tal recurso fornece um sistema de `autocomplentar` englobando código, parâmetros, listas, etc... 

Usei o VSCode durante uns 6 meses. Ele é muito bom mesmo e particularmente, achei boa parte das extensões dele melhores do que do Atom. Contudo, ainda existem coisas que me incomodam muito no VSCode. Primeiro, as mensagens de atualização são cansativas demais. Outra coisa é, embora seja mais rápido do que Atom para iniciar e carregar grandes arquivos de dados, ainda é bastante lento e tem uns arquivos associados ao Workspace que me incomodam também. Mas no geral, acho ele um editor superior ao Atom.

## Sublime

Creio que muito do que foi desenvolvido no Atom e VSCode é motivado por este editor. Em minha opinião, este editor é o bem superior aos demais Atom e VSCode. Talvez este seria meu editor principal se não fosse um problema: ele é fechado e pago. Ele é cheio de recursos que lembram os principais recursos do Atom e VSCode porém ele é bem mais leve carrega arquivos gigantescos de dados mais rápidos. Alerto, contudo, que embora tenha recursos compatíveis, tenho impressão que tanto Atom como VSCode têm extensões mais produtivas e sofísticadas do que o Sublime.  Mas o Sublime é muito bem aparado. Gosto bastante disso. Porém quase surto ao saber que este programa pode simplesmente morrer quando o autor quiser. Além disso, o preço para nós brasileiros é bem salgado, cerca de 80 dólares. 

## VIM


Atualmente, este é meu software preferido para edição. De fato, seu uso num primeiro momento pode ser um pouco complicado. Ele não terá um menu bonitinho no qual você irá clicar aqui ou ali e se virar até começar memorizar teclas de atalho. Ele é dividido entre modo de inserção, normal e seleção. Cada modo tem uma forma de trabalham mas trazem em comum a dependência forte da memória do usuário em saber qual comando faz qual tarefa neste ambiente. Assim, destaco que ele tem uma curva de aprendizado mais demorada que as curvas de aprendizado do Atom, VSCode e Sublime. Mas ele é sólido e estável. Além disso, é extremamente leve e você trabalha no terminal. Este último fato pode ser ruim para uns e bom para outros. Por exemplo, eu uso muito o terminal do Linux, então ficar utilizando programas programas externos torna improdutivo minhas ações. Assim, em meu caso,  já basta o navegador de internet e um player de música como programas externos utilizados de forma mais intensa durante o dia.

Embora uma busca na internet implique em diversos elogios a este editor, destaco que nem tudo são flores no uso do VIM, e não me refiro a curva de aprendizado e configuração dele- que são naturalmente, processos dolorosos no ínicio. Me refiro a dificuldades como lentidão em certas situações e outras coisas que qualquer editor sofre. Quer um exemplo? 

Vamos lá. O VIM depende de vários plugins para conseguirmos deixá-lo mais produtivo. Por exemplo, se você quer destacar sintaxes e compilar um arquivo .tex diretamente no VIM, terá que instalar um certo plugin. Este processo, por si só, pode ser bem chato no início. Mas não é sobre isso que quero falar. Quando você instala vários plugins para atender suas necessidades outros conflitos ao iniciar uma leitura de arquivos pode ocorrer. Eu mesmo já me deparei uma situação onde estava abrindo um grande arquivo de dados e VIM travava constantemente ou ficava incrivelmente lento. Depois de um tempo pesquisando percebi que isso tinha relação a desativação dos plugins ao iniciar. Pronto, desativei que o arquivo foi rapidamente lido. Percebe que, embora tenha resolvido o problema, este o tipo de coisa desagradável? 


Espero, em breve, iniciar uma documentação de dicas sobre o VIM e de problemas de imaturidade ao utilizá-lo com os quais me deparei ou ainda me deparo. Mas isso fica para um outro momento.



## Outros

Naturalmente, editor de texto para programação é algo de gosto particular. Meu objetivo foi apenas expor um pouco do que gosto e um pouco do que não gosto em cada caso. Isso foi feito de forma bem simples e até ingênua. Mas fica aqui minha sugestão de outros programas que merecem ser avaliadas: Notepad++, Micro e Emacs são alguns. 





