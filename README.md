# Vocalize AI User Guide

Your personal voice recording companion with AI-powered transcription, analysis, and voice cloning.

---

## Getting Started

### First Launch
1. Grant microphone permission when prompted
2. Grant speech recognition permission for transcription
3. (Optional) Enable Personal Voice access for voice cloning
4. (Optional) Grant calendar access for the Meetings tab

### Main Tabs
- **Library** - Browse and manage your recordings
- **Meetings** - View upcoming meetings and record with one tap
- **Teams** - Collaborate with others in workspaces
- **Settings** - Configure app preferences, sync, and permissions

### Floating Record Button
A red microphone button floats at the bottom of the screen on Library, Meetings, and Teams tabs. Tap it to instantly open the recording screen — recording starts automatically.

---

## Recording

### Start Recording
1. Tap the **floating red microphone button** from any tab
2. Recording starts automatically — speak into your device
3. Watch the live waveform visualization
4. A timer tracks your recording duration

### Stop & Save
1. Tap the **stop button** to finish
2. Review your recording with playback controls
3. View the auto-generated transcription and AI summary
4. Tap **Save** to keep it with a custom or AI-suggested title
5. Or tap the **trash icon** to discard

### Meeting Recording
1. Go to the **Meetings** tab
2. Tap **Record** on any upcoming meeting
3. The recording is auto-titled with the meeting name and auto-linked to the calendar event

### Recording Quality
Configure in Settings:
- **Standard** (22,050 Hz) - Smaller files, good for voice notes
- **High** (44,100 Hz) - Balanced size and clarity (default)
- **Maximum** (48,000 Hz) - Best quality for important recordings

---

## Library

### Browsing Recordings
- View all recordings in chronological order
- See duration, date, folder name, and transcription status
- Tap to play or view details

### Folders
Organize recordings into custom folders:

1. Tap the **+** button in the folders carousel
2. Enter a folder name
3. Choose a color and icon
4. Tap **Create**

**Smart Folders** automatically collect recordings based on rules:
- Date range (Today, This Week, This Month)
- Has transcription
- Contains specific text

### Moving to Folders
- Long-press a recording
- Select **Move to Folder**
- Choose the destination folder

### Tags
Add tags for flexible organization:

1. Long-press a recording
2. Select **Manage Tags**
3. Check/uncheck tags
4. Create new tags with the **+** button

Tags appear as colored pills on recording rows.

### Favorites
- Long-press a recording
- Select **Add to Favorites**
- Favorites show a heart icon

### Search
- Use the search bar to find recordings
- Searches titles and transcriptions
- Results update as you type

### Batch Export
1. Tap **Select** in the Library toolbar
2. Check multiple recordings
3. Tap the floating **Export N** button
4. Choose format and export options
5. Optionally export as a ZIP archive

---

## Meetings

### Calendar Integration
The Meetings tab reads events from all your synced calendars (iCloud, Google, Outlook, Exchange) via EventKit.

### Agenda View
- **Today** - Meetings happening today
- **This Week** - The rest of this week's schedule
- **Upcoming** - Events in the next 7 days

### Status Indicators
- **Red pulse** - Meeting in progress
- **Blue clock** - Upcoming
- **Gray** - Past meeting
- **Green checkmark** - Already recorded

### One-Tap Recording
Tap **Record** on any meeting card to open the recording screen with the meeting title pre-filled and auto-linked.

### Meeting Settings
Tap the gear icon in the Meetings tab to configure:
- Which calendars to display
- Show/hide all-day events
- Pre-meeting notification timing (5/10/15 minutes)
- Auto-tag recordings with "Meeting" tag

---

## Playback

### Basic Controls
- **Play/Pause** - Tap the play button
- **Seek** - Drag the progress slider
- **Stop** - Tap stop to reset

### Bookmarks
Mark important moments in your recordings:

1. During playback, tap the **bookmark button**
2. Add a label (optional)
3. Choose a color
4. Add notes (optional)
5. Tap **Add**

