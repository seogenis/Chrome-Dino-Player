# Chrome Dino Player

**Chrome Dino Player** is a Python-based bot that automates the Chrome Dino game. It detects obstacles and controls the dinosaur to help it jump over them, aiming to achieve a high score.

## Features

- **Obstacle Detection**: The bot uses pixel color detection to identify obstacles in the game.
- **Auto-Play**: It automatically controls the dinosaur to jump over obstacles.
- **Theme Detection**: The script detects whether the browser is in light or dark mode to adjust its obstacle detection accordingly.
- **Internet Check**: The bot verifies if the device is offline before starting the game, as the Dino game appears when there's no internet connection.

## How It Works

1. **Setup**: The bot checks for an internet connection and opens the browser if disconnected. It then prompts the user to click on the dinosaur to determine its position.
2. **Theme Detection**: It identifies the browser's theme to adjust the pixel color detection mechanism.
3. **Auto-Play**: Once the dinosaur's position is determined, the bot starts the game and controls the dinosaur's movements, jumping over obstacles as they appear.

## Dependencies

The script requires the following Python libraries:
- `pyautogui`
- `mouse`
- `keyboard`
- `win32gui`
- `itertools`
- `threading`
- `sys`
- `webbrowser`
- `socket`

These libraries are used for automation, keyboard control, pixel detection, and other functionalities.

## Disclaimer

This bot is intended for educational purposes only. Please use it responsibly and be aware that automating games may violate their terms of service.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
