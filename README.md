Multiple object tracking experiment
==============
This program is super-complicated, legacy of many different papers using tracking. I don't recommend you use it without my guidance. My other repositories, such as attentional-blink, are more user-friendly.

Want to add
- Modulation of radius as function of time. Radius calls function to determine its value at each time. 
- Add waveform to the trajectory. This is something added to radius, is function of angle.
Should also be a function of time? But if the idea is to know/determine individual objects' trajectories, then reversals will mess it up.
Is it about individual object paths or not?

How do we handle reversals? Reversals necessitate integration. So, either pre-generated trajectories or something really complicated with 
We already use incremental changes to the angle, which presently count on not missing a frame. I should probably start by functionising the position accumulation.

In the long term, want to set up exchange of objects among rings. Necessary to conduct an identity-tracking experiment. Can also push harder on speed limit that way.

Issues
- Change so doesn't go slower when miss frames

info