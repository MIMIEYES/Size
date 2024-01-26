## Two-player chess - a game of comparison

Methods:

- createGame: Create a game, bet n NULS, parameters 0-bet small 1-bet big

- joinGame: Participate in the game, bet <=n NULS

- draw: draw, the winner gets twice the minimum amount bet by both parties

- interrupt: Cancel this game. No one is participating in the game. This game can be canceled after 100 blocks of the game are created.

- updateCommissionRate: Set the platform commission ratio, range 0~100, default value 1

- viewRunningGameList: Get the list of unattended games

- viewDrawingGameList: Get the list of games waiting to be drawn
