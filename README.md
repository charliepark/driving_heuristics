# Driving Heuristics

This is a set of strategies for The Driving Game. Play it, tweak the strategies, and let me know what you'd change.

The goal is twofold: 1) use your brakes as little as possible, and 2) create a heuristic for driving that maximizes the distance you can travel without having to apply your brakes.

Here is the default starter heuristic. You should modify it to suit your driving, and should report back with improvements.

1. If the space between you and the car in front of you is static or shrinking, **coast**. Otherwise …
2. If the number of cars with brake lights in front of you (B) is greater than the number of lanes going in your direction (L), **coast**. Otherwise …
3. If you are going over the speed limit, **coast**. Otherwise …
4. You may accelerate.

Drive happy.
