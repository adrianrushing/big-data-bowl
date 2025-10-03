# big-data-bowl

We can acquire additional data, but what would that look like? 
Additional data is not necessarily a plus. Will the model generalize 
if the additional data is not available?

Remember the drive
Remember the play
Remember the season

Per player

Clean Data:
- Player ages instead of birthdays (game_id is date)
- Number of frames on the field (pre-snap + post-snap if tracked)
- Number of plays played
- Days since last game (only if game_id is reliably the data)


New measures:
- Clever way to calculate exhaustion?
- play-over-play difference in velocity and acceleration
- Rate of change of acceleration?
- Momentum


Silly little crazy ideas
- predict final position
- model as an optimization problem to either:
    - Maximize yards gained
    - Minimize time lost'
    - Concerns with this approach
        - Would offense and defense be separate