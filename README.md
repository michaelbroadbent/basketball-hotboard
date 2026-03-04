# 🏀 Basketball Coaching Hotboard

A React-based coaching intelligence platform for tracking basketball coaches, their career histories, connections, and performance metrics using T-Rank data.

Built to faithfully match the styling and functionality of the Football Coaching Hotboard.

## Features

- **By School**: Select a school to discover coaching connections. See which coaches on the current staff have overlapping career histories — where they worked together, for how long, and what positions they held.
- **By Alma Mater**: Find all current coaches in the database who played at a specific school as student-athletes.
- **By Coach**: Look up any coach directly by name. View their full career history, current position, bio details, and T-Rank performance at each stop.
- **By Stats**: Browse T-Rank team stats with sortable rankings. Click into any school to see who the head coach is and how the numbers have trended.
- **Staff History**: View the full year-by-year coaching staff breakdown for any school.
- **School History**: Search for any school to see every coach in the database who has ever coached there.

## T-Rank Stats

- **Basic**: Rank, Record, AdjOE, AdjDE, BARTHAG, WAB
- **Offense**: AdjOE, eFG%, TO%, ORB%, FTR
- **Defense**: AdjDE, eFG%D, TO%D, DRB%, FTRD

## Setup

```bash
npm install
npm run dev
```

## Data Files

- `/public/data/coaches_basketball.json` - Coach data with career histories
- `/public/data/torvik_trank_2008_2026.json` - T-Rank stats data

## Build

```bash
npm run build
```

## Credits

- T-Rank data from [barttorvik.com](https://barttorvik.com)
- Team logos from ESPN CDN
