# Counter Notch AON
A little research for F/A-18 and F-14 made together with Volley - the highly competent F-14 fan (Discord: Volley#8970).

# Concept
Here are presented pursuit parameters (TAS, AON) that guarantee fighter to counter bandit's notch within lead pursuit.

For current TAS:

• AON lower than specified degree would cause lose tracking (closing is within doppler filter's MLC).

• AON higher than specified degree would counter notch (closing is out of doppler filter's MLC).

# Results
Result data for F/A-18, F-14:

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/FA-18.png)

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/F-14.png)

# Used Data
MLC* (F/A-18) ≈ 70kn

MLC* (F-14) ≈ 111kn

For each aircraft there is a corresponded set of telemetries** for plain sea and ground where aircrafts move towards each other at 90 degrees.

*MLCs were found empirically as a mean for both cases of sea and hill deck with acceptable variance no higher than 10kn.

**Tacview files provided.


# Method
Problem solved by law of cosines applied to velocity vectors.

Reference maths:

![alt text](https://github.com/AKAD0/Edge_Tracking_Angle/blob/main/images/math.png)
