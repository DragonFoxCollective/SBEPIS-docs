# Momentum

Generally, momentum is conserved and requires input or friction to cancel out or redirect. Redirecting momentum by turning is not instant and has a certain turning radius.

# Dash

A dash occurs when the dash button is tapped. It redirects all momentum and moves the player at a constant velocity.

# Slide

A dodge occurs when the crouch button is held when you are moving. It increases the control of momentum, so the turning radius of redirecting momentum is finer, and decreases the player's momentum down to a cap. Holding input toward your momentum loses less of it. Holding input adverse to your momentum dramatically decreases momentum, like an emergency break. Holding input to the side turns the player's momentum like tank controls.

If the player is on the ground, this is a slide. If the player is in the air, this is a youth roll.

Sliding is affected little by the environment, decreasing velocity when moving up slopes, not increasing when going down, and surfing when moving along slopes.

# Stamina

"Hubris"

Dashing uses stamina. Attempting to perform dash actions while having no stamina and having little momentum causes the player to trip.

While sprinting does not decrease stamina, having low stamina prevents sprinting.

Dash-attacking refills stamina, to keep attack momentum going.

# Youth Roll

BALL FORME

Rolling is affected greatly by the environment, but has very little friction and control (but still some).

You can air strafe as a ball, but only for a limited amount of time since a jump. Being in the air by not jumping, or too long after jumping, has no air strafe. You can air strafe in the direction you're already rolling more effectively than other directions.

# Failure and Recovery

Movement fail states come in a few flavors. Bouncing is generally what happens when the player fails at movement and still has stamina. When they run out of stamina, they start a skid.

Tripping from a standstill gives the player a little boost upward and sends them into a bounce with no stun.

Landing at recoverable speeds and failing to recover, as well as running too fast, sends the player into a bounce.

Landing at extreme speeds splats/skids and probably kills the player.

Bouncing damages and stuns the player for an amount of health/time depending on impact speed and angle, even more than an additional bounce would take (does not stack impact stuns, but does stack damage and successive bounces). Landing like this bounces the player off angled terrain.

Skidding slows the player down at extreme friction until they come to a complete stop.

Recovering grants the player stamina/hubris.

## GROUND PARRY

If the player presses crouch when they land at recoverable speeds, they tech into a slide with a burst of momentum and increased hubris. Parrying a surface while looking orthogonal to the surface launches the player away from the surface.

When ground parrying from a standstill trip, the burst of momentum is larger.

## Trick Jumping

The player can perform a trick jump to recover.

# Charge // TODO

## Charge Jump

While charging, jumping causes a higher jump, higher than the high jump.

## Charge Dash

Charging a dash causes a faster dash.

## Charge Crouch



## UNREAL AIR

Performing a high jump when charged causes a charged high jump.

# Enemy Lock-on

When locked onto an enemy, dashing brings the player directly to them at a set time according to the fray.

# Jumps

If the player chains a jump after another jump, or performs a non-standard jump when hitting the ground or in the sliding/rolling states, they perform a "trick jump" and starts a combo meter that effectively caps at three. Each level of combo increases the effect of the jump, and gives the player hubris if it's a non-standard jump.

## Jump

The player adds momentum straight up and away from the surface.

There's air strafing.

Chaining jumps increases air strafe and height.

## Long Jump

If the player holds forward while trick jumping, they preserve momentum as if they bounce off of it, also gaining a boost.

Chaining long jumps increases speed boost.

## Backflip

If the player holds backward while trick jumping, they redirect momentum perpendicular the surface and a little bit backwards.

Chaining backflips increases height.

## Spin Jump

A twirl, not a cartwheel.

If the player holds to the side while trick jumping, they perform a regular jump but gain great horizontal air strafe relative to the player's current velocity.

Chaining spin jumps increases air strafe.

## Wall Jump

Wall jumping just does the same as all the other jumps.

# Pulling up ledges