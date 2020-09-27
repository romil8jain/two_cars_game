# ECE243


The code is written for ARM Cortex A9 processor and can be run on CPUlator website:
	https://cpulator.01xz.net/?sys=arm-de1soc&d_audio=48000

Instructions to play:

1. Select C code as language. Scroll down in settings and disable device specific warnings. Paste the code into the editor and press compile and load. Then press continue to run the application.

2. When you start the application you will be greeted with a title screen. Move the PS/2 keyboard tab near the VGA display tab on CPUlator. Click on ‘enter here’ and press ‘P’ to start the game. 

3. Control moving the red car to the left by pressing ’A’. It will move to the opposite lane based on its current lane.

4. Similarly, you can control the blue car to the right by pressing ‘D’.

5. You have to collect points in the form of ‘circles’ while simultaneously controlling the blue and red car. You have to completely swallow the circle the get it added to the scoreboard . If you miss a circle on either side, the game will be over.

6. You have to dodge the squares for the red and blue car, or the game will be over. You get no points for dodging squares. 

7. The PS/2 keyboard interaction works with interrupts, so I recommend to press a key for at least 0.5 seconds, but not too long, for optimal performance.Your car moves when you leave the key.

8. After game is over, you can start a new game by pressing ‘P’ again without recompiling or restarting.
