Contents
=============

#### - [Introduction to Gemini CLI](https://blog.naver.com/qbxlvnf11/223999168942)

#### - [Gemini CLI Git](https://github.com/google-gemini/gemini-cli)


How to Setup & Run (Linux, vscode etc.)
=============

### - Install Gemini CLI

   <details>
   <summary>Install using <a href="https://brew.sh/">Homebrew</a></summary>
     
```
# Install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo >> /home/{account_name}/.bashr
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/{account_name}/.bashrc
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
sudo apt-get install build-essential
brew --version
# Install Gemini CLI
brew install gemini-cli
```
   </details>

   <details>
   <summary>Install using <a href="https://www.npmjs.com/">npm</a></summary>

```
npm install -g @google/gemini-cli
# Install Gemini CLI (Preview version)
npm install -g @google/gemini-cli@preview
# Install Gemini CLI (Stable version)
npm install -g @google/gemini-cli@latest
# Install Gemini CLI (Nightly version)
npm install -g @google/gemini-cli@nightly
```
   </details>
   
### - Run Gemini CLI in Terminal

   <details>
   <summary>Run Commands & Parameters</summary>

```
# Start in current directory
gemini
# Include multiple directories
gemini --include-directories ../lib,../docs
```
   </details>

### - Run Gemini in vscode

   <details>
   <summary>Run Commands & Options</summary>

   * - Install [Google Cloud Code](https://marketplace.visualstudio.com/items?itemName=GoogleCloudTools.cloudcode) in Extensions

   </details>

### - Authentication Options of Gemini CLI

1. OAuth login (Using your Google Account)
   * Individual developers as well as anyone who has a Gemini Code Assist License.
2. Gemini API Key
3. Vertex AI
     
<img width="608" height="395" alt="Image" src="https://github.com/user-attachments/assets/ae61db96-3492-4785-903a-b97ae4ee00b1" />


Commands
=============

   <details>
   <summary>Help</summary>
      
```
│ Basics:                                                              │
│ Add context: Use @ to specify files for context (e.g.,               │
│ @src/myFile.ts) to target specific files or folders.                 │
│ Shell mode: Execute shell commands via ! (e.g., !npm run start) or   │
│ use natural language (e.g. start server).                            │
│                                                                      │
│ Commands:                                                            │
│  /about - show version info                                          │
│  /auth - change the auth method                                      │
│  /bug - submit a bug report                                          │
│  /chat - Manage conversation history.                                │
│    list - List saved conversation checkpoints                        │
│    save - Save the current conversation as a checkpoint. Usage:      │
│ /chat save <tag>                                                     │
│    resume - Resume a conversation from a checkpoint. Usage: /chat    │
│ resume <tag>                                                         │
│    delete - Delete a conversation checkpoint. Usage: /chat delete    │
│ <tag>                                                                │
│  /clear - clear the screen and conversation history                  │
│  /compress - Compresses the context by replacing it with a summary.  │
│  /copy - Copy the last result or code snippet to clipboard           │
│  /corgi - Toggles corgi mode.                                        │
│  /docs - open full Gemini CLI documentation in your browser          │
│  /directory - Manage workspace directories                           │
│    add - Add directories to the workspace. Use comma to separate     │
│ multiple paths                                                       │
│    show - Show all directories in the workspace                      │
│  /editor - set external editor preference                            │
│  /extensions - list active extensions                                │
│  /help - for help on gemini-cli                                      │
│  /ide - manage IDE integration                                       │
│  /init - Analyzes the project and creates a tailored GEMINI.md file. │
│  /mcp - list configured MCP servers and tools, or authenticate with  │
│ OAuth-enabled servers                                                │
│    list - List configured MCP servers and tools                      │
│    auth - Authenticate with an OAuth-enabled MCP server              │
│    refresh - Restarts MCP servers.                                   │
│  /memory - Commands for interacting with memory.                     │
│    show - Show the current memory contents.                          │
│    add - Add content to the memory.                                  │
│    refresh - Refresh the memory from the source.                     │
│  /privacy - display the privacy notice                               │
│  /quit - exit the cli                                                │
│  /stats - check session stats. Usage: /stats [model|tools]           │
│    model - Show model-specific usage statistics.                     │
│    tools - Show tool-specific usage statistics.                      │
│  /theme - change the theme                                           │
│  /tools - list available Gemini CLI tools. Usage: /tools [desc]      │
│  /settings - View and edit Gemini CLI settings                       │
│  /vim - toggle vim mode on/off                                       │
│  /setup-github - Set up GitHub Actions                               │
│  /terminal-setup - Configure terminal keybindings for multiline      │
│ input (VS Code, Cursor, Windsurf)                                    │
│  ! - shell command                                                   │
│                                                                      │
│ Keyboard Shortcuts:                                                  │
│ Alt+Left/Right - Jump through words in the input                     │
│ Ctrl+C - Quit application                                            │
│ Ctrl+J - New line (Alt+Enter works for certain linux distros)        │
│ Ctrl+L - Clear the screen                                            │
│ Ctrl+X - Open input in external editor                               │
│ Ctrl+Y - Toggle YOLO mode                                            │
│ Enter - Send message                                                 │
│ Esc - Cancel operation / Clear input (double press)                  │
│ Shift+Tab - Toggle auto-accepting edits                              │
│ Up/Down - Cycle through your prompt history                          │
│                                                                      │
│ For a full list of shortcuts, see docs/keyboard-shortcuts.md         │
```

   </details>
   

Author
=============

#### - [LinkedIn](https://www.linkedin.com/in/taeyong-kong-016bb2154)

#### - [Blog URL](https://blog.naver.com/qbxlvnf11)

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com

