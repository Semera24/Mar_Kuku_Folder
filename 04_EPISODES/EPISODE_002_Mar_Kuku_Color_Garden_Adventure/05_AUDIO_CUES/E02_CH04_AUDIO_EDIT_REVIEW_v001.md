# CH04 Audio Edit Review v001

Date: 22 October 2026 (Africa/Addis_Ababa).
Status: EDIT CANDIDATE — OWNER LISTENING REQUIRED. Not approved final audio or a verified cue sheet.

## Files and exact save directories

Original upload: `Mar and Kuku — Colour Garden Adventure (CH04).wav`.
Original SHA-256: `d5c5295075efc02dc068f8b8b3f9fe6263f561998fc4485979e60c5b52fb2aea`.
The original was not renamed, moved or modified.

Save `E02_CH04_Match_Red_Yellow_Blue_v002_EDIT_REVIEW_FULL_MIX.wav` in:
`/Users/yonassayfu/Desktop/DoroNesh_2D_Animation/06_AUDIO/MUSIC/EPISODE_002/CH04/`

Save this document as `E02_CH04_AUDIO_EDIT_REVIEW_v001.md` in:
`/Users/yonassayfu/Desktop/DoroNesh_2D_Animation/04_EPISODES/EPISODE_002_Mar_Kuku_Color_Garden_Adventure/05_AUDIO_CUES/`

Keep any matching source stems under the chapter's `01_STEMS/`. They do not automatically align with this edited full mix. Never layer the full mix and its stems together accidentally. Existing destination collisions have not been checked on the Mac; do not overwrite a different file.

## Result and evidence

- Source duration: 149.290667 seconds (02:29.29 rounded).
- Candidate duration: 90.42 seconds (01:30.42), stereo 48 kHz, 16-bit PCM WAV.
- All 26 retained transcript speech intervals are sample-identical to the original. No voice speed, pitch or gain adjustment within those intervals.
- Removed source intervals include the repeated blue question and Point, extra standalone Red, and the incorrect Blue with yellow line. Automated interval checks confirm none of their reported samples was retained.
- Yellow and blue response holds measure exactly 4.00 seconds between the supplied utterance boundaries. Their audible vocal-free status still needs listening confirmation.
- WAV reopened successfully; original hash unchanged. Candidate sample peak: 30619/32768; samples at an integer full-scale endpoint: 0. This is a sample-domain check, not a true-peak/loudness certification.
- No independent listening or new ASR was performed. Speech boundaries and instrumental labels come from the user-supplied Manus transcript. These checks cannot certify transcription accuracy, pronunciation, natural musical joins, or unreported voice tails.

## Unresolved pronunciation

The phrase at source 15.06–20.54 is unchanged. Its candidate interval is 01.40–06.88 seconds. Manus marked yellow uncertain, possibly yellowed. Listen specifically to this phrase. If it is wrong, repair or regenerate that phrase using the selected voice reference before audio approval; do not silently replace it with transcript text.

## Edit recipe

Keep source 13.66–134.38, leaving 0.50 seconds before first reported speech and 0.60 seconds after the final line. Apply a 150 ms opening fade and 400 ms ending fade in those reported music margins.

Each replacement below joins the two listed music portions with a linear audio crossfade. No repeated music loops, synthesized audio, inserted digital silence or global time stretching were used. These joins are not beat-matched or independently auditioned. AUDIO crossfades do not change the rule against VISUAL pose crossfades.

| Purpose | Source interval replaced (seconds) | Retained source music portions (seconds) | Crossfade | Candidate interval (seconds) |
| --- | --- | --- | --- | --- |
| Yellow response hold | 52.76–62.30 | 52.76–54.80 + 60.26–62.30 | 80 ms | 39.10–43.10 |
| Before yellow matching explanation | 64.18–68.38 | 64.18–64.72 + 67.84–68.38 | 80 ms | 44.98–45.98 |
| Blue response hold; remove repeated question and Point | 80.62–99.06 | 80.62–84.40 + 98.76–99.06 | 80 ms | 58.22–62.22 |
| Remove extra standalone Red | 110.62–111.72 | 110.62–110.68 + 111.24–111.72 | 40 ms | 73.78–74.28 |
| Remove incorrect Blue with yellow | 114.02–118.32 | 114.02–114.70 + 117.92–118.32 | 80 ms | 76.58–77.58 |
| Before transition to green orange purple | 124.18–128.40 | 124.18–124.72 + 127.86–128.40 | 80 ms | 83.44–84.44 |

