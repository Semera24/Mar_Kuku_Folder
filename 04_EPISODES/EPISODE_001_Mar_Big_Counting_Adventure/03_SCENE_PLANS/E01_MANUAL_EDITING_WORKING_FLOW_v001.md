# E01 Manual Editing Working Flow v001

**Status:** Production authority for CH05–CH09.  
**Format:** 1920 × 1080, 30 fps.  
**Date:** 2026-10-19.  
**Reference:** Latest read-only production audit in the conversation and the saved manually edited `EPISODE_001_Mar_Big_Counting_Adventure_BackUp.palmier`, timeline `E01_Audio_Master`.

This document governs the remaining chapter workflow and visual continuity. Older scripts, storyboards, cue sheets, and chapter markers remain useful historical references; their old master-timeline positions must not override the current placed audio. This document does not authorize repairs to completed chapters or changes to existing audio or markers. Confirm the intended working project before any future build; do not silently switch between original and backup projects.

## 1. Current Working Approach

The episode uses manually shortened chapter audio. The current edit no longer follows the original full-length chapter schedule. Do not stretch new visuals to old chapter markers or restore removed audio merely to match those markers.

Before each future chapter, inspect the actual audio clip on the working timeline and record:

- Project, timeline, clip ID, source asset, and frame rate.
- Timeline start, duration, and exclusive end frame/timecode.
- Source trim-in and trim-out, speed, and any split segments.
- Adjacent audio clips, fades, gain, and additional audio layers.

The latest reference audit found 15 tracks and 176 stored markers. Completed visuals end at frame 7651 (`00:04:15:01`), while the historical CH04_END remains at frame 11542 (`00:06:24:22`). These are reference observations, not permanent placement instructions. Re-inspect live state before building.

## 2. Approved Visual Template

- Maintain the normal `BG_Village_Open_Yard_v002.png` continuously across chapter joins.
- Place Mar on the left, centred around 24% of canvas width; place Kuku centre-left around 46%.
- Use approximately 63% canvas height for Mar and 40% for Kuku as starting proportions. Match the existing grounded feet baseline, around 93% canvas height, and check each PNG's transparent padding visually.
- Reserve the right-hand area for the teaching stage, objects, or large numbers. Keep both hosts visible and avoid covering their faces, gestures, or feet.
- Use only approved official PNG poses for Mar and Kuku. A chick prop is not a substitute Kuku pose.
- Change pose PNGs with direct hard cuts. No ghosted crossfades between poses.
- Use gentle, grounded position/scale motion only: small breathing, restrained sway, and short purposeful settles. No floating, strong rotation, or unnecessary crossfades.
- Use small coordinated reframes when helpful. Maintain the spatial relationship between background, stage, hosts, and objects; do not let separate layer animation make the scene slide apart.
- Keep sheep small, quiet, and subordinate to the lesson. Keep all teaching content readable at small viewing sizes.
- Do not introduce text, captions, effects, sound effects, transitions, or exports unless separately requested.

## 3. Object-Counting Pattern

Use one approved object PNG duplicated to the required count. Establish the stage, introduce one object at a time at its confirmed count, retain previously counted objects, and hold the completed group for review. Give each object a distinct readable position with consistent scale and sufficient spacing. Never hide an object behind another while it is being counted.

Use a brief position/scale entrance followed by a stable hold. Fit animation to the available sung timing; do not force a slow entrance across the next count. During rapid repeated counting, keep the completed group readable and emphasize individual objects with restrained position/scale cues instead of rebuilding or flashing the whole arrangement.

The manually edited egg scene provides a fixed-stage example: table beneath basket, with separate egg layers above. The flower scene provides a fixed planter with independently placed objects. Reuse this separation of stage and objects; do not copy the strong flower rotation or unrelated stage artwork into later chapters.

| Chapter | Stage and arrangement | Teaching and review pattern | Host direction and ending |
|---|---|---|---|
| CH05 Apples | Seven apples in a simple upper-right tree-like cluster; retain village continuity. No full tree is required by the approved plan. | Add apples 1–7 individually, retain each, then review the complete seven. Space the cluster so every apple remains countable. | Mar Look Up → Point → Talk/Happy; Kuku attentive reactions. Hold the completed group through the usable reward, then clear for Birds at the verified boundary. |
| CH06 Birds | Nine birds in a loose right-side sky arc, separated from host faces and background distractions. | Introduce each bird with a short drift into a stable position; retain all nine for review. Avoid crossing silhouettes during counts. | Mar Listen → Point → Hands Up; Kuku Look Up/Point/Happy. Settle the arc before the next chapter. |
| CH07 Chicks | Ten chicks in readable right-side rows or an arc, with a separate clear area for Number 10. | Add chicks 1–10 individually. Hold all ten and emphasize the final total with the approved Number 10 asset. Keep the hosts distinct from chick props. | Mar Surprise → Hands Up → approved celebratory pose; Kuku official happy/cheer pose where suitable. Quiet sheep activity may support the reward without competing. |
| CH08 Detective | Approved detective stage on the right with two or three large number choices. | Three rounds: find 3, 7, then 10. Preserve the actual placed audio's thinking intervals. Reveal or gently scale-pulse the correct answer only at the verified response. | Mar Think/Listen → Point → Happy; Kuku attentive reactions. Keep choices stable while children think; clear each round cleanly. |
| CH09 Goodbye | Established number presentation/badge in the right teaching area, then a village farewell composition. | Present 0–10 singly at the actual recap cues. Follow the retained summary and goodbye phrases; hold the final composition through the actual ending. | Use official happy/celebratory poses, then Wave. Keep Number 10 and any approved returning group readable. Do not add an overlay, fade, or other effect without explicit authorization. |

