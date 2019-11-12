# Kerbal Joint Reinforcement :: Change Log

* 2016-0420: 3.1.5 (ferram4) for KSP 1.1
```
Features
--Updated to be compatible with KSP 1.1
--Very minor efficiency improvements in physics easing and stiffening of joints
--Fully exempt EVAs from all KJR effects
--Update config parameters to function with stock fixing of never-breakable joints bug
```
* 2015-0622: 3.1.4 (ferram4) for KSP 1.0.5
	+ Misc
		- Fixed issue with .version file and compatible KSP versions
* 2015-0622: 3.1.4 (ferram4) for KSP 1.0.5
	+ Misc
		- Fixed issue with .version file and compatible KSP versions
* 2015-0427: 3.1.3 (ferram4) for KSP 1.0
	+ Update for KSP 1.0
* 2015-0326: 3.1.2 (ferram4) for KSP 0.90
```
Features  
--Added code to slightly stiffen connections between symmetrically-connected parts attached to a central part; should reduce some physics weirdness
BugFixes  
--Fixed issue where undocking was impossible.
```
* 2015-0115: 3.1.1 (ferram4) for KSP 0.90
	+ BugFixes
		- Fixed a serious lock-to-worldspace issue involving multipart joints and physicsless parts
* 2015-0113: 3.1 (ferram4) for KSP 0.90
	+ Features
		- Set multipart joints to account for large mass ratios in choosing which parts to join
		- Set Decoupler Stiffenning to require the connection of immediate decoupler children to stiffen things even further
	+ BugFixes
		- Fixed a decoupling issues with multipart joints
		- Fixed multipart joint lock-to-worldspace issues
		- Fixed some issues on loading very large, heavy parts
* 2014-1229: 3.0.1 (ferram4) for KSP 0.90
	+ BugFixes
		- Fix some issues involving multipart joints
		- More null checking for situations that shouldn't happen, but might
* 2014-1228: 3.0 (ferram4) for KSP 0.90
	+ Features
		- MultiPart joints: weak, but stiff connections along a stack that will add even more stiffness without making the connection cheatingly strong
		- Proper, guaranteed application of stiffened properties, regardless of stock joint parameters
		- Updated default config values for greater sanity
		- Refactoring of code for sanity
	+ BugFixes
		- Longstanding issue with radially-attached parts that were larger than their parent are now fixed
		- Many NREs from bad events or bad states now avoided
* 2014-1216: 2.4.5 (ferram4) for KSP 0.90
	+ Features
		- KSP 0.90 compatibility
		- Include some extra checks to prevent errors from occurring
* 2014-1007: 2.4.4 (ferram4) for KSP 0.25
	+ Features
		- KSP 0.25 compatibility
		- Update CompatibilityChecker
		- Shutdown functionality if CompatibilityChecker returns warnings
* 2014-0820: 2.4.3 (ferram4) for KSP 0.24.2
	+ 0.24.2 compatibility
* 2014-0724: 2.4.2 (ferram4) for KSP 0.24.1
	+ 0.24.1 compatibility
* 2014-0718: 2.4.1 (ferram4) for KSP 2.4
	+ Bugfixes:
	+ Included JsonFx.dll, which is required by ModStats
	+ Relabeled ModStatistics.dll to allow simple overwriting for ModStats updates
* 2014-0717: 2.4 (ferram4) for KSP 2.4
	+ Update to ensure KSP v2.4 compatibility
* 2014-0703: 2.3 (ferram4) for KSP 0.23.5
	+ Current for KSP v0.23.5
