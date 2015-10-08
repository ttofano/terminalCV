# terminalCV
Um Curriculum em linha de comando para sysadmins
Ainda é um WIP, e estamos para adicionar algumas características.
Este é um fork do trabalho de [@hauckd](http://github.com/hauckd/) (Daniel Hauck). Thanks for this, man! ;)
Este fork é principalmente para tradução pt_BR e algumas pequenas adaptações pessoais.


### Veja ao vivo!
Você pode ver meu terminalCV ao vivo aqui: http://tofanodesigns.com/cli/


### Uso
terminalCV é um pequeno script Python que usa jinja2 para renderizar um template html com algum javascript nele. Depois da renderização, você só precisa subir para seu site (onde preferir).

Para usá-lo, clone o repositório e instale os requisitos com `pip`:
```bash
$ git clone git@github.com:ttofano/terminalCV.git && cd terminalCV
$ sudo pip install -r requirements.txt
```

Modifique o about.yml com seu editor de texto favorito.

E finalmente, renderize a página:
```bash
$ python render.py
```


Se tudo funcionou corretamente, você pode subir os arquivos para sua www:
```bash
$ rsync -aH www/ usuario@webhost:/pasta/de/destino
```


### Jquery-Terminal & Projeto Original
terminalCV faz uso do [JQuery-Terminal, por J. Cubics](http://terminal.jcubic.pl/).
O Projeto original pode ser encontrado [aqui](http://github.com/hauckd/terminalCV/).
Obrigado, caras, vocês são fantásticos.


### Progresso da Customização e Detalhes Adicionais
```bash
$ sh details_progress.sh 
CUSTOMIZATION PROGRESS: [######----------------------------------] 20%
Tradução:                [  OK  ]
Café:                    [  OK  ]
CSS Personalizado:       [  OK  ]
JS Personalizado:        [ FAIL ]
Comandos Personalizado:  [ FAIL ]
Divulgação:              [ FAIL ]
Extensão da Navegação:   [ FAIL ]
Easter-eggs:             [ FAIL ]
```
