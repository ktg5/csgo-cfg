# Ktg5's CSGO cfg (autoexec)

## Stable build: [1013](https://github.com/ktg5/csgo-cfg/releases)

## Dev build: [1013](https://github.com/ktg5/csgo-cfg/archive/master.zip)

the autoexec i use for csgo

You may edit this autoexec/cfg to fit your playstyle if you need to or don't like something about this.

## How to install
1. Download the autoexec file
2. Go to your CSGO installation and go to `/csgo/cfg` then copy and paste the autoexec into that `cfg` folder.
3. Lanuch CSGO and make sure you enabled the "Developer console".
4. Open up console and type `exec autoexec`.
5. Test out the config, edit to your liking, and test some more.

## Build 1013!
### Remove all funnies, we gettin' serious in here.
Build 1012 has added the following:
- Crosshair changes when left-clicking or right-clicking.
- Remove the god awful sound effects on keybinds.
- Put the bomb icon in invertory instead of under the radar.
- `autoexec_help.cfg`
- Some other stuff I probably forgot about.

### How do I update?
For those who are just getting into autoexecs, follow the steps on "How to install".

If you have edited the autoexec with some code of your own, I recommend you rename your old autoexec to something else before copying the new autoexec over so nothing gets overwriten. Then import your extras from your old autoexec into the new one.

## So what does this do/change?
- L-SHIFT to duck, and L-CTRL to walk. (you can change this by running or by editing the autoexec.)
- Cool sound effects when pressing keys like L-SHIFT and L-CTRL.
- Turns off very uncool things like switching to the gun you just picked up, and use = buy as well.
- Swap left and right hands by pressing "V".
- Hide HUD by pressing "C"
- Aliases to turn on stuff. (see below)

### Cool aliases
If you download the `autoexec_help.cfg`, you can use `cfg_help` view all the aliases that are in the config.

You can add these to the start of the autoexec at the end of the autoexec/cfg or use the aliases in console.

`+streamer_mode` enables things streamers should enable. Read more about streamer mode [here](https://github.com/ktg5/csgo-autoexec#Information-about-streamer-mode).

`cfg_sens` - in-game mouse sens I use.

`cfg_reset_hud` - resets HUD scaling to default.

`cfg_reset_viewmodel` - resets viewmodel FOV to default and viewmodel offset to 0.

`cfg_reset_other` - resets all commands in the "other." section of the autoexec/cfg to default.

### [Buy binds](https://github.com/ktg5/csgo-autoexec/blob/master/key-binds.png)

### Information about streamer mode
The "Streamer mode" alias changes how CSGO looks and plays for casual CSGO streamers (this alias is most helpful for streamers on Twitch). 

The following is a list of things the alias changes:
- Scoreboard will now show the number of people on each team
- Mutes enemy team.
- Mutes all but friends and those in your CSGO party.