**Navigating Bookmarks:**
- Tap any bookmark to jump to that timestamp
- View bookmarks in the timeline
- Edit or delete from the detail view

---

## Transcription

### Auto-Transcription
- Recordings are transcribed automatically after you stop recording
- Uses on-device Apple Speech framework
- Green bubble icon indicates completed transcription

### Viewing Transcription
1. Tap a recording to open details
2. Scroll to see full transcription
3. Highlights appear in color

### Highlights
Select important parts of transcriptions:

1. Open recording details
2. Select text in the transcription
3. Choose **Highlight**
4. Pick a color and add notes

---

## AI Insights

### Overview
Vocalize AI uses on-device AI (Apple NaturalLanguage framework) to analyze your transcriptions. All processing happens locally for complete privacy.

### Getting AI Analysis
1. Open a recording with a transcription
2. Tap the **AI Insights** tab
3. Tap **Analyze Recording**
4. Wait for analysis to complete (progress shown)

### Features
- **Summary** - Concise extractive summary of key content
- **Key Points** - Important statements color-coded by importance (High/Medium/Low) and categorized (Meeting, Deadline, Decision, Idea, Issue)
- **Action Items** - Automatically detected tasks with priority levels and due date detection
- **Sentiment Analysis** - Overall tone with sentence-by-sentence breakdown and visual meter
- **Topics** - Main subjects discussed with relevance indicators

### Tips for Better Analysis
- Speak clearly for accurate transcription
- Longer recordings provide more context
- Use action words for better task detection
- Mention dates for due date recognition

---

## Read Aloud

### Using Read Aloud
- Open a recording and tap the **speaker icon** to read the transcription aloud
- Tap the speaker icon on any AI insight card to hear just that section
- Choose your **Personal Voice** (if set up) or a system voice
- Adjust speech speed and pitch with sliders

### Personal Voice
Your Personal Voice is created in iOS Settings:

1. Go to **Settings > Accessibility > Personal Voice**
2. Follow Apple's setup process (~15 minutes of recording)
3. Wait for processing (may take overnight)
4. Once created, it appears in Vocalize AI automatically

*Note: Personal Voice audio cannot be saved to files due to iOS limitations.*

---

## Audio Editing

### Trim
1. Open a recording and tap **Edit Audio**
2. Drag the selection handles to choose the portion to keep
3. Tap **Trim** to apply

### Split
1. Place split points on the waveform
2. Tap **Split** to divide the recording into separate files

### Zoom
- Pinch to zoom the waveform for precise editing

### Undo/Redo
- Use undo and redo buttons to safely experiment with edits
- Non-destructive editing preserves the original file

---

## Noise Reduction

### Step-by-Step Workflow
1. **Learn Noise** - Select a noise-only segment so the app learns the noise pattern
2. **Adjust Settings** - Choose aggressiveness (Light/Medium/Heavy), intensity, and voice preservation toggle
3. **Preview** - Compare before and after audio
4. **Apply** - Save the processed audio

---

## Audio Enhancement

### Auto Enhance
One-tap enhancement that normalizes volume, compresses dynamics, and applies voice EQ.

### Manual Controls
- **Normalize** - Adjust overall volume to a target loudness level (LUFS)
- **Compress** - Reduce dynamic range with presets (Voice, Podcast, Gentle) or custom settings
- **Equalizer** - Apply frequency adjustments with presets (Voice Clarity, Warmth, Brightness, Podcast, Telephone) or custom 8-band EQ

---

## Voice Separation

### Overview
Isolate speech from background audio using an AI model or spectral fallback.

### Using Voice Separation
1. The CoreML voice separation model is **bundled with the app** and ready to use immediately
2. Open a recording and tap **Separate Voice** from the enhance menu
3. Choose **AI Model** (higher quality) or **Basic Mode** (spectral fallback)
4. Preview results before applying

### Model Updates
Check for model updates in the Voice Separation settings to get improved quality over time.

---

## AI Voice Model

