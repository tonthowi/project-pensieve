Below is an **updated set of MVP User Stories & Acceptance Criteria**, now **including photo/video capture** under the **Capture** phase. This aligns with your requirement to capture images or videos directly from the camera or device gallery. Whimsical branding elements are kept out of the user story wording to maintain clarity, but can be integrated into UI messaging.

---

# **Pensieve It! — MVP User Stories & Acceptance Criteria**

## **Interaction Phase 1: Capture Anything Quickly**

### **User Story 1: Quick Text Notes**  
**As an overthinker**,  
**I want** to quickly type text whenever an idea strikes,  
**So that** I can capture my thoughts before they disappear.

**Acceptance Criteria**  
- **AC1.1**: A “+” or “New Note” button is always visible on the home screen.  
- **AC1.2**: Tapping or clicking this button immediately opens a text input (no intermediate screens).  
- **AC1.3**: The note auto-saves once the user exits the text input or taps “Done.”  
- **AC1.4**: Text notes support at least basic formatting (bold, italic, bullet points).  

---

### **User Story 2: Quick Sketch**  
**As a creative user**,  
**I want** to doodle or visually sketch an idea,  
**So that** I can express concepts better than with text alone.

**Acceptance Criteria**  
- **AC2.1**: A “Sketch” button or icon is available in the capture toolbar.  
- **AC2.2**: Users can draw using a basic pen/marker tool and an eraser (at minimum).  
- **AC2.3**: Option to choose from at least two pen colors (e.g., black, red).  
- **AC2.4**: Sketches are auto-saved as soon as the user taps “Save” or navigates away.

---

### **User Story 3: Audio Notes**  
**As a busy professional**,  
**I want** to record short audio clips,  
**So that** I can capture ideas when typing or sketching isn’t convenient.

**Acceptance Criteria**  
- **AC3.1**: A “Record Audio” button is accessible in the capture toolbar.  
- **AC3.2**: Tapping “Record Audio” immediately starts recording (with a brief countdown or immediate start).  
- **AC3.3**: Users can pause, resume, or stop the recording.  
- **AC3.4**: Audio file is automatically attached to a new note or existing note.  
- **AC3.5**: A basic waveform or audio icon displays for playback.

---

### **User Story 4: Image & Video Capture**  
**As a user referencing visual content**,  
**I want** to quickly capture or upload images and videos,  
**So that** I can attach visual records or inspiration directly to my notes.

**Acceptance Criteria**  
- **AC4.1**: The capture toolbar includes “Camera” and “Gallery” options.  
- **AC4.2**: Selecting “Camera” opens the device’s camera interface (mobile) or prompts a webcam (desktop/laptop if feasible).  
- **AC4.3**: Selecting “Gallery” opens the device’s file picker to choose images/videos.  
- **AC4.4**: Upon confirmation, the image/video is embedded as part of a new or existing note.  
- **AC4.5**: Video thumbnails display a play icon; tapping it plays the video inline or in a pop-up.  
- **AC4.6**: Larger files are either compressed automatically or prompt the user to confirm before embedding.  

---

### **User Story 5: Stickers**  
**As a visually oriented user**,  
**I want** to add stickers (fun icons, images) to my notes,  
**So that** I can enrich my brainstorming with playful visual elements.

**Acceptance Criteria**  
- **AC5.1**: A “Stickers” button or icon in the capture toolbar opens a small sticker library.  
- **AC5.2**: Users can drag or tap stickers to place them onto a note or sketch.  
- **AC5.3**: Stickers can be moved, resized, and rotated.  
- **AC5.4**: Stickers remain attached to the note/sketch so they don’t get lost when scrolling or reorganizing.  
- **AC5.5**: The initial sticker set includes a handful of free default stickers (e.g., emojis, symbols).  

---

### **User Story 6: Minimal Friction**  
**As a user with limited time**,  
**I want** the app to launch quickly and let me capture notes immediately,  
**So that** I never hesitate to use it due to slow loading or complicated menus.

**Acceptance Criteria**  
- **AC6.1**: App loads to the main capture screen in <2 seconds on a modern smartphone or laptop.  
- **AC6.2**: No mandatory sign-in step before capturing the first note (guest mode or minimal sign-up prompt).  
- **AC6.3**: Buttons for text, sketch, audio, image, video, and stickers are all visible on the main screen or within one tap.  
- **AC6.4**: After capturing anything, the note auto-saves unless it’s blank (leading to no clutter).

---

## **Interaction Phase 2: Clarify**

### **User Story 7: Mini “Cleanup Mode”**  
**As a user with many random notes**,  
**I want** a quick way to label or tag new notes right after I create them,  
**So that** I can reduce future confusion when reviewing them later.

