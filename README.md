# 🎮 Snake, Water, Gun Game

This is a simple **Snake, Water, Gun** game written in C, where you play against the computer. The computer randomly picks one of the three options: Snake (0), Water (1), or Gun (2). Your goal is to beat the computer based on the game's rules.

# 📋 Features

- Random choice generation by the computer using `rand()` and `srand()`.
- User inputs their choice (0, 1, or 2).
- Logic to decide Win / Lose / Draw based on traditional Snake-Water-Gun rules.
- Fun terminal-based gameplay.

# 🕹 Game Rules

- Snake drinks Water → 🐍 wins  
- Water disables Gun → 💧 wins  
- Gun kills Snake → 🔫 wins  
- Same choice → It's a Draw!

# 🚀 How to Run

Make sure you have a C compiler installed (like `gcc`).

## 🔧 Compile the code

```bash```
```gcc snake_water_gun.c -o snake_water_gun```

## ▶️ Run the executable
```bash```
```./snake_water_gun```

# 🧠 How It Works
Uses ```srand(time(0))``` to seed the random number generator based on the current system time.

**Computer generates a random number between 0 and 2:**

```c```

```int computer = rand() % 3;```

**User is prompted to input their choice:**

```rust```

```Choose 0 for Snake, 1 for Water and 2 for Gun```
Then, the game logic decides the outcome based on traditional Snake-Water-Gun rules using if-else conditions.

# 🛠 Example Output
<pre> Choose 0 for Snake, 1 for Water and 2 for Gun 1 Computer choose 2 You Win! </pre> <pre> Choose 0 for Snake, 1 for Water and 2 for Gun 2 Computer choose 0 You Win! </pre> <pre> Choose 0 for Snake, 1 for Water and 2 for Gun 0 Computer choose 0 It's a Draw! </pre>

# 📝 Author
**Developed by Saksham Sharma**
