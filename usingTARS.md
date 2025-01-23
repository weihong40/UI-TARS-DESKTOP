# Using UI-TARS: A Comprehensive Guide

UI-TARS is a powerful native GUI agent that can interact with your computer's interface through screenshots and perform human-like interactions using keyboard and mouse operations. This guide will help you understand how to effectively use UI-TARS after installation.

## Getting Started

1. **Launch UI-TARS**
   - Start the application using one of these commands:
     ```bash
     pnpm dev          # Development mode with hot reload
     pnpm start        # Production preview
     pnpm debug        # Debug mode with DevTools
     ```
   - The system will initialize and prepare the visual perception model
   - After launch, you'll see the UI-TARS interface with:
     - A command input area for typing instructions
     - A visualization panel showing what UI-TARS sees
     - A status indicator showing the agent's current state
     - An action log displaying recent operations

2. **First Steps After Launch**
   - The agent will ask for necessary permissions (screen recording, accessibility)
   - Grant these permissions when prompted
   - UI-TARS will perform an initial screen scan to understand your desktop layout
   - You can now start giving commands through the input area

3. **Giving Your First Command**
   - Start with a simple task like "Open Chrome"
   - Watch how UI-TARS:
     1. Identifies the Chrome icon
     2. Moves the cursor
     3. Performs the click action
   - Observe the visualization panel to see what UI-TARS recognizes

4. **Command Structure**
   Use natural language commands in these formats:
   ```
   "Open [application name]"
   "Click on [element description]"
   "Type [text] into [field description]"
   "Find and click [button/link text]"
   ```

## Understanding the Interface

UI-TARS operates by taking screenshots of your screen
- It processes these images to understand GUI elements and their context
- The agent can perform mouse clicks, keyboard inputs, and complex interactions

## Core Capabilities

### 1. Visual Understanding
- UI-TARS can understand:
  - Button locations and their functions
  - Text fields and input areas
  - Menu items and navigation elements
  - Complex UI hierarchies
  - State changes in the interface

### 2. Task Execution
UI-TARS can handle various types of tasks:
- Navigation through applications
- Form filling and data entry
- Button clicking and menu selection
- Complex multi-step operations
- Cross-application workflows

### 3. Interaction Methods
The agent uses:
- Mouse operations (clicks, drags, scrolls)
- Keyboard inputs
- Combined keyboard-mouse actions

## Best Practices

1. **Clear Task Description**
   - Be specific about what you want to achieve
   - Break complex tasks into smaller steps
   - Provide necessary context when switching applications

2. **Monitoring Progress**
   - Watch the agent's actions to ensure correct execution
   - Be ready to interrupt if needed
   - Verify results after task completion

3. **Error Handling**
   - If UI-TARS encounters an error, it will:
     - Provide feedback about the issue
     - Attempt to recover or suggest alternatives
     - Wait for user guidance if needed

## Common Use Cases

1. **Application Navigation**
   ```
   Example: "Open Chrome and navigate to my bookmarks"
   ```

2. **Settings Configuration**
   ```
   Example: "Change the background color in PowerPoint"
   ```

3. **File Operations**
   ```
   Example: "Create a new folder and move selected files into it"
   ```

## Advanced Features

### System-2 Reasoning
UI-TARS employs deliberate reasoning for complex tasks:
- Task decomposition
- Milestone recognition
- Reflection thinking
- Error recovery

### Learning from Experience
- The system learns from successful interactions
- Improves performance over time
- Adapts to user preferences

## Troubleshooting

If UI-TARS is not performing as expected:

1. **Check Visual Access**
   - Ensure the screen is visible
   - Avoid overlapping windows
   - Maintain clear contrast

2. **Task Clarity**
   - Rephrase commands if unclear
   - Break down complex tasks
   - Provide additional context

3. **System Resources**
   - Check system performance
   - Ensure sufficient memory
   - Monitor CPU usage

## Tips for Optimal Use

1. **Clear Screen Organization**
   - Keep your desktop organized
   - Minimize unnecessary windows
   - Use consistent layouts

2. **Task Planning**
   - Plan complex operations
   - Have necessary applications ready
   - Prepare required files beforehand

3. **Performance Optimization**
   - Close unnecessary applications
   - Maintain system resources
   - Regular system maintenance

## Safety and Limitations

1. **User Control**
   - Always maintain oversight
   - Ready to interrupt operations
   - Verify critical actions

2. **Data Safety**
   - Backup important files
   - Review automated changes
   - Monitor system modifications

## Getting Help

If you need assistance:
1. Check the documentation
2. Review common use cases
3. Contact support for complex issues

## Command Interface

### Main Input Area
- A clean, modern text input area where you type your instructions
- Placeholder text: "What can I do for you today?"
- Press `Enter` to execute commands (no need to hold Shift or Cmd/Ctrl)
- The interface shows your previous command while executing

### Status Indicators
- Running status shows when UI-TARS is executing a task
- Progress indicators show current action and thought process
- Error messages appear if something goes wrong
- Share button appears after completing tasks to export session reports

### Quick Launch
- Use the launcher interface for quick commands
- Type commands and press `Enter` to execute
- Press `Escape` to close the launcher
- The launcher remembers your previous commands

### Available Actions
UI-TARS can perform these specific actions:
```
click: Click on a specific element
left_double: Double-click on an element
right_single: Right-click on an element
drag: Drag from one location to another
hotkey: Execute keyboard shortcuts
type: Enter text (use \n to submit)
scroll: Scroll in any direction
wait: Wait for changes (5 seconds)
```

### Example Commands
1. Navigation:
   ```
   "Open Chrome and go to github.com"
   "Switch to the previous tab"
   ```

2. Interface Interaction:
   ```
   "Click the Settings button"
   "Scroll down to the bottom of the page"
   "Type my email address into the login form"
   ```

3. Complex Tasks:
   ```
   "Download the latest version of VS Code"
   "Create a new folder on the desktop named 'Projects'"
   "Take a screenshot and save it to Downloads"
   ```

## Technical Capabilities and Performance

UI-TARS achieves superior performance in GUI automation through its sophisticated architecture:

### Performance Benchmarks
- **OSWorld Tasks**: 
  - 24.6 score with 50 steps
  - 22.7 score with 15 steps
  - Outperforms other models including GPT-4V
- **AndroidWorld**: 
  - Achieves 46.6 score
  - Significantly higher than GPT-4V's 34.5

### Key Technical Advantages
1. **Enhanced Visual Understanding**
   - Dense captioning of UI elements
   - State transition tracking
   - Specialized UI element description
   - Set-of-Mark (SoM) prompting technique

2. **Standardized Action System**
   - Unified action space across platforms
   - Precise coordinate-based interactions
   - Learned from large-scale action traces
   - Standardized action parsing

3. **Advanced Reasoning**
   - GUI-specific tutorial integration
   - Milestone-based task decomposition
   - Reflection mechanisms
   - Complex task planning

4. **Adaptive Learning**
   - Online trace bootstrapping
   - Reflection-based improvements
   - Experience retention
   - Continuous performance optimization

These capabilities enable UI-TARS to handle complex GUI tasks more reliably and efficiently than traditional automation approaches.

---

Remember that UI-TARS is designed to be intuitive and adaptive. With practice, you'll develop a natural workflow for interacting with the agent and maximizing its capabilities. 