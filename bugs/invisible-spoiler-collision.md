# Invisible Spoiler Collision on Enus Paragon S

Status: Reproducible  
Frequency: High  

## Description
The rear spoiler of the Enus Paragon S does not render visually, but its collision remains active. This results in interaction with an invisible object.

## Steps to Reproduce
1. Spawn or obtain Enus Paragon S  
2. Observe rear of the vehicle  
3. Notice spoiler is not visible  
4. Stand on the rear of the car  
5. Shoot towards the back window  

## Expected Result
- Spoiler should be visible if collision exists  
- Bullets should pass through rear window if unobstructed  

## Actual Result
- Spoiler is invisible  
- Player stands on invisible surface  
- Bullets are blocked by invisible object  

## Severity
Medium (Visual + Collision Mismatch)

## Notes
- Collision model remains active despite missing visual model  
- Affects both interaction and shooting behavior  
