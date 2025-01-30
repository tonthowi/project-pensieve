

# **User Stories & Acceptance Criteria**  
*(Prioritized for MVP)*  

---

## **1. User Story: Instant Idea Capture**  
**As an overthinker**,  
**I want** the app to open directly to a blank canvas with zero barriers,  
**So that** I can dump my thoughts immediately without navigating menus or settings.  

### **Acceptance Criteria**  
- **AC1.1**: App launches directly to a blank canvas on all platforms (mobile/tablet/desktop).  
- **AC1.2**: No mandatory login/signup screen before accessing the canvas.  
- **AC1.3**: Basic tools (text, pen, screenshot) are visible by default in a collapsed toolbar.  
- **AC1.4**: Canvas loads in <1 second on all devices.  

---

## **2. User Story: Media as "Stickers"**  
**As a visual thinker**,  
**I want** to drag and drop media (images, audio, video) onto the canvas as movable "stickers,"  
**So that** I can spatially associate media with notes/sketches for better context.  

### **Acceptance Criteria**  
- **AC2.1**: Users can import media via:  
  - Drag-and-drop from desktop.  
  - Gallery picker on mobile/tablet.  
  - In-app screenshot tool.  
- **AC2.2**: Media appears as resizable, movable cards ("stickers") on the canvas.  
- **AC2.3**: Media previews:  
  - Images/videos: Show thumbnail.  
  - Audio: Display waveform + play/pause button.  
- **AC2.4**: Tap/click media to play (audio/video) or expand (images).  
- **AC2.5**: Media stays linked to its original source (e.g., editing source file updates the sticker).  

---

## **3. User Story: Auto-Save Only on Action**  
**As a forgetful user**,  
**I want** the canvas to auto-save only after I add content (text, media, etc.),  
**So that** blank canvases don’t clutter my workspace.  

### **Acceptance Criteria**  
- **AC3.1**: New canvases are *not* saved until the user adds at least one element (text, pen stroke, media).  
- **AC3.2**: Auto-save triggers immediately after:  
  - First element is added.  
  - Subsequent edits (e.g., moving a sticker, writing text).  
- **AC3.3**: Empty canvases close without prompting to save.  

---

## **4. User Story: Intuitive Tool Discovery**  
**As a first-time user**,  
**I want** to find advanced tools (mind mapping, media import) without clutter,  
**So that** I’m not overwhelmed but can still access powerful features when needed.  

### **Acceptance Criteria**  
- **AC4.1**: Core tools (text, pen, screenshot) are always visible in a minimalist toolbar.  
- **AC4.2**: Advanced tools (mind mapping, media library) are tucked under a "+" button or gesture:  
  - Mobile/Tablet: Swipe up from bottom edge.  
  - Desktop: Hover over canvas edge to reveal.  
- **AC4.3**: First-time users see a 3-second animation demonstrating gesture-based tool discovery.  

---

## **5. User Story: Non-Destructive Organization**  
**As a disorganized creator**,  
**I want** to freely move and group elements (text, media, sketches) without losing context,  
**So that** I can reorganize ideas spatially without breaking relationships.  

### **Acceptance Criteria**  
- **AC5.1**: All elements (text, media, sketches) can be moved, resized, or rotated.  
- **AC5.2**: Grouping elements creates a collective "sticker" that retains individual interactivity.  
- **AC5.3**: Users can draw arrows/connectors between elements to show relationships.  

---

# **Edge Cases & Additional Scenarios**  

### **Edge Case 1: Accidental Canvas Closure**  
- **Scenario**: User opens a blank canvas, does nothing, and exits.  
- **Requirement**: App does *not* save the empty canvas (AC3.1).  

### **Edge Case 2: Large Media Files**  
- **Scenario**: User imports a 4K video onto a mobile canvas.  
- **Requirement**: Video is auto-compressed to 720p for performance, with option to restore quality.  

### **Edge Case 3: Offline Use**  
- **Scenario**: User adds media stickers while offline.  
- **Requirement**: Media is cached locally and auto-synced when connectivity resumes.  

---

# **UI Screens to Support These Stories**  
*(Now that user stories are defined, here’s the UI blueprint)*  

| **Screen**                | **Mobile/Tablet**                                     | **Desktop**                                 |  
|---------------------------|-------------------------------------------------------|---------------------------------------------|  
| **1. Blank Canvas**       | - Full-screen canvas<br>- Floating "+" menu at bottom | - Maximized window<br>- Left-edge toolbar   |  
| **2. Media Library**      | - Slide-up panel with thumbnails<br>- Drag to canvas  | - Right-side dock<br>- Searchable grid      |  
| **3. Canvas Settings**    | - Hidden behind long-press on empty canvas area       | - Right-click context menu                  |  
| **4. Auto-Save Status**   | - Tiny cloud icon (gray = unsaved, green = saved)     | - Status bar at top with timestamp          |  

---

# **Why This Approach Works**  
1. **Reduces Friction**: Launching directly into a blank canvas aligns with the "brain dump" philosophy.  
2. **Spatial Context**: Media stickers let users associate ideas visually (e.g., audio note next to a sketch).  
3. **Progressive Disclosure**: Advanced features are hidden but easily discoverable, avoiding clutter.  

