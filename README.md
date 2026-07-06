# 🏃 Temple Runner - Mobile Game

A Temple Run-like endless runner game built with Pygame and optimized for mobile platforms.

## Features
- Endless running gameplay
- Swipe controls (mobile-friendly)
- Collect coins for points
- Avoid obstacles
- Progressive difficulty
- Score tracking
- High score system
- Mobile-responsive touch controls

## Requirements
- Python 3.7+
- pygame
- pygame-ce (for better mobile support)

## Installation

```bash
pip install -r requirements.txt
```

## How to Run

**Desktop:**
```bash
python temple_runner.py
```

**Mobile (via Kivy wrapper or web):**
- Use the mobile build configuration
- Or access via web version

## Controls

### Desktop
- **Left Arrow / A** - Move Left
- **Right Arrow / D** - Move Right
- **Up Arrow / W** - Jump
- **Space** - Jump

### Mobile (Touch Screen)
- **Swipe Left** - Move Left
- **Swipe Right** - Move Right
- **Tap / Swipe Up** - Jump

## Game Mechanics
1. Run through the temple while avoiding obstacles
2. Collect coins to increase your score
3. Don't hit obstacles or you lose!
4. Each level gets progressively faster
5. Compete for the highest score

## Scoring
- Collect a coin = 5 points
- Travel distance = 1 point per 10 pixels
- Obstacles to avoid: walls, pits, enemies

Enjoy the adventure! 🏃‍♂️💨
