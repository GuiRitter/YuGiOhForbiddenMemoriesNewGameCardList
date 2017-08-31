# YuGiOhForbiddenMemoriesNewGameCardList

This is a game that I always wanted to beat, and that includes getting all cards, all duelists and what not. For that, I wanted a starter deck as good as possible. I started a few games and analyzed which cards I was getting. I realized that most of them seldonly repeated, so I started to make several new games and trade all cards to a single memory card. When I saw that I had over 200 different cards, I got curious about exactly how many cards the game would give, and I realized that only a completely automatized approach would give the answer, so I built one.

By the way, I'm using the PCSX-R Emulator*. Firstly, I used ArtMoney to find the memory locations that had the values for the cards in the deck. Secondly, I made a Java program to read these values and store them in a list. Thirdly, I made an AutoHotKey script to play the game.

The script starts a new game, escapes from Simon Muran, goes to the shop, opens the Build Deck menu and notifies the program via the clipboard. The program reads the deck, updates the list and notifies the script via the clipboard too. The script returns to the main menu and the process repeats.

I left it all running for 24 consecutive hours, since I learned on the internet that the random number generator is influenced by the clock. The longest amount of runs without new cards was about 75. After 24 hours, I stopped the process and it was at 320 runs without finding new cards. It had found 345 different cards. I suspected that was all, but I wanted to be sure. Statistically, that's impossible, but to increase the certainty I started the process for another 24 consecutive hours. 770 runs later, no new cards. Must be it.

Unfortunately, I blindly updated JNA and the new version doesn't work as the old one, so my program is not working anymore. I'll make a new version and then upload it here. Until then, the list that was compiled can be kept here, so the results can still be used.

I couldn't find a reliable card database on the internet. Some were incomplete, some had conflicting information (between themselves and the game). I will make my own. I will make other automation tools to get as much information as possible from the game. After I do that, I will make a decent list. Before that, I'll just make a list with three fields: the card index, the amount of cards obtained, and the percentage to 1 542, which is the amount of full decks that can be built with all the cards obtained, which were 61 680. I made it so in order to make Dark Hole plus Raigeki be equal to 100 percent. This means that, in every deck, you'll get either one or the other, which is true for being enforced by the game.

All trademarks and copyrights mentioned throughout are owned by their respective trademark and copyright holders.

\*As I wrongly knew, know that it is not legal to own a PlayStation's BIOS, even if you do own a PlayStation. Fortunately, there's an emulator called PCSX-Reloaded (PCSX-R) that doesn't need a BIOS, so it's perfectly legal to play emulated PlayStation games, as long as you own the games themselves.
