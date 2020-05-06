# AutoExec

This is a fork of Icewind's 'autoexec' plugin (https://github.com/spiretf/autoexec)
UGC functionality has been completely replaced with rgl functionality. UGC will likely be properly reimplemented later.
Automatically execute the correct config for a map.

Only koth and 5cp_scrim config files have been tested. For all other uses please use the spire.tf repository. 

## Installation

[Download Plugin](https://github.com/nutcity/autoexec/blob/master/plugin/autoexec.smx)

## Usage

The plugin automatically executes the config while loading a map

### Configuration

- `sm_autoexec_league`: set the league for which to load the config (etf2l or rgl, defaults to rgl)
- `sm_autoexec_mode`: set the gamemode for which to load the config (4v4, 6v6 or 9v9, defaults to 9v9)
- `sm_autoexec_autoset`: try to set league and mode when a config is manually loaded (true or false)

### Manually execute the config

You can manually load the selected config using the `sm_autoexec` server command
