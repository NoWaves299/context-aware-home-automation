# Context-Aware Home Automation

This project is a modular home automation system built around Home Assistant and a Raspberry Pi.
It integrates lighting, heating, environmental sensors, and wearable input to create context-aware
behaviour rather than simple time-based automation.

## Goals
- Build a safe, low-voltage-first smart home system
- Use context (sleep, presence, activity) instead of rigid schedules
- Separate system design from deployment
- Document decisions clearly

## Architecture Overview
- Central controller: Raspberry Pi running Home Assistant
- Sensors: ESP32-based motion, pressure, and CO₂ sensors
- Actuators: Philips Hue, Hive thermostat, smart plugs
- Wearable input: Garmin Fēnix 7X Pro via webhook buttons

## Status
Design and offline development in progress.
Deployment to physical devices will be completed in the UK.
