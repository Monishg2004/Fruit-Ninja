
**Project Title:** Fruit Ninja

**Project Overview:**
Fruit Ninja is an engaging and interactive game developed in Unity, where players slice fruits while avoiding bombs. The game provides a thrilling experience with physics-based fruit slicing mechanics and dynamic object spawning. The objective is to achieve the highest score by slicing as many fruits as possible without hitting bombs.

**Features:**
- **Fruit Slicing Mechanics**: Realistic slicing effect with dynamic physics-based interactions.
- **Multiple Fruits & Bombs**: A variety of fruits spawn at random intervals along with bombs that end the game.
- **Score System**: Players earn points for slicing fruits, while hitting a bomb results in an instant game over.
- **Particle Effects**: Juice splatter effects enhance the realism of fruit slicing.
- **Randomized Spawning**: Fruits and bombs spawn at different positions and angles for an unpredictable experience.
- **Smooth Controls**: Intuitive mouse controls for slicing actions.

**Technologies Used:**
- **Game Engine**: Unity
- **Programming Language**: C#
- **Physics System**: Rigidbody and Collider for realistic object interactions
- **Particle System**: Juice effects when slicing fruits
- **Trail Effects**: Visual trails to show slicing motion

**Implementation Details:**

1. **Fruit Slicing Logic:**
   - The `Fruit` script manages the slicing behavior.
   - When a fruit is sliced by the `Blade`, it gets disabled and replaced with sliced pieces.
   - Sliced pieces receive force based on the slicing angle.

2. **Blade Mechanics:**
   - The `Blade` script detects player input and translates mouse movements into slicing actions.
   - A trail renderer creates a visual effect of slicing motion.
   - Direction and velocity are calculated to determine if slicing occurs.

3. **Spawning System:**
   - The `Spawner` script randomly generates fruits and bombs.
   - Objects spawn within a specified area and are given a random force.
   - The probability of spawning a bomb is configurable.

4. **Game Management:**
   - The `GameManager` keeps track of the score and handles game-over conditions.
   - When a bomb is hit, the game triggers an explosion event.

**How to Play:**
- Use the mouse to slice fruits by dragging across the screen.
- Avoid slicing bombs to continue playing.
- Earn points for each successful fruit slice.
- The game ends if a bomb is hit.

**Video Demonstration:**
[Upload your YouTube link here]

**Source Code:**
All the scripts mentioned above are included in the project repository.

This project showcases fundamental Unity mechanics such as physics-based interactions, object pooling, and smooth gameplay implementation. It is a great demonstration of real-time object manipulation and user interaction in Unity.

