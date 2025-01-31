

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

--- 

Here’s how to integrate the **Sticker Feature** and **Sticker Shop** into the existing PRD, user stories, and journey map while preserving the core MVP scope:

---

# Addendum to PRD: Sticker Feature & Monetization

---

## **New User Stories**  
### **1. User Story: Sticker-Based Creativity**  
**As a creative user**,  
**I want** to add themed stickers (static/animated) to my canvas,  
**So that** I can visually enhance my notes and brainstorm playfully.  

#### **Acceptance Criteria**  
- **AC1.1**: Sticker Library with categories (e.g., Productivity, Memes, Seasonal).  
- **AC1.2**: Drag, resize, and rotate stickers like other canvas elements.  
- **AC1.3**: Animated stickers play on canvas (GIF/APNG formats).  
- **AC1.4**: Users can "favorite" frequently used stickers.  

---

### **2. User Story: Sticker Shop & Purchases**  
**As a user seeking customization**,  
**I want** to browse and buy sticker packs from a Sticker Shop,  
**So that** I can access exclusive designs to personalize my workspace.  

#### **Acceptance Criteria**  
- **AC2.1**: Sticker Shop UI with sections: Featured, Free Monthly, Top Selling.  
- **AC2.2**: In-app purchases (IAP) via Apple Pay/Google Pay/credit card.  
- **AC2.3**: Free stickers require watching a 15s ad or sharing the app.  
- **AC2.4**: Preview sticker packs before purchase.  

---

### **3. User Story: User-Generated Stickers**  
**As a designer/creator**,  
**I want** to upload and sell my sticker packs on the Sticker Shop,  
**So that** I can monetize my creativity and expand Pensieve’s library.  

#### **Acceptance Criteria**  
- **AC3.1**: Sticker upload portal with format guidelines (PNG/GIF, max 500KB).  
- **AC3.2**: Revenue split (e.g., 70% to creator, 30% to Pensieve).  
- **AC3.3**: Moderation system to block inappropriate content.  

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


