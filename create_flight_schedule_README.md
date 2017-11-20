created and optimized a flight schedule between Dallas Love Field (DAL), Austin Bergstrom (AUS), and Houston Hobby (HOU). Here tail numbers are used to name the aircraft. We have 6 aircrafts T1, T2, T3, T4, T5, T6.

Due to noise restrictions:
• flights cannot have a departure time of 0559 or earlier
• flights can have a departure time of exactly 0600
• flights can have an arrival time of exactly 2200
• flights cannot have an arrival time of 2201 or later

Flight Times are as follows (assume same flight time either direction, presented in “half alpha” order). Flights must be scheduled for exactly their flight time (no more, no less).
Flight Time in Minutes
AUS - DAL: 50
AUS - HOU: 45
DAL - HOU: 65

We have secured gates at all airports. Each airport has a minimum ground time as follows. These are minimum times. Aircraft may be on the ground longer if designed.
Airport     Number of Gates     Minimum Ground Time in Minutes
AUS               1                        25
DAL               2                        30
HOU               3                        35

The schedule must start and end with the number of aircraft at an airport equal to the number of gates. It does not matter which specific tail number as all aircraft are configured the same, interchangeable, and may fly any route.

Optimization Goals:
Our optimization goals are to maximize the number of flights, utilize aircraft as evenly as possible, and utilize gates at airports as evenly as possible, and distribute flights among all 6 markets.
