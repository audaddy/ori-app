# Operator Readiness Intelligence (ORI)

A squadron-level biometric readiness tool built at the Rainier Spark Lab, 62d Airlift Wing, McChord AFB.

ORI aggregates data from Garmin, Oura Ring, and Apple Health into a unified dashboard and AI-powered readiness brief — giving operators and leaders a fast, actionable GO / CAUTION / NO-GO status based on real biometric data.

## Features
- Guided device setup wizard (Garmin MCP, Oura OAuth, Apple Health export)
- Live readiness dashboard — Body Battery, HRV, sleep, resting HR, circadian alignment
- Claude-powered AI chat for natural language readiness queries
- Unit view showing aggregate GO/CAUTION/NO-GO status across a flight
- Runs entirely in the browser — no backend, no data storage

## Built With
- Vanilla HTML/CSS/JS — single file, zero dependencies
- Garmin Connect via [garmin.amalgama.co](https://garmin.amalgama.co) MCP
- Oura Ring API v2 (OAuth2)
- Anthropic Claude API

## Part Of
Rainier Spark Lab innovation portfolio — AMC pathfinder effort supporting operator readiness, circadian health, and human performance optimization.
