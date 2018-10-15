# slaparoo

## Tasks:
- [ ] In-game message that config is wrong
- [ ] Indestructible arena (OPs can destroy the arena now)

## Bugs:
- [x] Third+ player does not receive the cookie
- [x] Third+ player does not have the score-board
- [ ] Wrong player is announced as a winner
- [ ] When rejoining the arena, player has cookie in lobby

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
