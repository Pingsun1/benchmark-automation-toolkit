# Tool 1 – Automated Benchmark Trigger

## Purpose
Automates repeated in-game benchmark execution and triggers CapFrameX to start FPS capture for each run. FPS data is captured by CapFrameX and saved as JSON files for later processing.

## Workflow
1. Tool launches and controls repeated in-game benchmark runs  
2. At the start of each benchmark run, the tool triggers CapFrameX to begin FPS capture  
3. The benchmark completes automatically  
4. CapFrameX generates FPS data as JSON output files  

## Pre-work / Setup
Before running the tool, complete the following setup:

- Set the game window mode to **Borderless Windowed**
- Set **Windows display scaling** to **100%**
- Capture a screenshot of the **“Again”** button only (button area only, no background)
- Save the file as `again.png`
- Place it in the **same folder as the executable** (Documents folder)
- Copy `MarvelRivals.exe` to the **Documents** folder

## Benchmark Execution Steps
1. Launch **Marvel Rivals** and **CapFrameX**
   - Ensure CapFrameX is in **Ready** state
2. Manually complete **one benchmark run**
   - Stop at the page where the **“Again”** button is visible
3. Double-click `MarvelRivals.exe`
4. Ensure the **game window is the active foreground window**
   - Use **Alt + Tab** if necessary
5. Close File Explorer
6. Press **Ctrl + Alt + Win + A** to start automation
7. Allow the system to run automatically
   - The benchmark will execute **9 runs**
   - CapFrameX will be triggered automatically at the start of each run
8. Press **Ctrl + Alt + Win + Q** to stop the script if needed

## Output
- FPS data is captured by CapFrameX
- Results are saved as **JSON files**
- These JSON files are used as input for **Tool 2 (JSON → TSV processing)**

## Notes
- Requires CapFrameX to be installed and configured
- Currently supports **Marvel Rivals**
- Designed for hands-free, repeatable benchmark execution