### Overview
The AI Voice Model settings let you manage the CoreML model used for voice separation. You can browse available models organized by category, follow model-specific conversion guides, supply a custom model URL, or revert to the bundled model. Only CoreML format (.mlmodel / .mlmodelc) is supported. All model inference runs 100% on-device -- your audio never leaves your device.

### Accessing AI Voice Model Settings
1. Go to the **Settings** tab
2. Scroll to the **AI Voice Model** section
3. View the current model status, version, and size

### Model Status
The status indicator shows the current state of the model:
- **Ready** -- The model is loaded and ready for voice separation
- **Not Downloaded** -- No custom model is downloaded; the bundled model is in use
- **Downloading** -- A model download is in progress (progress bar shown)
- **Failed** -- The download failed; tap to retry or revert to the bundled model

### Available Models
Expand the **Available Models** section to browse curated models organized into three categories:

**Music Separation**
- **Spleeter** -- Deezer, MIT license, Medium difficulty
- **MDX-Net** -- KUielab, MIT license, Medium difficulty
- **Demucs v4** -- Meta, MIT license, Hard difficulty

**Speech Separation**
- **Conv-TasNet** -- Asteroid, MIT license, Medium difficulty

**Speech Enhancement**
- **RNNoise** -- Xiph.org, BSD-3 license, Easy difficulty

Each model card shows the author, license, supported format, estimated size, and difficulty rating. Tap the **Guide** button on any model card to view model-specific conversion instructions.

### Conversion Guide
Expand the **Conversion Guide** section for step-by-step instructions on converting models to CoreML format:

1. Select a model from the Available Models section and tap **Guide**, or browse the general overview
2. Follow the provided Python script to convert the model to CoreML (.mlmodel) format
3. Tap the **copy button** on any code snippet to copy it to your clipboard
4. Run the script on your Mac or any machine with Python and coremltools installed
5. Use the resulting .mlmodel or .mlmodelc file as your custom model URL

> **Note:** Only CoreML format is supported. ONNX and TFLite models cannot be used directly -- they must be converted to CoreML first using the provided conversion scripts.

### Using a Custom Model URL
1. In the **Model URL** field, enter the direct download URL for a CoreML (.mlmodel or .mlmodelc) file
2. If the model is hosted in a private or gated repository, enter an **Auth Token** in the token field
   - The token is used only during download and is stored locally on your device
3. Tap **Download Model**
4. A progress indicator shows the download and compilation status

### Reverting to the Bundled Model
1. Tap **Revert to Bundled Model**
2. The custom model is removed and the app switches back to the model that shipped with the app
3. This frees storage used by the downloaded model

### Tips
- Make sure you have a stable internet connection before downloading a model
- Larger models may produce better separation quality but take longer to download
- The bundled model is always available as a reliable fallback
- Auth tokens are stored only in local UserDefaults and are never sent to any server other than the model host during download
- Use the Conversion Guide's copy-to-clipboard feature to quickly set up conversion scripts

---

## Export

### Export Options
Share your recordings in multiple formats:

1. Open a recording
2. Tap the **Export** button
3. Choose format:
   - **PDF** - Rich document with metadata, bookmarks, and transcription
   - **TXT** - Plain text transcript
   - **SRT** - Subtitle file format
   - **Audio** - Original audio file

### Export Settings
- Include/exclude metadata
- Include/exclude bookmarks
- Include/exclude tags

### Save to Files
- Use **Save to Files** to save exports directly to the iOS Files app

### Quick Export
- Long-press a recording
- Select **Export as PDF/TXT/SRT/Audio**
- Share immediately

---

## Calendar & Reminders

### Creating Events from AI
1. Run AI analysis on a recording
2. Tap action items to create calendar events or reminders
3. AI automatically detects dates mentioned in your recordings
4. Select multiple action items for batch creation

### Permissions
Grant Calendar and Reminders access in **Settings > Calendar & Reminders**.

---

## iCloud Sync

