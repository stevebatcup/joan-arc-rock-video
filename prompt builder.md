# Image Prompt Builder Guide - Joan of Arc Music Video
## Sora-Optimized for Direct Actor Likeness Generation

---

## PROJECT OVERVIEW

**Project:** Anachronic - Joan of Arc through Early 2000s Emo Rock  
**Tool:** Sora (via Wicked AI or DALL-E API for image generation)  
**Goal:** Generate 100+ high-quality images across 4 visual tracks for music video production  
**Approach:** Direct actor likeness ("ACTOR as CHARACTER") leveraging Sora's superior facial recognition

---

## CAST & CHARACTERS

### The 6-Piece Band

**1. JOAN OF ARC** → **Zendaya**  
Lead vocals, rhythm guitar (fluid - can play any instrument or just perform)

**2. JEAN DE DUNOIS** → **Oscar Isaac**  
Bass, backing vocals (fluid - warrior companion, steady presence)

**3. JEAN D'ALENÇON** → **Martin Freeman**  
Lead guitar (fluid - loyal friend, passionate performer)

**4. LA HIRE** → **Denzel Washington**  
Drums, percussion (fluid - fierce warrior, powerful presence)

**5. CHARLES VII** → **Timothée Chalamet**  
Keys, rhythm guitar, percussion (fluid - the weak king who abandons Joan)

**6. YOLANDE OF ARAGON** → **Cate Blanchett**  
Violin, keys, backing vocals (fluid - mentor figure, elegant power)

### Instrument Flexibility Note
Band members can fluidly swap instruments throughout the video. They may play guitar, bass, drums, keys, violin, percussion, or simply perform/sing. The goal is visual variety and emotional resonance, not literal role assignment.

---

## CHARACTER NOTATION IN PROMPTS

### Direct Actor Likeness Approach (Sora)

Since Sora has excellent actor recognition, use **direct notation**:

✅ **Correct Format:**
```
"Zendaya as Joan of Arc..."
"Oscar Isaac as Jean de Dunois..."
"Martin Freeman as Jean d'Alençon..."
"Denzel Washington as La Hire..."
"Timothée Chalamet as Charles VII..."
"Cate Blanchett as Yolande of Aragon..."
```

❌ **Old Format (No Longer Used):**
```
"A Joan of Arc character with features similar to Zendaya..."
"A young woman inspired by Zendaya as Joan of Arc..."
```

### Multiple Characters in Single Prompt

**CRITICAL RULE: Maximum 3 characters per shot**

Once you exceed 3 characters in frame, image quality degrades significantly, especially facial consistency. Structure prompts accordingly:

**Solo shots (1 character):** ~60% of prompts
**Duo shots (2 characters):** ~30% of prompts  
**Trio shots (3 characters):** ~10% of prompts  
**Never:** 4+ characters in single frame

**Examples:**
- ✅ "Zendaya as Joan of Arc and Oscar Isaac as Jean de Dunois..."
- ✅ "Zendaya as Joan of Arc, Martin Freeman as Jean d'Alençon, and Denzel Washington as La Hire..."
- ❌ "Zendaya as Joan of Arc with all five band members..."

---

## SORA PROMPTING BEST PRACTICES

### Optimal Prompt Structure

**Length:** Under 120 words (Sora performs best with concise prompts)  
**Target:** 150-200 words maximum per prompt  
**Complexity:** 1-2 primary visual elements per prompt (simple > complex)

### Cinematic Shot List Format

Every prompt should follow this structure:

1. **Shot Type** (in CAPITALS at the start)
2. **Scene Setup** - Location, time, atmosphere
3. **Subject & Action** - Character(s), specific actions, emotions
4. **Camera Angle & Lens** - Perspective, focal length
5. **Lighting & Color** - Light sources, mood, palette
6. **Physics & Materials** - Textures, forces (wind, fire, fabric)
7. **Exclusions** - What to avoid ("do not write text on the image")

### Camera Shot Types (Mix These Up)

