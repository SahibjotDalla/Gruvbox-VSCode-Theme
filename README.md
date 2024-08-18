## Custom VSCode Theme Setup

Enhance your VSCode experience with a customized theme! Follow these steps to apply your custom VSCode theme using the **_Dark Gruvbox With Italics_** theme and **_Custom CSS and JS Loader_** extension.

![Custom Theme](https://github.com/user-attachments/assets/a5675120-165d-4e17-8f24-1000f21a4090)

### 🛠️ Prerequisites
1. **Dark Gruvbox With Italics** Theme:  
   Download and install the **_Dark Gruvbox With Italics_** theme from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=sagaban.dark-gruvbox-with-italics).

2. **Custom CSS and JS Loader**:  
   Download and install the **_Custom CSS and JS Loader_** from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css).

### 📂 Setup Instructions

1. **Move Files:**
   - **On Windows**:
     - Move your `settings.json` and `custom-vscode.css` files to `%APPDATA%\Code\User\`.
   - **On macOS**:
     - Move your `settings.json` and `custom-vscode.css` files to `$HOME/Library/Application Support/Code/User/`.

2. **Configure `settings.json`:**
   - Open `settings.json` in your VSCode configuration folder.
   - Scroll to the bottom of the file (around line 72).
   - Add the path to your `custom-vscode.css` file. Use the following format:
     - **For Windows**:  
       ```json
       "vscode_custom_css.imports": ["file:///C:/Users/Sahib/AppData/Roaming/Code/User/custom-vscode.css"]
       ```
     - **For macOS**:  
       ```json
       "vscode_custom_css.imports": ["file:///Users/Sahib/Library/Application%20Support/Code/User/custom-vscode.css"]
       ```

3. **Enable Custom CSS and JS:**
   - Open VSCode and press `Ctrl + Shift + P` to open the Command Palette.
   - Type `Enable Custom CSS and JS` and press `Enter`.
   - Restart VSCode to apply the changes.

4. **Reload Custom CSS and JS (if necessary):**
   - If you don’t see the changes immediately, press `Ctrl + Shift + P` again.
   - Type `Reload Custom CSS and JS` and press `Enter`.
   - Restart VSCode to apply the changes.
   - If the issue persists, double-check that the file path in `settings.json` is correct.

If you’re still having issues with the **_Custom CSS and JS Loader_**, check out the [official troubleshooting guide](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) for additional help.

And that's it! Your custom VSCode theme should now be active and looking great. Enjoy your personalized coding environment!