### Enabling Sync
1. Go to the **Settings** tab
2. Toggle **iCloud Sync** on
3. Sign in to iCloud if prompted

### What Gets Synced
- All recordings and audio files
- Folders and organization
- Tags and metadata
- Bookmarks and highlights
- AI analysis results

### Sync Management
- **Sync Now** - Force an immediate sync from Settings
- **Conflict Resolution** - Choose strategy (newest wins or manual)
- **Offline Mode** - Changes queue automatically and sync when back online

---

## Sharing Recordings

### Creating a Share Link
1. Open a recording
2. Tap the **Share** button
3. Select **Create Share Link**
4. Configure options:
   - **Access Level**: View, Comment, or Edit
   - **Password**: Optional protection
   - **Expiration**: When the link expires (24h, 7d, 30d, never)
   - **Allow Download**: Let others save the audio
5. Tap **Create Link**

### Comments
- Add timestamped comments on shared recordings
- Reply to other comments with @mentions
- Tap a comment to jump to that moment

---

## Collaborative Folders

### Sharing a Folder
1. Long-press a folder and select **Share Folder**
2. Configure default role, invite permissions, and approval settings
3. Invite members by email

### Member Roles
| Role | View | Add | Edit | Delete | Manage Members |
|------|------|-----|------|--------|----------------|
| **Viewer** | Yes | No | No | No | No |
| **Contributor** | Yes | Yes | Yes | No | No |
| **Admin** | Yes | Yes | Yes | Yes | Yes |
| **Owner** | Yes | Yes | Yes | Yes | Yes |

---

## Team Workspaces

### Creating a Workspace
1. Go to the **Teams** tab
2. Tap the **+** floating button
3. Enter name, description, icon, and color
4. Tap **Create**

### Workspace Features
- **Analytics Dashboard** - Recordings, duration, members, storage
- **Role-Based Access** - Owner, Admin, Member, Guest
- **Shared Folders** - Organize recordings within workspaces
- **Activity Feed** - Track all changes

---

## Shortcuts & Automation

### Siri Commands
- "Start recording in Vocalize AI"
- "Get my recent recordings from Vocalize AI"
- "Search recordings in Vocalize AI"
- "Export recording from Vocalize AI"

### Shortcuts App
Build custom automations with 9 available actions:
Start Recording, Get Recent Recordings, Search Recordings, Export Recording, Create Folder, Get Transcription, Run AI Summary, Apply Noise Reduction, Share Recording.

---

## Widgets

### Available Widgets

| Size | Features |
|------|----------|
| **Small** | Recording count, recent recording, tap to open |
| **Medium** | Stats + recent recordings list |
| **Large** | Full dashboard with quick record button |
| **Lock Screen** | Circular mic icon, tap to start recording |

### Adding Widgets
1. Long-press your home screen
2. Tap the **+** button
3. Search for "Vocalize AI"
4. Choose a widget size and tap **Add Widget**

---

## Files App Integration

### Accessing Files
1. Open **Files**
2. Navigate to **On My iPhone/iPad**
3. Open **Vocalize AI**
4. Browse Recordings and Synthesized folders

### File Names
Files use readable names: `Recording_2026-02-13_14-30_2m15s.m4a`

---

## Settings

### Accessing Settings
Tap the **Settings** tab at the bottom of the screen. Settings includes:

- **iCloud Sync** - Enable/disable sync, check status, force sync
- **Calendar & Reminders** - Grant permissions for event/reminder creation
- **Voice Cloning** - Personal Voice status and setup link
- **AI Voice Model** - View model status, browse available models by category, follow conversion guides, download custom CoreML models, revert to bundled
- **Recording** - Quality settings, storage usage, recording count
- **Privacy** - On-device processing confirmation
- **Help & How-To** - Feature guides and troubleshooting
- **About** - App version and feature overview
- **Reset** - Reset onboarding or delete all data

---

## Privacy & Security

### On-Device Processing
- All transcription happens on your device
- AI analysis runs locally using Apple's NaturalLanguage framework
- No audio or text sent to external servers
- Personal Voice stays completely local

