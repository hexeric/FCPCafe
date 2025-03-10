# Explore LateNite's Tools

This website has been thrown together by [Chris Hocking](https://twitter.com/chrisatlatenite) at [LateNite](https://latenitefilms.com/technology).

Constantly looking for ways to innovate, LateNite is as passionate about production and post production as it is storytelling. Their pursuit of creative excellence has seen them work closely with global cinematic technology companies to craft post workflow solutions and critically celebrated software in-house.

---

## Pro Editor Bundle

For only **USD$100**, you can now buy BRAW Toolbox, Gyroflow Toolbox, Marker Toolbox, Recall Toolbox & Fast Collections as a bundle!

You can find the bundle on the Mac App Store [here](https://itunes.apple.com/us/app-bundle/id1717681153?mt=12).

---

## Mac App Store

Here's some of our products currently for sale on the **Mac App Store**:

{{ include "latenite/braw-toolbox" }}

---

{{ include "latenite/gyroflow-toolbox" }}

---

{{ include "latenite/marker-toolbox" }}

---

{{ include "latenite/fast-collections" }}

---

{{ include "latenite/recall-toolbox" }}

---

## Free Apps

Here's some of our free tools used by professional editors worldwide:

{{ include "latenite/commandpost" }}

---

### Rename Avid MXF Files

This simple Python script is used to rename MXF files generated from Avid Media Composer to match the **Package Name** in their metadata.

The script can process a **single file** or a **folder** containing multiple MXF files.

This is useful if you want to move native Avid MXF files from Avid Media Composer to Final Cut Pro.

This script is very basic, and doesn't contain any special error handling or messaging. It may not work in all use cases.

You should duplicate the MXF files you want to process prior to using, as there's no "undo" once you run the script.

You can learn more [here](https://github.com/CommandPost/RenameAvidMXFFiles).

---

## In Development

Here's a **sneak peak** of some of the things we have in development:

---

### Timecode Toolbox

We're spinning out the Sony Timecode Repair Toolbox from CommandPost and making it a standalone app.

In addition to the current functionality, you'll also be able to modify the original camera files to add Final Cut Pro friendly timecode.

---

### RAW Toolbox

Following in the footsteps of [BRAW Toolbox](#braw-toolbox), RAW Toolbox will initially add Nikon N-RAW support to Final Cut Pro.

---

### Metadata Toolbox

**Metadata Toolbox** is a Workflow Extension that allows you to drag in a project, select burn-in metadata options, then drag a Compound Clip back to the timeline with all the metadata as titles.

---

### Import Toolbox

**Import Toolbox** will be a Workflow Extension that allows you to import files with better metadata and preset controls (i.e. clip volume).

We will also be spinning out the **Watch Folders** from CommandPost and moving them into this app.

---

### Assistant Toolbox

**Assistant Toolbox** will be a Workflow Extension that spins out **Titles to Keywords** and **Auto Sequence** from CommandPost.

It'll include various improvements and enhancements to make the job even easier for Assistant Editors working on long-form feature film projects.

---

### Magic Toolbox

**Magic Toolbox** is our first Machine Learning experiment.

You'll be able to add titles to the timeline, to trigger Machine Learning actions such as:

- **SUBTITLES** - Analyses the audio and adds subtitles
- **NARRATION** - Turns text into speech in a narration tone
- **VOICE** - Turns text into speech based on your description
- **GRADE** - Adds Color Effects based on your description
- **MUSIC** - Adds stock music or machine learning generated music based on your description
- **SFX** - Adds sound effects from places like FreeSound.org
- **VIDEO** - Adds machine learning generated video based on your description

Magic Toolbox will use existing services like [ChatGPT](https://chat.openai.com) and [ElevenLabs](https://beta.elevenlabs.io) - and it'll be BYO API Key.

![](/static/magic-toolbox.jpg)