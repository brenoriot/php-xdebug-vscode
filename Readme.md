Iniciando artisan serv e xdebug no vscode com php.

Não irei abordar a instalação do x-debug no php, irei supor que você já tenha instalado o xdebug em seu php. Caso não tenha instalado, siga esse tutorial para instala-lo em sua maquina.

https://www.treinaweb.com.br/blog/como-instalar-o-php-e-xdebug-no-windows

Se você seguiu todo o procedimento do link acima, seu xdebug estará instalado e seu vscode estará pronto para debugar o código, agora basta você adicionar o comando para executar junto o servidor do laravel.

![image](https://user-images.githubusercontent.com/30961900/149639532-4b801ed0-a86e-4d2e-8036-96941094ec16.png)

Basta adicionar essas duas linhas em seu launche.json, salve e em seguida execute seu debug (apertando ctrl+f5). Isso iniciará seu servidor artisan e junto o xdebug.
