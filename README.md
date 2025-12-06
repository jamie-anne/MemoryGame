# MemoryGame
I built a memory game in Python for our case study, complete with a shop, adventure mode, and a house feature. It includes colors, designs, and ASCII art. The project was a bit challenging since it was my first time creating something like this, but it was also a great learning experience.



=======================================================================================================================================================================

                       TITLE: MISSION 404

=======================================================================================================================================================================





=======================================================================================================================================================================

                           DEVELOPER
=======================================================================================================================================================================


 								   The game was developed by:

 							     Jamie Anne A. Banjola (Head Developer)

 								
 								       YEAR & SECTION:

 									  BSIT 2-A


	

=======================================================================================================================================================================

                         ASCII ART USED

=======================================================================================================================================================================

 				   * The developer used the following website to convert images into ASCII art for the game.

 				   * It is also used to convert the text into ASCII art format.
 

 									 asciiart.eu
 							   https://emojicombos.com/dot-art-generator



=======================================================================================================================================================================

                          GAME OVERVIEW

=======================================================================================================================================================================

						* A sequence of symbols will appear on the screen for 3 seconds,
						  with additional time granted as you unlock new areas. 
						  Memorize the pattern carefully. When it disappears,
						  enter the exact sequence as shown. Each correct answer rewards you with coins.
						  But if you lose all your lives, you’ll be sent to jail. 
						  Stay sharp and focused  to earn rewards and avoid penalties.



						* The game starts simple but becomes progressively 
						  more difficult as sequences get longer and more complex. 
						  The player is given 3 lives, and each incorrect answer removes one life.
				 	    	  The game ends when all lives are lost.


=======================================================================================================================================================================

                          RUN THE GAME

=======================================================================================================================================================================


 						* Open file directory
 						* Open CMD prompt
 						* Copy the main file or drag it to paste it into cmd prompt

						ANOTHER WAY
						* Open file directory
						* Open CMD prompt
						* Type "python" and copy the main file or drag it to cmd.



=======================================================================================================================================================================

                         LP_STORY_MENU

=======================================================================================================================================================================


New Ascii = Normal -> ANSII 

--means that instead of using plain ASCII text (which can only show basic characters), the system is switching to ANSI formatting, which allows colored and styled text.



ANSI escape sequence - used to color text in the terminal.

--ANSI escape sequences are the special codes used to apply those effects—Python prints them to the terminal so the text can appear in different colors or styles, making the menu look more visually appealing while still being text-based.



=======================================================================================================================================================================

                              SHOP

=======================================================================================================================================================================

 				   * Access the shop by selecting option [3]. In the shop you can purchase various computer parts.

   			           * Every computer part you buy will go to your house menu. And you can buy all the computer parts once.

                                   * And you can't buy the next item if you haven't bought the previous item.

 			       * ITEMS:

 			       * Press option [1] if you want to buy Lamp.
 			       * Press option [2] if you want to buy Fan.
 			       * Press option [3] if you want to buy Mouse.
 			       * Press option [4] if you want to buy Keyboard.
 			       * Press option [5] if you want to buy Mic.
 			       * Press option [6] if you want to buy Headset.
 			       * Press option [7] if you want to buy Chair.
 			       * Press option [8] if you want to buy Monitor.
 			       * Press option [9] if you want to buy System Unit.
	


			       * The shop_menu function renders three rows of shop items using display_row, 
			       which aligns each item’s ASCII art, unlock status, button prompt, and price.

			       * Items become available sequentially, controlled by update_unlocks, which unlocks the next item only after the previous one is bought.
			       When the player selects an item, buy_item handles purchase validation by checking inventory duplicates and coin balance,
			       updating the player’s data, and marking the item as bought.

			       * A special case exists for purchasing the “Unit” item, which activates unit_feature — 
			       a placeholder screen intended for future special functionality.
			       The entire shop runs inside main, which plays music, updates item unlocks, shows the shop display,
			       and processes user input in a continuous loop until the player exits back to the main menu.

=======================================================================================================================================================================

                              HOUSE

=======================================================================================================================================================================


 	        	   * The house is connected to the shop. When an item is purchased from the shop, it will be displayed in the house.

 		           * For example, you have purchased the lamp and fan, the ASCII art of these items will be displayed in the house.

 			   * The display in your house will change depending on what items you already bought.



=======================================================================================================================================================================

                          GAME DIFFICULTY

=======================================================================================================================================================================

 							             Adventure Mode (Core Gameplay)

 			* This is the main driver of player progression. Players explore five different worlds, each containing five levels:

       							* Worlds: Plaza, Arcade, Cafeteria, Hotel, and Bank.

 									  Level Challenge:

 						* In each level, the player encounters characters, makes a choice, and then faces
 						  a memory challenge. The screen displays a series of symbols (letters, numbers, etc.)
                                                  for a few seconds, which the player must then input correctly.

 									      Outcomes:

 							     * Success: Rewards the player with coins.
 							     * Failed: Sends the player to jail.


=======================================================================================================================================================================

                          GAME CONTROLS

=======================================================================================================================================================================
 
 							       The game uses dynamic keyboard inputs.



 							     \- Press the key shown beside each option.

                                                             \- Keys may be numbers, letters or symbols.

                                                             \- The meaning of each key changes depending on the menu or game state.
 
                                                             \- Always follow the on-screen instructions.



=======================================================================================================================================================================

                      TECHNICAL REQUIREMENTS

=======================================================================================================================================================================

 								      Required Modules/Functions:
 
 									    import pygame

 									    import os
 
 									    import time

 									    pygame.mixer.init()

 									    import random

 									    import string
 
 									    import pyfiglet

 									    import sys

 									    import shutil



=======================================================================================================================================================================

                            CHEAT CODE

=======================================================================================================================================================================


 					           Available Cheat Codes

					           * Cheat/Code: plaza

					           * Effect: Unlocks Plaza and instantly add 300 pesos to your balance.

						   * Cheat/Code: arcade

						   * Effect: Unlocks the Arcade and instantly add 300 pesos to your balance.

						   * Cheat/Code: cafeteria

						   * Effect: Unlocks the Cafeteria and instantly add 300 pesos to your balance.

						   * Cheat/Code: hotel

 						   * Effect: Unlocks the Hotel and instantly add 300 pesos to your balance.

						   *Cheat/Code: bank

						   * Effect: Unlocks the Bank and instantly add 300 pesos to your balance.

										 HOW TO USE:

						   - Go to the Adventure Menu where you are prompted to play.
					           - Type the name of the place (e.g. plaza or arcade etc.
						   - Press enter to trigger the instant completion sequence.

			   Note: Cheat codes are optional and intended for players who wish to quickly test content or bypass difficulty.





=======================================================================================================================================================================

                             CONTACT

=======================================================================================================================================================================

			    	             	   * ANSI escape sequence - used to color text in the terminal.

							    * New Ascii = Normal -> ANSII, pagga, Big

--means that the text system supports multiple ASCII-style font styles or text render modes. Normal is plain text, ANSI uses colored/styled text with escape codes, pagga is an ASCII art font style (blocky/line-based), and Big is another large ASCII-art font used to display big titles or headings.


=======================================================================================================================================================================

                             CONTACT

=======================================================================================================================================================================

 		   * Got questions, feedbacks or suggestions? Feel free to reach out! We're always excited to hear from player's and would love to help.

 									    Contact:

 						          Facebook: Jamie Anne Banjola

 					                  Phone: 0953 751 7012


=======================================================================================================================================================================

                         ENJOY THE GAME!

=======================================================================================================================================================================

 
 
