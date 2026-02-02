# Benchmark Automation Toolkit

## Overview
This project automates repeated in-game benchmarks, triggers CapFrameX to start FPS capture at each run, and batch-processes the resulting FPS data into Excel-compatible TSV files.

## Tools Included

### Tool 1 – Automated Benchmark Trigger
- Runs in-game benchmarks multiple times automatically
- Triggers CapFrameX to start FPS capture at each benchmark run
- FPS data is captured by CapFrameX and saved as JSON files

### Tool 2 – FPS Result Processing (JSON → TSV)
- Batch-processes CapFrameX-generated JSON files
- Performs FPS calculations 
- Outputs results as `.TSV` files compatible with Excel  
- Designed for environments where Excel may not be installed or licensed

## Supported Games
- Marvel Rivals (current)

## Requirements
- Windows
- CapFrameX installed and configured

## Disclaimer
This is a personal project and is not affiliated with any employer.