**Distance:**
- EXTREME CLOSE-UP (ECU)
- CLOSE-UP (CU)
- MEDIUM CLOSE-UP (MCU)
- MEDIUM SHOT (MS)
- MEDIUM WIDE SHOT (MWS)
- WIDE SHOT (WS)
- EXTREME WIDE SHOT (EWS)

**Angles:**
- LOW ANGLE SHOT
- HIGH ANGLE SHOT
- EYE LEVEL SHOT
- BIRD'S EYE VIEW
- DUTCH ANGLE SHOT
- OVER-THE-SHOULDER (OTS)

### Lens Specifications

- **24mm wide angle** - environmental context, group shots
- **35mm standard** - natural perspective, general use
- **50mm** - balanced, cinematic
- **85mm portrait** - character focus, shallow depth of field
- **Shallow depth of field** - subject isolation
- **Deep focus** - everything sharp

### Lighting Descriptors

- **Golden hour** - warm, soft, magical
- **Blue hour** - cool, ethereal, mysterious
- **Candlelight** - warm, intimate, flickering
- **Stage lighting** - dramatic, colored, high contrast
- **Firelight** - orange, dancing, warm
- **Backlighting** - silhouettes, rim light, dramatic
- **Natural light** - soft, diffused, organic
- **High contrast** - dramatic shadows, stark
- **Moody** - shadowy, atmospheric, tense

---

## VISUAL TRACK PRESETS

Create prompts based on these four distinct visual tracks. Each track has specific aesthetic guidelines.

### TRACK 1: ORIGINS / ISOLATION

**Purpose:** Establish Joan's calling, isolation, and divine connection before her warrior journey

**Era & Capture:**
- Medieval rural France, 1420s
- Natural, pastoral settings
- Dawn/dusk magic hour filming
- Intimate, documentary-style capture

**Production Design:**
- Wheat fields, forest clearings, village edges
- Simple wooden structures, stone churches
- Rustic, authentic medieval peasant environment
- Minimal props, emphasis on natural beauty

**Lighting:**
- Soft golden hour (dawn/dusk)
- Candlelight for interior moments
- Natural diffused sunlight
- Ethereal, gentle, spiritual quality
- Warm color temperature

**Wardrobe & Styling (Joan):**
- Simple medieval peasant dress (earth tones, rough linen)
- Long hair, loose or simply braided
- Bare feet or simple leather shoes
- No armor, no weapons yet
- Natural, unglamorous authenticity

**Wardrobe & Styling (Band Members):**
- Medieval peasant clothing (browns, grays, earth tones)
- Village companions aesthetic
- Practical working clothes
- Simple, period-appropriate

**Performance & Camera:**
- Intimate close-ups on Joan's face (listening, hearing voices)
- Quiet, contemplative moments
- Joan alone in wide landscapes
- Small group interactions (max 2-3 people)
- Various angles: low, high, eye-level
- 35mm or 50mm lens for natural perspective

**Editorial & Effect:**
- Soft focus, dreamy quality
- Natural film grain
- Gentle color grading (warm, organic)
- Minimal contrast, softer shadows

**Finish:**
- Cinematic pastoral realism
- Ethereal without being fantasy
- Intimate, personal, spiritual

**Vibe:**
- Lonely, haunting, divine obsession
- The girl who hears voices
- Isolation before transformation
- Quiet power building

**Exclusions:**
- Do not write text on the image
- Avoid overt fantasy elements
- No modern elements
- No weapons or armor yet

---

### TRACK 2: WARRIOR

**Purpose:** Joan as military leader, battlefield commander, armored warrior—power and violence

**Era & Capture:**
- Medieval battlefield, 1429-1430
- Siege warfare, open field combat
- Golden hour warfare, smoke-filled atmosphere
- Epic, heroic cinematography

**Production Design:**
- Medieval battlefields with smoke and fire
- Castle sieges, burning structures
- Banners, heraldic symbols, medieval weapons
- Muddy, chaotic, visceral warfare
- Strategy tents, military camps

**Lighting:**
- Golden hour backlit through smoke
- Firelight from burning structures
- Dramatic shadows, high contrast
- Orange and red tones from flames
- Silhouettes against fire

