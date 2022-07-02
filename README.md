# Python Game: 利用Pygame module 自己創造的小遊戲
  
1. **參考資料:**
    1. Pygame Page: http://pygame.org
    2. documentation: http://pygame.org/docs/ref/
    3. Icon Archieve: https://iconarchive.com/(下載遊戲角色)
    4. Leshy SFMaker: https://www.leshylabs.com/apps/sfMaker/(下載音效)
    5. ~XXXXXXX忘記了~


------

**_2. What is Pygame_**:
  * Pygame提供Display, Sound, Music, Image, Text, Event 幫助製作遊戲
  * Pygame可以做出2-D小遊戲
  * Pygame偵測使用者使用Keyboard, joystick, mouse控制遊戲
  * Pygame提供許多內建的game objects 來製作遊戲

**_3. PYGame Basics_**:
| name | Description |
|:-----:|:----------:|
| _1.py_ | Create my game surface, game loop and drawing.|
| _2.py_ | Blit text, font, sound and image objects.   |
| _3.py_ | Getting user keyboard and collision dection.|

**_4. Code snippet_**
```python
#Create game display
WINDOW_WIDTH, WINDOW_HEIGHT = 1000, 600
displayscreen = pygame.display.set_mode((WINDOW_WIDTH, WINDOW_HEIGHT))
pygame.display.set_caption("Feed the Angry Bird!")

```
```python
#Blit image object and setting its rec.
player_image = pygame.image.load("angry_bird.png")
player_rect = player_image.get_rect()
player_rect.left = 32
player_rect.centery = WINDOW_HEIGHT//2

```
