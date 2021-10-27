---
title: Data and Applications | Project Phase - 4
subtitle: Team-40 'Life is a Schema'
author:
- Pratyaksh Gautam (2020114002)
- Shubh Bhullar (2020101009)
- Shikhar Saxena (2021121010)
---

# Introduction

`Dump.sql` contains all tables created and filled with data.
Main code is in `cli.py` file.
Run using

```shell
$ python3 cli.py
```

Video can be found at 
https://drive.google.com/file/d/1f9o37Bsv3ASMqa3l4g9UcGOvblkc4dYE/view?usp=sharing 

# Assumption made

Instead of Eleven Players (PlayingEleven) for each team,
we have taken 5 players for each Team (for demonstration purpose).

# Queries

## insertStadium

To insert Stadium into the database.

## updateStadiumID

To update a Stadium's ID in the database.

## updateCapacity

To update the capacity of a particular Stadium.

## getGoalScorers

Gets PlayerID and PlayerName of Goal Scorers among the Players.

## getAvgGoals

Get average goals (sum of scores (from result table) for all matches divided by the number of matches).

## searchTeam

Retrieves Team information for given TeamID.

## insertTeam

Inserts Team into database (Assigns five(eleven) players to the team which are not associated with any other team).
Similarly alots a manager and stadium to this team which are not associated with any other team.

## insertMatch

To insert Match between two teams.

## removeMatch

To remove Match for given MatchID.

## removeTeam

Removes Team for given TeamID.
Sets TeamID to NULL for the players associated with this team.

## getPlayer

Gets Player information about the given PlayerID.  

## getPlayingEleven

Displays the PlayingEleven members for the given TeamID.

## updateJerseyName

Update Jersey Name for given Player (PlayerID).

## updateJerseyNumber

Update Jersey Number for given Player (PlayerID).

## insertManager

Inserts Manager into the database.

## removeManager

Deletes Manager from the database.
Will allot a new Manager to the team if this Manager is mapped to some team. 