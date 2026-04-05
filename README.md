## Easy Demo Control CFG

> **Usage:** type `exec democtrl` in console  
> **Restore:** press `x` on your keyboard or type `democtrl_exit` in console

### Controls
*  **Pause/Play:** `Caps Lock`
*  **Fast Forward:** `F1` - `F6`
*  **Slow Motion:** `1` - `6`
*  **Open DemoUI:** `R`
*  **Spec Certain Player:** `E`
*  **Reset Spec Target:** `0`
*  **Restore Keys:** `x`

## IFile Management Notice

Due to Source Engine's security restrictions, the game client cannot physically delete files from your hard drive. This configuration uses `host_writeconfig` to create a temporary backup of your settings.

To prevent configuration conflicts and ensure a clean environment for your next session, **it is highly recommended to manually delete the backup file after you finish watching the demo.**

### How to Manually Clean Up
1. Navigate to your TF2 configuration folder:
   `...\Steam\steamapps\common\Team Fortress 2\tf\cfg\`
2. Locate and delete the file named: **`democtrl_restore`**

> **Note:** If left in the folder, this file may contain stale aliases or settings that could interfere with your default configuration during future updates or changes.
