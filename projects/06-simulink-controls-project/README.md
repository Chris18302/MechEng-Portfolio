# XY Motion Control in MATLAB/Simulink

**Portfolio status:** Supplemental controls archive — relevant to feedback-control fundamentals, but not featured because generic XY motion control is less directly aligned with my BAS/BMS and HVAC-controls targets than a building-controls project would be.

## Executive Summary

Tuned a MATLAB/Simulink feedback-control model for XY trajectory tracking, increasing controller gains from an initial low-response setup to improve tracking behavior. Example tuning explored **P = 30, D = 3, N = 40**. The project demonstrates controller tuning and error-response concepts, but it does not yet show building-system sequences, sensors/actuators, alarms, trends, or functional testing.

## Objective

Improve desired-versus-actual XY trajectory tracking using feedback control.

## Actions

- Worked with a Simulink feedback-control model.
- Adjusted proportional and derivative controller parameters.
- Compared response behavior as gains changed.
- Evaluated tracking quality and controller-response trade-offs.

## Key Engineering Trade-Off

Higher gains can improve tracking, but aggressive tuning can also increase overshoot, sensitivity, noise amplification, or unstable behavior depending on the system. Controller tuning therefore requires balancing speed, accuracy, and robustness.

## Current Result

The tuned setup improved tracking compared with the initial low-gain condition, but the public project currently lacks quantitative error metrics and plots.

## Skills Demonstrated

MATLAB · Simulink · Feedback control · Controller tuning · Tracking error · Dynamic systems

## Hiring-Manager Test Questions

1. What did increasing P change in the response?
2. What did the derivative term contribute?
3. What does N represent in the derivative-filter implementation?
4. How would you quantify tracking improvement?
5. Why is this not yet equivalent to BAS/DDC control work?

## Why It Is Not Featured

For my target BAS/BMS and commissioning roles, a stronger project would use HVAC equipment, sensors, setpoints, deadbands, alarms, trend logs, sequences of operation, and functional tests. This project will remain as supplemental controls evidence until that replacement exists.
