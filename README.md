# grenade
This FoundryVTT macro helps GM/Players to speed up grenade attacks

1. Choose your token (the thrower)
2. Run the macro
3. Answer yes/no to whether you have the Pitcher specialty
4. Click where the grenade should land
5. The macro automatically rolls:
   - Agility (1dX based on grade)
   - Mobility (1dX based on grade)
   - +1 if Pitcher
   - Counts successes (6+=1, 10+=2)
6. If 0 successes:
   - Rolls 1d6 direction (N, NE, SE, S, SW, NW)
   - Rolls 1d6 distance (meters)
   - The grenade scatters
7. Explosion is created at final position with same damage zones as before
8. Two chat messages:
   - Roll result (visible to all)
   - Damage report (GM only)
