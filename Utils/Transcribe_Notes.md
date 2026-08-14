## Purpose
Staff often have handwritten notes from site visits, meetings, or in person convenings that are easily not incorporated in the Grants Management System, file storage system, or project management system. Important insights or follow up tasks may get lost. Your job is to synethsize notes and provide a structured output.
## When to Use
Deploy this skill when staff ask for help with notes.
## When NOT to Use
There are currently no limits on this tool.
## Required Inputs and Context
- Ask staff for type of meeting. Common answers might b:e Site Visit, Team Meeting, Partnership Meeting, Docket Review Meeting, or Grantee Convening.
- Ask staff for format of meeting notes (or draw conclusions based on files provided). Common formats include: Personal handwritten notebook, large flipchart paper (with multiple writers), or a printed agenda with handwritten notes in the margin. You should be able to handle any type of notes within these categories or others.
- Ask staff to upload meeting notes as a photo or a photocopy. Photocopied notes are a bit more effective.
- Ask staff to provide any other information that will be helpful, including the original meeting agenda, attendees, time/date/location, artifacts, outputs, reports, etc. If the meeting type is "Site Visit" ask for Site Visit Questions. If the meeting type is "Grantee Convening" ask for agenda.

## AI Workflow
I am a [role][program officer/director/senior leader] at a philanthropic foundation in [city] and want to transcribe my handwritten notes from a site visit with an applicant.  

Follow the instructions below for each meeting. There may be one meeting or many meetings included in the materials. 

First, provide the raw transcription of the handwritten notes. Flag any words that are difficult to read with [unclear]. 

Next, provide structured notes using the outline below: 

- Meeting information (Name of applicant, Date, Meeting Attendees) 

- Responses to specific site visit questions (see attached list of questions). Show the full question text above the corresponding answer notes. If a note does not correspond to a site visit question, include it under ‘Other Key Points’ rather than forcing it into a question response. 

- Overview of other key points not captured above 

Next, provide clarifying questions.  

Finally, append the photo of the source notes to the end of the structured notes doc. This is for future verification.

This is the end of instructions for each meeting instance. Repeat these steps for all of the meetings present in the materials. 

Finally, provide a summary of the number of meetings that you processed and any flags that may be relevant to the review process. 

Additional instructions: 

Tone: professional, not formal 

Format: Bullet points, abbreviations, and shorthand are acceptable. Brevity is appreciated. 

Scope: Only draw from the source materials in this chat. Do not make assumptions based on outside knowledge.  

Sequence: Images are provided in order. Treat them as continuous notes unless otherwise indicated. If notes cover more than one meeting, produce a separate output file for each. If one meeting has more than one page of notes, combine the notes according to the meeting instance that the notes correspond to. 

Skip: Do not include text that has been crossed out in source materials.

Confidence: If anything is unclear, complete the summary as best you can and list clarifying questions. Note any unclear words or concepts with [unclear].  

## Output Format
Once the summary is complete, produce a separate output file (.md) for each applicant so that the structured notes can be easily copied and saved. The Output File should only contain the Structured Notes component of the total output. 

Append the photo of notes to the end of the output file.

## Human Review or Decision Points
Ask staff member to review notes for accuracy and resolve any inconsistencies before producing the final output file.

## Quality Checklist
- Do the number of notes output files match the number of meeting instances?
x- Does the first output file conform to information related to the first meeting instance, and the next output file include information only from that meeting instance?
- Does every piece of information in the final note output file appear in the source files or in additional context provided by the staff?
- Are there any remaining [uncertain] flags that have not been resolved?

## Examples

