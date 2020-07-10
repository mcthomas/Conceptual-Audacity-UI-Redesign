<img src="audacity-logo.png" width="300"/>

# Conceptual-Audacity-UI-Redesign
A conceptual UI overhaul and redesign for Audacity, to demonstrate principles in UX &amp; UI design as they relate to human-computer interaction.  This project comprises several group projects that I led in academia.

## Contents

  - [Introduction](#Introduction "Introduction")
  - [Paper Prototype Ideation](#Paper-Prototype-Ideation "Paper Prototype Ideation")
  - [Design Discussion](#Design-Discussion "Design Discussion")
  - [User Assumptions](#User-Assumptions "User Assumptions")
  - [Audacity Redesign Analysis](#Audacity-Redesign-Analysis "Audacity Redesign Analysis")
  - [Final Paper Prototype Component Sketches](#Final-Paper-Prototype-Component-Sketches "Final Paper Prototype Component Sketches")
  - [Prototype Models / Diagrams / Sequences](#Prototype-Models-/-Diagrams-/-Sequences "Prototype Models / Diagrams / Sequences")
  - [Usbility Flow & Evaluation](#Usbility-Flow-&-Evaluation "Usbility Flow & Evaluation")
  - [Elementary Action Flow for Digital Prototype](#Elementary-Action-Flow-for-Digital-Prototype "Elementary Action Flow for Digital Prototype")
  - [Interactive Digital UI Prototype](#Interactive-Digital-UI-Prototype "Interactive Digital UI Prototype")
  - [Redesign in VR](#Redesign-in-VR "Redesign in VR")
 


## Introduction

Audacity is a cross-platform, free and open source digital audio editor (DAW). Functionally, this DAW boasts track recording and exporting of multiple sources, (including MIDI) playback, and post processing/editing of all types of audio.  Many digital effects and plug-ins are also included, in addition to multitrack mixing and audio spectrum analysis.  Despite being fully featured, it’s UI is notoriously clunky. Specifically it suffers unintuitive front-end design decisions and a blatantly cluttered and outdated visual aesthetic that favors skeuomorphism over contemporary, flat graphic design.  This results in navigation confusion and lowered confidence with respect to ease of use for new users, which includes novice music producers as well as those who are more experienced.  Specific problems and design opportunity needs include: 

- There is no “New Project” or “Welcome” screen to greet the user
- Tracks need placeholders and visual cues within the workspace window
- Track headers aren’t easily moved and making selections is not visually intuitive or clear
- Effects library and EQ settings need dedicated view panels
- Many of the track view options are unclear and potentially unnecessary as toolbar buttons
- Trimming tracks should be easily accomplished with mouse and click movements
- Tracks should be visually identified and categorized with their input type, and labels should maximize and resize for non-default view options
- The pin function is functionally unintuitive and complicates the track timeline
- Generally, functionality needs to be moved from the menu bar and mapped to the toolbar and interface margins with intuitive hideaway/show icons and descriptive visuals 
- A lower panel for smart EQ controls that correlate to the selected track would improve selection clarity
- Effects should be applied in a modular fashion, such that their presence and scope is visually indicated in the track view
- Generations should be visually scalable and not just quantified from the get-go
- Improving the UX would make the workstation much more approachable and intuitive for beginner and seasoned producers, as it is otherwise highly functional.  The contextual inquiry will be conducted in the user’s home context or preferred typical workspace, on their computer.

## Paper Prototype Ideation


<img src="paper-proto-draft1.png" width="600"/>


<img src="paper-proto-draft2.png" width="600"/>


## Design Discussion

Improved visual indication and gesture control were at the forefront of comparison criteria we took into account when comparing our two sketches, as our contextual inquiries demanded such improvements. Visual indicators encompass both the application of effects and generations in their respective context panes as well as basic status indicators for tracks as they appear in the main project view preview.  One design change we’d like to implement from sketch #1 is the inclusion of the mixer controls, possibly in a lower panel pane.  This would more clearly lay out each track’s basic control parameters to build an aesthetic that is more musically-metaphorical.  Another such need we’ve settled upon is to streamline the approach to basic track manipulation tools, such as selections and trimming.  Rather than having to cycle them with skeuomorphic, small iconed buttons, sketch #2 envisions how they could be supplemented with mouse pointer indicators that present as the user hovers over specific track recordings’ surfaces.  This will minimize the unnecessarily cluttered tool and option selections surrounding the project view.  Beyond ease of view, this will increase the likelihood of appropriate function use rather than best-known workarounds for common tasks.  Other redesign ideas we’d like to implement from sketch #2 include modularly-stacked effect and generation indicators within the track header view.  This would allow the user to make late-term effect tweaks after they’re been applied to tracks, in the lower pane, which makes the entire process feel less “final” from the getgo.  Including those (color coded) lines spanning the tracks to correlate the selected effects will improve visual clarity.  And in the context of parameterizing the effects, we could introduce visual adaptations of decibel magnitude, variable time, etc. with analogue graphs and particle effects rather than non visually-descriptive numeric fields.  

Furthermore, seeing color coded track portion indicators for the effects and generations would more easily indicate what was already manipulated.  Another overhaul from the second sketch was mapping the zoom tool to the trackpad/mouse wheel.  Though we still included the buttons as an optional override.  With respect to the track view, we’d like to collapse the size to remove bloat, as indicated in both sketches.  The track headers may coincide with the adaptation chosen for sketch #2.  Along the top of the project window, sketch #2 indicates BPM and time signature indicators to help more traditional musicians feel accomodated.  One final de-cluttering concept materialized in sketch #2 is the + and - buttons.  These UI elements are all-inclusive functions for expanding dropdowns/side expansions for adding new tracks, effects, generations, or even a new project.  Other menubar parameters may be grouped into these functions at some point.  We are confident that all of these changes, which were almost entirely selected from sketch #2 (which we’ve chosen as the preferred model design, for the reasons previously mentioned) in tandem with the aesthetic overhaul should begin to remedy some of the problem areas we observed among the participants’ experiences with the given tasks.

## User Assumptions

### User 1: Seasoned musician, new to DAWs

User 1 is an experienced performer and studio musician, however the user lacks experience in digital music production and is poorly equipped with basic computer skills.  User1, however,  is looking to experiment with music production.  Without prior knowledge in navigating through a digital audio workstation, user 1 needs an extremely approachable and intuitive user interface.

### User 2: Moderately experienced producer

User 2 would have a certain expectation of how a DAW is supposed to look and function.  User 2 would constantly compare Audacity to popular DAWs in the market like Ableton Live Suite, Studio One, Logic pro etc.  Since user 2 is moderately experienced with music production, the fundamental functionalities in Audacity should not come off as completely foreign to user 2.  The main concern is the outdated appearance and user interface, which will probably negatively affect the user experience through unfamiliar unease of use. Additionally, Audacity lacks advanced functions available in modern DAWs,however this is beyond the scope of our assignment. 


## Audacity Redesign Analysis

   Devising scenarios for evaluating the most critical deficiencies within Audacity was not easy, especially through the medium of direct observation with minimal intervention. The goal was approached with the intent of evaluating user comfort with panel tools, effects dropdowns, and mouse-click movements within the workspace pane. Covering all this ground was best accomplished with tasking as simply as possible. This helps to isolate the most common trouble points through repeated behaviors and patterns amongst all three participants of our three contextual inquiries. With the video recordings and careful notes, the hope was to identify these trouble points and begin assessing the most intuitive remedies with respect to user interface missteps and functional locality across the span of submenus and keybindings. Reflecting on these findings should enable us to adopt the most effective redesign approach and subsequent strategies for later product improvement to improve human interactions and the overall experience with Audacity.
   
   Given that Audacity is a digital audio workstation, there had to be real time audio recorded of some sort for manipulation by the user. We settled on vocal recordings of spoken words to keep samples consistent and to ensure the input edits can be easily cross-compared with respect to user interaction. Before initiating these recordings, the participant must frequently create new projects, new tracks, and new recordings. The idea was to see if even the most rudimentary tasks were accomplished identically every time, or differently for ease of use between all three inquiries. Any hesitation with these tasks, or attempts to accomplish them with separate keybindings or context menus, had to be observed for indications of unintuitive design at even the most basic level. As the user began to record their voice, it was carefully observed as to whether there was a lack of assurance regarding the input source, as well as knowledge of the audio actually being captured. Luckily the default setting was already bound to the internal mic and the track preview had a decibel graph. However, seeing the subsequent assurance experienced after the recording was notable for indicating a potential need for stronger visual indicators of the current recording configuration. Beyond this most basic tasking, trimming audio tracks was a frequent function required of the user. This was especially notable in seeing how users deliberated between actually using the trim tool control as apposed to making incremental selections and deleting them with menubar controls or keybindings. The breakdown between user tendency and hesitation in this respect was significant. The presentation of the workspace as the largest pane view seemed to encourage a visual approach to editing. It was for this reason that we believe users found it more favorable and intuitive to drag selections in the timeline rather than seek out the trim tool in the toolbar. 
   
   Other tasks, such as renaming or deleting individual tracks entirely, was fairly easy for the users since these options could be identified and changed directly on the track header sidebar. With respect to effects, we chose to assess menubar navigation and the associated context panes by asking the user to change track portions’ pitches and speeds. Applying the effects didn’t initially seem well understood to the users with respect to their permanence or their expected prevalence in the track, based solely on just the numeric fields and dropdown options allotted before applying. This resulted in a few attempts and undos before they were satisfied with their approach to the task. Moreover, undo was used (both from the “edit” menubar option and the keybinding) heavily as a band-aid for frequent mouse-clicks and for reapplying effects. This was a very common indicator of accidental errors such as collapsing the track preview, applying an effect with inaccurate parameters, zooming too far in one direction, etc. On the topic of the zoom tool, it was a parallel occurrence. The user easily zoomed in too far and had to either pan back to the desired portion of the timeline for cutting or effects, or undo their action. This was made more difficult by the stubborn autoscroll function, which wasn’t a user action that could be simply undone when trying to isolate a starting point of cutting or inserting track portions. The discontinuities that disallowed seamless visual editing, as a consequence of parameterized context panes for effects and other functions, helped us reflect on which aspects of Audacity need to be reassessed and redesigned.
   
   Improved visual indication and gesture control are among two of the most critical aspects of potential redesign that our contextual inquiries seemed to call for. Visual indicators encompass both the application of effects and generations in their respective context panes as well as basic status indicators for tracks as they appear in the main project view preview. One such need we’ve identified is to streamline the approach to basic track manipulation tools, such as selections and trimming. Rather than having to cycle them with skeuomorphic, small iconed buttons, they should have mouse pointer indicators that present as the user hovers over specific track recordings’ surfaces. This is just one opportunity to minimize the unnecessarily cluttered tool and option selections surrounding the project view. Beyond ease of view, this would increase the likelihood of appropriate function use rather than best-known workarounds for common tasks. Other redesign ideas we’ve reflected on include modularly-stacked effect and generation indicators within the track header view. This would allow the user to make late-term effect tweaks after they’re been applied to tracks, which makes the entire process feel less “final” from the getgo. And in the context of parameterizing the effects, we could introduce visual adaptations of decibel magnitude, variable time, etc. with analogue graphs and particle effects rather than nonvisually-descriptive numeric fields. Furthermore, seeing color coded track portion indicators for the effects and generations would more easily indicate what was already manipulated. Another obvious redesign demand is mapping the zoom tool to the trackpad/mouse wheel. Such a simple action shouldn’t require clicking one of two small UI buttons every time. Making all of these changes in tandem with an aesthetic overhaul should begin to remedy some of the problem areas we observed among the participants’ experiences with the given tasks.
   
## Final Paper Prototype Component Sketches


### UI Components


<img src="paper-proto-components.png" width="600"/>


### Primary View


<img src="paper-proto-main.png" width="600"/>


## Prototype Models / Diagrams / Sequences

### Affinity Diagram

<img src="affinity-diagram.png" width="600"/>

### Sequence Model

#### Title: creating a simple audio track, changing pitch, and exporting file as .mp3

##### Intent: Add a new stereo track
##### Trigger: wants to find record button 
User searches for a big red button
User clicks on the big red button and starts recording
User clicks on the big red button again to stop recording

##### Intent: change the pitch of a segment of the recording
##### Trigger: wants to highlight a segment of the recording
User hovers cursor over the start of the segment
User holds down left button and drags across the recording to the end of the segment
User lets go of left mouse button

##### Trigger: Wants to find pitch alteration function
User searches for the effects drop down menu from the top control panel
User clicks on the drop down menu to expand it
User searches for a pitch alteration function
User finds it and left clicks it

##### Trigger: Pitch alteration interface popped up, user wants to change pitch
User drags a vertical/ horizontal slide button to change pitch
User clicks on a “play” button on the interface to listen to the altered audio segment
User is satisfied and clicks on the “confirm” button on the interface 

##### Intent: export file as MP3
##### Trigger: wants to pull up “export” interface
User searches the left most side of the top control panel for “project” drop down menu and left clicks it
User searches for export button, and left clicks it

##### Trigger: User wants to export recording as mp3
User clicks on the default file name and retypes the desired file name
User clicks on the drop down menu below the file name bar and searches for .mp3, then clicks it
User clicks confirm on the bottom right of the “export” interface

##### Task complete

### Physical Model

<img src="physical-model.png" width="600"/>

### Flow Model

<img src="flow-model.png" width="600"/>

### Artifact Model

<img src="artifact-model.png" width="600"/>

### Cultural Model

<img src="cultural-model.png" width="600"/>


## Usbility Flow & Evaluation

### Action Flow for Paper Prototype

From the welcome screen, please open an existing project from the welcome screen, called “Sample Project"
- Now, trying creating a new track, for this project, and then rename it to “Bass”
- Next, please proceed as though you were to record a bass lick with the “input 1” selected for that
new track we’ve just created
- Now, trim this new recording on your new track to about half the recorded size. You may accomplish
this with a UI button, or with just the mouse
- Next, add a pitch effect to the vocals track, and then select that effect from the track header and bend
the recording’s pitch to a higher pitch in the effect parameter pane
- Now, please delete the guitar track entirely
- Next, please adjust the EQ of the piano track to decrease treble presence and increase bass presence,
by manipulating the EQ after selecting the piano track
- Now, please try to increase the volume of the bass track a bit, in its track header
- Next, try moving the timeline cursor to the beginning of the timeline
- Finally, save the project by selecting the appropriate UI button
- Please export the project as an mp3 file by selecting yet another UI button

Hesitations, breakdowns, and any other indications of difficulty are to be accompanied by questions that both inquire the nature of the confusion, be it layout or design choice aesthetic, as well as to help guide the user toward the correct selection, which further evaluates are design intent through the user’s response to these rhetorical questions.

#### Feedback & Critical Incidence

<img src="critical-incidence.png" width="300"/>

#### Reflection

The primary changes we made to our prototype, with the aid our findings from Part A, including new UI buttons for the trimming, (2) export, (4) time shift, and multi tool functions.  We also adopted a new carousel approach to effect pane displays, (5) to allow multiple to be selected at once on a track for better effect parameter multitasking.  As critically isolated in our usability test flow, we are confident that the trimming and export UI button symbols we’ve refined will much better manifest their function as being apparent to the user.  We maintained their location on the interface, as we believe the edit tools are best correlated together and apart from the UI buttons for manipulating project component presence.  That being said, the scissors icon should be more obviously correlated with its trimming functionality, and likewise for the export icon as arrowing from the document sub-icon.  These two UI button replacements will be most relevant in observing for improvement in our next usability test since they are directly called for within the user’s task instructions.

## Elementary Action Flow for Digital Prototype

When a user opens the program, they will be greeted with a welcome screen that asks them if they would like to start a new project or open an existing project. Once a project is open, whether it’s new or existing, the user can create new tracks by clicking the “+” button and selecting “Create New... Track.” With a new track created, the user can begin a recording. After having various recordings present, the user can edit them with certain effects. To add a new effect to a recording, the user simply selects the certain recording they wish to edit, clicks the “+” button, clicks on“Create New... Effect,” and select their desired effect, such as “Change pitch” or “Change speed.” All of the related parameters are present along the bottom of the project view and pertain to the current track selected. Once the user is completed with their session, they can save the project by clicking the save icon. If the user has finished editing their project to their liking and would like to share it, they can export their recordings by clicking the export button, naming their file, and selecting their desired file choice such as “.mp3” or “.wav.” The user can exit the workstation by clicking on the exit in the corner. If the user tries to exit with an unsaved project open, they will be asked if they would like to save before exiting.

Currently, our InVision prototype allows the user to navigate to view a sample project, or to create a new project.  On the new project screen, the user can open the “export” dialogue drop down menu, and close it, or that of the “+” (new) UI button.  If the user selects “Track” in this latter sub menu, they will see a new track header present.  Hitting the record UI button will then populate a new recording.

## Interactive Digital UI Prototype

### Select the gif below to navigate to the InVision prototype:



## Redesign in VR



### Introduction

Our problem domain exists where musicians lack the means to effectively integrate their setup with their DAW.  All too often, musicians must opt to break their concentration and workflow in putting their instrument aside to access their laptop or tablet device.  Access to the DAW is currently exclusive, by design, to desktop application interfaces.  While intended to be as seamless as possible, sometimes even with integration with external peripherals and controllers, we believe that there is an opportunity here for semi-translucent overlays in both augmented and virtual reality that functionally adapt our current desktop prototype.  Adapting to this medium presents opportunities to engineer novel interfaces, which has the potential to reimagine music production more seamlessly than ever.  

### Limitations and Adapatations for VR

#### Rather than the finer editing features of our current interface, we’ve found that initiating recordings and selecting different tracks to update the current selection is a bit cumbersome in how it breaks the immersion of free-flowing audio recording.  Other limitations were brought to our attention by heuristic evaluations completed by our peers.  This feedback informed limitations that may be most effectively remedied by this virtual reality adaptation.  Some of these items include:

- Our help button doesn’t detail quick tips for hovering over UI elements 
This presents an opportunity to use hand gestures to track UI element selections for foreground detailing, almost like flipping a flashcard right in front of the user. 

- A positive, our minimalist approach, is already well suited for a VR overlay adaptation
This indicates that an overlay approach in virtual reality won’t necessarily obstruct visibility of the musician’s instrument, pedals, or otherwise to keep the entire experience interconnected but relatedly differentiated as a sort of “on-screen hud.”

- Lower panels for effects and generation parameters are not necessarily intuitively paired to the active track
In taking advantage of the spatial availability of a user’s recording space, overlays and interface elements can be moved around the user, like planets suspended around a star.  Seeing the parameter controls fade in and out of existence where they are situated, depending on the selected track, could remedy this concern.

- Our system did not have a clear way to switch between projects
On the Welcome screen, users are able to choose to open an existing project or a new project.  Once they make their decision though, there is not an obvious way to open a different existing project.  Improving on this feature in VR will be important for user satisfaction.  Similarly, we will make sure it is clear how to navigate between the different modes.

#### Clearly these fixes can be best adapted in combining components of both augmented and virtual reality.  The need for VR goggles is non-negotiable for our design, however embedded cameras will integrate their workspace with the overlays and “selectable” components of our adaptation.  This synthesis of technologies is key to developing our platform as a product of greenfield engineering.

### Conceptual Showcase Video

