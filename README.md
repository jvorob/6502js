# FORSH Interpreter

6502 Simulator forked from elsewhere,
Modified slightly to have a few extra label/debugging features
Also modified the simulated screen to be slightly larger to fit a usable amount of text

Assembly code in mos.txt written by me, implements a simple virtual terminal and FORTH interpreter

Because of the way input is handled in 6502js, some of the input controls are a little janky:
\d to backspace:
\c to clear the line
\e for enter
\h for help



![Screenshot of FORSH running](./arithmetic.png)