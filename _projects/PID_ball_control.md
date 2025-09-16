---
title: Two-axis PID Control of Rolling Ball
excerpt: Controlling the rolling motion of a ball on a pan-tilt platform
thumbnail: /assets/images/projects/PID_ball_control/IMG_6953.JPEG
date: 2021-10-01
permalink: /projects/PID_control/
layout: splash
---

# Two-axis PID Control of Rolling Ball

<figure style="margin: 0 auto; display: flex; flex-direction: column; align-items: center; max-width: 600px;">
  <img src="/assets/images/projects/PID_ball_control/IMG_6953.JPEG"  
       alt="Two-axis PID control table"  
       style="width: 100%; height: auto;">
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    Two-axis PID control table
  </figcaption>
</figure>

This project demonstrates dynamic control of a pan-tilt platform such that positional control of a rolling ball is achieved. The control mechanism consists of a glass plate actuated by two servo motors and controlled by a microcontroller running a PID control algorithm. Ball detection is done using a CMUcam5 object recognition camera. The system is resistant to disturbances and has been tuned to attempt to approach critical damping. For dynamic setpoints, position is interpreted through an exponential moving average filter to ensure smooth object tracking.

<div style="margin: 2em auto; display: flex; flex-direction: column; align-items: center; max-width: 640px;">
  <video width="640" height="360" controls>
    <source src="{{ '/assets/images/projects/PID_ball_control/IMG_6957_trim.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    Stationary setpoint position control (center of plate)
  </figcaption>
</div>

<div style="margin: 2em auto; display: flex; flex-direction: column; align-items: center; max-width: 640px;">
  <video width="640" height="360" controls>
    <source src="{{ '/assets/images/projects/PID_ball_control/IMG_6959.MP4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    Dynamic setpoint position control (circle around plate center)
  </figcaption>
</div>
