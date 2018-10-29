# slaparoo

## Tasks:
- [x] In-game message that config is wrong
- [x] Indestructible arena (OPs can destroy the arena now)
- [x] No need for food (disable hunger)

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
    "name": "xvojta",
    "level": 4,
    "bypassesPlayerLimit": false
  }
]
~~~~
