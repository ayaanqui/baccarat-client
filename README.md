# 🃏 Baccarat Client
This repository serves as the frontend GUI for the [Baccarat Server](https://github.com/ayaanqui/baccarat-server). This repo connects to an IP address where the server is active. Once the client is connected to a Baccarat Server, the user is able to play the game.

## Rules of the game
* The suits of the cards are irrelevant.
* Face cards and 10’s count as zero (’Baccarat’ pronounced ‘Bak-Ar-Ah’).
* Aces always count as one.
* When two cards are dealt and the total of the cards equals more than nine, remove the first number of the total. For example, if the Player's hand is a 9 and a 6, the total is 15, which means your Baccarat hand is 5.
* To even out the odds, the casino charges up to five percent commission when a bet is placed on the Banker and the Banker's hand wins. No commission is charged on bets placed on the Players hand.
* In the event of a tie and no one bet on tie, the hand is considered a ‘push’— all wagers are returned.

## Working with the project

### Clone project

```
git clone https://github.com/ayaanqui/baccarat-server.git
```

### Compile project

```
mvn package
```

### Run program
```
mvn exec:java
```