# slaparoo

## Tasks:

- [ ] In-game message that config is wrong
- [x] Indestructible arena (OPs can destroy the arena now)
- [x] No need for food (disable hunger)
- [ ] Support for more arenas (multiple worlds)
- [ ] Team-game (friendly-fire on/off, assign team random/choice)
- [ ] Mode: TNT-run (blocks are disappearing)

## Bugs:

- [x] Third+ player does not receive the cookie
- [x] Third+ player does not have the score-board
- [x] Wrong player is announced as a winner
- [x] When rejoining the arena, player has cookie in lobby

## Notes

### Setup OP
Edit the file `*\server\ops.json`
~~~~
[
  {
    "uuid": "xxx",
    "name": "Arcifrajer",
    "level": 4,
    "bypassesPlayerLimit": false
  }
]
~~~~
