# Match3
A fully functional, browser-based Match-3 puzzle game built with vanilla JavaScript and HTML5 Canvas. Experience five levels of increasing difficulty, strategic stone block obstacles, and smooth arcade-style mechanics.
FeaturesClassic Match-3 Gameplay: Swap adjacent gems to create rows or columns of three or more.
Dynamic Level System: 5 unique levels with escalating point goals and move constraints.
Environmental Hazards: "Stone Blocks" introduced in later levels that cannot be moved or matched, requiring clever maneuvering.
Smooth Animations: Built-in gravity system for falling gems and visual feedback for swaps.
Responsive UI: Real-time tracking of Score, Moves, Level, and Target Goals.
How to PlayObjective: Reach the "Target Goal" score before you run out of moves.Controls: * Click a gem to select it.Click an adjacent gem (Up, Down, Left, or Right) to swap.If the swap creates a match of 3+, the gems clear and new ones drop in.If no match is made, the gems will automatically swap back.Strategy: Plan your moves to trigger chain reactions (cascades) for higher scores!📊 Level BreakdownLevelGoalMovesGem TypesSpecial Features11,000305Tutorial Level22,500256Increased Complexity34,000306Stone Blocks in corners46,000207High Difficulty / Low Moves510,000157Stone Cross center pattern
Technical DetailsEngine: HTML5 Canvas (2D Context).Logic: Pure Vanilla JavaScript (No external libraries or frameworks).
Styling: Modern CSS3 with a dark-mode "Cyber" aesthetic.Architecture: * gameState object manages the core loop and level transitions.findMatches() uses a scanning algorithm for horizontal and vertical detection.Recursive gravity system handles cascading matches.
