# Ted Tweaks

A large collection of various tweaks I enjoy using for 'Hideous Destructor'. Current feature set:

- Make *ERPs not require spamming reload in order to be fixed.
- Make Light Amp Goggles not have fucky FOV scaling.
- Made the Jetpack not so obscenely loud and heavy.
- Radsuit now has a unique overlay instead of just a screen tint and weighs less.
- Decreased ladder weight.
- Added the compass changes from Cozi's Hideous Helmet fork.
- Improved Player Climbing.
- Removed Zerk constant wounding and messages.
- Integrated keeper, updated for both.
- Added a CVAR to make Invulnerability Spheres not break if wanted.


### Notes
- The following stats are restored (by default):
	- 60% of bleeding, wounds, aggro, burns, bloodloss, and diseases (if applicable);
- CVars are:
	- `keeper_percent_* [0.0 - 1.0]`: Sets the percentage of stats restored on respawn, where * is one of the following: `bleeding`, `blues`, `burns`, `aggro`, `bloodloss`, `diseases`.
