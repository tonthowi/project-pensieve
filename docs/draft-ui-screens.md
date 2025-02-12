# UI Screens to Add 

Here’s a comprehensive list of **UI screens** for Pensieve’s MVP, including edge cases, optimized for mobile (iOS/Android), tablet (stylus), and desktop (web):

---

### **Core Screens**  
#### **1. Blank Canvas (Home Screen)**  
**Purpose**: Immediate idea capture.  
**Components**:  
- Fixed-size canvas (A4 aspect ratio, scrollable).  
- Floating toolbar (collapsed by default).  
- *Mobile/Tablet*: Bottom bar with **+** (add media) and **Export** buttons.  
- *Desktop*: Left-edge toolbar with hoverable icons.  

**Edge Cases**:  
- **Empty Canvas**: Subtle ghosted hint (“Tap + to add ideas”).  
- **First Launch**: Quick tooltip pointing to the **+** button.  

---

#### **2. Media Import Screen**  
**Purpose**: Add images, audio, video, or screenshots.  
**Components**:  
- Grid/list of options:  
  - **Upload from device** (gallery/file picker).  
  - **Record** (audio/video via mic/camera).  
  - **Screenshot/Screen Record** (mobile/tablet only).  
- Preview thumbnail for selected media.  

**Edge Cases**:  
- **Unsupported Format**: Toast error (“This file type isn’t supported”).  
- **Large File**: Warning modal (“File exceeds 25MB – compress?”).  

---

#### **3. Media Sticker Screen**  
**Purpose**: Position and interact with media on the canvas.  
**Components**:  
- Draggable/resizable media card (image, audio waveform, video thumbnail).  
- Context menu on long-press: *Delete*, *Duplicate*, *Add Note*.  
- *Desktop*: Hover shows playback controls (▶️ for video/audio).  

**Edge Cases**:  
- **Overlap Alerts**: Semi-transparent borders if stickers overlap significantly.  
- **Corrupted Media**: Gray placeholder with “File unavailable” text.  

---

#### **4. Media Player Modal**  
**Purpose**: Play audio/video directly on the canvas.  
**Components**:  
- Native player controls (play/pause, seek bar, volume).  
- *Mobile*: Full-screen modal.  
- *Desktop*: Floating window (resizable).  

**Edge Cases**:  
- **Unplayable Media**: Error message (“Can’t play this file – try re-uploading”).  

---

#### **5. Basic Drawing Tools**  
**Purpose**: Freehand sketching.  
**Components**:  
- Floating toolbar with:  
  - Pen (2 sizes: 1mm/3mm).  
  - 2 colors (black, gray).  
  - Eraser.  
- *Tablet*: Pressure sensitivity indicator (line thickness preview).  

**Edge Cases**:  
- **Undo/Redo**: Swipe left/right (mobile) or **Ctrl+Z** (desktop).  

---

#### **6. Export/Save Screen**  
**Purpose**: Save or share the canvas.  
**Components**:  
- Options: **Export as PDF**, **Save to Device**, **Backup to Cloud**.  
- Preview of flattened PDF (stickers as static images).  
- *Desktop*: Drag-and-drop export to folders.  

**Edge Cases**:  
- **Export Failure**: Retry button with error details (“Low storage space”).  

---

### **Edge Case Screens**  
#### **1. Empty Canvas State**  
**Components**:  
- Ghosted illustration (e.g., a lightbulb + “Start dumping ideas here”).  
- **+** button pulsing gently.  

---

#### **2. Network Error Screen**  
**Components**:  
- Banner at top: “Offline – changes saved locally”.  
- Disabled **Cloud Backup** button.  

---

#### **3. Onboarding Flow**  
**Purpose**: Teach core interactions.  
**Components**:  
- 3-step walkthrough (skippable):  
  1. “Tap + to add media”.  
  2. “Drag stickers to organize”.  
  3. “Export to save your work”.  
- *Desktop*: Interactive hotspots instead of slides.  

---

#### **4. Storage Limit Warning**  
**Components**:  
- Modal: “Storage full – delete old canvases to free up space”.  
- Link to **Manage Storage** screen (list of canvases sorted by size).  

---

### **Device-Specific Variations**  
| **Screen**              | **Mobile**                          | **Tablet**                          | **Desktop**                        |  
|-------------------------|-------------------------------------|-------------------------------------|-----------------------------------|  
| **Canvas**              | Vertical scroll only                | Pinch-to-zoom + scroll              | Mouse wheel zoom + drag pan       |  
| **Media Import**        | Bottom sheet modal                  | Slide-over panel                    | File explorer dialog              |  
| **Drawing Tools**       | Collapsed toolbar (tap to expand)   | Always-visible toolbar (right edge) | Right-click context menu          |  
| **Export**              | Share sheet (iOS/Android native)    | Export preview panel                | Save As dialog                    |  

---

### **User Flow Validation**  
1. **Add Media → Position → Play**:  
   - *Test*: Ensure video/audio plays without leaving the canvas.  
2. **Draw → Undo**:  
   - *Test*: Swipe/gesture works across devices.  
3. **Export → PDF**:  
   - *Test*: Verify stickers render as static images.  

---

### **Tools to Build These Screens**  
- **Prototyping**: Figma (for drag-and-drop previews).  
- **UI Components**:  
  - React Native (Mobile): `react-native-reanimated` for smooth gestures.  
  - Web: `react-konva` for canvas interactions.  
- **Edge Case Handling**:  
  - Error boundaries (React) + custom toast notifications.  

---

# Addendum: Sticker

---
### **1. Sticker Library Screen**  
- **Mobile**: Bottom sheet with tabs (Categories, Favorites, Recent).  
- **Desktop**: Left sidebar with expandable folders.  

### **2. Sticker Shop Screen**  
- **Components**:  
  - Featured banner carousel.  
  - "Free Sticker of the Month" section.  
  - Purchase history and download queue.  

### **3. Sticker Upload Portal**  
- **Components**:  
  - Drag-and-drop zone for sticker files.  
  - Tagging system (keywords, categories).  
  - Earnings dashboard for creators.  


### **UI Screens**  
- **Canvas Toolbar**: Add "Stickers" icon next to "+" button.  
