# tictactoe
During the development of the PvP project, I encountered initial challenges primarily related to debugging various bugs. Addressing these issues required meticulous line-by-line examination to identify and rectify them.

One notable issue arose when handling user input following the completion of the game, specifically in response to the prompt: "Play again? (y/n):". Initially, I overlooked scenarios where users might input invalid responses. To resolve this, I implemented a while True loop that continuously prompts the user for input. The loop breaks only when the user inputs either "y" or "n". For any other input, the program displays a message instructing the user to enter either 'y' or 'n', ensuring the loop persists until a valid response is provided.

In developing the AI bot, I experimented with different board formatting approaches, which initially caused display issues. To overcome this challenge, I referred back to the board formatting logic used in the PvP project, allowing for a swift resolution of the formatting discrepancies.

The most demanding aspect of the project was integrating the minimax algorithm with alpha-beta pruning into the AI. This required research involving resources such as YouTube videos, sample projects, and AI. Despite being time-intensive, this effort significantly enhanced the project's efficiency. Implementing this complex feature enriched my knowledge of alpha-beta pruning in a minimax algorithm.
