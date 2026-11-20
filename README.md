# kr-soloq-research.

# KR Solo Queue Research

Personal statistical research on high-elo Korean solo queue in League of Legends.

## What it does

- Reads the Korean Challenger and Grandmaster ladders (league-v4) and the ranked solo queue matches of those players (match-v5).
- Computes aggregate statistics: champion performance by patch and by role, and how in-game state (gold, objectives, items) relates to game outcomes over time.
- These statistics feed personal analysis of professional League of Legends matches.

## Riot API usage

- Endpoints: league-v4 (Challenger / Grandmaster ladders, KR) and match-v5 (match ids, match details, ASIA routing).
- Volume: one update per hour of the ladder and of the recent matches of its players, within the standard rate limits.
- Data is stored privately for analysis only. No Riot data is redistributed, sold or exposed through a public service.

## Status

Personal, non-public project run by a single developer. No end users, no public application.

League of Legends and Riot Games are trademarks or registered trademarks of Riot Games, Inc. This project isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties.