### Cloud Sync Privacy
- **Apple CloudKit Only** - No third-party servers
- **End-to-End Encryption** - Shared data is encrypted
- **You Control Sharing** - Explicit consent required
- **Delete Everywhere** - Remove from all devices at once

### Permissions Used
- **Microphone** - For recording audio
- **Speech Recognition** - For transcription
- **Personal Voice** - For voice cloning (optional)
- **iCloud** - For sync and collaboration (optional)
- **Calendar** - For Meetings tab and event creation (optional)
- **Reminders** - For creating reminders from action items (optional)

---

## Troubleshooting

### Recording Won't Start
- Check microphone permission in iOS Settings > Vocalize AI
- Ensure no other app is using the microphone
- Restart the app

### Transcription Failed
- Check speech recognition permission
- Ensure internet connection (for initial setup)
- Try shorter recordings

### Personal Voice Not Showing
- Verify Personal Voice is set up in iOS Settings > Accessibility > Personal Voice
- Check Personal Voice permission for Vocalize AI
- Reload voices from Settings

### Export Failing or Empty File
- Ensure the recording has a transcription for PDF/TXT/SRT export
- Audio export copies the original file — verify it exists in storage

### iCloud Sync Not Working
- Ensure you're signed into iCloud in iOS Settings
- Have iCloud Drive enabled
- Toggle Vocalize AI sync on in the Settings tab

### Calendar Events Not Creating
- Grant Calendar and Reminders access in Settings > Calendar & Reminders
- If already granted, try toggling permissions off and on in iOS Settings > Vocalize AI

### Noise Reduction Sounds Distorted
- Try a lower aggressiveness level (Light)
- Enable Voice Preservation
- Ensure the noise profile was learned from a segment with only background noise

### Voice Separation Not Working
- The model is bundled with the app and should work immediately
- If deleted to save space, it will be restored automatically
- For model updates, ensure you have a stable internet connection

---

## iPad Support

Vocalize AI is fully optimized for iPad with a native multi-column interface.

### Sidebar Navigation
On iPad, the tab bar is replaced by a sidebar that lists Library, Meetings, Teams, and Settings. A prominent Record button sits at the bottom of the sidebar for quick access.

### Multi-Column Layouts
- **Library**: A three-column layout shows your folders on the left, recordings in the center, and the full recording detail on the right — all visible at once.
- **Meetings**: A two-column layout shows your calendar events on the left and meeting details on the right.
- **Teams**: A two-column layout shows workspaces on the left and workspace details on the right.

### Popovers
Small dialogs such as Create Folder and Meeting Settings appear as lightweight popovers instead of full-screen sheets.

### Pointer & Hover
Interactive cards and rows highlight when you hover with a trackpad or Apple Pencil for a more responsive feel.

### Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Library Tab | Cmd + 1 |
| Meetings Tab | Cmd + 2 |
| Teams Tab | Cmd + 3 |
| Start Recording | Cmd + R |
| New Recording | Cmd + N |
| Play/Pause | Space |
| Stop | Esc |
| Save | Cmd + S |
| Delete | Cmd + Delete |
| Search | Cmd + F |

---

## Version

**Vocalize AI 1.0.0** - First Production Release (February 2026)

### What's Included
- Voice Recording with quality settings and auto-start
- On-device Transcription and AI Summary
- AI Insights (Key Points, Action Items, Sentiment, Topics)
- Smart Meeting Assistant with Calendar Integration
- Folders, Tags, Bookmarks & Highlights
- Audio Editing, Noise Reduction, Enhancement, Voice Separation
- iCloud Sync, Sharing, Collaborative Folders, Team Workspaces
- Export (PDF, TXT, SRT, Audio) with Batch Export
- Shortcuts & Siri Automation
- Home Screen & Lock Screen Widgets
- Read Aloud with Personal Voice Support
- Full iPad support with sidebar navigation, multi-column layouts, and keyboard shortcuts

---

*Made with care for your voice.*
