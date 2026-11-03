# ImmersiLearn — AR/VR HCI Training System

A polished, responsive academic prototype built using **HTML, CSS and vanilla JavaScript**. No framework, package installation, backend, or API key is required.

## Run in VS Code (about 1 minute)

1. Extract `ImmersiLearn.zip`.
2. Open the extracted `ImmersiLearn` folder in VS Code.
3. Open `index.html`.
4. If you have the **Live Server** extension, right-click `index.html` → **Open with Live Server**.
5. Otherwise, double-click `index.html` to open it in a modern browser.

## Features

- Responsive dashboard with learner progress and XP.
- Four structured learning paths with outcomes and completion tracking.
- Interactive virtual training room with clickable object hotspots and HCI explanations.
- Challenge arcade: XR quiz, HCI concept matching and scenario-based design detective.
- Ten-question competency assessment with instant explanations and score.
- Analytics, achievements and browser-local progress persistence.
- Keyboard shortcut: press `R` while in the lab to reset the scene.
- Help panel, mobile navigation, toast feedback and module dialogs.

## Technology

- `index.html` — semantic page structure and sections.
- `styles.css` — responsive visual system, cards, animations and CSS-based 3D room.
- `app.js` — navigation, learning modules, quizzes, games, assessment, scoring and localStorage.
- `localStorage` — saves demo learner progress in the current browser.

## Important scope note for your HCI presentation

This is a **browser-based immersive-learning prototype**, not a production VR headset application. The lab uses a CSS 3D-inspired scene and mouse/touch interactions to demonstrate spatial interaction concepts. Actual headset-based VR requires a compatible device, browser support for WebXR, and a WebXR implementation. The project intentionally avoids claiming that a CSS scene is a full VR experience.

## Suggested 60-second project explanation

“ImmersiLearn is an interactive AR/VR HCI training system prototype. It combines structured learning paths, a virtual training-room simulation, gamified knowledge checks and a competency assessment. The design applies HCI principles such as discoverability, feedback, consistency, user control and accessibility. The prototype is implemented with HTML, CSS and vanilla JavaScript, and learner progress is stored locally in the browser. It demonstrates how experiential and scenario-based learning can make XR concepts more engaging and measurable.”

## Suggested demo flow

1. Show the overview dashboard.
2. Open Learning paths and complete a module.
3. Enter Immersive lab and inspect the three hotspots.
4. Play XR Quickfire or HCI Match-up.
5. Complete the competency assessment.
6. Show analytics and explain how progress is persisted.

## Reset demo progress

Open browser developer tools → Console and run:

```js
localStorage.removeItem('immersilearn-state');
location.reload();
```

## HCI concepts to discuss in viva

- **Affordance:** an object's appearance suggests possible use.
- **Signifier:** a visible cue indicates where/how to act (for example, a hotspot).
- **Feedback:** the interface communicates the result of an action.
- **Discoverability:** users can understand what actions are available.
- **Consistency:** similar controls behave in similar ways.
- **User control:** learners can pause, reset and navigate.
- **Accessibility:** readable text, clear labels and alternatives to colour-only cues.
- **Usability evaluation:** task completion, time on task, errors, questionnaires and interviews.
