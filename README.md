# Adaptive Flow

Adaptive Flow is a multimodal interaction interface developed as an HCI project. The idea is to create an interface that responds to different forms of user input and changes its visual behavior according to the interaction taking place.

The interface combines mouse, keyboard, touch, voice, and gamepad input into a single interactive environment. Different interactions produce different visual responses, allowing the user to see how the interface reacts in real time.

## Project Overview

The interface is designed to demonstrate adaptive behavior using standard web technologies.

Mouse movement and clicks generate visual feedback, keyboard input can change the interface theme, typed commands can modify the interface, voice input can be used for commands, and touch interaction provides a more touch-friendly experience.

The project is implemented as a single-page web application using HTML, CSS, and JavaScript.

## Main Features

### Pointer Interaction

The interface responds to pointer movement and tracks the user's position.

Clicking on the interface produces visual feedback, including ripple and particle effects.

### Keyboard Interaction

Keyboard input is detected throughout the interface.

Number keys can be used to switch between different interface themes.

| Key | Theme |
| --- | --- |
| 1 | Red |
| 2 | Blue |
| 3 | Green |
| 4 | Purple |
| 5 | Orange |
| 6 | Pink |
| 7 | Yellow |
| 8 | Teal |

### Text Input

The interface includes a command area where users can enter text.

Color names are detected from the entered text and can change the interface theme.

Examples:

```text
make it red
change to blue
make it green
```

Other commands can also be used to change the interface size or clear the current state.

### Voice Interaction

Voice input is supported through the Web Speech API.

Users can speak commands instead of typing them. Browser microphone permission may be required.

### Touch Interaction

The interface detects touch interaction and adapts its controls for touch-based use.

### Gamepad Interaction

Gamepad input is supported through the browser Gamepad API.

Connected gamepads can be detected and button interactions are displayed through the interface.

## Adaptive Interface

The interface changes its appearance based on the selected theme and user interaction.

Different colors can be selected through keyboard input, typed commands, or voice commands. The background and interface elements respond to the selected color.

## Technologies

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Gamepad API
