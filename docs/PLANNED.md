# Pokémon Solus RGB: Planned Features

Some changes/features I have planned for upcoming releases.

### For the game
- Restore Rival's unused victory speeches (cut content)
    - This is quite easy to do, but to make it work nicely, I will need to also add new victory speeches for every trainer in the game. Otherwise, they will use their 'loser' speech even if they win. So it will take some time to write/source new victory speeches.
- Make only the fossil that was not chosen in Mt. Moon appear in the new Victory Road Fossil Room (right now, both fossils will appear there regardless of the player's early-game choice)
- Add unused "Porygon on monitor" text on Silph Co. 11F (cut content)
- Fix the badges to apply the correct stat boosts
- Fix EXP bar color in Super Game Boy (should not color match to the HP bar)

### For the repository
- Add config command line flags for users to modify certain settings while building the ROMs
    - Which sprite sets are used for front sprites (R/B, R/G, Yellow, Solus, Space World 97)
    - Which back sprite sets are used (original low-res(?), Space World high-res, Gen 2 high-res, and potentially a newly-curated 'Solus set' for back sprites as well)
    - Whether to enable certain other features?