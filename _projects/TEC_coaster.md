---
title: Thermoelectric Effect Coaster
excerpt: Waste heat recovery from hot beverages to power electronics
thumbnail: /assets/images/projects/TEC_coaster/TEC_coaster_CAD.JPEG
date: 2021-09-01
permalink: /projects/TEC_coaster/
layout: splash
---

# Thermoelctric Effect Coaster

<figure style="margin: 0 auto; display: flex; flex-direction: column; align-items: center; max-width: 600px;">
  <img src="/assets/images/projects/TEC_coaster/TEC_coaster_CAD.JPEG"  
       alt="CAD model of coaster setup"  
       style="width: 100%; height: auto;">
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    CAD model of coaster setup
  </figcaption>
</figure>

This project was my attempt to make a coaster that can charge my phone with the waste heat from my morning oatmeal. The device consists of an aluminum coaster plate and four 40mm thermoelectric generator (TEG) units connected in a 2s2p configuration. The TEGs are attached to heat sinks and suspended over a water reservoir. Setting a hot beverage or bowl on the coaster plate creates a thermal gradient across the TEGs, which produces electrical current due to the Seebeck effect. The current is fed through a DC-DC step-up voltage convertor and into a USB port that can be connected to an electronic device. Using a hot mug to generate a temperature difference of approximately 65°C produces the voltage output plotted below. This energy is enough to charge an iPhone 11 for about two minutes (or about 1-2% of battery capacity).

<figure style="margin: 0 auto; display: flex; flex-direction: column; align-items: center; max-width: 600px;">
  <img src="/assets/images/projects/TEC_coaster/voltage_data.jpg"  
       alt="Voltage over time"  
       style="width: 100%; height: auto;">
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
    Plot of voltage over time in 2s2p configuration
  </figcaption>
</figure>

In the future, I would like to add more TEGs, monitor output current, and experiment with series and parallel configurations to increase the total energy generated. Using a thermal interface material between the aluminum plate and the TEGs could also help transfer more heat from a hot container to the device.
