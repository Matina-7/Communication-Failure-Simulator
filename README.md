# Communication Failure Simulator

An interactive low-fidelity prototype that demonstrates how different communication tones trigger different emotional responses.

## Overview

This simulator guides users through a conversation with a friend, where each response choice affects the emotional state and can lead to either harmonious communication or a complete breakdown.

## Features

- **Grayscale Design**: Clean, minimalist interface focusing on the interaction
- **Expressive Emoji Faces**: Visual feedback showing emotional states (happy, neutral, sad, worried, confused, angry)
- **Communication Breakdown Meter**: Real-time indicator (0-100) showing relationship health
- **Branching Dialogue**: 3-5 interactions with dynamic responses based on choices
- **Three Possible Endings**:
  - Green (Harmonious): Relationship strengthened
  - Yellow (Tension): Miscommunication occurred
  - Red (Failure): Complete communication breakdown

## How to Use

1. Open `index.html` in any modern web browser
2. Read the initial message from your friend
3. Choose one of three response options (A, B, or C)
4. Continue the conversation by selecting responses
5. Watch the meter and background color change based on your choices
6. Reach the conclusion after 5 interactions
7. Click "Restart Simulator" to try different conversation paths

## Response Effects

### Initial Choices:
- **A: "It's okay, a bit tired."** → Neutral response (+3 breakdown points)
- **B: "Why did you suddenly ask this?"** → Defensive response (+20 breakdown points)
- **C: "Haha, I'm fine! How about you?"** → Warm response (-5 breakdown points, improves relationship)

### Meter Levels:
- **0-29 (Green)**: Harmonious communication
- **30-59 (Yellow)**: Slight tension
- **60-100 (Red)**: Communication failure

## Technical Details

- Pure HTML, CSS, and JavaScript (no dependencies)
- Responsive design works on desktop and mobile
- Smooth animations and transitions
- State management for conversation tracking

## Educational Purpose

This simulator demonstrates:
- How tone affects emotional responses
- The cumulative effect of communication choices
- The difference between warm, neutral, and defensive communication
- How small choices compound over a conversation

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

Simply open the `index.html` file to start!