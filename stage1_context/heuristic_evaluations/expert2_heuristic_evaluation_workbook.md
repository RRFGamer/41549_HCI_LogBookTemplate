<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Rúben Franco
**Date**: 05-03-2024
**Product**: Google Keep


Severity Scale adopted: [here](severity_scale_heuristic_evaluation.md)
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                      | **Severity** | Recommendation |
| ---------------------------------------------- | ------------ | -------------- |
| Writing to a new note shows text in note body. | 0            | N/A            |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                                     | **Severity** | Recommendation                           |
| ------------------------------------------------------------- | ------------ | ---------------------------------------- |
| Notes can be dragged like real sticky notes.                  | 0            | N/A                                      |
| However, notes can't be dragged to labels, Archive and Trash. | 3            | Allow dragging notes to mentioned items. |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                                                                                                    | **Severity** | Recommendation                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------- |
| Deleting notes from Trash requires a second confirmation.                                                                    | 0            | N/A                                                                                             |
| Moving notes to trash pops a brief, small notification with undo button on the bottom left of the screen.                    | 2            | Move the notification to a commonly used area or replace note with notification itself briefly. |
| A new note can't be "cancelled". The only way to cancel a new note is to clear ALL text, including title, and then close it. | 3            | Add a new button to cancel note.                                                                |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**                                                                                           | **Severity** | Recommendation |
| --------------------------------------------------------------------------------------------------- | ------------ | -------------- |
| Pinned notes are presented first, clearly seperated.                                                | 0            | N/A            |
| Notes keep their position after closing and opening app again.                                      | 0            | N/A            |
| A Trash can keeps deleted notes for 7 days.                                                         | 0            | N/A            |
| Keyboard navigation uses some "vim" keybindings: "j"/"k" for next/previous note, and "/" to search. | 0            | N/A            |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**                             | **Severity** | Recommendation |
| ------------------------------------- | ------------ | -------------- |
| Deleted notes are moved to the Trash. | 0            | N/A            |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**                                                                                           | **Severity** | Recommendation |
| --------------------------------------------------------------------------------------------------- | ------------ | -------------- |
| The button to change a note's color is a color palette.                                             | 0            | N/A            |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**                                                                                                 | **Severity** | Recommendation                                                                               |
| --------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------- |
| Labels can be added to notes as visible text: #<label>, which looks different than labels added normally. | 2            | When a label is added as #<label>, the text should be removed and the label added as normal. |
| Keyboard controls does not feature bidimensional navigation, only "next" and "previous" note.             | 3            | Default controls use "vim" keybindings. Extend controls with "h" and "l".                    |

# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**                                                                              | **Severity** | Recommendation                                                                            |
| -------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------- |
| "Open-sources licenses" button is visible, although faintly, and outside of main area. | 1            | Create a dedicated "About" page with information about product, including mentioned item. |

# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                                                   | **Severity** | Recommendation                      |
| ----------------------------------------------------------- | ------------ | ----------------------------------- |
| Help is always located in the settings menu.                | 0            | N/A                                 |
| Help has a search prompt, but does not search in real time. | 2            | Update search results in real time. |
