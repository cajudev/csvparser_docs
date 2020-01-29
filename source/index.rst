======================
Bem Vindo ao CsvParser
======================

.. toctree::
   :hidden:
   :glob:

   1. Obtendo dados <pages/getdata>
   2. Customizando o retorno <pages/setcolumns>
   3. Filtrando dados <pages/filter>

.. image:: https://img.shields.io/packagist/v/cajudev/csvparser.svg
   :target: https://packagist.org/packages/cajudev/csvparser

.. image:: https://img.shields.io/packagist/dt/cajudev/csvparser.svg
   :target: https://packagist.org/packages/cajudev/csvparser

.. image:: https://img.shields.io/github/license/cajudev/csvparser.svg
   :target: https://raw.githubusercontent.com/cajudev/csvparser/master/LICENSE

.. image:: https://img.shields.io/travis/cajudev/csvparser.svg
   :target: https://travis-ci.org/cajudev/csvparser

.. image:: https://coveralls.io/repos/github/cajudev/csvparser/badge.svg?branch=master
   :target: https://coveralls.io/github/cajudev/csvparser

.. image:: https://img.shields.io/github/issues/cajudev/csvparser.svg
   :target: https://github.com/cajudev/csvparser/issues

.. image:: https://img.shields.io/github/contributors/cajudev/csvparser.svg
   :target: https://github.com/cajudev/csvparser/graphs/contributors


Uma simples, porém eficiente interface para trabalhar com arquivos csv.

Características
===============

* Padrão PSR-4
* Testes unitários com PHPUnit

Instalação
==========

Realize a instalação utilizando o seguinte comando ``composer require cajudev/csvparser``

Considerações Iniciais
======================

Para as instruções que serão fornecidas ao longo desta documentação, considere os seguintes dados como sendo o conteúdo utilizado:

========== ======== =========== ========== ======== ==============
Data       Produto  Preço       Pagamento  Nome     Estado        
========== ======== =========== ========== ======== ==============
11/01/2019 Produto1 R$ 1.400,00 Mastercard João     Rio de Janeiro
12/01/2019 Produto2 R$ 1.800,00 Visa       Maria    São Paulo       
11/01/2019 Produto3 R$ 1.200,00 Mastercard Pedro    Minas Gerais    
14/01/2019 Produto3 R$ 2.200,00 Mastercard Henrique São Paulo       
11/01/2019 Produto2 R$ 1.200,00 Visa       Julio    Minas Gerais    
16/01/2019 Produto2 R$ 5.000,00 Visa       Emanuel  Rio de Janeiro  
17/01/2019 Produto2 R$ 3.600,00 Visa       Silvia   São Paulo       
18/01/2019 Produto1 R$ 1.200,00 Visa       Reinaldo Minas Gerais    
========== ======== =========== ========== ======== ==============