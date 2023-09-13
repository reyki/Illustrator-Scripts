# Illustrator-Scripts
Ultimately maximizing efficiency and productivity in Adobe Illustrator.

---
## CloseAllPaths (Modified)

[Download](https://github.com/reyki/Illustrator-Scripts/blob/main/closeAllPaths.jsx)


This script is a modification of the original "WR-closeAllPaths" script created by Wolfgang Reszel (ai-js@rumborak.de). The original script's purpose is to close open paths in Adobe Illustrator. This modified version enhances the functionality to close both filled paths and paths with strokes (also stroke with fill).

The Illustrator Join Path Script enhances the functionality of the native CTRL+J (Cmd+J on macOS) command, allowing you to seamlessly join paths while preserving the current path's bezier handles and information. This script intelligently connects endpoints using the selected item's bezier details, ensuring precise and controlled path joining in Adobe Illustrator. Streamline your workflow and maintain creative control with this powerful path manipulation tool.


### How to Use the Script

Follow these simple steps to use the Illustrator Join Path Script:

1. **Select the Paths:**
   - Using the Selection Tool, select the paths you want to join.

5. **Run the Script:**
   - Go to `File` > `Scripts` > `Other Script...`.
   - Choose the script file (`CloseAllPaths.jsx`) and click `Open`.

6. **Watch It Work:**
   - The script will automatically join the selected paths while preserving bezier handle information.

7. **Review the Result:**
   - Examine the joined paths and make any further adjustments as needed.

### Function:

The script automates the process of closing open paths in Adobe Illustrator. It works in two modes:

- **All Paths Mode:** It closes all open paths within the current Illustrator document, whether they are filled shapes or paths with strokes.

- **Selected Paths Mode:** It closes open paths among the selected objects in the Illustrator document, also considering both filled paths and paths with strokes.

-  **Close all Open Paths inside Clipping Mask:** It closes all open paths within clipping masks.

### Limitation:
- If multiple paths from different objects are selected, it will close the currently selected chosen paths.