**Acceptance Criteria**  
- **AC7.1**: Right after saving a note (text, sketch, audio, image, video, sticker), a mini “cleanup prompt” appears.  
- **AC7.2**: The user can accept an auto-suggested label (Task, Idea, Worry, Project/Area) or skip it.  
- **AC7.3**: Users can also add a custom tag via a single text field.  
- **AC7.4**: If the user does nothing within 5 seconds, the cleanup prompt disappears without forcing a tag.  

---

## **Interaction Phase 3: Organize**

### **User Story 8: PARA Lite Buckets**  
**As a PKM enthusiast**,  
**I want** to assign my notes to Projects, Areas, Resources, or Archive,  
**So that** I can maintain a lightweight structure without overcomplicating my workflow.

**Acceptance Criteria**  
- **AC8.1**: The app provides four optional buckets: Projects, Areas, Resources, Archive.  
- **AC8.2**: A note can be assigned to only one bucket at a time (or left unassigned).  
- **AC8.3**: Users can reassign notes between buckets later if needed.  
- **AC8.4**: The home screen or side menu displays these four buckets as primary navigation sections.

---

### **User Story 9: Basic Search & Filter**  
**As a user with growing content**,  
**I want** to search my notes or filter by tags/buckets,  
**So that** I can quickly find what I need without endless scrolling.

**Acceptance Criteria**  
- **AC9.1**: A search bar is present on the home screen or top navigation.  
- **AC9.2**: Typing keywords returns matching note titles, tags, and text content.  
- **AC9.3**: Users can filter by bucket (Projects, Areas, etc.) or by user-assigned tags.  
- **AC9.4**: Search results load in under 2 seconds for up to 500 notes.

---

## **Interaction Phase 4: Connect**

### **User Story 10: Note Linking**  
**As a user who sees connections between ideas**,  
**I want** to link one note to another,  
**So that** I can easily navigate related concepts without manual copy/paste.

**Acceptance Criteria**  
- **AC10.1**: Within an open note, the app suggests “related notes” based on shared tags or keywords.  
- **AC10.2**: Tapping a suggested note inserts a hyperlink/reference to that note.  
- **AC10.3**: Users can manually search for and link to any note.  
- **AC10.4**: Linked notes display as clickable references in both directions (backlinking).

---

### **User Story 11: Basic Mind Map View (Optional for MVP)**  
**As a visual thinker**,  
**I want** to see a simple map of how my notes connect,  
**So that** I can recognize bigger patterns or relationships at a glance.

**Acceptance Criteria**  
- **AC11.1**: A “Mind Map” button shows each note as a node, connected by shared tags/links.  
- **AC11.2**: Users can drag nodes around to rearrange the layout.  
- **AC11.3**: Tapping a node opens the corresponding note.  
- **AC11.4**: The mind map updates automatically when notes or links change.

> *Note*: This feature can be deprioritized if development resources are limited in the MVP.

---

## **Interaction Phase 5: Publish**

### **User Story 12: Combine & Export**  
**As a user finalizing ideas**,  
**I want** to group multiple notes/sketches/stickers/images/videos into a single “board” and export it,  
**So that** I can share a cohesive document or snapshot with others.

**Acceptance Criteria**  
- **AC12.1**: Users can select multiple notes, then choose “Combine” to create a new board.  
- **AC12.2**: The board displays the selected notes in a simple, scrollable or grid layout.  
- **AC12.3**: Tapping “Export” offers a PDF option or a shareable read-only link.  
- **AC12.4**: The exported PDF includes text, sketches, stickers, and placeholders for audio/video (e.g., icons or preview images).

---

### **User Story 13: Shareable Read-Only Link**  
**As someone collaborating with others**,  
**I want** to generate a link for my board or note,  
**So that** friends/colleagues can view it without editing.

**Acceptance Criteria**  
- **AC13.1**: Tapping “Share” creates a unique URL that anyone with the link can access.  
- **AC13.2**: Shared link displays notes, stickers, sketches, images, and video/audio placeholders (no editing).  
- **AC13.3**: The link remains valid unless the user chooses to revoke it (a “Revoke Link” option in settings).  
- **AC13.4**: Basic analytics (e.g., view count) are tracked if feasible in MVP scope.

---

## **Edge Cases & Additional Scenarios**  
1. **Blank Note Handling**: If a user opens a new note but doesn’t add text/sketch/media/stickers, it’s not saved to avoid clutter.  
2. **Offline Capture**: If no internet is available, notes still save locally and sync automatically when online.  
3. **Large File Uploads**: For media or stickers exceeding size thresholds, the app prompts a warning or compresses automatically.  
4. **Permission Handling**: The app requests microphone and camera/gallery permissions where needed (mobile).  
5. **Multiple Media Attachments**: Users may attach multiple images or videos to a single note; the interface should handle this gracefully.

