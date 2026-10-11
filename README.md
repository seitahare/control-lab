# control-lab

> Control theory experiments in C, including PID loops and simulated actuators.

**Status:** Planned — roadmap only. No implementation has been claimed.

## Goal

Make a simulated system track a target predictably and measure control quality.

## Available / suggested hardware

No hardware required at first; external encoder-equipped motor can be a later upgrade.

## MVP (first demonstrable result)

1. Build a simple first- or second-order simulated plant with an adjustable target.
2. Implement a discrete-time P controller, then PI and PID.
3. Plot target, measured state, error, and control output.

## Next milestones

- [ ] Explore saturation, integral windup and anti-windup.
- [ ] Measure overshoot, settling time and steady-state error.
- [ ] Control a simulated pendulum or motor model; only later move to external motor hardware.

## Skills to learn

- Feedback loops
- Sampling interval and discrete control
- PID tuning, stability and noise
- Actuator limits

## Connections to other repositories

- **sim-engine:** provides physical systems that the controller can regulate.
- **teleop-lab:** provides safe command limits and tracking behavior.
- **robot-hand:** supports later actuator-position control experiments.

## Important scope note

A hobby SG90 servo already contains an internal position controller; sending angle commands is not the same as implementing motor PID from scratch.

## Definition of done for MVP

- [ ] A reproducible demo or data output is committed.
- [ ] README explains how to run it.
- [ ] At least one validation result, plot, photo or screenshot is included.

## License

License to be selected before redistributing code.