## 4. Audio Workflow for Each Remaining Chapter

1. **Inspect the actual placed audio length first.** Record current start, source trims, duration, end, speed, and joins. Do not infer these from the filename or historical chapter markers.
2. **Map the usable sung/counting section.** Read the source-relative transcript as an aid, then verify audible phrases and counts against the retained source interval. Include invitations, individual number starts, repeated passes, major instrumental holds, reward, and ending. Ignore tiny pauses inside lyric lines. Do not guess uncertain words or timings.
3. **Convert timing using the current placement.** For an unspeeded, unsplit clip at 30 fps: `masterFrame = clipStartFrame + round(sourceSeconds × 30) − sourceTrimStartFrame`. Keep only cues within the retained clip range. For split or speed-adjusted audio, use the actual segment/time mapping rather than this simple formula. End frames are exclusive.
4. **Build visuals to the actual clip timing.** Preserve intentional shortening. Use the retained lyric sequence and real review spaces; do not recreate removed sections to satisfy an old plan. Do not create or reposition markers without authorization.
5. **Verify before continuing.** Listen through the chapter and both joins. Check for unintended digital silence, unwanted overlaps, duplicate audio, clipped syllables, missing counts, or truncated rewards. Inspect first/last frames and count transitions for black frames, gaps, or lingering props. Clip coverage alone does not prove audible sound.
6. **Hold unresolved problems for a specific correction.** Do not silently repair audio, move unrelated tracks, or ripple the whole timeline. Record the issue and exact affected interval before requesting or applying an authorized repair.

## 5. Track Organization Recommendation

Use these roles for future organization. They are recommendations, not instructions to rename or rearrange existing tracks now. Resolve existing content by stable track/clip IDs and referenced assets: current names are misleading (`Sheep` also contains the planter; `Teasers` contains stages and count objects).

| Track role | Intended contents |
|---|---|
| Village | Continuous approved village background. |
| Atmosphere/Sheep | Quiet background life only. |
| Teaching Stage | Basket/table, planter, detective stage, or badge as appropriate. |
| Count Objects | Separate object layers/lanes for independently countable apples, birds, or chicks. |
| Numbers | Approved number PNGs, separate from counted objects. |
| Mar | Official Mar pose PNGs only. |
| Kuku | Official Kuku pose PNGs only. |
| Chapter Audio | Clearly identifiable chapter full-mix clips; separate authorized music layers only when required. |

Composite the background beneath atmosphere and foreground teaching content. Keep objects above their stage where required and check the final composite for occlusion. Track names alone do not establish layer purpose or safe edit scope.

## 6. Quality Checklist Before Chapter Approval

- [ ] Correct working project and timeline verified; actual chapter clip start, trim, speed, length, and end recorded.
- [ ] Cue mapping uses current audio placement, not historical master markers.
- [ ] All retained counts and repeated passes have correct visuals; uncertain words/times remain flagged.
- [ ] One new object per count; accumulated group has the correct total and readable spacing.
- [ ] Both hosts remain visible, grounded, consistently scaled, and represented by official poses.
- [ ] Pose cuts are direct; no ghost images, floating, excessive rotation, or distracting motion.
- [ ] Number/object entrances settle within available time; no clipped edges or hidden counted items.
- [ ] Village coverage is continuous, including chapter joins; no accidental black or empty frames.
- [ ] Previous chapter props clear at the intended boundary; new props do not appear prematurely.
- [ ] Keyframes and endpoint holds are checked against actual clip durations, including first and last displayed frames.
- [ ] Audio has been heard through both joins: no unintended silence, duplicate layers, unwanted overlap, or truncated words/reward.
- [ ] Existing unrelated audio, visuals, markers, and completed chapters remain preserved.
- [ ] Any unresolved issue is recorded explicitly; the next chapter does not proceed on an unverified timing assumption.

## Known Issues Not To Copy Forward

- **Stale markers:** Original chapter and detailed markers no longer align with the shortened edit. Treat them as historical reference until an authorized timing reconciliation.
- **Kuku-to-chick substitutions:** The reference uses `E01_Chick_v001` on Kuku's track at `00:02:26:09–00:02:31:09` and `00:03:33:00–00:03:38:00`. Keep Kuku's identity consistent in future chapters.
- **CH03/CH04 audio overlap:** Both chapter mixes play for ten frames at `00:02:50:07–00:02:50:17`. Do not repeat unverified chapter overlaps.
- **Black after Flowers:** Completed visuals end at `00:04:15:01` while later audio continues. Future builds must provide continuous intended picture coverage; the old CH04_END is not the visual endpoint.
- **Overly strong flower rotation:** One measured rotation reaches approximately 42°. Future object motion should remain restrained and readable, using gentle position/scale changes.

These issues are documented for prevention. Creating this authority document does not repair them or authorize edits to existing project content.
