# FS SimRate Bandit
This tool will help you with controlling and indicating current SimRate in Microsoft FlightSimulator 2020 via SimConnect.

It can display and announce the current SimRate via voice. Another feature is the automatic increase and decrease of SimRate along your flight plan.

<img src="https://i.imgur.com/0xm5cgx.png" width="220" />

## Features
* Display current SimRate and distance to next waypoint in app
* Announce current SimRate via voice on change
* Automatic SimRate increase/decrease until final waypoint of flight plan is reached (description below)
* _[TODO] Configurable Auto SimRate_
* _[TODO] Display current SimRate as overlay_
* ...

Come back or "Star" the repo for future updates.

### Automatic SimRate
When you click the "Start Travel" button the SimRate will automatically increase and decrease when the final waypoint is reached

Best use this when you departed and autopilot and speeds are set.

The conditions for auto travel to automatically stop are currently:
* 15nm before final waypoint in flight plan (before approach)
* 25nm before final waypoint on direct flights
* Approach activated

A few nm before any waypoint, the SimRate will decrease to allow the autopilot to properly adjust heading. SimRate will increase after the waypoint again.

## Usage
Download or clone the app and start. When the sim is loaded press "Connect".
