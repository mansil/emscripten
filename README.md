![emscripten logo](media/switch_logo.png)

[![Build Status](https://travis-ci.org/kripken/emscripten.svg?branch=incoming)](https://travis-ci.org/kripken/emscripten)
[![CircleCI](https://circleci.com/gh/kripken/emscripten.svg?style=svg)](https://circleci.com/gh/kripken/emscripten)

Emscripten é um compilador de [LLVM](https://pt.wikipedia.org/wiki/Low_Level_Virtual_Machine) para JavaScript. Este utiliza o "bitcode" do LLVM - que pode ser gerado
a partir de C/C++, utilizando `llvm-gcc` (DragonEgg) ou `clang`, ou qualquer outra linguagem que pode ser
convertida para LLVM - e compila-a para JavaScript, que pode ser executada na Web (ou
onde quer que o JavaScript seja executado).

Hiperligações para **demonstrações**, **tutorial**, **PERGUNTAS MAIS FREQUENTES**, etc...: <https://github.com/kripken/emscripten/wiki>

Página do projeto principal: <http://emscripten.org>

Licença
-------

Emscripten está disponível sob 2 licenças, a licença MIT e a Licença de Còdigo Aberto da University of Illinois/NCSA.

Ambas são licenças permissivas de código aberto, com pouca ou
nenhuma diferença prática entre elas.

A razão para oferecer ambas, é que (1) a licença MIT é bem conhecida,
enquanto que (2) a Licença de Código Aberto da University of Illinois/NCSA
permite que o código Emscripten seja integrado na fonte do
LLVM, que utiliza essa licença, caso surja a oportunidade.

Consulte `LICENÇA` para o conteúdo completo das licenças.
