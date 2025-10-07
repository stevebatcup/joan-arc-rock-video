# Image Prompt Builder Guide - Joan of Arc Music Video
## Sora-Optimized for Direct Actor Likeness Generation

---

## PROJECT OVERVIEW

**Project:** Anachronic - Joan of Arc through Early 2000s Emo Rock  
**Tool:** Sora for t2i generation, Freepik for upscaling, Higgsfield for i2v  
**Goal:** Generate 100+ high-quality images across 4 visual tracks for music video production  
**Approach:** Direct actor likeness ("ACTOR as CHARACTER") leveraging Sora's superior facial recognition

**CRITICAL CONTEXT REQUIREMENT:** Each prompt must be completely standalone and self-contained. No references to "same as before," "previous shot," or assumptions about shared context between prompts. Every prompt will be used individually in a t2i model interface where no context persists between requests.

---

## HISTORICAL ACCURACY & SETTING EVOLUTION

**Time Period:** 1420s-1430s France (Late Medieval Period, not Early Medieval)
- End of Middle Ages, Hundred Years' War period
- Gothic architecture at peak, just before Renaissance

**Joan's Actual Access to Settings:**
- **ORIGINS (Track 1):** Small rural village (Domrémy), modest parish church, peasant cottage, fields and forests - NO grand cathedrals or elaborate Gothic spaces
- **WARRIOR (Track 2):** Military camps, siege warfare sites, town fortifications, modest castle courtyards - functional not ornate
- **TRIAL/PYRE (Track 4):** Rouen castle chapel (modest), town marketplace execution - NOT grand Gothic cathedral
- **STAGE (Track 3):** Anachronistic, so artistic license allowed for surreal/metaphorical spaces

**PROGRESSION STRATEGY (Option 3 - Surreal Escalation):**
- **Early prompts (1-80):** Grounded in Joan's actual modest medieval settings, historically accurate scale
- **Mid prompts (81-110):** Reality beginning to crack - walls rippling, architecture stretching, surreal elements emerging
- **Late prompts (111+):** Full surreal medieval expressionism - kaleidoscoping geometry, melting architecture, transcendent imagery

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

---

## SORA PROMPTING BEST PRACTICES

### Optimal Prompt Structure

**Length:** Under 120 words (Sora performs best with concise prompts)  
**Target:** 150-200 words maximum per prompt  
**Complexity:** 1-2 primary visual elements per prompt (simple > complex)

### Cinematic Shot List Format - IMAGE PROMPTS ONLY

**CRITICAL:** Image prompts should NOT include camera movement or motion descriptions. Those belong ONLY in video prompts.

Every IMAGE prompt should follow this structure:

1. **Shot Type** (in CAPITALS at the start)
2. **Scene Setup** - Location, time, atmosphere
3. **Subject & Action** - Character(s), specific static poses/positions, emotions
4. **Lens & Framing** - Perspective, focal length, depth of field
5. **Lighting & Color** - Light sources, mood, palette
6. **Physics & Materials** - Static textures, environmental state (wind captured mid-motion, fire frozen)
7. **Exclusions** - "Do not write text on the image" (included in all presets)

**NO camera movement language in image prompts** - no "push in," "dolly," "tracking," "orbiting," etc.

### VIDEO PROMPTS - Motion & Camera Language

Video prompts should contain ALL motion and camera movement details:

**Structure:**
[PRIMARY SUBJECT MOTION] + [SECONDARY MOTION] + [CAMERA MOVEMENT] + [ENVIRONMENTAL EFFECTS] + [PHYSICS DETAILS] + [MOTION NOTES INTEGRATED]

**DO NOT include:** 
- Duration information ("5 seconds")
- Separate motion notes field - integrate everything into the video prompt itself

**Camera Movement Vocabulary:**
- **Tracking shots:** "Camera tracking alongside at ground level maintaining pace"
- **Push/Pull:** "Slow camera push-in toward subject" / "Camera pulling back revealing scale"
- **Orbiting:** "Camera orbiting around subject clockwise" / "Subtle arc movement"
- **Handheld:** "Aggressive handheld camera rush forward, frame shaking with intensity"
- **Crane:** "Crane shot ascending rapidly while spinning"
- **Whip pan:** "Whip pan left to right, motion blur streaking"
- **Dolly zoom:** "Vertigo effect - subject stays same size while background warps"
- **Static:** "Static camera, subject motion only"

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
- LOW ANGLE TRACKING (for action)

### Lens Specifications

- **24mm wide angle** - environmental context, group shots, epic scale
- **35mm standard** - natural perspective, general use
- **50mm** - balanced, cinematic, versatile
- **85mm portrait** - character focus, shallow depth of field, intimacy
- **85mm macro** - extreme detail on objects/hands
- **Shallow depth of field** - subject isolation, bokeh
- **Deep focus** - everything sharp, environmental context

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

