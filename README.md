sud
===

Generate or solve Sudoku puzzles.

## Installation

    npm install sud --save

## Usage

    var sud = require('sud')
    var input_sudoku =
        '005070904600508002020000000000080500408000206001090000000000070300104005802030600'
    var solutions = sud.solve(input_sudoku)
    console.log(JSON.stringify(solutions))

