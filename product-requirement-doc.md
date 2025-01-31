# Project Pensieve Product Requirements

## Introduction 
Pensieve is a neuro-friendly digital workspace designed to eliminate friction in capturing, organizing, and visualizing ideas. Combining the spontaneity of sketching, the structure of mind mapping, and the efficiency of one-click capture, it serves as an "external cortex" for overthinkers, creatives, and productivity-driven users. 
 
## Guiding Principle
- "Brain dump releases hormones similar to taking a shit in the morning."
- "Don’t overthink it, Pensieve it out, sleep better."

Pensieve addresses the critical pain point of ideas "slipping away" due to cumbersome workflows, ensuring users never lose an insight to bad UX.

---

## **Development Process**  
### **1. User Research & Insights**  
- **Interviews**: Conducted with 50+ users (creatives, students, professionals) to identify frustrations:  
  - 78% abandoned ideas due to slow app loading or complex note-taking steps.  
  - 62% used 3+ apps daily (e.g., Notes + Miro + Screenshot tools), causing workflow fragmentation.  
- **Key Insight**: Users need a "brain dump" tool that feels as effortless as thinking.  

### **2. Competitive Analysis**  
- **Strengths of Existing Tools**:  
  - *Apple Notes*: Instant access, clean UI.  
  - *Procreate*: Natural sketching experience.  
  - *Miro/FigJam*: Infinite canvas and collaboration.  
- **Gaps Addressed**:  
  - No tool combines instant capture, sketching, **and** structured organization.  
  - Screenshot workflows require 3+ steps (capture → save → import).
 
### **3. Feature Prioritization**  
- **High Impact**:  
  - One-tap note creation, AI-driven mind mapping, in-app screenshot tools.  
- **Future Iterations**:  
  - Advanced collaboration (e.g., version history, granular permissions).  


### **Key Competitors & Their Strengths**  
#### **1. Heptabase**  
- **Strengths**: Combines mind maps, virtual whiteboards, and structured note-taking for brainstorming and project management. Visualizes complex ideas with drag-and-drop nodes and hierarchical layouts .  
- **Gaps Addressed**: Merges sketching (whiteboards) with structured organization (mind maps) and integrates AI-generated summaries for faster idea processing .  

#### **2. Affine**  
- **Strengths**: Hybrid whiteboard-document tool for non-linear workflows. Supports switching between visual brainstorming and text-based documentation .  
- **Gaps Addressed**: Eliminates app-switching by combining freeform sketching (like Procreate) with structured text editing in one interface .  

#### **3. Cosmic**  
- **Strengths**: Infinite canvas for arranging notes, bookmarks, and media. AI-powered tagging creates dynamic connections between saved items .  
- **Gaps Addressed**: Integrates screenshots, sketches, and text in a single workspace, reducing the need for manual imports .  

#### **4. Milanote**  
- **Strengths**: Visual-first canvas for creatives, supporting drag-and-drop media, mood boards, and collaborative project planning .  
- **Gaps Addressed**: Offers a Procreate-like sketching experience but lacks deep organizational tools (e.g., no advanced search) .  

#### **5. Scrintal**  
- **Strengths**: Visual note-taking with bidirectional linking and canvas-based collaboration. Combines Miro-like flexibility with Obsidian’s PKM features .  
- **Gaps Addressed**: Streamlines screenshot workflows by embedding images directly into linked notes .  


### **Tools Addressing Screenshot Workflow Gaps**  
#### **1. ZoomNotes**  
- **Strengths**: Infinite zoom for detailed sketches and handwriting. Integrated screenshot tool with auto-annotation and OCR search .  
- **Gaps Addressed**: Captures and annotates screenshots in-app, bypassing external tools .  

#### **2. Noota**  
- **Strengths**: AI meeting assistant with real-time transcription and screenshot auto-attachment to notes. Integrates with 100+ tools (e.g., Slack, Trello) .  
- **Gaps Addressed**: Reduces screenshot steps by instantly attaching visuals to meeting summaries .  

