# Organizing your work and knowledge
## Projects
Projects are ideal for storing knowledge Claude should reference, organizing related chats around a specific topic or work area, and collaborating with team members who need access to the same shared context.
 * Self-contained workspaces with their own memory, chat histories, knowledge bases, and customized instructions. 
 * Project knowledge enhances Claude's understanding
 * Project instructions guide Claude's behavior
 * Projects scale automatically

When to use projects?
Projects are particularly valuable when you're working on something ongoing.
When have a workflow with:
* Reference materials you'll use repeatedly (meeting notes, reports, historical data, etc)
* Consistent requirements for how Claude should respond (always use formal language, always cite sources, always follow our template)
* Team collaboration needs where multiple people should work from the same foundation

Best practices for projects:
* Start focused, then expand.
* Keep your knowledge base current. Remove outdated knowledge, update the project knowledge periodically
* Write clear instructions. Be specific about what you want.
* Group related documents (helps Claude to create connections between references)
* Reference documents by name 

Collaboration features:
* Permission levels: Can View, Can Edit, Owner

How projects handle large knowledge base?
* Projects automatically scale to handle large amounts through a feature called Retrieval Augmented Generation (RAG).
---
## Artifacts
What are artifacts?
* Artifacts are standalone, interactive outputs that Claude creates in a dedicated window alongside your conversation.
Claude automatically creates an artifact when content meets certain criteria:
* It's significant and self-contained, typically over 15 lines
* It's something you're likely to want to edit, iterate on, or reuse
* It represents complex content that stands on its own without needing the surrounding conversation
* It's content you'll want to reference or use later

Common artifact types:
* Documents (md, plain text, etc): Great for text heavy type, like meeting notes, reports, plans
* Code snippets: Working code for programming languages
* HTML pages: Complete web pages with HTML, CSS, and JavaScript in a single file.
* SVG images
* Mermaid diagrams: Flowcharts, sequence diagrams, Gantt charts, org charts, and more. Describe the relationships you want to visualize, and Claude will create a diagram you can refine.
* React components: Interactive UI elements with real functionality

Creating artifact:
Creating an artifact is as simple as having a conversation.
For example: "Create a flowchart showing our customer onboarding process"

Getting the most from Artifact:
* Be specific about what you want.
* Describe the end user. Telling Claude who will use the artifact helps it make appropriate design choices.
* Iterate incrementally. Add one feature or make one change at a time.
* Request artifacts when needed.
---
## Skills
What are Skills?
* Skills are folders of instructions, scripts, and resources that Claude loads dynamically to improve performance on specialized tasks.("Expertise Packages" that teach Claude how to complete certain tasks in repeatable way)

Types of Skills:
* Anthropic Skills: Create and maintained by Anthropic.
* Custom Skills: The skills created for specialized workflows and domain-specific tasks. 

Using Skills:
Claude handles skill selection automatically based on the request.

Security considerations:
Skills can include executable code, it's important to use them thoughtfully:
* Only install custom Skills from trusted sources
* Custom Skills you upload are private to your individual account
* Anthropic's built-in Skills are tested and maintained by Anthropic
* Review its contents before use when installing custom skills from an internal source

Creating custom skills:
Custom Skills let you teach Claude your specific workflows, brand guidelines, and ways of working.
The Skills can be created through Claude's conversation:
* Start a new chat and tell Claude what you want to create.(1)
* Answer Claude's questions (2)
* Upload references materials (templates, style guides, brand assets, etc)
* Download the Skills
* Upload the Skills to settings

Project vs Skills
* Project: store knowledge. It holds reference materials for Claude (project specs, meetiong nodes, documents, etc). Store knowledge Claude references
* Skills: perform tasks. Skills are procedural machines. "How Claude execute a task": order of operatisons, methodology that follows every time (Repeatable workflows). Define processes Claude executes
 