## MEDIEVAL VISUAL RICHNESS & SPECIFICITY

### Medieval Architecture as Character

**Specific Structures (matching Joan's historical access):**
- **Small village churches:** Rough stone walls, low ceilings, simple wooden crosses
- **Peasant cottages:** Single room, thatched roof, dirt floor, central hearth, low wooden beams
- **Castle courtyards:** Functional spaces, stone walls, practical not ornate
- **Military tents:** Canvas, rough wooden poles, muddy ground
- **Town marketplaces:** Cobblestones, merchant stalls, medieval town square scale
- **Town walls:** Battlements, gates, functional fortifications

**For Surreal/Late Prompts ONLY (Stage Track & final sections):**
- **Gothic cathedrals:** Soaring ribbed vaults, rose windows, pointed arches (as metaphorical/transcendent spaces)
- **Grand castle halls:** Tapestries, massive fireplaces (anachronistic artistic license)

### Medieval Light Sources (BE SPECIFIC)

Instead of generic "lighting," specify actual medieval sources:
- **Torch fire:** Orange flickering, casting dancing shadows on stone, handheld or wall-mounted
- **Brazier flames:** Large standing fire baskets, intense orange glow, outdoor/courtyard use
- **Candlelight:** Warm intimate glow, wax dripping, multiple candles creating layered light
- **Forge fire:** Intense white-hot center with orange edges, sparks flying
- **Bonfire:** Massive outdoor flames, crowd silhouettes around edges
- **Dawn through windows:** Natural soft light filtering through small openings
- **Golden hour:** Late afternoon sun, warm long shadows across fields
- **Pyre fire:** Orange and red flames from below, creating dramatic uplighting

### Medieval Materials & Textures

**Be specific about what things are made of:**
- **Stone:** Rough-hewn castle walls, worn smooth stone floors, carved details on church elements
- **Iron:** Heavy chains, prison bars, sword blades, armor joints, candleholders
- **Wood:** Rough timber beams, splintered doors, torch handles, pyre structure, simple furniture
- **Fabric:** Heavy wool cloaks, rough linen peasant dress, silk banners (rare), leather straps and armor
- **Metal:** Hammered copper braziers, tarnished silver, rusted iron, polished steel armor

### Medieval Weather & Atmosphere

**Environmental conditions that enhance medieval mood:**
- **Rain on stone:** Water streaming down castle walls, puddles reflecting torchlight, mud
- **Fog in courtyard:** Thick mist swirling around medieval structures, limited visibility
- **Storm:** Lightning illuminating castle silhouette, wind howling, dramatic clouds
- **Dust motes:** In window light beams, showing age and stillness
- **Smoke:** From fires, battles, pyres - always present and atmospheric
- **Heat shimmer:** Around fires, pyres, creating distortion

### Medieval Action & Battle Details

**Specific medieval warfare elements:**
- **Weapons:** Swords, polearms, crossbows, longbows, morning stars, axes - varied not just swords
- **Siege equipment:** Trebuchets, battering rams, scaling ladders, siege towers
- **Formations:** Shield walls, cavalry wedge, archer lines on battlements
- **Heraldry:** Fleur-de-lis on white banners, specific coat of arms, medieval symbols
- **Battle chaos:** Mud spray from hooves, debris flying, smoke thick, bodies suggested not explicit

### Surreal Medieval Elements (for later/intense prompts)

**When reality breaks, use medieval-specific surrealism:**
- **Architecture distorting:** Stone walls rippling like water, vaults stretching impossibly upward, arches melting
- **Medieval symbolism manifesting:** Fleur-de-lis multiplying, religious iconography warping, gargoyles coming alive
- **Fire transcending physics:** Flames defying gravity, spiraling upward unnaturally, responding to sound
- **Illuminated manuscript aesthetics:** Gold leaf effects, decorated borders appearing in air, medieval art styles breaking through
- **Gothic geometry:** Pointed arches fragmenting into kaleidoscopes, ribbed vaults becoming abstract patterns

---

## VISUAL TRACK PRESETS

Create prompts based on these four distinct visual tracks. Each track has specific aesthetic guidelines.
Include "Do not include text in the images" as Sora has a tendency to add text for historial imagery.

### TRACK 1: ORIGINS / ISOLATION

**Purpose:** Establish Joan's calling, isolation, and divine connection before her warrior journey

**Era & Capture:**
- Medieval rural France, 1420s
- Natural, pastoral settings
- Dawn/dusk magic hour filming
- Intimate, documentary-style capture

**Production Design:**
- Wheat fields, forest clearings, village edges
- Simple wooden structures, stone churches (SMALL/MODEST ONLY)
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
- Avoid overt fantasy elements
- No modern elements
- No weapons or armor yet
- No grand cathedrals or elaborate Gothic spaces (not historically accurate)

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
- Castle sieges (modest scale), burning structures
- Banners, heraldic symbols, medieval weapons
- Muddy, chaotic, visceral warfare
- Strategy tents, military camps (FUNCTIONAL NOT ORNATE)

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
- Avoid gratuitous gore (suggest violence, don't show explicit)
- No modern warfare elements

---

### TRACK 3: ANACHRONIC STAGE

**Purpose:** Joan and her band as early 2000s emo rock performers—cathartic musical expression

**Era & Capture:**
- Early 2000s emo/punk rock aesthetic
- MEDIEVAL VENUE transformed to concert space
- Dramatic stage lighting
- High-energy performance cinematography

**Production Design - MEDIEVAL SETTINGS:**

**Early/Grounded Stage Prompts:**
- **Castle courtyard converted to concert venue:** Stone walls, burning braziers for lighting, night sky above, cobblestone ground, instruments on medieval stone platform
- **Small village church transformed:** Rough stone walls, simple wooden beams, candlelight mixed with impossible stage lighting
- **Town marketplace at night:** Cobblestones, merchant stalls pushed aside, medieval crowd as audience, torchlight

**Mid/Reality-Cracking Stage Prompts:**
- **Castle courtyard with warping walls:** Stone beginning to ripple, braziers burning unnaturally bright
- **Church with melting architecture:** Stone liquefying subtly, religious symbols distorting

**Late/Surreal Stage Prompts:**
- **Gothic cathedral as metaphorical space:** Soaring impossible heights, stained glass kaleidoscoping, architecture obeying music not physics
- **Castle courtyard becoming abstract:** Walls fragmenting into geometric shapes, fire defying gravity, medieval structure dissolving into pure color and energy
- **Expressionist medieval nightmare:** All solid medieval elements becoming liquid, multiplying, transcending reality

**Lighting:**
- Stage lighting: blues, purples, deep reds
- High contrast shadows
- Spotlights, backlighting
- Colored gels, dramatic pools of light
- Smoke catching light beams
- Moody, atmospheric
- BRAZIER FLAMES as practical light source mixed with impossible stage lights

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
- Film grain for analog feel
- Saturated colors in lighting
- Surreal distortion increasing with song intensity

**Finish:**
- Raw concert cinematography
- Intimate and explosive
- Authentic emo performance energy
- Medieval setting creating unique anachronistic aesthetic

**Vibe:**
- Cathartic, emotional, defiant
- Raw performance vulnerability
- Explosive energy release
- Musical unity and chemistry
- Medieval architecture responding to modern music

**Exclusions:**
- Avoid overly polished/pop aesthetic
- Keep it authentic emo, not parody

---

### TRACK 4: PYRE / TRANSCENDENCE

**Purpose:** Joan's martyrdom and transformation into eternal legend—beautiful and terrible

**Era & Capture:**
- Medieval public execution, 1431
- Rouen marketplace (HISTORICALLY ACCURATE)
- Fire and smoke cinematography
- Transcendent, spiritual, apocalyptic beauty

**Production Design:**
- Wooden pyre structure, stakes
- Medieval town square architecture (modest marketplace scale)
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
- Avoid explicit torture/suffering imagery
- Focus on transcendence, not pain
- Keep it spiritual, not exploitative

---

## ADVANCED PROMPTING TECHNIQUES

### Vivid Action Scene Strategies

**For intense battlefield/action moments, include:**

1. **Specific physics details:**
   - "Mud exploding up from thundering hooves creating spray"
   - "Sword arcing through frame trailing sparks"
   - "Arrows streaking with motion blur trails"
   - "Banner whipping violently with edges tearing"

2. **Material responses:**
   - "Leather creaking and straining with movement"
   - "Metal armor clanking and scraping"
   - "Fabric snapping with force in wind"
   - "Wood splintering under impact"

3. **Environmental interaction:**
   - "Dust clouds rising with each hoof impact"
   - "Rain streaming down helmet and face"
   - "Smoke churning through frame"
   - "Heat shimmer distorting air around flames"

### Black & White vs. Color Strategy

**Use B&W for:**
- Most intimate/vulnerable Origins moments
- Peak emotional intensity close-ups (screaming, crying)
- Artistic transitions between sections
- Moments emphasizing texture over color

**Use Color for:**
- Stage performance (vibrant lighting essential to emo aesthetic)
- Fire/Pyre scenes (orange essential to meaning)
- Epic battlefield moments (sunset, fire, blood suggested)
- Surreal expressionist sections (color = transcendence/madness)

**Randomly switch between them** for visual variety and impact, following WickedAI's approach

### Composition Boldness

**Push for dramatic, memorable framing:**
- **Extreme angles:** Bird's eye straight down, worm's eye straight up
- **Negative space:** Subject tiny in huge empty space emphasizing isolation
- **Crowd crush:** Face pressed against masses, claustrophobic intensity
- **Silhouettes:** Backlit figures against fire, sunset, or light
- **Reflections:** Action/emotion reflected in armor, water, fire
- **Layered depth:** Foreground smoke/fire/objects framing main subject

---

## PROMPT TEMPLATE & STRUCTURE

### JSON Format Requirements

Each prompt must be formatted as valid JSON with these exact fields:

```json
{
  "id": [number],
  "section": "[Section name describing narrative beat]",
  "track": "Track [1-4] - [Track Name]",
  "shotType": "[SHOT TYPE IN CAPITALS]",
  "characters": "[Character names or 'None']",
  "bpm": [number],
  "imagePrompt": "[Complete standalone image prompt with NO camera movement]",
  "videoPrompt": "[Complete motion and camera prompt with motion notes integrated, NO duration]",
  "motionNotes": "[Comma-separated key motion elements for reference]",
  "priority": "[A/B/C]"
}
```

### Image Prompt Structure (Static, No Camera Movement)

```
[SHOT TYPE IN CAPITALS]. [Medieval location and specific time/conditions]. 
[Actor(s) as Character(s), specific static pose/position, clothing details]. 
[Lens spec, framing]. [Medieval lighting source details]. [Material textures, 
environmental state frozen]. [Emotional tone]. [Color/style notes]. 
[Medieval authenticity or surreal elements as appropriate to section].
```

**Length:** 120-200 words, concise and specific

### Video Prompt Structure (All Motion & Camera)

```
[Primary subject motion with specific body mechanics], [secondary character/element 
motion], [camera movement type and direction], [environmental effects in motion], 
[physics details like spray/smoke/fabric], [lighting changes], [emotional escalation], 
[material sounds implied through motion], [integrated motion notes describing key 
movement beats]
```

**NO duration statements** - remove all "5 seconds" references

---

## QUALITY CONTROL CHECKLIST

Before finalizing any prompt, verify:

✅ **Context Independence:** Prompt makes complete sense standalone, no references to other prompts  
✅ **Historical Accuracy:** Setting matches Joan's actual access for that track/section  
✅ **Surreal Escalation:** Early prompts grounded, later prompts increasingly surreal as appropriate  
✅ **Image Prompt = Static:** No camera movement, no motion verbs  
✅ **Video Prompt = Motion:** All camera and subject movement, motion notes integrated  
✅ **Medieval Specificity:** Actual medieval materials, light sources, architecture named  
✅ **Shot Type Variety:** Mixing distances and angles throughout batch  
✅ **Character Limit:** Maximum 3 characters per shot  
✅ **Length Appropriate:** Image prompts 120-200 words, video prompts as detailed as needed  
✅ **Track Aesthetic Match:** Visual style matches the specific track guidelines  
✅ **Priority Assigned:** A for essential, B for strong support, C for nice-to-have  

---

## INSPIRATION & REFERENCE

**WickedAI Visual Approach:**
- Extreme vividness and dynamic composition
- Bold switching between B&W and color for impact
- Surreal anachronistic juxtapositions (Picard on horseback with guitar)
- Raw cinematic energy, nothing feels static or safe
- High contrast, dramatic lighting, memorable framing

**Our Adaptation:**
- Maintain medieval authenticity early, then break reality intentionally
- Use emo aesthetic mixed with medieval settings for Stage track
- Fire, smoke, and medieval materials as constant visual language
- Escalate from grounded realism to surreal expressionism
- Every prompt should be vivid enough to make someone stop scrolling

---

## PRODUCTION WORKFLOW INTEGRATION

### Post-Generation Workflow
1. **Sora** generates base images from prompts
2. **Freepik** upscales and refines images
3. **Higgsfield** converts to video using video prompts
4. **Editing** assembles into music video with orchestral audio

### Organization Strategy
- Tag all images by track, section, and priority
- Group potential transition pairs
- Note which song sections each image/video suits
- Maintain flexibility for creative editing decisions

---

*This document incorporates lessons learned from WickedAI's visual approach, historical accuracy research for 1420s France, surreal escalation strategy (Option 3), and technical requirements for standalone t2i prompts with separate i2v motion descriptions.*