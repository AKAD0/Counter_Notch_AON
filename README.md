# Minimal AON for Notch Neutralization.
A little research for F/A-18 and F-14 made together with Volley - the highly competent F-14 fan (Discord: Volley#8970).

# Concept.
Calculating AON for specific TAS that would be the lowest for Lead Pursuit in terms of guaranteed radar tracking.

• Angles lower than calculated would conceal target within doppler filter (radar will struggle to track).

• Angles higher than calculated would neutralize notch.

# Results.
Result data for F/A-18, F-14:

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/FA-18.png)

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/F-14.png)

# Used Data.
For each aircraft there is a corresponded set of telemetries for plain sea and ground where aircrafts move towards each other at 90 degrees.

Tacview files provided.

# Method.
Problem solved by law of cosines applied to velocity vectors.

Reference maths:

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/math.png)
