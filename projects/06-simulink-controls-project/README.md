# XY Motion Control in MATLAB/Simulink

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
