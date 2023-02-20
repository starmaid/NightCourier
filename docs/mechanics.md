# Mechanics

This file overviews the planned game mechanics.

## Flight+Controls

The game is a plane game. You spend 99% of your time flying these dang things around. The flight, therefore, has to be good. 

Xbox controller is recommended. Its better to fly on analog sticks. However, I will support keyboard players.

These fun tron-like planes also should fly in a more interesting way than real planes. I want both high speed aero-dominated interactions while dogfighting, but I want to be able to hover around the city.

Core:

- Conservation of Momentum
    
    The plane will keep going in the direction it was going unless acted on by a force.
    
- Turn rate is determined by RCS-thrusters

    This allows the user to rotate while hovering. This also allows the user to rotate more than their plane is pitching/yawing, effectively stalling their control surface in that direction. The plane then enters sideslip, allowing crazy rotational tracking while still moving quickly.
    
    This was the first 'new' fighting technique. If you stall out your control surfaces, you can then freely track a stationary object that you are flying past. It is a skill to keep your guns on target.
    
- Follow standard convention

    The RC-plane controls are the ones we are using here. They are standard for a reason. Transferrable skills for the player.
    
- Throttle should be used, but not hard to use

    Good throttle control is key to an engaging fight. The throttle moves a setpoint up and down, and this is a VELOCITY setpoint. User can hold the button to go the last 10%, and it will auto come back down to 90% when not held. This gives the user a 'boost' feeling. (thanks project wingman for that idea)
    
### Control Scheme

![](/docs/controls/controls.drawio.png)
