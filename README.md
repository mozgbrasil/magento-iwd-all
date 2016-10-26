![valid XHTML][checkmark]
[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/master/assets/images/logos/Red_star_32_32.png "MOZG"
[psr4]: http://www.php-fig.org/psr/psr-4/
[getcomposer]: https://getcomposer.org/
[uninstall-mods]: https://getcomposer.org/doc/03-cli.md#remove

# Mozg\IWD_All

## Sinopse

Módulo de compra em 1 passo para Magento

## Motivação

Para mais informações, visite 

https://www.iwdagency.com/extensions/one-step-page-checkout.html

Note que não somos o desenvolvedor desta extensão

Esse repositório foi criado com o intuito de instalar o módulo via composer

Neste repositório foi adicionado somente o suporte ao composer e modman.

## Suporte / Dúvidas

Para obter o devido suporte entre em contato com a desenvolvedora do módulo

## Instalação - Atualização - Desinstalação - Desativação

Esta biblioteca destina-se a ser instalado usando o [Composer][getcomposer].

Autoloading compatível é [PSR-4][psr4]

--

Certique se da existencia do arquivo composer.json na raiz do projeto Magento e que o mesmo tenha os trechos "minimum-stability", "prefer-stable", "repositories" e '"magento-root-dir":"./"', conforme https://gist.github.com/mozgbrasil/0c9bb8792ea6273ea24aed30b0fbcfba

Caso não exista o arquivo composer.json na raiz do projeto Magento, efetue o download

	wget https://gist.githubusercontent.com/mozgbrasil/0c9bb8792ea6273ea24aed30b0fbcfba/raw/b53c403620c111c43834fec9aa025809d1cb96b1/composer.json

--

Para qualquer atualização no Magento sempre mantenha o Compiler e o Cache desativado

--

### Para instalar o módulo execute o comando a seguir no terminal do seu servidor

	composer require mozgbrasil/magento-iwd-all

Você pode verificar se o módulo está instalado, indo ao backend em:

	STORES -> Configuration -> ADVANCED/Advanced -> Disable Modules Output

--

### Para atualizar o módulo execute o comando a seguir no terminal do seu servidor

	composer clear-cache && composer update

Na ocorrência de erro, renomeie a pasta /vendor/mozgbrasil e execute novamente

Para checar a data do módulo execute o seguinte comando

	grep -ri --include=*.json 'time": "' ./vendor/mozgbrasil

--

### Para [desinstalar][uninstall-mods] o módulo execute o comando a seguir no terminal do seu servidor

	composer remove mozgbrasil/magento-iwd-all && composer clear-cache && composer update

--

### Para desativar o módulo

Renomeie a pasta do módulo

Cada módulo tem a sua pasta no diretório /vendor/mozgbrasil/

--

## Badges

[![Join the chat at https://gitter.im/mozgbrasil](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mozgbrasil/)
[![Latest Stable Version](https://poser.pugx.org/mozgbrasil/magento-iwd-all/v/stable)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)
[![Total Downloads](https://poser.pugx.org/mozgbrasil/magento-iwd-all/downloads)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)
[![Latest Unstable Version](https://poser.pugx.org/mozgbrasil/magento-iwd-all/v/unstable)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)
[![License](https://poser.pugx.org/mozgbrasil/magento-iwd-all/license)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)
[![Monthly Downloads](https://poser.pugx.org/mozgbrasil/magento-iwd-all/d/monthly)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)
[![Daily Downloads](https://poser.pugx.org/mozgbrasil/magento-iwd-all/d/daily)](https://packagist.org/packages/mozgbrasil/magento-iwd-all)

:cat2:
