# shooting-game

My shooting game that I have edited is a sci-fi concept, where the robot(player) is shooting aliens in a wierd eerie lab.
I will explain the parts that I have edited from the original code: "Shmup part 10"

1. I have found a pixel 2D image that seems like a labortory from google and replaced it with the original background asset.
2. I replaced the player (planecraft) to a robot image that I found from https://opengameart.org/
3. I found some fire/explosion assests from https://opengameart.org/ so I replaced it with the original laser image.
4. I cropped out alien images that I found in https://opengameart.org/ and gave it a black background so that the background can be seen transparent. (at first I had a problem where the background of the alien images were seen as white even though I had already previously erased their backgrounds. I figured it was because it's colorkey was set as BLACK.
5. From the asset I found for the laser, I used the explosion images. I gathered 8 images that would show the process of the explosion and made the code read it in its numerical order.

6. I found a different shooting sound effect and some explosion sound effects on youtube and replaced them with the original sound.
7. I found a background music that matched more with the new concept I had, and replaced it with the original one.

8. for the player image, I figgured the size didn't match. So I rearranged the size to 70 by 90 inside the "Player class"