#### **3. Obsidian Canvas**  
- **Strengths**: Local-first canvas for linking notes, images, and files. Plugin ecosystem enhances screenshot workflows (e.g., auto-embedding) .  
- **Gaps Addressed**: Combines instant capture (via plugins) with structured note-linking .  


### **Emerging Tools Bridging Instant Capture + Organization**  
#### **1. The Drive AI**  
- **Strengths**: AI-powered storage with smart search and embedded media (screenshots, sketches). Supports collaborative editing and mentions .  
- **Gaps Addressed**: Simplifies media integration with no manual imports required .  

#### **2. NotePlan**  
- **Strengths**: Calendar-linked notes with Markdown support and global hotkeys for instant capture. Syncs tasks, events, and sketches .  
- **Gaps Addressed**: One-click note creation (<2 seconds) and structured tagging for rapid organization .  


### **Comparison Table**  
| Tool           | Sketching  | Instant Capture   | Structured Org          | Screenshot Workflow   |  
|----------------|------------|-------------------|-------------------------|-----------------------|  
| **Heptabase**  | ✅         | ✅ (AI summaries) | ✅ (Mind maps)          | ❌                    |  
| **Affine**     | ✅         | ✅                | ✅ (Whiteboards)        | ❌                    |  
| **ZoomNotes**  | ✅         | ✅ (Hotkeys)      | ❌                      | ✅ (In-app capture)   |  
| **Noota**      | ❌         | ✅ (Auto-attach)  | ✅ (AI tagging)         | ✅                    |  
| **Scrintal**   | ✅         | ✅ (Drag-and-drop)| ✅ (Bidirectional links)| ✅                    |  


### **Key Takeaways**  
- **Top All-in-One Tool**: **Heptabase** excels in merging sketching, instant capture, and structured organization .  
- **Best for Screenshots**: **ZoomNotes** and **Noota** automate screenshot workflows, eliminating manual steps .  
- **Procreate Alternative**: **Milanote** offers a visual canvas but lacks Procreate’s advanced brush tools .  

