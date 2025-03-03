<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: João Su
**Date**: 26-02-2025
**Product**: Google Keep

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|Writing a note provides clear real-time feedback | 0            | No changes needed. |
|Has a lateral bar that to communicates its state in the app | 0            | No changes needed. |
| Deleting a note   | 2            | The delete button could be more intuitive by using a visible icon instead of requiring users to press the "More" option.               |
| Cloud syncing feedback  | 1            | Display a syncing indicator to show progress.                |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|The archive feature may not be immediately clear  |     2        |	Rename or provide a brief tooltip explaining the archive function.                |
| The reminder feature follows real-world scheduling but could be more visually distinct.   |     1        |	Improve visibility by using a calendar-style layout for better recognition.                |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|  |             |                |
|   |             |                |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Some icons (e.g., the archive button) are not labeled, which may confuse new users. | 2            |    	Add optional text labels or tooltips for better clarity.            |
| The placement of the delete option under the "More" menu   | 2            |   Move the delete button to a more visible location, such as the bottom toolbar.             |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| There is no confirmation before deleting a note, making accidental deletions easy. | 3            |    Add a confirmation dialog or allow users to enable/disable confirmation in settings.            |
| The recovery period in the trash is only 7 days |  2        | Provide a longer period               |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The search function lacks filters for easier retrieval of notes based on categories like labels, checklists, or images. | 2            |Add advanced search filters to help users quickly find specific notes without recalling exact details.                |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The app does not allow users to create custom shortcuts or automate repetitive actions. | 2            | Introduce customization options for shortcuts and actions to improve workflow efficiency.               |

# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The note interface can feel visually overwhelming when many notes are displayed, especially without clear separation or organization. | 3            | Provide more layout customization options, such as collapsible sections or different note view styles.               |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|  |             |                |
|   |             |                |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|Help documentation is not directly accessible from the app interface, requiring users to search for it online. | 2            | 	Add a visible "Help" or "Support" section within the app for quick access to documentation.               |

