# Winnipeg Sports API
*Created by Group 14*

## Description
- **Manitoba sports event API**

- This is a restful API which is used to people for giving information about sports match that going on in Winnipeg. It gives the information about the team that you are looking for, roster and also line up of the match.

## Parameters
**teamName** (String) The name of the team

**year** (integer) The year of game play 


## Endpoints
**nextGameInfo(teamName)**: returns when & where the team is playing and who its against.

**roster(teamname, year)** : returns a list of the team members in the selected year.

**playsTonight(teamName)**: returns a true or false if a team is playing tonight.

## Resources
> "gameInfo":
>
>   {
>
>     "teamName": "Winnipeg Jets",
>
>     "when": "2020-11-20-19:00UTC",
>
>     "opponent": "Calgary Flames",
>
>     "where": "Winnipeg"
>
>   }
>     
>

### Sample requests

