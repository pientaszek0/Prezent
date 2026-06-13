*Read this in other languages: [English](README.en.md), [Polski](README.md).*

# 💖 Interactive Gift "For My Beloved"

Welcome to the repository of my personal, interactive project! It was created with my girlfriend in mind, as a digital, romantic gift designed to bring a smile to her face, remind her of my feelings, and provide a sense of security.

The project consists of three visually cohesive subpages (designed in a cute, pastel *glassmorphism* style) that serve different purposes: from a compliment generator, through a mini-game, to a virtual valentine. The main theme and mascot of the project is a sweet Pufferfish 🐡.

---

## 🚀 Features and Subpages

### 1. 💌 Main Page (Compliment Generator)
**File:** `index.html`
The heart of the entire gift. It includes:
*   **Time Counter:** Precisely counting the time (in years, months, days, hours, minutes, and seconds) of our relationship.
*   **Word Generator:** A database of several dozen personalized compliments and romantic promises that are randomly drawn on the screen.
*   **Floating Background:** Animated particles (hearts, flowers, cute symbols) generated dynamically in JavaScript.

### 2. 🎮 Mini-game: Take Care of the Pufferfish
**File:** `Gra_Zadbaj_o_Rozdymke.html`
A simple Tamagotchi-style game featuring our cute mascot.
*   The player uses action buttons (feed, pet, tell a joke, send a kiss) to increase the Pufferfish's "Happiness Bar".
*   Each action triggers a funny quote in a speech bubble and a responsive animation of shooting emojis.
*   Upon reaching 100% happiness, a special win screen with a dedication appears.

### 3. 🌹 Valentine's Question
**File:** `walentynki-index.html`
An interactive, virtual valentine card.
*   It asks the most important question with a pool of randomly shuffled, positive answers.
*   After clicking a button, a dedicated screen appears with a Ukrainian declaration of love ("я дуже люблю тебе ❤️") and a cute graphic.

---

## 🎨 Graphic Assets

The main folder contains dedicated graphics that bring the project to life and give it a unique character:
*   `Dwie_Rybki.png` - Concept art/background graphic.
*   `Rozowe_Serce.png` - Used as a decorative element.
*   `Usmiechnieta_Rozdymka.png` - A cute mascot graphic with a background, used on final screens.
*   `Usmiechnieta_Rozdymka_Bez_Tla.png` - A sprite used directly in the mini-game for levitation and jump animations.

---

## 🛠️ Technologies and Interesting Solutions

The project is built on pure **HTML, CSS, and Vanilla JavaScript**. It does not require any external libraries or frameworks, which guarantees lightning-fast loading.

*   **Real-time Notifications (Discord Webhooks):** The project is integrated with a private Discord server. The script sends notifications every time the page is opened, a compliment is drawn, or an action is taken in the game.
*   **"Sleeping Tabs" Workaround:** Utilizing the `Page Visibility API` allows detecting when the minimized browser tab on a smartphone is brought back to the foreground, triggering a notification without the need to refresh the page.
*   **Full Responsiveness (RWD):** Interface elements use modern CSS functions, such as `clamp()`, `vmin`, and `dvh`, ensuring the project scales perfectly on any mobile device and prevents UI clipping when the phone's keyboard is open.

---

## 💡 How to run?

The project is a static website (Frontend).
To run it, simply download the repository and open any of the `.html` files in a modern web browser. Ultimately, the project is hosted in the [GitHub Pages](https://pientaszek0.github.io/Prezent/), allowing it to work on any device with internet access.

---
*Made with love ❤️*