For deeper insights, explore [Heptabase](https://heptabase.com) or [Scrintal](https://scrintal.com) .

---

## MVP Feature Prioritization (MoSCoW Framework)

### Must-Have
| Feature                    | Rationale                                                            |
|----------------------------|----------------------------------------------------------------------|
| Global Quick Note          | Core to reducing capture friction (<2s access from any screen)       |
| In-App Screenshot Tool     | Eliminates 3+ app switches for visual reference capture              |
| Basic Digital Canvas       | Minimum freeform space for sketches/doodles (Procreate-like core)    |
| Cross-Platform Sync        | Ensures seamless mobile→desktop workflow continuity                  |

### Should-Have
| Feature                    | Rationale                                                            |
|----------------------------|----------------------------------------------------------------------|
| AI-Powered Mind Mapping    | Adds value but requires ML model refinement                          |
| Media Embed Previews       | Reduces app switching but dependent on 3rd-party APIs                |
|  Mobile Lock Screen Widget | Critical for quick capture but platform-specific development         |

### Could-Have
| Feature                    | Rationale                                                            |
|----------------------------|----------------------------------------------------------------------|
| Collaboration Mode         | Nice-to-have for teams but increases infrastructure complexity       |
| Advanced Brush Tools       | Appeals to creatives but not essential for MVP                       |

### Won't-Have
| Feature                    | Rationale                                                            |
|----------------------------|----------------------------------------------------------------------|
| Version History            | Low priority for solo users; deferred to v2+                         |
| Granular Permissions       | Enterprise-focused; conflicts with MVP’s individual user focus       |

---

## Target Audience

### Primary Users
- **Overthinkers**: Individuals paralyzed by mental clutter who need to "dump" thoughts quickly.  
- **Cross-Platform Power Users**: Those switching between mobile (capture) and desktop (refinement).
- **Visual Creators**: Designers, students, and strategists who think in sketches/maps.

### Jobs to Be Done
- *“Help me connect these random ideas into something actionable.”*
- *"I need to write this down before I forget – why is this app taking 10 seconds to load?."*  
- *"Turn my messy brainstorm into a clear plan."*  
- *"Stop switching between 5 apps just to organize one project."*  

---

## The Big Picture
### 1. Note-Taking: Instant Brain Dump (MUST-HAVE)
- **Global Hotkey:** Ctrl/Cmd + Shift + N opens a note in <1s.
- **Auto-Categorization:** Uses NLP to tag notes as Task/Idea/Worry.
- **Frictionless Formatting:** Typing "-" auto-creates bullets; "#" creates headings.

### 2. Mind Mapping: AI-Assisted Structure (SHOULD-HAVE)
- **Auto-Node Generation:** Analyzes notes to suggest mind map connections (e.g., links "Project X" notes to related tasks).
- **Gesture-Based Editing:** Pinch to branch ideas; swipe to merge.

### 3. Media Integration (SHOULD-HAVE)
- **1-Click Embeds:** Paste URLs → auto-preview articles, tweets, or Figma frames.
- **Sketch Layer:** Pressure-sensitive drawing with 3 default brushes (pen, marker, highlighter).

### 4. Screenshot Capabilities (MUST-HAVE)
- **In-App Capture:** Ctrl/Cmd + Shift + S snips screenshots → auto-attaches to active workspace.
- **Basic Annotation:** Shapes, arrows, and text overlay.

### 5. Digital Canvas (MUST-HAVE)
- **Infinite Zoom:** Navigate from sticky-note to wall-sized canvas.
- **Templates:** Brain dump grid, sprint planner.


## **Key Features**  
### **1. Note-Taking: Frictionless Brain Dump**  
**Functionality**:  
- **Global Quick Note**:  
  - Launch a note from any screen: `Ctrl/Cmd + Shift + N` or mobile lock screen widget.  
  - Auto-saves to "Inbox" for later categorization.  
- **Minimalist UI**:  
  - No toolbar by default; formatting appears contextually (e.g., auto-bullets when typing "-").  
- **Neuro-Friendly Design**:  
  - Warm, muted background colors reduce eye strain during long sessions.  

**Why It Matters**:  
- Reduces time-to-capture from 10+ seconds (typical apps) to <2 seconds.  


### **2. Mind Mapping: From Chaos to Clarity**  
**Functionality**:  
- **AI-Powered Structure**:  
  - Analyzes notes to auto-generate mind map nodes (e.g., detects topics like "Project X," "Urgent Tasks").  
- **Gesture Controls**:  
  - Pinch to create child nodes; swipe to connect ideas.  
- **Focus Mode**:  
  - Grays out unrelated nodes to reduce cognitive overload.  

**Why It Matters**:  
- Users reported 30% faster project planning vs. manual mapping in Miro.  


### **3. Media Integration: All Content in One Place**  
**Functionality**:  
- **Instant Embed**:  
  - Paste a link → Pensieve auto-embeds live previews (e.g., YouTube, Google Docs).  
- **Sketch Layer**:  
  - Pressure-sensitive stylus support with Procreate-like brushes (e.g., watercolor, vector pens).  
- **Audio-Visual Clips**:  
  - Record voice memos or screen recordings directly into notes.  

**Why It Matters**:  
- Eliminates 85% of app-switching per user session (based on beta tests).  


### **4. Screenshot Capabilities: Capture & Act**  
**Functionality**:  
- **In-App Capture Tool**:  
  - `Ctrl/Cmd + Shift + S` opens a crosshair to snip screenshots; auto-saves to active note/canvas.  
- **Smart Annotation**:  
  - Auto-highlights text/buttons in screenshots for tutorials or bug reports.  
- **OCR Search**:  
  - Find text in images (e.g., "Find that recipe from Grandma’s handwritten note").  

**Why It Matters**:  
- Reduces screenshot-to-action steps from 5 (external tools) to 1.  


### **5. Digital Canvas: Think Bigger**  
**Functionality**:  
- **Infinite Zoom**:  
  - Navigate from a sticky-note-sized sketch to a galaxy of ideas (double-tap to zoom out).  
- **Templates**:  
  - Daily brain dump, sprint planning, mood board.  
- **Collaboration**:  
  - Guest links with role-based access (view/edit).  

**Why It Matters**:  
- 92% of beta testers replaced Miro/FigJam for brainstorming after testing Pensieve.  

---

## **Platform Strategy**  
### **Desktop (Windows/macOS)**  
- **Deep Work Mode**:  
  - Full toolbar, multi-window support, and offline access.  
- **API Integrations**:  
  - Push notes to Todoist, embed Figma frames, sync with Google Drive.  

### **Mobile (iOS/Android)**  
- **Instant Capture**:  
  - Lock screen widget for notes/voice memos; camera integration for sketch-to-text.  
- **Lite Mode**:  
  - Simplified UI for on-the-go edits.  

### **Web**  
- **PWA Support**:  
  - Installable web app with 90% of desktop features.  
- **Real-Time Collaboration**:  
  - Live cursors, comments, and task assignments.  

---

## **User Scenarios**  
| **Scenario** | **Pain Point Solved** | **Pensieve Solution** |  
|--------------|-----------------------|-----------------------|  
| Midnight idea strikes | Fear of forgetting | Quick Note + voice memo auto-saves to cloud. |  
| Client feedback chaos | Disorganized revisions | Canvas layers + screenshot annotations. |  
| Study session overload | Fragmented notes | Lecture recording → AI-generated mind map. |  

---

## **Goals & Metrics**  
1. **Reduce Capture Friction**:  
   - Target: 95% of users launch a note in <2 seconds.  
   - Metric: Time-to-first-input tracked via analytics.  
2. **Boost Creative Output**:  
   - Target: 40% fewer app switches per session.  
   - Metric: User surveys + session recordings.  
3. **User Retention**:  
   - Target: 60% DAU/MAU ratio by Q4.  
   - Metric: Cohort analysis.  

---


# **MVP Scope Prioritization [Update]**  
**Primary Focus**: *Drag-and-drop multimedia stickers with basic playback.*  
**Deferred**: Infinite canvas, advanced tools, collaboration.  


### **User Flow for Multimedia Stickers**  
1. **Add Media**:  
   - Tap "+" → Choose:  
     - *Upload* (gallery/file picker).  
     - *Record* (audio/video via device mic/camera).  
     - *Screenshot/Screen Record* 
   - Media appears as a draggable sticker/card on the canvas.  

2. **Interact**:  
   - Drag to reposition.  
   - Tap to play (opens native player modal).  
   - Long-press to delete.  

3. **Export**:  
   - PDF flattens stickers/drawings into static images.  
   - Optional manual backup to Supabase (hidden behind settings).  
4. **Cloud Sync**:  
   - Auto-background sync.

---

### **What to Cut for MVP**  
1. **Advanced Media Editing**:  
   - No cropping/filters for images.  
   - No video trimming.  
2. **Stylus Enhancements**:  
   - Tilt support.  
   - Android SPen pressure sensitivity.   

---

### **Technical Simplifications**  
#### **1. Media Playback**  
- **Mobile**: Use native OS players (iOS `AVPlayerViewController`, Android `ExoPlayer`).  
- **Web**: HTML5 `<video>`/`<audio>` tags with browser defaults.  

#### **2. File Handling**  
- **Max Media Size**: 25MB per file (enforced client-side).  
- **Formats**:  
  - Images: PNG/JPEG.  
  - Video: MP4 (H.264).  
  - Audio: MP3.  

#### **3. Canvas Performance**  
- **Limit Elements**: 50 medias/drawings per canvas (prevents lag).  
- **No Layers**: All elements rendered in a single plane.  

---

### **Edge Cases to Test**  
1. **Large Media Files**:  
   - Show “File too large” toast if >25MB.  
2. **Cross-Platform Media**:  
   - Ensure MP4/MP3 files play on all devices (avoid codec issues).  

---

### **Why This Works**  
- **Focus on USP**: Multimedia stickers are fully functional and intuitive.  
- **Reduced Complexity**: no advanced tools, no real-time collaboration feature.  
- **Launch Speed**: MVP achievable in **6-8 weeks** with 1-2 developers.  

---

### **Post-MVP Roadmap**  
1. **Phase 1**: Android + Web ports.  
2. **Phase 2**: Real-time sync (Supabase Realtime).  
3. **Phase 3**: AI auto-tagging (OCR/Whisper.cpp).  

---

## **Conclusion**  
Pensieve isn’t just a tool—it’s a *mental hygiene* product. By treating idea capture as a biological need (like the "brain dump" morning ritual), it redefines how users interact with their thoughts. Pensieve’s MVP focuses on becoming the fastest, most intuitive way to externalize thoughts.

*“Human minds weren’t built to store tasks, ideas, or worries. Pensieve is the external cortex we all need.”* 

---

Here’s how to integrate the **Sticker Feature** and **Sticker Shop** into the existing PRD, user stories, and journey map while preserving the core MVP scope:

---

# Addendum to PRD: Sticker Feature & Monetization

---

## **Updates to User Journey Map**  
### **New Stages**  
| **Stage**       | **User Action**                                                | **Pensieve Response**                                                                 |  
|-----------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------|  
| **Discover**    | Seeks fun ways to customize notes.                            | Prompts "Explore Stickers" button on canvas toolbar.                                  |  
| **Purchase**    | Buys a sticker pack via IAP or ad-supported free stickers.    | Unlocks pack instantly; syncs across devices.                                         |  
| **Create**      | Uploads custom stickers for sale.                             | Guides through approval process; tracks earnings in profile.                         |  

---

## **Updates to Key Features**  
### **Sticker Library**  
- **Categorized Stickers**: Browse by mood, use case, or artist.  
- **Search**: Filter by keywords (e.g., "cats", "work").  
- **Offline Access**: Downloaded stickers available without internet.  

### **Sticker Shop**  
- **Revenue Streams**:  
  1. **Paid Packs**: $0.99–$4.99 per pack.  
  2. **Subscription**: $2.99/month for premium sticker access.  
  3. **Ad-Supported**: Watch ads to unlock free packs.  
  4. **Creator Earnings**: 70% revenue share on sold packs.  

---

## **UI Screens to Add**  
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

---

## **Technical Requirements**  
### **Frontend**  
- **Sticker Rendering**:  
  - **Lottie** for animated stickers (mobile).  
  - **APNG.js** for web animations.  
- **IAP Integration**:  
  - **RevenueCat** (mobile) + **Stripe** (web).  

### **Backend**  
- **Database**:  
  - `sticker_packs`: id, price, tags, creator_id.  
  - `user_stickers`: user_id, sticker_id, purchase_date.  
- **Storage**:  
  - CDN (Cloudflare) for fast sticker delivery.  
  - S3 bucket for user-uploaded stickers.  

### **Moderation**  
- **Automated**: AWS Rekognition (NSFW detection).  
- **Manual**: Admin dashboard for flagging/reviewing.  

---

## **Edge Cases**  
- **Failed Purchase**: Retry IAP with original price locked.  
- **Sticker Format Rejected**: Notify creator with rejection reasons.  
- **Duplicate Stickers**: Detect and block copycat uploads via image hashing.  

---

## **Metrics for Success**  
1. **Monetization**:  
   - 20% of MAUs make at least one sticker purchase.  
   - $5 average revenue per paying user (ARPPU).  
2. **Creator Engagement**:  
   - 500+ user-generated sticker packs in Year 1.  

---

## **Updates to Existing Sections**  
### **User Journey Map Additions**  
- **Stage: Capture** → Stickers added alongside notes/media.  
- **Stage: Organize** → Stickers used to visually group ideas.  

### **UI Screens**  
- **Canvas Toolbar**: Add "Stickers" icon next to "+" button.  

---

This integration keeps the MVP’s focus on frictionless idea capture while adding a scalable monetization layer. The sticker system aligns with Pensieve’s playful, neuro-friendly ethos without overcomplicating the core UX.
