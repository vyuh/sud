su-do-ku-js
===========

A fast library to generate or solve sudoku puzzles.

## Installation

  npm install su-do-ku-js --save

## Usage

  var sud = require('su-do-ku-js')
  var input_sudoku = '005070904600508002020000000000080500408000206001090000000000070300104005802030600'
  var solutions = sud.solve(input_sudoku)
  console.log(JSON.stringify(solutions))

