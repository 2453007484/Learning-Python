# Learning-Python
Personal Python Learning Record

1. CRAPS
  The basic flow of a single game is: 
    1. The shooter wagers to pass (win) and then makes an initial come-out roll with two six-sided dice.
        a. If the come-out roll is 7 or 11, that is a natural and the shooter has a pass (wins); the game is over.
        b. If the come-out roll is 2, 3, or 12, that is a crap and the shooter has a missout (loses); the game is over.
        c. If the come-out roll is any other number (4, 5, 6, 8, 9, or 10), that value becomes the shooter's point.
    2. If a point has been set, the shooter continues to roll until either:
        a. A subsequent roll matches the point and the shooter has a pass (wins); or
        b. A subsequent roll is 7 and the shooter has a missout (loses).
    3. Once a point is set and a missout occurs, the dice are passed to the person on the shooter's left, who becomes the new shooter.
