[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283784&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

**Prerequisites:**

* **Operating System:** Windows 11 (Home, Pro, Education, etc.)
* **System Requirements:** VS Code is lightweight, but ensure you have enough disk space and a reasonable processor/RAM combination for smooth operation.

**Steps:**

1. **Download the Installer:**
   * Go to the official VS Code download page: [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
   * Click the "Download for Windows" button. This will download the installer file (usually a `.exe`).

2. **Run the Installer:**
   * Locate the downloaded file (usually in your "Downloads" folder) and double-click to run it.
   * You might see a User Account Control prompt asking for permission. Click "Yes" to proceed.

3. **Accept the License Agreement:**
   * Read through the license agreement and, if you agree, click "I accept the agreement" and then "Next."

4. **Choose the Installation Location:**
   * By default, VS Code will be installed in your user's AppData folder. You can choose a different location if desired. Click "Next."

5. **Select Start Menu Folder:**
   * Choose the Start Menu folder where the VS Code shortcut will be placed. Click "Next."

6. **Select Additional Tasks (Optional):**
   * These are optional but useful:
      * **Create a desktop icon:** Makes it easier to launch VS Code.
      * **Add to PATH:** Lets you open VS Code from your terminal/command prompt.
      * **Register Code as an editor for supported file types:** Opens compatible files directly in VS Code.
   * Choose the options you prefer and click "Next."

7. **Install:**
   * Review your choices, then click "Install" to begin the installation process.

8. **Launch VS Code:**
   * Once the installation completes, you can check the "Launch Visual Studio Code" box and click "Finish." This will open VS Code.

**Post-Installation Tips:**

Extensions may be added and VS Code can be customised to one's liking
Reference (Download Page: https://code.visualstudio.com/download
Documentation: https://code.visualstudio.com/docs)) 

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

After installing VS Code, adjusting certain configurations and settings can significantly enhance your coding experience.

**1. Theme and Appearance:**

* **Theme:** Choose a theme that suits your preferences and reduces eye strain. Popular choices include "One Dark Pro," "Material Theme," and "Dracula Official."
* **Font:** Select a clear and readable font like "Fira Code," "Cascadia Code," or "JetBrains Mono."
* **Font Size:** Adjust the font size to your comfort level for optimal readability.

**2. Essential Extensions:**

* **Language Support:** Install extensions specific to your programming language(s). Examples include "Python" for Python development, "C/C++" for C/C++ development, and "ESLint" for JavaScript linting. 
* **GitLens:** Supercharges your Git capabilities within VS Code, providing insights into code authorship, commit history, and blame annotations.
* **Prettier:** Automatically formats your code consistently, saving you time and ensuring a uniform code style.
* **Live Server:** Launches a local development server with live reload, allowing you to instantly preview changes made to HTML, CSS, and JavaScript files.
* **Bracket Pair Colorizer:** Colorizes matching brackets, making it easier to visually track code blocks.

**3. Editor Settings:**

* **Word Wrap:** Enable word wrap to prevent horizontal scrolling in long lines of code.
* **Auto Save:** Enable auto-save to automatically save your changes after a short delay or on focus change.
* **Tab Size and Indentation:** Set your preferred tab size (e.g., 2 or 4 spaces) and indentation style (tabs or spaces).
* **Minimap:** Enable the minimap for a high-level overview of your code structure.
* **Render Whitespace:** Enable this to visualize spaces and tabs in your code.

**4. Keyboard Shortcuts:**

* **Learn Essential Shortcuts:** Familiarize yourself with commonly used keyboard shortcuts to speed up your workflow.
* **Customize Shortcuts:** Adjust default shortcuts or create your own to match your preferences.

**References:**

* **VS Code Documentation:**
    * User and Workspace Settings: [https://code.visualstudio.com/docs/getstarted/settings](https://code.visualstudio.com/docs/getstarted/settings)
    * Extensions Marketplace: [https://marketplace.visualstudio.com/vscode](https://marketplace.visualstudio.com/vscode)

The best configuration is subjective and depends on your individual needs and preferences. Experiment with different settings and extensions to create an optimal coding environment that boosts productivity.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

The main components of Visual Studio Code's (VS Code) user interface (UI):

**1. Activity Bar (Leftmost Bar):**

* **Purpose:** The Activity Bar serves as your main navigation hub within VS Code. It provides quick access to different views and functionalities.
* **Icons:**  Each icon represents a view. Common icons include:
    * **Explorer:** Manage your files and folders (opening, creating, deleting, etc.).
    * **Search:** Search across your project for specific text or code snippets.
    * **Source Control:** Manage your Git repositories and track changes.
    * **Run and Debug:** Execute your code, set breakpoints, and inspect variables.
    * **Extensions:** Browse, install, and manage VS Code extensions.

**2. Side Bar:**

* **Purpose:** The Side Bar displays the contents of the currently active view from the Activity Bar. It provides more detailed information and actions specific to that view.
* **Examples:**
    * In the Explorer view, the Side Bar shows your project's file tree.
    * In the Search view, it displays search results.
    * In the Source Control view, it shows changes in your Git repository.

**3. Editor Group (Center Area):**

* **Purpose:** This is where the magic happens! The Editor Group is the main area for editing your code files. You can open multiple files simultaneously in separate tabs or split the editor into multiple sections to view different files side by side.
* **Features:** The Editor Group supports features like syntax highlighting, code completion (IntelliSense), linting (error checking), code formatting, and more.

**4. Status Bar (Bottom Bar):**

* **Purpose:** The Status Bar provides information about your current project and the active file. It also offers quick access to certain settings and actions.
* **Information Displayed:**
    * **Current line and column number:** Helps you navigate your code.
    * **File encoding:** Indicates the character encoding used for the file.
    * **Language mode:** Shows the selected programming language.
    * **Git branch:** Displays the current branch (if using Git).
    * **Errors and warnings:**  Indicates if there are issues in your code.
* **Actions:** Click on various elements in the Status Bar to:
    * Change the language mode
    * Switch Git branches
    * Toggle word wrap

**References:**

* **Visual Studio Code Documentation - User Interface:** [https://code.visualstudio.com/docs/getstarted/userinterface](https://code.visualstudio.com/docs/getstarted/userinterface)


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

**What is the Command Palette?**

The Command Palette is a powerful tool in VS Code that provides a central location to access all of the editor's commands, settings, and functionalities. It acts as a command line interface within the editor itself, allowing you to perform a wide range of tasks without having to navigate through menus or remember complex keyboard shortcuts.

**How to Access the Command Palette:**

There are two primary ways to open the Command Palette:

1. **Keyboard Shortcut:** The most common way is to press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS). This instantly brings up the Command Palette overlay.
2. **View Menu:** You can also access it through the "View" menu and select "Command Palette."

**Common Tasks Performed Using the Command Palette:**

The Command Palette is incredibly versatile. Here are some common tasks you can perform:

* **Opening Files:** Start typing the name of a file in your workspace, and the Command Palette will provide suggestions for quick navigation.
* **Executing Commands:** Type the name of any VS Code command (e.g., "Format Document," "Open Settings," "Install Extensions") to execute it directly.
* **Changing Settings:** Quickly search and modify any setting in VS Code's configuration.
* **Navigating to Symbols:** Jump to specific functions, classes, or variables within your code by typing their names.
* **Installing Extensions:** Search for and install extensions from the VS Code Marketplace directly.
* **Accessing Git Commands:** Perform Git operations like committing, pushing, pulling, and branching.
* **Debugging:** Start and manage debugging sessions.
* **Refactoring Code:** Rename symbols, extract methods or variables, and perform other refactoring actions.
* **Creating New Files or Folders:** Generate new files or folders within your workspace.
* **And Much More:** The Command Palette essentially gives you access to the entire functionality of VS Code.

**Example:**

To format a document using the Command Palette:

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P`).
2. Start typing "Format Document."
3. Select the "Format Document" command from the suggestions.
4. Your code will be automatically formatted according to your settings.

**References:**

* **VS Code Documentation - Command Palette:** 


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.


**Role of Extensions in VS Code:**

VS Code, at its core, is a powerful but streamlined code editor. Its true potential is unlocked through extensions. These extensions are like add-ons or plugins that provide extra features, tools, and integrations to enhance your development workflow. They cater to various needs:

* **Language Support:** Add support for different programming languages (e.g., Python, Java, C++, Go) with features like syntax highlighting, code formatting, debugging, and IntelliSense (code completion).
* **Linters and Formatters:** Enforce code style consistency and catch errors automatically with tools like ESLint, Prettier, and Stylelint.
* **Debugging Tools:** Extend VS Code's debugging capabilities for specific languages and frameworks.
* **Framework and Library Support:** Get integrated support for popular frameworks like React, Angular, Vue.js, or Django.
* **Themes and Icons:** Personalize the look and feel of your editor to match your preferences.
* **Productivity Tools:** Enhance your workflow with features like snippets, Git integration, and project management.
* **And Much More:** The VS Code Marketplace offers thousands of extensions for virtually any purpose imaginable!

**How to Find, Install, and Manage Extensions:**

1. **Finding Extensions:**
    * **Extensions View:** Click the Extensions icon on the Activity Bar (or press `Ctrl+Shift+X` / `Cmd+Shift+X`) to open the Extensions View.
    * **Search Bar:** Use the search bar to find extensions by name, keyword, or category.
    * **Marketplace:** Browse or search the VS Code Marketplace online: [https://marketplace.visualstudio.com/vscode](https://marketplace.visualstudio.com/vscode)

2. **Installing Extensions:**
    * **Extensions View:** Click the "Install" button next to the extension you want to install.
    * **Command Palette:** Press `Ctrl+Shift+P` / `Cmd+Shift+P`, type "Install Extensions," and search for the desired extension.

3. **Managing Extensions:**
    * **Extensions View:** Here, you can see a list of your installed extensions. Click the gear icon next to an extension to:
        * Disable/Enable it
        * Update it
        * Uninstall it
        * See its details

**Essential Extensions for Web Development:**

Here are some must-have extensions for web development:

* **Live Server:** Launches a local development server with live reload, making it easy to preview changes as you code.
* **ESLint:** Lints your JavaScript code to catch errors and enforce style guidelines.
* **Prettier:** Formats your code automatically for a consistent and clean look.
* **Auto Rename Tag:** Automatically renames paired HTML/XML tags.
* **CSS Peek:** Lets you quickly jump to CSS definitions for specific styles.
* **Debugger for Chrome:** Provides an integrated debugging experience for JavaScript in Chrome.
* **Vetur/Volar:** Provides excellent support for Vue.js development.
* **GitLens:** Supercharges Git integration in VS Code.

**References:**

* **VS Code Marketplace:** [https://marketplace.visualstudio.com/vscode](https://marketplace.visualstudio.com/vscode)
* **VS Code Documentation - Extensions:** [https://code.visualstudio.com/docs/editor/extension-marketplace](https://code.visualstudio.com/docs/editor/extension-marketplace)



6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

**How to Open the Integrated Terminal in VS Code:**

You have several options to open the terminal:

1. **Menu:** Click on `View` in the top menu, then select `Terminal`.

2. **Keyboard Shortcut:**
   * **Default:** `Ctrl+` (backtick) (Windows/Linux) or `Control+` (backtick) (macOS) 
   * **Alternative:** `Ctrl+Shift+` (backtick) (Windows/Linux) or `Cmd+Shift+` (backtick) (macOS) to create a new terminal instance.

3. **Command Palette:**
   * Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS)
   * Type "View: Toggle Terminal" and press Enter.

4. **Context Menu:** Right-click in the Explorer (file tree) and select "Open in Integrated Terminal."

**Using the Integrated Terminal:**

Once the terminal is open:

* **Run Commands:**  You can type any command you would normally use in your system's terminal, such as `cd` (change directory), `ls` (list files), `git` commands, and more.
* **Split Terminal:**  Split the terminal pane into multiple sections by clicking the split icon in the terminal tab bar.
* **Navigate Tabs:** Easily switch between different terminals by clicking the tabs or using shortcuts like `Ctrl+PageUp` and `Ctrl+PageDown` (Windows/Linux) or `Cmd+Option+Left Arrow` and `Cmd+Option+Right Arrow` (macOS).
* **Customize:** Right-click on the terminal or use the settings icon in the tab bar to customize the appearance and behavior of the terminal.

**Advantages of Using the Integrated Terminal Compared to an External Terminal:**

* **Convenience:** Seamlessly switch between your code editor and terminal without leaving VS Code.
* **Contextual Awareness:** The integrated terminal starts in your current project directory, simplifying file navigation.
* **Customization:** VS Code offers various options to customize the appearance and behavior of the terminal to suit your preferences.
* **Shell Integration:**  Seamlessly run VS Code commands and tasks (e.g., launching tasks defined in your project's `.vscode/tasks.json` file) directly from the terminal.
* **Copy and Paste:**  Easily copy and paste code snippets between the editor and terminal.
* **Integrated Debugging:** Debug your code directly within the VS Code environment.

**References:**

* **VS Code Documentation - Integrated Terminal:** [https://code.visualstudio.com/docs/terminal/basics](https://code.visualstudio.com/docs/terminal/basics)



7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
**Creating Files and Folders:**
There are several ways to create new files or folders in VS Code:
1. **Explorer Context Menu:**
   * Right-click on a folder in the Explorer sidebar (or in the main editor area if you have a file open).
   * Select "New File" or "New Folder" from the context menu.
   * Enter the desired name and press Enter.
2. **File Menu:**
   * Click on the "File" menu at the top.
   * Select "New File" or "New Folder."
   * Enter the name and press Enter. This will create the file/folder in your currently open workspace.
3. **Keyboard Shortcuts:**
   * For a new file: `Ctrl+N` (Windows/Linux) or `Cmd+N` (macOS)
   * For a new folder: No default shortcut exists, but you can create a custom one.
**Opening Files:**
1. **Explorer:** Double-click on a file in the Explorer sidebar to open it.
2. **Quick Open:** Press `Ctrl+P` (Windows/Linux) or `Cmd+P` (macOS), then start typing the file name to search and open it.
3. **File Menu:** Click on "File" > "Open File" (or "Open Folder" to open an entire project).
**Managing Files and Folders:**
* **Renaming:** Right-click on a file or folder and select "Rename."
* **Deleting:** Right-click and select "Delete" (or use the `Delete` key).
* **Moving:** Drag and drop files/folders within the Explorer sidebar.
* **Copying:** Right-click and select "Copy," then right-click in the destination folder and select "Paste."**Navigating Between Files and Directories:**
VS Code offers several efficient navigation options:

1. **Explorer:**
   * Use the file tree structure to visually navigate.
   * Expand/collapse folders by clicking on the arrows.
   * Use the search bar at the top of the Explorer to filter files/folders.
2. **Open Editors:**
   * Click the "Open Editors" view in the Activity Bar to see a list of currently open files.
   * Click on a file to switch to it.
   * Right-click on a file to reveal options like "Close," "Close Others," or "Close All."

3. **Quick Open:**
   * Use `Ctrl+P` (Windows/Linux) or `Cmd+P` (macOS) to search and open files by name.
4. **Go to Symbol:**
   * Use `Ctrl+Shift+O` (Windows/Linux) or `Cmd+Shift+O` (macOS) to search for and navigate to specific symbols (functions, classes, etc.) within a file.
5. **Breadcrumbs:**
   * Located at the top of the editor, breadcrumbs show the current file's path and allow you to quickly navigate to parent directories.
**References:**
* **VS Code Documentation - User Interface - Explorer:**
* **VS Code Documentation - File Handling:**
Settings and Preferences:
**Two Main Ways to Access Settings:**
1. **Graphical User Interface (GUI):**
   * Go to `File` (or `Code` on macOS) > `Preferences` > `Settings`.
   * This opens a user-friendly Settings editor, split into two panes:
     * **Default Settings (Read-Only):** Shows all available settings with their descriptions.
     * **User Settings (Editable):** Shows your current settings, which you can modify.
2. **`settings.json` File:**
   * Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
   * Type "Preferences: Open Settings (JSON)" and press Enter.
   * This opens your `settings.json` file directly, where you can edit settings in JSON format.
**Examples of Customization:**
* **Theme:**
    * **GUI:** Search for "Theme" in the Settings editor.
    * **`settings.json`:**
        ```json
        "workbench.colorTheme": "One Dark Pro"
        ```
* **Font Size:**
    * **GUI:** Search for "Font Size" in the Settings editor.
    * **`settings.json`:**
        ```json
        "editor.fontSize": 16 
        ```
* **Keybindings:**
    * **GUI:** Go to `File` (or `Code` on macOS) > `Preferences` > `Keyboard Shortcuts`.
    * **`keybindings.json`:** You can customize keybindings by modifying your `keybindings.json` file (opened via Command Palette). Here's an example to change the "Go to Definition" shortcut:
        ```json
        [
            { "key": "ctrl+f12",                "command": "editor.action.revealDefinition" },
        ]
        ```
**Important Notes:**
* **User vs. Workspace Settings:**
    * User settings apply globally to all your VS Code instances.
    * Workspace settings are stored in a `.vscode/settings.json` file within your project folder and override user settings for that specific workspace.
* **Search Functionality:**
    * Both the GUI and the `settings.json` file have a search bar to quickly find specific settings.
* **Additional Customization:**
    * Explore other settings like `editor.fontFamily` (font family), `editor.tabSize` (tab size), and `editor.wordWrap` (word wrap).
**References:**
* **VS Code Documentation - Settings:** [https://code.visualstudio.com/docs/getstarted/settings](https://code.visualstudio.com/docs/getstarted/settings)
* **VS Code Documentation - User and Workspace Settings:** [https://code.visualstudio.com/docs/getstarted/settings](https://code.visualstudio.com/docs/getstarted/settings)



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Steps for setting up and starting a debugging session in VS Code, along with some of its key debugging features:

**Steps to Set Up and Start Debugging:**

1. **Install a Debugger Extension:** VS Code doesn't come with a built-in debugger for specific languages. Install an extension appropriate for your language (e.g., "Python" for Python, "C/C++" for C/C++, "Debugger for Chrome" for JavaScript).

2. **Create a Configuration File (`launch.json`):**
   * Open the Run and Debug view (click the bug icon on the sidebar or press `Ctrl+Shift+D`/`Cmd+Shift+D`).
   * If you don't have a `launch.json` file yet, click the "create a launch.json file" link.
   * Choose your debugging environment (e.g., Python, Node.js, Chrome) from the dropdown. 
   * VS Code will generate a sample configuration file that you can customize.

3. **Configure Your Debugging Environment:** 
   * Fill in the required fields in `launch.json`, such as the path to your program file (`program`) and any arguments (`args`).
   * Adjust other settings as needed (e.g., setting environment variables, specifying the working directory).

4. **Set Breakpoints:** Click in the margin next to a line of code where you want the execution to pause.

5. **Start Debugging:** 
   * Click the green "Start Debugging" button or press `F5`.
   * VS Code will launch your program in debug mode.

**Key Debugging Features in VS Code:**

* **Breakpoints:** Pause execution at specific lines of code.
* **Stepping:**
    * **Step Over:** Execute the current line and move to the next.
    * **Step Into:** Enter the function call on the current line.
    * **Step Out:** Finish executing the current function and return to the caller.
* **Variables Inspection:** View the values of variables in the current scope during debugging.
* **Call Stack:** See the function call hierarchy to understand how you reached the current point of execution.
* **Debug Console:** Evaluate expressions, interact with your program, and view logging output.
* **Watch Expressions:** Monitor the values of specific variables or expressions as your program runs.
* **Conditional Breakpoints:** Pause execution only if certain conditions are met.
* **Example `launch.json` (Python):**

```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Python: Current File",
            "type": "python",
            "request": "launch",
            "program": "${file}",
            "console": "integratedTerminal"
        }
    ]
}
```

**References:**

* **VS Code Debugging Documentation:** [https://code.visualstudio.com/docs/editor/debugging](https://code.visualstudio.com/docs/editor/debugging)
* **Debugging in VS Code (video):**


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
How to integrate Git with VS Code for version control and manage your code effectively:

**Prerequisites:**

* **Git:** Ensure you have Git installed on your system. You can download it from the official Git website: [https://git-scm.com/](https://git-scm.com/)
* **GitHub Account (Optional):** If you want to push your changes to a remote repository on GitHub, you'll need a GitHub account.

**Integrating Git with VS Code:**

VS Code comes with built-in Git support, so you don't need to install any additional extensions. However, if you want enhanced features and visualizations, consider installing the official "GitLens" extension.

**Initializing a Git Repository:**

1. **Open Your Project Folder:** Open the folder containing your code in VS Code.
2. **Open the Source Control View:** Click the branch icon on the Activity Bar (or press `Ctrl+Shift+G` / `Cmd+Shift+G`).
3. **Initialize Repository:** If your project isn't already a Git repository, you'll see a button to "Initialize Repository." Click it. This creates a hidden `.git` folder in your project directory to track changes.

**Making Commits:**

1. **Stage Changes:** After making changes to your files, they'll appear in the "Changes" section of the Source Control view. Tick the checkbox next to each file you want to include in the commit.
2. **Commit Message:** Enter a clear and concise message describing your changes in the input box at the top.
3. **Commit:** Click the checkmark icon to create a commit.

**Pushing Changes to GitHub:**

1. **Connect to GitHub:** If you haven't already, connect your GitHub account to VS Code. Go to `File` (or `Code`) > `Preferences` > `Settings`, search for "GitHub," and sign in.
2. **Publish Repository:** If this is a new repository, click the ellipsis (...) button in the Source Control view and select "Publish to GitHub." Follow the prompts to create a new repository on GitHub and link it to your local repository.
3. **Push Changes:** Click the sync icon or use the `Ctrl+Shift+P` / `Cmd+Shift+P` shortcut to open the Command Palette and type "Git: Push" to push your local commits to the GitHub repository.

**Other Git Operations in VS Code:**

* **Pulling Changes:** Use the sync icon or "Git: Pull" command to pull changes from the remote repository.
* **Branching:** Create, switch, and merge branches from the Source Control view or Command Palette.
* **Viewing History:** Explore your commit history, see diffs between versions, and revert to previous states.
* **Resolving Conflicts:** VS Code provides tools to help you resolve merge conflicts.

**References:**

* **VS Code Documentation - Version Control:** [https://code.visualstudio.com/docs/sourcecontrol/overview](https://code.visualstudio.com/docs/sourcecontrol/overview)
* **VS Code Documentation - Git Support:** [https://code.visualstudio.com/docs/sourcecontrol/intro-to-git](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)

With these steps and resources, you'll be well-equipped to harness the power of Git for version control within VS Code.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

