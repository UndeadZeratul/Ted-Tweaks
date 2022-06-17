# Ted Tweaks

A large collection of various tweaks I enjoy using for 'Hideous Destructor'. Current feature set:

- Make *ERPs not require spamming reload in order to be fixed.
- Make Light Amp Goggles not have fucky FOV scaling.
- Made the Jetpack not so obscenely loud and heavy.
- Radsuit now has a unique overlay instead of just a screen tint and weighs less.
- Decreased ladder weight.
- Added the compass changes from Cozi's Hideous Helmet fork.


// Keeper Readme
### Notes
- The following stats are restored (by default):
	- 60% of bleeding, wounds, aggro, burns, bloodloss, and diseases (if applicable);
- CVars are:
	- `keeper_percent_* [0.0 - 1.0]`: Sets the percentage of stats restored on respawn, where * is one of the following: `bleeding`, `wounds`, `burns`, `aggro`, `bloodloss`, `diseases`.

### Warning
- If you set bleeding to anything above 0, **do not bandage**. Tell your teammates to use a medikit. Bandaging results in Wounds Already Treated accumulating STUPIDLY fast and will likely result in you crawling around for the rest of the level. This mod can be brutal. Use with care!