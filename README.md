# Mind-Reader-Game---Claude-Shannon-s-Algorithm-II
A game I created where the computer competes with the player and tries to read their next move using Claude Shannon's "A Mind Reading Machine" based algorithm.

The algorithm of my game:

The computer looks for certain patterns in the player inputs (Heads or Tails) and tries to remember them. Furthermore, it assumes that the player will follow these patterns the next time if the same situation arises. If an assumed pattern is not repeated at least twice by the player, the machine predicts Heads or Tails randomly.
The types of patterns remembered, involve the outcome of two successive plays, i.e., whether or not the player won on those plays and whether the player changed their choice between the plays and after the plays.

There are 8 possible situations and, for each situation, a player can do two things. These 8 situations are:
1)The player wins, plays the same and wins again. The player then plays the same or plays differently.
2)The player wins, plays the same and loses. The player then plays the same or plays differently.
3)The player wins, plays differently and wins again. The player then plays the same or plays differently.
4)The player wins, plays differently and loses. The player then plays the same or plays differently.
5)The player loses, plays the same and wins. The player then plays the same or plays differently.
6)The player loses, plays the same and loses again. The player then plays the same or plays differently.
7)The player loses, plays differently and wins. The player then plays the same or plays differently.
8)The player loses, plays differently and loses again. The player then plays the same or plays differently.

Each situation corresponds to a different cell in the memory of a machine. Within a cell, two events are registered:
            Whether the last time this situation arose, the player played the same or different.
            Whether or not the behaviour indicated in the first point, was a repeat of the same behaviour in the preceding situation
