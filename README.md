# Mini Gaming Console For Chrome Dino Game 🦖 # 

A small DIY handheld console inspired by the classic Google Chrome Dinosaur game!. I thought it would be fun to make a dedicated console for the game and i also plan to add other games in the future.


## ✨ Features

Here's what I'm planning to include:

- **ESP32:** The main controller that handles the game and processes inputs.
- **Display:** Shows the dinosaur, obstacles, and the rest of the game.
- **Joystick:** Used to control the dinosaur and navigate the game.
- **Physical buttons:** For additional controls and interactions.
- **Vibration motor:** Adds a little haptic feedback while playing.
- **Custom PCBs:** Two separate boards to keep the components organized.
- **3D component layout:** A preview of how everything fits together inside the console.

## 3d image

<img width="1675" height="895" alt="image" src="https://github.com/user-attachments/assets/b8909cf9-a580-4cec-8b57-1d17449ed063" />


## PCB

I originally tried to fit everything onto one board, but I wasn't really happy with how it looked. So, I decided to split the design into two boards instead.

- **Controller Board:** Holds the joystick, buttons, display connections, and other components.
- **ESP32 Board:** Contains the ESP32 and its supporting circuitry.

The two boards are connected using a bundle of wires and a dedicated connector.

I also wanted to keep the routing as clean as possible, so I managed to route everything using just one copper layer. This should also help reduce manufacturing costs.

<img width="1568" height="817" alt="image" src="https://github.com/user-attachments/assets/58ead1be-cfa2-4d0e-bb97-d11c5e794da0" />
