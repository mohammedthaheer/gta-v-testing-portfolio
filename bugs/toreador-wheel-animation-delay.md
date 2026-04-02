# Wheel Rotation Delay After Submersible Transition (Toreador)

Status: Reproducible  
Frequency: Medium–High  

## Description
After switching the Toreador vehicle from submersible mode back to standard driving mode, the wheels do not rotate for several seconds despite the vehicle moving.

## Steps to Reproduce
1. Use Toreador in water or land (submersible mode)  
2. switch back to vehicle mode  
3. Start driving immediately  
4. Observe wheel behavior  

## Expected Result
Wheels should rotate immediately when vehicle starts moving  

## Actual Result
Vehicle moves, but wheels remain static for ~5 seconds before rotating  

## Severity
Medium–Low (Animation Delay / Visual Inconsistency)

## Notes
- Occurs consistently when transitioning from water to land  
- Indicates delayed synchronization between movement and animation systems  
