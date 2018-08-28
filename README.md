
# Nested Looping Lab

## Introduction
In this lab, we will practice using nested loops to iterate over nested data structures and create new collections. We'll be using data for a basketball team to practice our nested loops.

## Objectives
* Understand how a nested loops work
* Identify when to use nested loops

## Instructions


```python
data = {
    "home_team": {
      "country": "France",
      "num_passes": 484,
      "passes_completed": 423,
      "fouls_committed": 16,
      "players": [
        {
          "name": "Hugo LLORIS",
          "captain": True,
          "shirt_number": 1,
          "position": "Goalie"
        },
        {
          "name": "Benjamin PAVARD",
          "captain": False,
          "shirt_number": 2,
          "position": "Defender"
        },
        {
          "name": "Raphael VARANE",
          "captain": False,
          "shirt_number": 4,
          "position": "Defender"
        },
        {
          "name": "Samuel UMTITI",
          "captain": False,
          "shirt_number": 5,
          "position": "Defender"
        },
        {
          "name": "Paul POGBA",
          "captain": False,
          "shirt_number": 6,
          "position": "Midfield"
        },
        {
          "name": "Antoine GRIEZMANN",
          "captain": False,
          "shirt_number": 7,
          "position": "Forward"
        },
        {
          "name": "Kylian MBAPPE",
          "captain": False,
          "shirt_number": 10,
          "position": "Forward"
        },
        {
          "name": "Ousmane DEMBELE",
          "captain": False,
          "shirt_number": 11,
          "position": "Forward"
        },
        {
          "name": "Corentin TOLISSO",
          "captain": False,
          "shirt_number": 12,
          "position": "Midfield"
        },
        {
          "name": "Ngolo KANTE",
          "captain": False,
          "shirt_number": 13,
          "position": "Midfield"
        },
        {
          "name": "Lucas HERNANDEZ",
          "captain": False,
          "shirt_number": 21,
          "position": "Defender"
        }
      ],
    },
    "away_team": {
      "country": "Australia",
      "num_passes": 390,
      "passes_completed": 332,
      "fouls_committed": 19,
      "players": [
        {
          "name": "Mathew RYAN",
          "captain": False,
          "shirt_number": 1,
          "position": "Goalie"
        },
        {
          "name": "Mark MILLIGAN",
          "captain": False,
          "shirt_number": 5,
          "position": "Defender"
        },
        {
          "name": "Mathew LECKIE",
          "captain": False,
          "shirt_number": 7,
          "position": "Forward"
        },
        {
          "name": "Robbie KRUSE",
          "captain": False,
          "shirt_number": 10,
          "position": "Forward"
        },
        {
          "name": "Andrew NABBOUT",
          "captain": False,
          "shirt_number": 11,
          "position": "Forward"
        },
        {
          "name": "Aaron MOOY",
          "captain": False,
          "shirt_number": 13,
          "position": "Midfield"
        },
        {
          "name": "Mile JEDINAK",
          "captain": True,
          "shirt_number": 15,
          "position": "Midfield"
        },
        {
          "name": "Aziz BEHICH",
          "captain": False,
          "shirt_number": 16,
          "position": "Defender"
        },
        {
          "name": "Joshua RISDON",
          "captain": False,
          "shirt_number": 19,
          "position": "Defender"
        },
        {
          "name": "Trent SAINSBURY",
          "captain": False,
          "shirt_number": 20,
          "position": "Defender"
        },
        {
          "name": "Tom ROGIC",
          "captain": False,
          "shirt_number": 23,
          "position": "Midfield"
        }
      ]
    }
  }
```
