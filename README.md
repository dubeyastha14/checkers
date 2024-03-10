# CHECKERS GAMING

## Introduction

The game of checkers is considered a complicated game with <img src="/tex/dbab8293b66086459d4464168538e091.svg?invert_in_darkmode&sanitize=true" align=middle width=29.54351234999999pt height=26.76175259999998pt/> possible legal positions in the English draughts version ( <img src="/tex/5786a8e466b20e868a9d801cbb6c4521.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52961069999999pt height=21.18721440000001pt/> board) alone (much more on higher dimensions). In this attempt to create a game agent, a tree traversal approach has been used. This approach is not only fast but also efficient given that good heuristics are used. The agent has been created which is capable of playing the game of checkers with a remarkable win rate against average players. Checkers is a 1vs1 zero-sum game. Minimax or Minimax algorithm is best suited for such types of games. Following is the development procedure practised during the development of the project.

1. Implemented a basic Minimax Agent with limited depth.
2. Applied ⍺-β pruning.
3. Improved the evaluation functions.

<table>
    <tr>
        <td><img src="imgs/checker_gif_1.gif" alt="AI vs Player I"></td>
        <td><img src="imgs/checker_gif_4.gif" alt="AI vs Player II"></td>
    </tr>
    <tr>
        <td><img src="imgs/checker_gif_7.gif" alt="AI vs Player I"></td>
        <td><img src="imgs/checker_gif_8.gif" alt="AI vs AI II"></td>
    </tr>
</table>


## Contributing

Found a bug? Create an **[issue](https://github.com/Hsankesara/Draughts-AI/issues/new)**.
