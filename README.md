# SpaceInvaders

;3: Simply running the program should be sufficient to begin a new game of Space Invaders. When the game ends – a mark in the top right ;corner for a victory or a mark in the bottom left corner for a defeat – simply stop and rerun the program to begin again.
;Occasionally, the oscilloscope will just display a bunch of dots on a vertical line when you turn it on and try to run the program for the ;first time. Simply disable and re-enable the XY mode on the oscilloscope to fix.
;You may run into a bizarre bug – a big vertical line appears on the screen. For some reason, the program occasionally gets stuck in an ;infinite loop of “draw down”. I haven’t been able to determine why, as it happens completely at random and doesn’t seem to have a specific ;trigger. Unfortunately, you will have to restart the program to fix this – I haven’t had time to include a “break free of loop if longer ;than X steps” sort of thing to stop it.
;Be warned that the hit detection is wonky – as spoken about in the report. Aim to the right hand side of the lines representing the aliens ;to see that they can be killed, and that the game will end only when an alive alien reaches the bottom of the screen (or you kill them ;all.)
;The movement feels clunky – try to have a light touch on the buttons. They’re not debounced, so pressing them very lightly seems to count ;as pressing them many times so you move quite fast.
;And have fun!
