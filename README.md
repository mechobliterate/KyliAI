# Kyli AI

<p align="center">Kyli AI is an artificial intelligence that learns to solve mazes using a genetic algorithm.</p>

Kyli AI applies the principles of natural selection and survival of the fittest to improve its maze-solving abilities over successive generations. Each generation consists of randomly initialized "agents." As they attempt the maze, the most successful agent—measured by its distance to the next checkpoint and the fewest moves taken—is selected to influence the next generation.

Every five generations, agents are allowed more moves, enabling them to learn more complex paths (“incremental learning”). Over time, efficient strategies are “passed down” and refined, dramatically improving the AI's performance.

**Note:** Kyli AI typically reaches the first checkpoint in about 50 generations (with evolution speed set to 6), the second in around 120 generations, and continues to improve as learning progresses. Be patient—evolution takes time!

<img src="https://imgur.com/zpuw4bf.jpg" alt="Kyli AI demo screenshot"/>

## Features

- **AI Visualization**: The square at the start is the “fittest” agent of the current generation. Press <kbd>SPACE</kbd> to view all agents.
- **Evolution Controls**: Adjust population size, mutation rate, and evolution speed for faster or more diverse learning. You can also configure how moves per agent increase over generations (e.g., 5 moves every 5 generations).
- **Manual Play**: Press <kbd>P</kbd> to try the maze yourself.
- **Replay Highlights**: Press <kbd>G</kbd> to watch notable moments from the evolution process.

Inspired by [Code Bullet](https://github.com/Code-Bullet)'s implementation of genetic algorithms.