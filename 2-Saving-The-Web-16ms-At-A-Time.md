# 2 - Saving the Web 16ms at a Time, Joshua Comeau
- Animations important to bridge the gap between native apps and web apps
- Important for web apps to stay relevant
- Each frame needs to be animated within 16ms time in order to be fluid within 60Hz
- To do this, we need to make sure as little as possible get's re-painted
- If we can, animate props that don't cause re-painting like transform. Check https://csstriggers.com/
- Requires creative solutions to animations, but: Don't be afraid to do hacky solutions
- E.g. use sprites for an animation