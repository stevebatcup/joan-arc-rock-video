# Anachronic: Historical/Literary Characters Through Musical Genres

## Project Overview

**Concept:** Create cinematic music videos that explore historical and literary figures through unexpected, anachronistic musical genres. Each video pairs a recognizable character with a genre that illuminates their emotional journey in fresh ways, enhanced with sophisticated orchestral arrangements.

**Example:** Joan of Arc through 90s/00s emo rock

**Core Innovation:** 
- Use AI-generated music (Suno) as foundation
- Add human compositional skill via orchestral enhancements
- Pair with AI-generated visuals using "actor as character" formula
- Create narrative through three distinct visual "tracks" or themes

**Differentiation:** This is NOT pure AI content. The orchestral arrangements, visual curation, narrative structure, and conceptual pairing are all human artistic choices that elevate AI-generated elements into cohesive artistic statements.

---

## Production Workflow

### Phase 1: Concept & Lyrics Development
**Goal:** Establish character, genre, and emotional arc

**Process:**
1. Select historical/literary character with strong emotional journey
2. Identify musical genre that resonates with their internal experience
3. Research character's life, key moments, psychological state
4. Write original lyrics that:
   - Use first-person POV (character's internal voice)
   - Match genre conventions (emo = confessional, grunge = raw, glam = theatrical, etc.)
   - Follow standard song structure with strategic instrumental breaks
   - Build from intimate verses to cathartic choruses
   - Include 2-3 strategic 8-bar instrumental breaks for orchestral showcases

**Claude's Role:**
- Research character background
- Suggest thematic elements and emotional beats
- Write original lyrics in appropriate genre style
- Structure song with instrumental breaks for orchestral enhancement
- Create artifact with lyrics formatted for Suno input

**Deliverable:** Complete lyrics with structure tags, ready for Suno

---

### Phase 2: Music Generation (Suno)
**Goal:** Generate foundation track with intentional gaps for orchestral enhancement

**Process:**
1. Craft detailed Suno prompt including:
   - Specific genre and era (e.g., "early 2000s emo rock")
   - Vocal style and energy
   - Instrumentation guidelines
   - Emotional progression cues
   - Reference artists for style
2. Input lyrics with instrumental break tags
3. Generate 3-5 versions
4. Select best version based on:
   - Vocal performance quality
   - How well it honors instrumental breaks
   - Overall energy and emotional arc
   - Mix quality
5. Extract 12-track stems (vocals, drums, bass, guitar, keyboard, strings, brass, woodwinds, percussion, synth, FX, other)

**Claude's Role:**
- Write optimized Suno prompts based on genre and character
- Suggest multiple prompt variations for testing
- Advise on evaluating different generated versions

**Deliverable:** Suno-generated track with extracted stems, ready for DAW import

---

### Phase 3: Orchestral Enhancement
**Goal:** Add sophisticated compositional layers that showcase human musical skill

**Process:**
1. Import stems into DAW (Logic Pro, Ableton, etc.)
2. Analyze harmonic structure and emotional beats
3. Compose orchestral arrangements for:
   - **Verses:** Sparse support (solo cello, violas, subtle texture)
   - **Pre-Choruses:** Building tension (strings entering, brass hints)
   - **Choruses:** Full orchestral support (strings soaring, brass punctuation)
   - **Instrumental Breaks:** Featured orchestral moments (8-bar showcases)
   - **Bridge:** Vulnerability or tension (solo instruments, chamber arrangements)
   - **Final Chorus:** Epic orchestral peak (full section, choir if appropriate)
   - **Outro:** Ethereal fade (choir, sustained strings)
4. Record/program orchestral parts
5. Mix Suno stems with orchestral layers
6. Master final audio

**Claude's Role:**
- Suggest orchestral arrangement ideas based on emotional arc
- Recommend instrumentation for specific moments
- Advise on dynamic build and orchestral structure

**Deliverable:** Final mixed audio with orchestral enhancements

---

### Phase 4: Visual Strategy & Preset Development
**Goal:** Establish three distinct visual "tracks" that tell the character's story

**Visual Track Concept:**
Each video intercuts between 3 thematic visual streams that together create narrative:

**Example for Joan of Arc:**
- **Track 1 "Origins":** Young Joan in rural France, hearing voices, isolation, family life
- **Track 2 "Warrior":** Joan in armor, battlefield, leading armies, medieval warfare
- **Track 3 "Anachronic Stage":** Joan and her soldiers as an emo rock band, performance aesthetic, instruments, stage energy

**Process:**
1. Analyze song structure and identify which visual tracks map to which sections
2. Create visual preset prompts for each track:
   - **Base formula:** "[Actor Name] as [Character Name]"
   - **Track-specific elements:** setting, costume, mood, lighting, action
   - **Stylistic consistency:** establish visual language for each track
3. Map visual tracks to song timeline:
   - Which track dominates verses? Choruses? Bridge?
   - Where do tracks intercut or blend?
   - What's the visual arc across the whole piece?

**Claude's Role:**
- Develop three cohesive visual track concepts
- Write detailed preset prompts for each track (including actor, character, setting, mood, lighting, action, style)
- Create visual arc/timeline mapping tracks to song structure
- Ensure anachronistic elements feel intentional, not random

**Deliverable:** 
- Three visual track preset prompts
- Timeline/structure document showing which tracks appear when
- Visual arc description

---

### Phase 5: Image Prompt Generation
**Goal:** Generate ~200 specific image prompts across three visual tracks

**Process:**
1. Work in batches of 10-20 prompts at a time
2. Use preset framework but vary:
   - Specific actions/poses
   - Camera angles (close-up, medium, wide, silhouette)
   - Lighting scenarios
   - Emotional expressions
   - Environmental details
   - Composition elements
3. Ensure variety within each track:
   - Different emotional beats
   - Different visual compositions
   - Mix of intimate and epic shots
4. Create prompts that can pair for img2vid:
   - Start/end frame pairs for 5-second clips
   - Subtle motion potential (hair blowing, flames flickering, eyes moving)
5. Include transition/intercut prompts where tracks blend

**Prompt Formula:**
```
[Actor Name] as [Character Name], [Track-Specific Setting], 
[Specific Action/Pose], [Camera Angle], [Lighting], 
[Emotional Tone], [Compositional Elements], [Style Notes]
```

**Example:**
"Natalie Portman as Joan of Arc, medieval battlefield at dusk, raising sword toward sky, low angle hero shot, golden hour backlighting, determined expression, smoke and banners in background, cinematic medieval realism"

**Claude's Role:**
- Generate batches of 10-20 prompts per session
- Ensure variety and coverage across all visual tracks
- Create start/end frame pairs for img2vid workflow
- Track total prompt count toward ~220 goal
- Maintain consistency within tracks while varying specifics

**Deliverable:** ~220 image prompts organized by visual track, formatted for easy copy/paste into image generators

---

### Phase 6: Video Prompt Generation
**Goal:** Create i2v prompts that bring static images to life

**Process:**
1. Review generated images and select best candidates for animation
2. For each selected image pair (start/end frames), write i2v prompt specifying:
   - Type of motion (subtle/dynamic)
   - Camera movement (push in, pull out, pan, static)
   - Subject movement (hair blowing, turning head, raising weapon, etc.)
   - Environmental motion (flames flickering, flags waving, smoke drifting)
   - Emotional progression if relevant
3. Create variety in motion types:
   - **Intimate moments:** Subtle (eyes moving, slight head turn, breathing)
   - **Action moments:** Dynamic (sword swing, running, dramatic gesture)
   - **Atmospheric moments:** Environmental (wind, fire, weather effects)
   - **Performance moments:** Stage energy (playing instruments, singing, band dynamics)
4. Match motion intensity to musical moments:
   - Quiet verses = subtle motion
   - Building pre-chorus = increasing motion
   - Explosive chorus = dynamic motion
   - Instrumental breaks = featured orchestral performance visuals

**Video Prompt Formula:**
```
[Motion description], [camera movement], [subject action], 
[environmental effects], [5 seconds], [cinematic], [smooth motion]
```

**Example:**
"Slow motion hair and cape blowing in wind, subtle camera push in, subject's eyes shifting from down to forward gaze, embers floating in background, 5 seconds, cinematic, smooth motion"

**Claude's Role:**
- Write i2v prompts matched to specific image pairs
- Suggest motion types appropriate to musical moments
- Ensure variety in motion vocabulary
- Match motion intensity to song dynamics
- Create prompts optimized for Runway/Kling/other i2v tools

**Deliverable:** Video prompts for each selected image pair, organized by song section

---

## Project Guidelines & Best Practices

### Character Selection Criteria
**Viable characters have:**
- Strong emotional journey or internal conflict
- Cultural recognition (not necessarily mainstream)
- Visual iconography (distinctive costume, setting, or imagery)
- Thematic resonance with chosen genre

**Actor Casting Strategy:**
- Use A-list or highly recognizable actors as visual anchors
- Ensure actor has played similar roles (increases AI recognition)
- Test with simple "[Actor] as [Character]" prompt before committing
- Consider actor's range and emotional expressiveness

### Genre Pairing Philosophy
**Good pairings:**
- Illuminate character's internal experience in unexpected ways
- Feel conceptually meaningful, not random
- Have stylistic overlap (Joan's defiance = emo's emotional intensity)
- Offer orchestral enhancement opportunities

**Avoid:**
- Surface-level "this would be funny" pairings without depth
- Genres that clash with orchestral enhancement
- Overly obscure genres that lose audience

### Visual Track Development
**Effective tracks:**
- Each tells a distinct part of the story
- Work independently but enhance each other when intercut
- Have clear visual identity (color palette, lighting, composition style)
- Progress emotionally across the video

**The Anachronistic Track:**
- Should feel intentional, not goofy
- Bridges historical/literary and modern musical contexts
- Can be stylized/theatrical rather than realistic
- Celebrates the genre (costumes, instruments, performance energy)

### Orchestral Enhancement Strategy
**Purpose:**
- Differentiate from pure AI content
- Add emotional depth and cinematic weight
- Showcase human compositional skill
- Create featured moments in instrumental breaks

**Approach:**
- Serve the song, don't overwhelm it
- Use orchestral texture for emotional beats
- Feature orchestration in the intentional gaps
- Match intensity to song dynamics

---

## Technical Specifications

### Audio
- **Suno Output:** 44.1kHz, stereo
- **Stem Extraction:** 12-track separation
- **Final Mix:** Professional mastering, suitable for video sync

### Visuals
- **Image Generation:** 1024x1024 or 1024x1792 (vertical for social)
- **i2v Output:** 5-second clips, 24fps minimum
- **Final Video:** 1920x1080 or higher, 24-30fps

### Workflow Tools
- **Music Generation:** Suno AI
- **Image Generation:** Flux, Midjourney, DALL-E, or Nano Banana
- **i2v:** Runway, Kling, or similar
- **DAW:** Logic Pro, Ableton, FL Studio, or equivalent
- **Video Editing:** Any professional NLE

---

## Success Criteria for Proof of Concept

A successful proof of concept demonstrates:

✅ **Workflow viability:** All steps function as planned  
✅ **Orchestral enhancement adds value:** Human arrangements elevate AI foundation  
✅ **Visual concept works:** Three-track approach tells coherent story  
✅ **Anachronistic pairing resonates:** Genre choice illuminates character  
✅ **Technical quality:** Professional-level audio and visual output  
✅ **Differentiation:** Final product clearly distinct from standard AI content  

---

## Future Project Ideas

### Historical Figures:
- Vincent van Gogh + Grunge
- Cleopatra + Disco
- Marie Curie + Synthwave
- Captain Ahab + Sea Shanty Metal
- Nikola Tesla + Electronic/Industrial

### Literary Characters:
- Ophelia + Shoegaze/Dream Pop
- Jay Gatsby + Enhanced Jazz
- Dorian Gray + Darkwave
- Heathcliff + Gothic Rock/Post-Punk
- Jane Eyre + Indie Folk/Riot Grrrl

### Expanding the Format:
- Mini-documentary style (interview footage + music video)
- Lyric video variant (focus on words + imagery)
- "Making of" content showing orchestral enhancement process
- Educational series about the historical figures

---

## Brand Identity

**Series Name:** Anachronic (or alternative: "Out of Time," "Through the Genre Glass")

**Tagline:** "Exploring historical and literary icons through unexpected musical genres, enhanced with orchestral depth."

**Positioning:** 
- Composer/filmmaker exploring character psychology through music
- AI as creative partner, human artistry as differentiator
- Educational + entertaining
- Premium production values

**Audience:**
- History/literature enthusiasts
- Music lovers (especially genre fans)
- Film/video creators
- AI + human creativity advocates
- Students and educators

---

## Notes for Claude

**When assisting with this project:**

1. **Stay in character context:** Always remember which character and genre we're working with
2. **Maintain consistency:** Visual tracks and prompts should feel cohesive
3. **Think cinematically:** Every prompt should consider composition, lighting, emotion
4. **Serve the arc:** All elements should support the character's emotional journey
5. **Balance AI and human:** Celebrate both the AI tools and human creative choices
6. **Be specific:** Vague prompts get vague results—details matter
7. **Work in batches:** Don't try to generate all ~200 prompts at once
8. **Track progress:** Keep count of prompts generated, sections completed
9. **Adapt as needed:** If something isn't working, adjust the approach
10. **Celebrate the weird:** The anachronistic juxtaposition is the point—lean into it

**Key reminders:**
- The "[Actor] as [Character]" formula is crucial for visual consistency
- Instrumental breaks are for orchestral showcase—don't forget them
- Three visual tracks should be distinct but complementary
- Quality over quantity—better to have 80 great prompts than 120 mediocre ones
- This is proof of concept—perfection isn't required, viability is

---

## Project Status Template

**Current Project:** [Character Name] - [Genre]  
**Phase:** [1-6]  
**Completed:**
- [ ] Lyrics written
- [ ] Suno track generated
- [ ] Stems extracted
- [ ] Orchestral arrangement planned
- [ ] Visual tracks defined
- [ ] Image prompts: [X/~200]
- [ ] Images generated
- [ ] Video prompts written
- [ ] Video clips generated
- [ ] Final edit complete

**Next Steps:** [What needs to happen next]

---

## Prompt Naming Convention:

LY## - Lyrics prompts (song structure, genre variations, lyrical themes)
IM## - Image prompts (visual descriptions for image generation)
VI## - Video prompts (i2v motion descriptions)
MU## - Suno Prompts (the actual music generation prompts) since those are distinct from lyrics.

Examples:
MU01, MU02, MU03... = Suno music generation prompts
LY01, LY02, LY03... = Lyric variations or new songs
IM01, IM02, IM03... = Image generation prompts (will be batches of 10-20)
VI01, VI02, VI03... = Video/i2v prompts

*This documentation is a living document and will evolve as the production process is refined through actual project work.*