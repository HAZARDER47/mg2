# minigame 2
## Devlog
When fixing the if statement in Step 2, I encountered a syntax error. The original commented line was //if _timeLeft <= 0.0. To fix it, I had to add parentheses around the condition to make it valid C# syntax: if (_timeLeft <= 0.0f). I also added the 'f' suffix to 0.0 because _timeLeft is a float type, and this ensures the data types match correctly.

My best guess is that the period (.) is used to access a specific property or component belonging to an object. In this case, we are accessing the color property that lives inside the spriteRenderer object.
I think the word new is used to create or spawn a brand new Color object with the specific RGB float values we provided (r, 0.2f, 0.2f). So the whole line creates a new color mix and applies it to the sprite's color property.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
