# Brick-Breaker
Created the brick breaker game using mips asembly. Created using the Mars IDE.

# Setup
After installing Mars to start a game the user must create a bit map display and keyboard simulator from the tools drop down. Both should be connected and the bitmap
display should be configured as described at the top of the file.
# How To Play 
\begin{itemize}
    \item Hit the white ball with the purple paddle on the bottom to destroy all the bricks on the board that are yellow to dark purple to win the game as they disappear when hit. The dark grey ceiling and walls will not disappear when hit. Refer to Figure 4.
    \item The ball will bounce around intuitively, use your spatial awareness to determine the ball's intuitive movement and follow with your paddle to rebound it. 
    \item Two players will play the game together where the first controls the bottom paddle and the second the top paddle. Once the game is started a timer of 60 seconds starts to beat the game or else the players lose.
\end{itemize}
\newline \textbf{Controls}:

Player 1: Bottom Paddle
\begin{itemize}
    \item Press 'a' to move the bottom paddle left
    \item Press 'd' to move the bottom paddle right
\end{itemize}
\newline

Player 2: Top Paddle
\begin{itemize}
    \item Press 'j' to move the top paddle left
    \item Press 'l' to move the top paddle right
    \item Press space bar to launch the ball at the start of attempt.
\end{itemize}


\newline

General Controls:
\begin{itemize}
    \item Press 'p' to pause the game after during the state where the ball has been launched.
    \item Press 'q' to quit the game anytime during the execution of the game
    \item Press 'r' to restart the game during win or lose state.
\end{itemize}
\newline \textbf{Gameplay}:
\begin{itemize}
    \item The player may move their paddles for each attempt before they launch the ball to gain a better position.
    \item After the ball is launched the game has started and the ball will randomly launch either top left or top right.
    \item During the game either player may press the key 'p' to freeze/pause the game and press 'p' again to resume.
    \item If both players miss the ball and exits off screen the lives the player has will decrease by 1 and the game will restart to a neutral position but with the current brick states retained.
    \item Different sound effects will play when the player hits a wall, ceiling, brick or paddle with the ball.
    \item If the players manage to destroy all the bricks the game will freeze and transition to a WIN screen where it displays a big W.
    \item If the players miss the ball three times, the game has been lost and will transition to a GAME OVER screen. 
    \item Players may press the key 'r' to restart the game when they see the win screen or the game over screen. This will effectively reset the position of the players, reset the brick states and give the players three new lives.
\end{itemize}
