# bgg-steam-finder 🛰️🎲

A unified recommendation engine that bridges the gap between physical tabletop libraries and digital Steam collections.

## The Vision

I have a collection of board games on BoardGameGeek (BGG) and a video game library on Steam. Often, the "vibe" or mechanics I enjoy in one medium (e.g., Deck Building, Resource Management, Dungeon Crawling) translate perfectly to the other. This app analyzes both libraries to suggest what I should play next or what I’m missing from my collection.

## Initial Tech Stack Goals

- Frontend: Simple, mobile-responsive web interface (React/Next.js, typescript).
- APIs: * BGG XML API2 for tabletop data.
Steam Web API for digital library data.
- Storage: LocalStorage/SessionStorage for initial V1 to keep it lightweight.
## Core Features (Roadmap)
- Library Sync: Fetch "Owned" games from BGG and Steam.
- Tag Mapping: A logic engine that maps BGG "Mechanics" (e.g., Draft, Card-game) to Steam "Tags" (e.g., RPG).
- The "Vibe" Suggestor: A dashboard showing Steam games I own that match my top-rated board games, and vice-versa.
- Discovery Mode: Suggesting new games based on cross-platform taste profile.
