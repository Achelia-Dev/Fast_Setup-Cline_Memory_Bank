# Fast_Setup-Cline_Memory_Bank
This is just for easy&fast setup to use cline memory bank prompt for any agent ai.
Normally, Cline's memory is reset at each session, but thanks to the Memory Bank, markdown files containing important project information are loaded at each new session, allowing Cline to resume from where it left off.
Memory Bank works best when your starting context is lean.

Cline Memory Bank
Search for rules from your IDE.
If it doesn't exist
Create a AGENTS.md file
Paste the system prompt into the AGENT.md file 

Finally write your agent to

Read the AGENTS.md file, complete the tasks within it, and ask questions about any parts that are unclear or that you don't understand.


If you are using Cline for Agent 
Copy this into custom instructions or a .clinerules file:
Ask Cline to “initialize memory bank”

                  Core Files
    File	                              Purpose
projectbrief.md	          Foundation document with core requirements and goals
productContext.md	  Why the project exists, problems it solves, UX goals
activeContext.md	  Current focus, recent changes, next steps (updates most frequently)
systemPatterns.md	  Architecture, design patterns, component relationships
techContext.md	          Tech stack, setup, constraints, dependencies
progress.md	          What works, what’s left, known issues


                                               Key Commands
“follow your custom instructions” - Tells Cline to read Memory Bank and continue where you left off
“initialize memory bank” - Creates the initial structure for a new project
“update memory bank” - Triggers a full documentation review and update




                                         Working with Plan & Act Modes
Memory Bank pairs naturally with Plan & Act mode:
Plan mode: Start here when resuming a project. Ask Cline to read the Memory Bank, review the current state, and discuss strategy before making changes.
Act mode: Switch to Act mode once you have a plan. Cline retains everything from the planning session and can implement changes.


                                 When your context window fills up:
Ask Cline to “update memory bank” to document the current state
Start a new conversation
Ask Cline to “follow your custom instructions”
This preserves important context in your Memory Bank files before the window clears, letting you continue seamlessly in a fresh conversation.




Cline’s built-in commands offer more targeted options:
/smol compresses your conversation history while keeping you in the same task. Use this when you want to free up space without starting over.
/newtask distills key decisions, file changes, and progress into a fresh task with a clean context window. This is like a developer handoff that preserves what matters.
  



Enable Auto-Compact to let Cline automatically compress context as you work. This reduces how often you need to manually manage the context window, though you should still update the Memory Bank after significant milestones.

<img width="912" height="132" alt="image" src="https://github.com/user-attachments/assets/8bdd6f45-944d-4f31-8724-bb47c20f791b" />