The extra Red is tightly spaced: only 60 ms separates the prior phrase from it in the supplied transcript. Its removal uses a 40 ms fade wholly inside reported music. Listen closely for a clipped ending or residual consonant around the recap join. All source boundaries are provisional until auditioned.

## Provisional speech mapping

These are mathematical remappings of the supplied transcript, not newly measured onsets. Source seconds refer to the original upload; candidate seconds refer only to this edited WAV. No master timeline placement exists. Do not apply the original transcript unchanged to the candidate.

| Original seconds | Candidate seconds | Supplied line |
| --- | --- | --- |
| 14.16–14.48 | 0.50–0.82 | Look. |
| 15.06–20.54 | 1.40–6.88 | Each basket has a color marker: red, yellow [UNCERTAIN: sounds like yellowed], blue. |
| 21.72–24.12 | 8.06–10.46 | Let’s match our flowers. |
| 24.60–27.28 | 10.94–13.62 | These petals are red. |
| 28.38–31.62 | 14.72–17.96 | Look for the red marker. |
| 31.72–34.02 | 18.06–20.36 | There it is. |
| 35.02–38.30 | 21.36–24.64 | Red petals, red marker. |
| 38.36–40.50 | 24.70–26.84 | They match. |
| 41.70–43.76 | 28.04–30.10 | Now it’s your turn. |
| 44.58–47.64 | 30.92–33.98 | These petals are yellow. |
| 48.34–51.10 | 34.68–37.44 | Which basket has the matching marker? |
| 51.64–52.76 | 37.98–39.10 | Point to it. |
| 62.30–64.18 | 43.10–44.98 | The yellow marker. |
| 68.38–71.62 | 45.98–49.22 | Yellow petals, yellow marker. |
| 71.68–73.90 | 49.28–51.50 | They match. |
| 74.56–76.26 | 52.16–53.86 | These petals are blue. |
| 76.82–78.98 | 54.42–56.58 | Which basket has the matching marker? |
| 79.58–80.62 | 57.18–58.22 | Point to it. |
| 99.06–100.68 | 62.22–63.84 | The blue marker. |
| 101.66–104.96 | 64.82–68.12 | Blue petals, blue marker. |
| 105.04–107.10 | 68.20–70.26 | They match. |
| 108.36–110.62 | 71.52–73.78 | Red with red. |
| 111.72–114.02 | 74.28–76.58 | Yellow with yellow. |
| 118.32–121.36 | 77.58–80.62 | Blue with blue. |
| 121.44–124.18 | 80.70–83.44 | Our flowers have matching places. |
| 128.40–133.78 | 84.44–89.82 | Now let’s match green, orange, and purple. |

## Review and next gate

Listen to the full candidate, paying particular attention to:
1. Yellow pronunciation in candidate 01.40–06.88.
2. Both 4-second answer gaps and their musical joins.
3. The recap after Red with red and the transition from Yellow with yellow to Blue with blue.
4. Intact beginnings/endings of every line and the closing transition to green, orange and purple.

Do not mark this approved until the owner listens. If joins are distracting, revise against matching instrumental stems or regenerate a short passage rather than claiming that crossfades ensure musical continuity.

After listening approval, verify onsets on this exact selected candidate (or obtain a fresh transcript), then enter them in the episode's single current cue sheet. Frame mapping at 30 fps uses the selected file timebase and half-up rounding for nonnegative frame offsets. Do not invent scene placements before approval. This report does not authorize editor assembly.
