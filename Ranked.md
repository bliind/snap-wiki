# Ranked
The first game mode you're introduced to in SNAP is ranked mode. In ranked, you play random opponents in one game. The cube value at the end of the game is the number of cubes you've won or lost. 

## How Ranked Works
Ranked mode ranks range from 1 to 100. For ranks 1-10, you only need 1 cube to advance to the next rank. Within this range, there is also a unique milestone at rank 5.

Once you hit rank 10, you're introduced to the concept of snapping. From here on out, you must win 7 cubes to advance to the next rank. It is also at this point that you are able to drop ranks that you gain; however there is a rank floor at rank 10, meaning you cannot drop below that.

Every 10 ranks past rank 10, you will hit a new milestone. If it's the first time you hit a milestone in a season, the game will award you with 3 extra ranks. For example, if you rank up to 50 for the first time, you will be placed at rank 53 (with 0/7 cubes toward the next rank). Additionally, you'll be able to claim the ranked reward for that milestone.

## Rank Reset
- If you are Infinite rank you’ll go to rank 75
- If you are between rank 90 and 99 you’ll go to rank 73
- 80-89 -> 65
- 70-79 -> 63
- 60-69 -> 55
- 53-59 -> 53
- 1-52 -> No decay

Rank 10, Iron, is the rank floor and you can not go below it.
No matter how high you rank at Infinite, you will always reset to rank 75.

## Rewards

- Rank 5 (Agent): Marvel Snap cardback (can only be claimed once per account)
- Rank 10 (Iron): 200 Credits
- Rank 20 (Bronze): 40 Random Boosters
- Rank 30 (Silver): 250 Credits
- Rank 40 (Gold): Season-themed Title
- Rank 50 (Platinum):  400 Credits
- Rank 60 (Diamond): Mystery Variant
- Rank 70 (Vibranium): 500 Credits
- Rank 80 (Omega): Season-themed Avatar (The season pass card's base avatar)
- Rank 90 (Galactic): 500 Gold
- Rank 100 (Infinite): Infinite style of Season-themed cardback

![rewards image](https://github.com/bliind/snap-wiki/raw/main/images/ranked/RankedRewards.webp)

## Pre-Infinite Matchmaking
While not everything is known about how ranked matchmaking works, the devs have given us *some* information on how the matchmaking algorithm works. Ranked matchmaking is regional, meaning you will only queue against players in your region; there are currently 3 regions with an intent to eventually make matchmaking global ([Source](https://discord.com/channels/978545345715908668/978547819214434304/1174025706313875466))

The opponents who you match against are based on your CL, MMR (Matchmaking Rating), and current rank. ([Source](https://discord.com/channels/978545345715908668/978547819214434304/1002627840778436618)). CL and MMR are handled individually; the CL bracket attempts to restrict the pool of players available to match against to the same range that you're in. The MMR then influences who exactly within that bracket you are paired with. After reaching a certain Collection Level, you are placed in the XXXX+ CL bracket (this exact number is not known) ([Source](https://discord.com/channels/978545345715908668/978547819214434304/1187123836303446107))

The game will attempt to increase your MMR till it is around 50%, and will put you against opponents with higher Collection Levels to do so.  For example, if you're a CL 1000 player consistently playing against CL 5000 players, it means that you're winning ~50% of matches against that range of players ([Source](https://discord.com/channels/978545345715908668/978547819214434304/1141799130700709979))

Your current rank is taken into account when pairing you with an opponent. Like Collection Level, there is a range of ranks the game will pair you against, with this range increasing the longer you are queued for a game, maxing out at -30 to +30 ranks from yours. The exception to this is Infinite rank: pre-Infinite players cannot play against post-Infinite players.

The MMR then influences who exactly within that bracket you'd pair with. 

It is possible to play against bots in pre-Infinite ranked mode. The higher your rank, the fewer bots you will encounter, though you will have higher odds of playing against a bot if your queue times are long.

## Infinite Ranked
Once you've hit Infinite (Rank 100), you will be assigned an Infinite rank based on the number of Snap Points you have. This number is calculated based on your MMR. Your Infinite rank is a global rank ([Source](https://discord.com/channels/978545345715908668/978547819214434304/1148662841780473947) ).

The Ranked Infinite Leaderboards for the current and previous Snap season's can be found in the "News" tab. You can sort the leaderboards based on region, or globally. The ranked leaderboards only show the top 1000 players in the sort.

### Differences between pre-Infinite and Infinite Ranked
* There are no bots in Infinite
* CL banding for matchmaking in Infinite is [different](https://discord.com/channels/978545345715908668/1394374483917410416/1394390438844039290)
* Your MMR cannot fall below the MMR you had when you got to Infinite in a season, even if you're losing more than 50% of your games
* You no longer gain or lose cubes; instead you gain or lose Snap Points

## Matchmaking Rating
Your Matchmaking Rating is a hidden number that the game keeps track of. As you win games, that number goes up; as you lose games, that number goes down. The amount of points you win or lose from a match is also weighted by the cube value of the match and the MMR of your opponent. For example, an 8-cube game has roughly 8 times the MMR impact of a 1-cube game ([Source](https://discord.com/channels/978545345715908668/978547819214434304/991828645356257330) ).
