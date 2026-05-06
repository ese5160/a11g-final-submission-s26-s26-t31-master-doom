[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Y5lYn2wb)

# a11g-final-submission

**Team Number: 31**

**Team Name: MasterDoom**

| Team Member Name | Email Address           | GitHub Username |
| ---------------- | ----------------------- | --------------- |
| Yunzhe Deng      | deng1@seas.upenn.edu    | yunzhedeng      |
| Jilu Wang        | jlwang25@seas.upenn.edu | Arbeiterschaft  |

**GitHub Repository URL: [https://github.com/ese5160/a11g-final-submission-s26-s26-t31-master-doom](https://github.com/ese5160/a11g-final-submission-s26-s26-t31-master-doom)**

**GitHub Pages URL: [https://ese5160.github.io/a11g-final-submission-s26-s26-t31-master-doom/](https://ese5160.github.io/a11g-final-submission-s26-s26-t31-master-doom/)**

## 1. Video Presentation

<section id="video-presentation">
  <h2>Team 31 MasterDoom – Texas Hold’em AI Poker Assistant Demo</h2>

<iframe
    width="100%"
    height="500"
    src="https://www.youtube.com/embed/CqMz-0Z3tis"
    title="Team 31 MasterDoom – Texas Hold’em AI Poker Assistant Demo"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
  </iframe>

<p><strong>Team 31: MasterDoom</strong></p>

<p>
    This project is an AI-assisted Texas Hold’em poker card recognition system.
    It uses a camera module to detect the rank and suit of playing cards in real time
    and provides GTO-based decision support to help players make better game decisions.
  </p>

<p>
    Detected cards, game status, and decision-related information are displayed on an LCD screen.
    A joystick is used for local control and menu selection, while a Node-RED dashboard provides
    remote monitoring and user interaction.
  </p>

<p>
    The camera, LCD, and user interface communicate wirelessly using MQTT over Wi-Fi.
    The system also supports OTA updates, allowing firmware to be updated wirelessly without
    a physical connection.
  </p>

<p>
    Main features include poker card recognition, Texas Hold’em game display,
    GTO-based decision support, LCD real-time display, joystick control,
    Node-RED dashboard, MQTT communication, and OTA firmware updates.
  </p>
</section>

## 2. Project Summary

**Device Description:**

- Our device is an AI-assisted Texas Hold’em poker assistant that uses a camera to recognize playing card rank and suit in real time. It displays game information on an LCD, supports joystick control, connects to a Node-RED dashboard through MQTT over Wi-Fi, and supports OTA firmware updates.
- Our project was inspired by the fact that GTO-based poker algorithms can often make stronger and more consistent decisions than human players in Texas Hold’em. We wanted to give this type of algorithm vision, display, wireless communication, and user input so it could interact with a real poker table more like a human player. The problem our device solves is that most poker decision-support algorithms only work with manually entered card and game information. Our system helps bridge the gap between software strategy and the physical world by recognizing cards with a camera, showing game information on an LCD, and allowing users to interact with the system through a joystick and Node-RED dashboard.
- We use the Internet through Wi-Fi and MQTT to connect the camera, MCU, and Node-RED dashboard. Most importantly, the camera sends detected card rank and suit information to the MCU through MQTT, so the MCU can update the LCD, process game information, and support remote monitoring and OTA firmware updates.

**Device Functionality:**

-jilu

**Challenges**:

-jilu

**Prototype Learnings:**

-jilu

**Next Steps & Takeaways:**

**Project Links**:

[Node Red Link](http://4.154.36.28:1880)

[Altium PCBA Link](https://upenn-eselabs.365.altium.com/designs/907BC697-1F1F-4DA7-AD57-F23FF5449B87#design)

## 3. Hardware & Software Requirements

-jilu

## 4. Project Photos & Screenshots

![](./images/overview.png)
![](./images/PCBA.png)
![](./images/thermal.png)
![](./images/altium.png)
![](./images/nodered.png)


Block Diagram -- jilu

## 5. Codebase

Do *not* commit any of your source code to this repository. Rather, provide links to the other GitHub repository you've already been using with your firmware.

- A link to your final embedded C firmware codebases
  [Codebases Link](https://github.com/yunzhedeng/ese5160_finalproject)
- A link to your Node-RED dashboard code
  [Node-Red dashboard link](https://github.com/yunzhedeng/ese5160_finalproject/tree/main/mqtt)
- Links to any other software required for the functionality of your device