**Wardrobe & Styling (Joan):**
- Full medieval plate armor (silver/steel)
- White banner with fleur-de-lis
- Sword raised or at side
- Hair tied back or hidden under armor
- Battle-worn, dirt and blood
- Heraldic tabard over armor

**Wardrobe & Styling (Band Members):**
- Medieval armor (varied styles)
- Soldiers, commanders, warriors
- Battle-worn, muddy, bloodied
- Weapons (swords, bows, polearms)
- Heraldic colors and symbols
- Brotherhood of warriors aesthetic

**Performance & Camera:**
- Epic low angle hero shots
- Close-ups of intense faces
- Wide shots of battlefield scale
- Various dramatic angles
- Smoke and fire as foreground/background elements
- 24mm wide for scale, 50mm for character focus

**Editorial & Effect:**
- High contrast, dramatic
- Desaturated with orange/teal push
- Film grain, gritty texture
- Motion blur for action
- Smoke and particle effects

**Finish:**
- Cinematic medieval warfare
- Gritty realism with epic scale
- Powerful, violent, glorious

**Vibe:**
- Fierce, defiant, powerful
- Burden of command
- Violence and glory
- Warriors united in battle

**Exclusions:**
- Do not write text on the image
- Avoid gratuitous gore (suggest violence, don't show explicit)
- No modern warfare elements

---

### TRACK 3: ANACHRONIC STAGE

**Purpose:** Joan and her band as early 2000s emo rock performers—cathartic musical expression

**Era & Capture:**
- Early 2000s emo/punk rock aesthetic
- Concert venue, stage performance
- Dramatic stage lighting
- High-energy performance cinematography

**Production Design:**
- Dark stage with dramatic lighting
- Smoke machines, stage haze
- Musical instruments (guitars, bass, drums, violin, keys)
- Microphones, stands, cables
- Minimal set, focus on performers
- Intimate venue aesthetic (not arena scale)

**Lighting:**
- Stage lighting: blues, purples, deep reds
- High contrast shadows
- Spotlights, backlighting
- Colored gels, dramatic pools of light
- Smoke catching light beams
- Moody, atmospheric

**Wardrobe & Styling (Joan):**
- Early 2000s emo aesthetic
- Dark clothing (black, deep reds, purples)
- Band t-shirts, worn jeans, or performance clothes
- Eyeliner, emotional expression
- Hair down or styled emo-fashion
- Leather jacket or hoodie
- Raw, authentic performance style

**Wardrobe & Styling (Band Members):**
- Emo/punk rock aesthetic (early 2000s)
- Dark clothes, band tees, worn denim
- Individual style but cohesive band aesthetic
- Casual performance wear
- Authentic musician look (not costume-y)

**Performance & Camera:**
- Concert cinematography style
- Close-ups on faces (emotion, sweat, intensity)
- Close-ups on hands playing instruments
- Medium shots of performers with instruments
- Wide stage shots showing 2-3 band members
- Various dynamic angles
- Over-shoulder shots from behind performers
- Audience POV shots

**Editorial & Effect:**
- High contrast, vibrant stage colors
- Motion blur for energy (minimal, for static image)
- Lens flares from stage lights (subtle)
- Film grain for analog feel
- Saturated colors in lighting

**Finish:**
- Raw concert cinematography
- Intimate and explosive
- Authentic emo performance energy

**Vibe:**
- Cathartic, emotional, defiant
- Raw performance vulnerability
- Explosive energy release
- Musical unity and chemistry

**Exclusions:**
- Do not write text on the image
- Avoid overly polished/pop aesthetic
- No medieval elements in this track
- Keep it authentic emo, not parody

---

### TRACK 4: PYRE / TRANSCENDENCE

**Purpose:** Joan's martyrdom and transformation into eternal legend—beautiful and terrible

**Era & Capture:**
- Medieval public execution, 1431
- Rouen marketplace
- Fire and smoke cinematography
- Transcendent, spiritual, apocalyptic beauty

**Production Design:**
- Wooden pyre structure, stakes
- Medieval town square architecture
- Crowd of witnesses (shadowy, background)
- Rising flames and smoke
- Ethereal, hellish, beautiful

**Lighting:**
- Firelight from below (orange, red, gold)
- Divine light from above (white, ethereal)
- High contrast between fire and shadow
- Smoke creating atmospheric haze
- Backlit silhouettes
- Dramatic, supernatural quality

**Wardrobe & Styling (Joan):**
- Simple white or pale garment (symbolic purity)
- Hair loose, blowing in heat
- Bound to stake or standing defiant
- Face lit by flames but peaceful
- Eyes skyward, transcendent expression
- Becoming light itself

**Wardrobe & Styling (Band Members - Optional/Minimal):**
- Medieval crowd clothing (dark, shadowy)
- Witnesses in background (not primary focus)
- Grief-stricken, reaching but unable to help
- Or: Absent entirely (Joan's solitary moment)

**Performance & Camera:**
- Low angle shots (Joan towering, heroic)
- Extreme close-ups on eyes, face
- Wide shots showing scale of flames
- Fire as foreground and background
- Smoke obscuring and revealing
- Transcendent, spiritual framing
- 85mm for intimate face shots, 24mm for epic scale

**Editorial & Effect:**
- Rich orange/red fire tones
- Ethereal white light from above
- High contrast, dramatic
- Particle effects (embers, ash floating)
- Dreamlike, surreal quality

**Finish:**
- Beautiful apocalyptic spirituality
- Fire as transformation, not torture
- Transcendent, legendary

**Vibe:**
- Martyrdom, transformation, eternal
- Peaceful defiance
- Becoming legend
- Fire as beauty and power

**Exclusions:**
- Do not write text on the image
- Avoid explicit torture/suffering imagery
- Focus on transcendence, not pain
- Keep it spiritual, not exploitative

---

## IMAGE PROMPTING WORKFLOW

### Task Overview

**Goal:** Create 100+ images across 4 visual tracks  
**Distribution by Track:**
- Track 1 (Origins): ~25 images
- Track 2 (Warrior): ~25 images
- Track 3 (Stage): ~30 images (more band visibility)
- Track 4 (Pyre): ~20 images

**Shot Distribution:**
- 60% Joan solo shots
- 25% Joan + 1 band member
- 10% Joan + 2 band members
- 5% Band members without Joan (1-3 characters)

### Prompt Generation Strategy

We're building a **massive visual library**, not a strict shot list. The goal is to create more material than we need, covering:
- What we know we need
- What we think we might need
- What we might not need but could be useful

**Flexibility over rigidity:** Generate variety within each section and accept that the editing process will determine final selection.

### 10-Section Outline Structure

Organize prompts into these functional categories:

#### THE NARRATIVE CORE (40% of images)
**Section 1: Joan's Calling & Isolation (Track 1)**
- Joan alone hearing voices
- Rural France, fields, forests
- Divine moments, spiritual connection
- Family/village dismissing her

**Section 2: The Warrior Emerges (Track 1 → Track 2)**
- Donning armor for first time
- Transition from peasant to warrior
- Early training, preparation
- Determination and resolve

**Section 3: Battlefield Glory (Track 2)**
- Joan leading troops
- Combat, smoke, fire, chaos
- Banner raised, sword drawn
- Epic warfare moments

**Section 4: The Betrayal & Trial (Track 2 → Track 4)**
- Capture, imprisonment
- Trial scenes (Joan defiant)
- Band members as witnesses, unable to help
- Charles VII's absence

#### THE MUSIC VIDEO SPECTACLE (40% of images)
**Section 5: Stage Performance - Intimate (Track 3)**
- Close-ups on Joan singing
- Quiet acoustic moments
- Individual band members with instruments
- Emotional vulnerability

**Section 6: Stage Performance - Explosive (Track 3)**
- Full band energy
- Dynamic performance shots
- Crowd energy, hands up
- Cathartic release, peak moments

**Section 7: Band Chemistry & Interaction (Track 3)**
- Band members glancing at each other
- Musical synchronization
- 2-3 members in frame
- Performance connection

#### THE EMOTIONAL/THEMATIC DEEP CUTS (20% of images)
**Section 8: Fire & Transcendence (Track 4)**
- Joan on the pyre
- Flames rising, smoke swirling
- Peaceful defiant expression
- Becoming light/legend

**Section 9: Symbols & Atmosphere (All Tracks)**
- Banners, flames, smoke
- Close-ups on hands, eyes, objects
- Textural details
- Environmental atmosphere

**Section 10: Interstitial & Transitions (All Tracks)**
- Ambiguous moments between tracks
- Silhouettes, shadows
- Abstract emotional beats
- Connective tissue for editing

---

## PROMPT TEMPLATE & STRUCTURE

### Required Elements Per Prompt

Every prompt must include:

1. **Prompt ID** (e.g., ORIGINS_001, WARRIOR_015, STAGE_023, PYRE_008)
2. **Visual Track** (Track 1, 2, 3, or 4)
3. **Characters Present** (list actor names)
4. **Shot Type** (in CAPITALS at start of prompt)
5. **Full Prompt** (150-200 words, copyable block)

### Prompt Template Format

```
**PROMPT ID:** TRACK#_###

**VISUAL TRACK:** Track # - [Track Name]

**CHARACTERS:** 
- [Actor Name as Character Name]
- [Actor Name as Character Name] (if applicable)

**PROMPT:**
[SHOT TYPE] [Scene setup with location and time]. [Character(s) and specific action]. [Camera details: lens, angle, movement]. [Lighting description and color palette]. [Physics/materials: wind, fire, fabric]. [Emotional tone]. [Style/finish notes]. Do not write text on the image.
```

### Example Prompt - Track 1 (Origins)

**PROMPT ID:** ORIGINS_003

**VISUAL TRACK:** Track 1 - Origins/Isolation

**CHARACTERS:**
- Zendaya as Joan of Arc

**PROMPT:**
```
CLOSE-UP. Dawn in a misty wheat field in rural France, 1420s. Zendaya as Joan of Arc kneels alone, eyes closed, head tilted slightly upward as if listening to something only she can hear. 35mm lens, shallow depth of field with wheat stalks softly blurred in foreground. Soft golden hour light from low angle, warm color temperature, gentle glow on her face. She wears simple medieval peasant dress in earth tones, hair loosely braided. Natural light, ethereal quality. A gentle breeze moves wheat and loose strands of hair. Her expression is peaceful but intense, caught between this world and something beyond. Cinematic pastoral realism, soft focus, natural film grain. Do not write text on the image.
```

### Example Prompt - Track 2 (Warrior)

**PROMPT ID:** WARRIOR_012

**VISUAL TRACK:** Track 2 - Warrior

**CHARACTERS:**
- Zendaya as Joan of Arc
- Oscar Isaac as Jean de Dunois

**PROMPT:**
```
LOW ANGLE SHOT. Medieval battlefield at dusk, smoke and embers filling the air. Zendaya as Joan of Arc in full plate armor stands with white banner raised high, beside Oscar Isaac as Jean de Dunois in battle-worn armor holding a sword. 24mm wide angle lens. They are silhouetted against orange firelight from burning structures behind them. Smoke drifts across frame. Dramatic shadows, high contrast. Both faces show fierce determination and exhaustion. Mud, blood, gritty realism. Golden hour backlight through smoke creates epic scale. Cinematic medieval warfare aesthetic, desaturated with orange push, film grain. Do not write text on the image.
```

### Example Prompt - Track 3 (Stage)

```
**PROMPT ID:** STAGE_018

**VISUAL TRACK:** Track 3 - Anachronic Stage

**CHARACTERS:**
- Zendaya as Joan of Arc
- Martin Freeman as Jean d'Alençon

**PROMPT:**
MEDIUM CLOSE-UP. Dark intimate concert stage with dramatic blue and purple stage lighting. Zendaya as Joan of Arc sings intensely into microphone, wearing black emo aesthetic clothing with eyeliner, hair loose. Beside her, Martin Freeman as Jean d'Alençon plays lead guitar, focused on his instrument. 50mm lens, shallow depth of field. Stage lights create pools of colored light, smoke machine haze catches beams. High contrast shadows. Both show raw emotional performance energy—sweat, intensity, connection. Early 2000s emo rock aesthetic. Concert cinematography style, motion blur suggesting movement, vibrant colored lighting. Do not write text on the image.
```

### Example Prompt - Track 4 (Pyre)

```
**PROMPT ID:** PYRE_005

**VISUAL TRACK:** Track 4 - Pyre/Transcendence

**CHARACTERS:**
- Zendaya as Joan of Arc

**PROMPT:**
EXTREME CLOSE-UP. Medieval marketplace, flames rising around the frame edges. Zendaya as Joan of Arc's face fills the frame, lit from below by orange firelight and from above by ethereal white light. 85mm portrait lens, shallow depth of field. Her eyes look skyward, expression peaceful and defiant, transcendent. She wears simple pale white garment. Smoke drifts across frame, embers float like stars. Hair moves gently in heat. Firelight creates dramatic contrast—deep shadows and brilliant highlights. Her face shows no fear, only spiritual transformation. Beautiful apocalyptic cinematography, rich orange and gold tones, high contrast, ethereal quality. Do not write text on the image.
```

---

## CONTENT GUIDELINES & RESTRICTIONS

### Sora Content Policies

**Cannot Generate:**
- Real people without consent (we have explicit actor-based approach, acknowledge this is proof-of-concept, non-commercial)
- NSFW/sexual content
- Graphic violence or gore
- Content sexualizing minors
- Copyrighted characters (beyond our historical Joan of Arc)

### Project-Specific Guidelines

**Avoid:**
- Sexual imagery
- Overt terror, especially involving children
- Text or words on images
- Explicit torture or graphic suffering (pyre should be transcendent, not exploitative)
- Gratuitous gore in battle scenes (suggest violence, show consequences, but keep it cinematic not graphic)

**Embrace:**
- Emotional intensity and raw feeling
- Cinematic beauty even in difficult moments
- Transcendence over exploitation
- Power, defiance, vulnerability
- Authentic emo aesthetic (not parody)

---

## BATCH GENERATION WORKFLOW

### Step 1: Select Section
Choose from the 10-section outline based on current needs

### Step 2: Determine Shot Distribution
- How many solo Joan shots?
- How many duo shots (Joan + 1)?
- How many trio shots (Joan + 2)?
- How many band-only shots?

### Step 3: Vary Shot Types
Mix up camera angles, distances, and movements within each batch

### Step 4: Generate Prompts
Create 10-20 prompts per batch, following template structure

### Step 5: Review & Iterate
Check for:
- Character consistency (max 3 per shot)
- Shot type variety
- Track-appropriate aesthetic
- Sora best practices (under 120-200 words, concise, specific)
- All required elements present

---

## QUALITY CONTROL CHECKLIST

Before finalizing any prompt, verify:

✅ **Prompt ID** assigned and formatted correctly  
✅ **Visual Track** specified  
✅ **Characters** listed (1-3 maximum)  
✅ **Shot Type** in CAPITALS at start  
✅ **Length** under 200 words  
✅ **Structure** follows cinematic shot list format  
✅ **Specificity** on location, lighting, camera, emotion  
✅ **Exclusion** "Do not write text on the image" included  
✅ **Content** appropriate (no violations of Sora policies)  
✅ **Aesthetic** matches visual track guidelines  
✅ **Copyable** formatted as clean text block  

---

## PRODUCTION NOTES

### Post-Generation Curation
- Generate more images than needed
- Select best 60-70% for animation phase
- Organize by track and section
- Note which images pair well for transitions

### Image-to-Video Preparation
- Identify strong start/end frame pairs
- Consider motion potential (hair, fabric, fire, eyes)
- Plan camera movements (push-in, pan, static)
- Match motion intensity to song dynamics

### Editing Integration
- Maintain organization by track
- Tag images with emotional beats
- Note which sections of song each image suits
- Create flexibility for creative editing decisions

---

*This prompt builder is a living document. Adjust and iterate based on actual generation results and creative needs. The goal is a massive, varied visual library that serves the music video's emotional arc and cinematic vision.*