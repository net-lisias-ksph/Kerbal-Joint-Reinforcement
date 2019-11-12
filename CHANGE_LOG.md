# Kerbal Joint Reinforcement :: Change Log

* 2019-0824: 4.1.15 (Rudolf Meier) for KSP 1.7.3
	+ bugfix
	+ split into multiple versions for latest ksp version (4.1.x) and compatible ksp versions (4.0.x) to get better performance in the latest ksp version
	+ new visualization of joint instability in debug mode
	+ [ works with KSP 1.7.3 and later ]
* 2019-0825: 4.0.15 (Rudolf Meier) for KSP 1.4.0
	+ bugfix
	+ split into multiple versions for latest ksp version (4.1.x) and compatible ksp versions (4.0.x) to get better performance in the latest ksp version
	+ new visualization of joint instability in debug mode
	+ [ works with KSP 1.4.0 and later ]
* 2019-0713: 4.0.14 (Rudolf Meier) for KSP 1.4 PRE-RELEASE
	+ fix for dlc robotics
	+ improvement
	+ preparation for next update
	+ [ works with KSP 1.4 and later ]
* 2019-0614: 4.0.13 (Rudolf Meier) for KSP 1.4
	+ major update for 1.7.2
	+ compatibility fixes for older versions (tested with 1.4, 1.6 and 1.7.x)
	+ [ works with KSP 1.4 and later ]
* 2019-0611: 4.0.12 (Rudolf Meier) for KSP 1.4
	+ api update for mod compatibility
	+ [ works with KSP 1.4 and later ]
* 2019-0607: 4.0.11 (Rudolf Meier) for KSP 1.4
	+ api update for mod compatibility
	+ [ works with KSP 1.4 and later ]
* 2019-0527: 4.0.10 (Rudolf Meier) for KSP 1.4
	+ update
	+ [ works with KSP 1.4 and later ]
* 2019-0519: 4.0.9 (Rudolf Meier) for KSP 1.4
	+ update
	+ [ works with KSP 1.4 and later ]
* 2019-0503: 4.0.0 (Rudolf Meier) for KSP 1.4
	+ the original version I made based on the v3.4, with a lot of modifications
	+ but not including the latest implementations
	+ [ works with KSP 1.4 and later ]
* 2019-1017: 3.5.0 (ksp-ro) for KSP 0ersions starting from 1.3
	+ Features
	+ Integrated settings into stock UI
* 2019-0603: 3.4.1 (ksp-ro) for KSP 0ersions 1.3.x through 1.7.x
	+ Features
	+ Added basic support for robotic parts
* 2019-0422: 3.4.0 (ksp-ro) for KSP 0ersions 1.3.x through 1.7.x
	+ Features
	+ Recompile for use in KSP 1.3.x through 1.7.x (thanks @siimav)
	+ Launch Clamps can now be set to completely rigid (thanks @siimav)
	+ Removed compatibility checker (thanks @siimav)
* 2018-1229: 3.3.5 (ksp-ro) for KSP 1.4.5
	+ If physics jolts cause a vessel with launch clamps to to shift out of PRELAUNCH then put it back in PRELAUNCH. (and reset launch / MET timers)
* 2018-1227: 3.3.4 (ksp-ro) for KSP 1.4.5
	+ Recompile and versioning update for KSP 1.4.5
* 2017-0724: 3.3.3 (ferram4) for KSP 1.3.0
	+ Features
		- Recompile against KSP 1.3, ensure CompatChecker compatibility with 1.3
* 2017-0724: 3.3.3 (ferram4) for KSP 1.3.0
	+ Features
		- Recompile against KSP 1.3, ensure CompatChecker compatibility with 1.3
* 2017-0522: 3.3.2 (ferram4) for KSP 1.2.2
	+ Bugfixes
		- Fix multijoints breaking IR joints and any other exempted parts from moving
* 2017-0522: 3.3.2 (ferram4) for KSP 1.2.2
	+ Bugfixes
		- Fix multijoints breaking IR joints and any other exempted parts from moving
* 2016-1029: 3.3.1 (ferram4) for KSP 1.2
```
v3.3.1  
    Bugfixes  
    --Fix a critical bug involving unphysical forces applied to vessels on load / unload of other vessels and SOI switches  
```
* 2016-1029: 3.3.1 (ferram4) for KSP 1.2
```
v3.3.1  
    Bugfixes  
    --Fix a critical bug involving unphysical forces applied to vessels on load / unload of other vessels and SOI switches  
```
* 2016-1027: 3.3.0 (ferram4) for KSP 1.2
```
Features  
--Recompile to fix for KSP 1.2  
--Update method of handling multi-part-joints to ensure compatibility with Konstruction mod  
--Removal of old symmetry-based multi-part stabilization due to ineffectiveness in all situations to reduce overhead  
--Implementation of new vessel-part-tree leaf-based stabilization for greater stability on space stations and other convoluted shapes  
```
* 2016-1027: 3.3.0 (ferram4) for KSP 1.2
```
Features  
--Recompile to fix for KSP 1.2  
--Update method of handling multi-part-joints to ensure compatibility with Konstruction mod  
--Removal of old symmetry-based multi-part stabilization due to ineffectiveness in all situations to reduce overhead  
--Implementation of new vessel-part-tree leaf-based stabilization for greater stability on space stations and other convoluted shapes  
```
* 2016-0630: 3.2.0 (ferram4) for KSP 1.1.3
	+ Features
		- Recompile to ensure KSP 1.1.3 compatibility
		- Change multi-part-joint system to stabilize space stations and similar vehicles with very large masses connected by very flexy parts
* 2016-0630: 3.2 (ferram4) for KSP 1.1.3
```
Features  
--Recompile to ensure KSP 1.1.3 compatibility  
--Change multi-part-joint system to stabilize space stations and similar vehicles with very large masses connected by very flexy parts  
```
* 2016-0430: 3.1.7 (ferram4) for KSP 1.1.2
```
Features
--Recompile to ensure KSP 1.1.2 compatibility, especially within CompatibilityChecker utility  
```
* 2016-0430: 3.1.7 (ferram4) for KSP 1.1.2
```
Features
--Recompile to ensure KSP 1.1.2 compatibility, especially within CompatibilityChecker utility  
```
* 2016-0429: 3.1.6 (ferram4) for KSP 1.1.1
```
Features  
--Update to ensure KSP 1.1.1 compatibility  
--Minor optimization in joint setups  
--Remove B9 pWings from stiffening exemption, as it is unnecessary  
```
* 2016-0429: 3.1.6 (ferram4) for KSP 1.1.1
```
Features  
--Update to ensure KSP 1.1.1 compatibility  
--Minor optimization in joint setups  
--Remove B9 pWings from stiffening exemption, as it is unnecessary  
```
* 2016-0420: 3.1.5 (ferram4) for KSP 1.1
```
Features
--Updated to be compatible with KSP 1.1
--Very minor efficiency improvements in physics easing and stiffening of joints
--Fully exempt EVAs from all KJR effects
--Update config parameters to function with stock fixing of never-breakable joints bug
```
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
