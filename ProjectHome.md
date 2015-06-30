# Confogl is a configurable competitive server plugin that aims to balance the Left 4 Dead 2 multiplayer gameplay. #

## Need Help? ##

If you are having trouble installing Confogl on your server or similar problems, please create a topic in the [Confogl Discussion forum on L4DNation](http://www.l4dnation.com/confogl-and-other-configs/).
If you think you found a bug within Confogl that needs fixing, check the issues list [here](http://code.google.com/p/confogl/issues/list) and create a new issue if theres none yet for your bug.

## Main Confogl Features ##

Match mode can be enabled anytime with !match command. Match mode includes the following features:

  * Reduced Spawn Timers to 20 seconds
  * Tank on EVERY map
  * Tank is frozen and ghosted with fire immunity for 5 seconds
  * Tank punch-fix (allows the tank to punch survivors off an edge that otherwise would have incapacitated them on the spot)
  * No tanks will spawn after the rescue vehicle approaches
  * Witch always seated.  Increased spawn rate.
  * Jockey re-leap after incap timer reduced to 15 seconds (from 30)
  * Special infected 'Ghost-warp'
  * Infected bots kicking
  * Finale spawn radius reduced
  * All hordes (boomer and natural) are 25 common infected, and natural hordes spawn every 100 seconds
  * Time for spit to ignite cans reduced
  * All T2/3 weapons removed and replaced by T1 weapons (Options to limit T2/3 weapons instead)
  * Hunting rifles limited with hunting rifle pickups acting as ammo piles when limit is reached
  * Laser Sights removed
  * Chainsaw removed
  * Grenade Launcher removed
  * Fire ammo removed
  * Medkits replaced with Pills, including on finales
  * Defibs removed
  * Health based survivor bonus dependent on incap count and number of survivors alive. Current survivor bonus is viewable with `!health` command.
  * Water slow down
  * Pause Feature
  * Kills lobby reservation
  * Password feature
  * HUD in spectator mode and for infected team which shows health and control of a tank when in play
  * Commands `confogl_cvarsettings` and `confogl_cvardiffs`  to show server confogl settings
  * Supports `!forcematch cfgname` (i.e. multiple parallel versions of Confogl)
  * 1v1 and 2v2 configurations included
  * Option to kick for 'illegal' settings of `mat_hdr_level`,  `cl_interp`
  * Item tracking system to reduce quantity of pills, adrenaline and throwables.
  * Support for shoutcast HUD
  * Fallen Survivor commons and bilebombs from Hazmat commons removed.
  * Cvar settings module to allow more flexibility for customization by config makers
  * Disabled punk+jump+rock for tank with `confogl_block_punch_rock`
  * Includes L4DReady
    * Saferoom closed until 90 seconds after ready up ends preventing early spawns
    * Enable or disable ghost spawns during ready up with `l4dready_disable_spawns` (default: disabled)