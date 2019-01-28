# sudosolver
Projekt för TDDC74 
;; Welcome to SudoSolver!
;; INSTRUCTIONS:
;; ALT I) Graphical interface
;; To open graphical interface, type (open-solver).
;; ALT II) Using the text editor
;; To set a new board, type (set-board! user-board (list val1 val2...)) ; where the vals correspond to the 81 values in sudoku, row by row. 0 means empty cell.
;; To use a preset sudoku, type (set-board! user-board sdk1) ; Other options include sdk2, sdk3, and sdk4
;; Other board functions: solve-sudoku!, step-solve! reset-board!, sudoku-solved?, sudoku-solvable? and print-board ; all with user-board as argument.
;; To set a specific element, type (send user-board set-value! i value) ; where i is the index, starting on 0.
;; Authors: Algirdas Bartkevicius & Emil Eriksson
