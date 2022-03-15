# TIC-TAC-TOE

CURRENTLY WORK IN PROGRESS

Homework 2b for Python Academy - Tic-tac-toe

# Task Assignment

Cílem této hry je umístit 3 hrací kameny (křížek X nebo kolečko O), a to horizontálně, vertikálně nebo diagonálně. Jde o hru pro dva hráče (příp. počítač).
Program bude obsahovat:

 1. Program pozdraví uživatele
 2. Vypíše v krátkosti pravidla hry
 3. Zobrazí hrací plochu
 4. Vyzve prvního hráče, aby zvolil pozici pro umístění hracího kamene
 5. Pokud hráč zadá jiné číslo, než je nabídka hracího pole, program jej upozorní.
 6. Pokud hráč zadá jiný vstup, než číselný, program jej opět upozorní.
 7. Pokud se na vybraném poli nachází hrací kámen druhého hráče, program jej upozorní, že je pole obsazené
 8. Jakmile hráč úspěšně vybere pole, zobrazíme nový stav hrací plochy
 9. Program vyhodnocuje, jestli horizontálně/vertikálně/diagonálně není některý hrací kámen tříkrát. Pokud ano, vyhrává hráč, kterému tyto tři kameny patří
11. Pokud nezbývá žádné volné hrací pole a žádný hráč nevyhrál, jde o remízu.


Příklad fungujícího kódu:

    Welcome to Tic Tac Toe
    ============================================
    GAME RULES:
    Each player can place one mark (or stone)
    per turn on the 3x3 grid. The WINNER is
    who succeeds in placing three of their
    marks in a:
    * horizontal,
    * vertical or
    * diagonal row
    ============================================
    Let's start the game
    --------------------------------------------
    +---+---+---+
    | | | |
    +---+---+---+
    | | | |
    +---+---+---+
    | | | |
    +---+---+---+
    ============================================
    Player o | Please enter your move number: 5
    ============================================
    +---+---+---+
    | | | |
    +---+---+---+
    | | O | |
    +---+---+---+
    | | | |
    +---+---+---+
    ============================================
    Player x | Please enter your move number: 1
    ============================================
    +---+---+---+
    | X | | |
    +---+---+---+
    | | O | |
    +---+---+---+
    | | | |
    +---+---+---+
    ============================================
    Player x | Please enter your move number:
    ...
    ============================================
    Player o | Please enter your move number:
    ============================================
    +---+---+---+
    | X | | |
    +---+---+---+
    | | O | |
    +---+---+---+
    | | | |
    +---+---+---+
    ============================================
    Congratulations, the player o WON!
    ============================================