---

## **Why This Approach Works**  
- **Granular Coverage**: Each user story targets a distinct action (text, sketch, audio, images/videos, stickers) under the Capture phase.  
- **Streamlined Clarification & Organization**: Mini “cleanup mode” and PARA Lite keep notes tidy without overwhelming.  
- **Connectivity & Publishing**: Basic note linking and optional mind mapping let users see relationships, while Publish Mode enables sharing or exporting.  
- **Playful UI, Straightforward Core**: These stories remain concise, but the interface can incorporate fun animations and copy to reflect Pensieve’s “flush your thoughts” brand identity.

This set of **User Stories & Acceptance Criteria** now fully integrates **image/video capture** alongside text, sketch, audio, and stickers, ensuring a comprehensive and frictionless capture experience for the MVP.

---

Below is a **UI Screens Table** outlining the key interactions from the updated user stories, along with how each screen or flow would be presented on **mobile/tablet** vs. **desktop**. Each row references one or more relevant user stories (US) and highlights the essential interface elements that satisfy the Acceptance Criteria.

---

# **UI Screens to Support MVP User Stories**

| **Screen / Flow**                             | **Mobile/Tablet**                                                                                                                                   | **Desktop**                                                                                                                                |
|----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| **1. Main Capture/Home** <br>*(US 1, 2, 3, 4, 5, 6)*<br>_Quick Access to Text, Sketch, Audio, Image/Video, Stickers_ | - **Layout**: Full-screen feed or grid of recent notes. <br>- **Capture Toolbar** (bottom or floating): icons for Text, Sketch, Audio, Camera/Gallery, Stickers. <br>- **One-Tap Capture**: Tapping any icon immediately opens that capture mode (minimal transitions). <br>- **Guest Mode** (no forced login) if first-time user. | - **Layout**: Wider grid or list of notes on the right, with a persistent left sidebar. <br>- **Capture Toolbar**: Typically at the top or left sidebar with icons for each capture mode. <br>- **Quick Launch**: Clicking an icon opens a modal or pop-up for text/sketch/audio capture. <br>- **Minimal friction**: Possibly a larger “+” button that expands into capture options. |
| **2. Text Note Editor** <br>*(US 1, 6)*        | - **Screen**: Modal overlay or dedicated page for typing. <br>- **Basic Formatting**: Bold/italic/bullets as small icons above the keyboard. <br>- **Auto-Save**: Once user exits or taps “Done.”                                                                                                  | - **Window/Panel**: Opens as a pop-up or in a split view. <br>- **Text Formatting Toolbar** just above the text field (bold, italic, bullets). <br>- **Auto-Save** triggered when user clicks away or closes the editor.                                                                        |
| **3. Sketch Canvas** <br>*(US 2, 6)*          | - **Fullscreen Canvas**: Pen, eraser, basic color selector. <br>- **Undo/Redo** buttons at the top or bottom. <br>- **Save**: Tapping “Done” or back arrow auto-saves the sketch as an image note.                                                                                               | - **Resizable Panel** or pop-up. <br>- **Tool Sidebar**: Pen, eraser, color palette. <br>- **Save/Close**: Clicking an “Apply” or “Save” button finalizes the sketch and embeds it into a note.                                                                                         |
| **4. Audio Recorder** <br>*(US 3)*            | - **Overlay or Modal**: A big “Record” button starts recording. <br>- **Waveform Visualization** (if possible on mobile). <br>- **Pause/Stop** buttons: Stop finalizes the audio note. <br>- **Auto-Save**: Audio note is created once user stops recording.                                                    | - **Panel** or “Record Audio” modal. <br>- **Real-Time Waveform** (desktop typically has more power for visual feedback). <br>- **Playback**: A small audio player within the note once saved.                                                                                             |
| **5. Image/Video Capture** <br>*(US 4)*       | - **Camera/Gallery Flow**: Tapping “Camera” launches the built-in camera app or a custom camera preview. <br>- **Gallery Picker**: Native OS file picker or gallery. <br>- **Inline Preview**: After selection, a thumbnail appears in a new note. <br>- **Video**: Displays a play icon on the thumbnail. | - **Modal or System File Dialog** for choosing images/videos. <br>- **Webcam Prompt** if “Camera” is selected (only if hardware available). <br>- **Thumbnail Display**: Hovering shows preview or play icon. <br>- **Inline or pop-up Player** for videos once attached.                                                       |
| **6. Stickers Library** <br>*(US 5)*          | - **Sliding Bottom Sheet** or floating panel with sticker categories (e.g., Basic, Emojis). <br>- **Drag & Drop** or tap to insert a sticker onto a note/sketch. <br>- **Resizing**: Pinch with two fingers or use on-screen handles.                                                                 | - **Side Panel** or pop-up window listing sticker sets. <br>- **Drag & Drop** onto the note or canvas. <br>- **Resizing Handles** on corners for quick scaling/rotation. <br>- Possibly a simple right-click context menu to remove or edit the sticker.                                        |
| **7. Mini “Cleanup Mode”** <br>*(US 7)*       | - **Post-Capture Prompt**: After saving a new note/sketch/audio/etc., a small toast or overlay suggests tagging (e.g., “Task,” “Idea,” “Worry”). <br>- **Skip**: Tapping outside or waiting 5 seconds closes the prompt.                                                                                   | - **Lightweight Popup**: On a new note creation, a small popup or side panel says “Add a tag?” <br>- **Click** the suggested tag or type a custom one. <br>- **Auto-Close**: Closes if user ignores it after a few seconds.                                                                   |
| **8. PARA Buckets Screen** <br>*(US 8)*       | - **Home Screen**: Tabs or a dropdown menu for “Projects,” “Areas,” “Resources,” and “Archive.” <br>- **Simple List/Grid** of notes under each bucket. <br>- **Assign/Move**: Press-and-hold on a note to reassign to a different bucket.                                                                         | - **Sidebar**: Four main sections (Projects, Areas, Resources, Archive). <br>- **Drag & Drop** a note from one bucket to another. <br>- **Bulk Actions**: Multi-select notes and move them at once.                                                                                         |
| **9. Search & Filter** <br>*(US 9)*           | - **Search Bar** at top or within a floating button. <br>- Typing keywords instantly filters note thumbnails or list items. <br>- **Tag/Bucket Filters**: Simple toggle or drop-down next to the search field.                                                                                        | - **Persistent Search Field** in the top navigation bar. <br>- Real-time filtering of a note list or grid. <br>- **Advanced Filter Panel** (if needed) to refine results by bucket or tag.                                                                                              |
| **10. Note Linking & Mind Map** <br>*(US 10, 11)* | - **Related Notes**: Displayed below the note content (“You may also like…”). <br>- **Link to Another Note**: Press-and-hold or a dedicated link button to connect them. <br>- **Mind Map (Optional)**: Tap a “View Connections” button to see a simplified node graph.                                          | - **Related Notes Sidebar**: Shown on the right with clickable references. <br>- **Link Button**: Possibly an icon in the note editor to insert a link to another note. <br>- **Mind Map**: Opens a separate panel or view with draggable nodes, each representing a note.                                                    |
| **11. Combine & Export** <br>*(US 12)*        | - **Multi-Select**: Tap-and-hold on multiple notes in a grid view, then choose “Combine.” <br>- **New Board**: A simple layout where each note is represented by a card or thumbnail. <br>- **Export**: Button to generate PDF or share link.                                                           | - **Checkbox/Shift-Select**: Users can select multiple notes and click “Combine.” <br>- **Board Interface** in a new tab or modal. <br>- **Export**: A top-right button offering PDF or shareable link.                                                                                          |
| **12. Shareable Read-Only Link** <br>*(US 13)* | - **Share Button**: On the new board or an individual note, tapping “Share” generates a link. <br>- **Mobile Sharing**: Native share sheet (copy link, message, email). <br>- **Read-Only**: Link opens in a mobile browser view with no edit tools.                                                      | - **Share Button**: On the board or note, triggers a modal with the unique URL and a “Copy Link” button. <br>- **Desktop Browser**: The read-only link opens in a standard browser tab. <br>- **Optional**: “Revoke Link” button in user settings.                                           |

---

### **How This Table Supports the User Stories**

- **Mobile vs. Desktop Differences**:  
  - On mobile/tablet, the UI focuses on gestures (tap, press-and-hold, pinch to resize) and uses bottom sheets or floating buttons for actions.  
  - On desktop, users have more screen space, so sidebars, split views, and drag-and-drop are natural interactions.

- **Consistent Branding / Whimsy**:  
  - The *look and feel* (animations, playful messages, confetti, etc.) can be layered on top of these core layouts.  
  - The table focuses on functional layout differences rather than brand copy.

- **Scalable Layouts**:  
  - Each screen can adapt responsively—especially relevant for tablets, which often sit in between mobile and desktop in available screen real estate.
