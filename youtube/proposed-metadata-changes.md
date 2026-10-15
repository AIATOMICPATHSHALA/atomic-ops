# Proposed Metadata Changes (awaiting approval)

Status: **NOT APPLIED.** Nothing here has been changed on YouTube.
Approve by batch ID (A–E). After approval, each change will be applied, re-read from the API to verify, and logged in `CHANGELOG.md` with its old and new values.

Text in `{curly braces}` must be confirmed by the teacher. I will not publish a sub-topic I cannot verify.

---

## A. Defective videos (Priority 1)

### A1. `-z1Ku6lsh2E`: 46-second stub
- **Existing title:** Bohr Atomic Model | Atomic Structure Class 14 | Lecture 11 | NEET 2027
- **Recommended title:** Bohr Atomic Model (Short Clip) | Class 11 Chemistry | Full Lecture 11 Link in Description
- **Why:** "Class 14" is wrong. The video is 46 s but presented as a full lecture, so viewers who click leave after 19 s, which tells YouTube the video disappoints. An honest title stops the mismatch.
- **Search intent:** none (not a discovery asset). Purpose: redirect.
- **Description (first lines):**
  ```
  ⚠️ यह सिर्फ 46 सेकंड का clip है। पूरा Lecture 11 (Bohr Atomic Model) यहाँ देखें 👉 https://youtu.be/ZRLj5ImpQpA
  📚 Atomic Structure – पूरी playlist: {playlist link}
  ```
- **Tags:** remove "Atomic Structure Lecture 10". Keep: bohr atomic model, atomic structure class 11, firoz sir, atomic pathshala.
- **Playlist:** remove from every chapter playlist.
- **End screen:** not possible (the video is under 25 s of usable length). **Pinned comment:** "पूरा lecture यहाँ है 👉 https://youtu.be/ZRLj5ImpQpA"
- **Visibility:** unchanged (your rules). Unlisting it would be the cleanest fix, but that is your decision.
- **Metric:** fewer new views landing on the stub. **Confidence:** high that this is a defect; low effect on total views.

### A2. `-UyCGqkdDGs`: truncated Motion in Straight Line Lec 04
- **Existing title:** Motion in Straight Line | Lec : 04 | NEET 2027 Physics | Sashan Yadav Sir
- **Recommended title:** Motion in a Straight Line L04 (Partial Recording) | Class 11 Physics | NEET 2027 | Sashan Sir
- **Why:** The stream ran about 40 minutes but the recording is 5:52, and the description promises a "One Shot". Viewers leave after 32 s on average.
- **Description:** replace the "One Shot Revision" text with:
  ```
  इस class की recording technical issue की वजह से सिर्फ 5 मिनट की है।
  पूरा lecture: {link if a full file exists / "जल्द upload होगा"}
  Motion in a Straight Line – Class 11 Physics | NEET 2027 | Sashan Yadav Sir
  ```
- **Tags (currently none):** motion in a straight line, motion in a straight line class 11, kinematics class 11 neet, sashan yadav sir, atomic pathshala.
- **Question for you:** do you have the full 40-minute file? If yes, upload it as a new video and link it here.
- **Metric:** comments and AVD. **Confidence:** high (defect).

### A3. `oLhq_3-h4ps`: chapter mismatch
- **Existing title:** ठोस के यांत्रिक गुण | Mechanical Properties of Fluids | Lec-01 | NEET 2027 Physics | Mukul Sir #neet
- **Question for Mukul Sir:** is this Fluids L01 or Solids? The tags and the next video (`VpJd-j9IIgo`, "तरलों के यांत्रिक गुण Lec-02") suggest **Fluids**.
- **Recommended title (if Fluids):** तरलों के यांत्रिक गुण | Mechanical Properties of Fluids L01: {sub-topic} | Class 11 Physics | NEET 2027 | Mukul Sir

---

## B. Isomerism series (Class 11 Chemistry, Firoz Ali)

**Why this series first:** it is the current, active series. The next five lectures, a test and a test discussion are scheduled. vidIQ estimates "isomerism class 11" at about 14.4k searches/month and "isomerism one shot" at about 27.6k, but none of the current titles say "Class 11". It also has the lowest median engaged views among Firoz Ali's chapters (116 vs 184 for IUPAC), although the October videos are younger.

| Video | Existing title | Recommended title |
|---|---|---|
| `lc9-yWLWG8I` | Isomerism - समावयवता Lecture 01 \| Selection Pro Batch \| Atomic Pathshala \| By FA Sir | Isomerism (समावयवता) L01: Introduction & Degree of Unsaturation \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `kebWkzFwjKw` | …Lecture 02… | Isomerism (समावयवता) L02: {sub-topic} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `c9TRDb6gqbI` | Structural Isomerism Masterclass \| FGI, Ring-Chain & Metamerism for NEET UG Chemistry 🔥 | Isomerism (समावयवता) L03: Structural Isomerism – {FGI / Ring-Chain} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `wTjXUhxX8Tk` | Structural Isomerism \| FGI, Ring-Chain & Metamerism for NEET UG Chemistry By FA sir | Isomerism (समावयवता) L04: Structural Isomerism – {FGI / Ring-Chain / Metamerism} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `Y0LmdYO3-qk` | Structural Isomerism Lec - 05 \|\| Metamerism for NEET 2027 \|\| Chemistry By Firoz #neet2027 | Isomerism (समावयवता) L05: Metamerism \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `cfUAWwna6Hw` | …Lecture 06… | Isomerism (समावयवता) L06: {sub-topic} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `C_-nYlIOEtY` | …Lecture 07… | Isomerism (समावयवता) L07: {sub-topic} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |
| `4AgMENEJDKw` | …Lecture 08… | Isomerism (समावयवता) L08: {sub-topic} \| Class 11 Chemistry \| NEET 2027 \| Firoz Sir |

Confirm the lecture order of `c9TRDb6gqbI` (3 Oct) and `wTjXUhxX8Tk` (5 Oct). I inferred it from publish dates. Sub-topics marked `{}` come from Firoz Sir's notes.

**Primary search intent:** "isomerism class 11", "{sub-topic} isomerism". **Secondary:** "isomerism neet", "समावयवता", "isomerism hindi medium".

**Thumbnail (series template):** teal Chemistry band; big text = sub-topic (e.g. "METAMERISM"); small "L05 • Class 11"; Firoz Sir cut-out on the right; one example structure pair on the left. The current vidIQ score for L08 is 76/100 ("busy background, low energy"): simplify the background and raise saturation.

**Description (L05 shown; others follow the same structure with their own sub-topic and links):**
```
Metamerism को आसान तरीके से समझिए – कैसे पहचानें कि दो structures metamers हैं, और NEET में इससे कैसे सवाल आते हैं।

📌 इस lecture में:
• Metamerism की definition और पहचान
• {Firoz Sir के notes के अनुसार बाकी points}

⏮ पिछला lecture (L04): https://youtu.be/wTjXUhxX8Tk
⏭ अगला lecture (L06): https://youtu.be/cfUAWwna6Hw
📚 Isomerism – पूरी playlist: {playlist link}

Class 11 Chemistry | NEET 2027 | Hindi Medium | Selection Pro Batch – Firoz Sir (Atomic Pathshala)
🌐 https://atomicpathshala.in   📲 App: {link}   💬 Telegram: {link}
🔔 रोज़ live class के लिए Subscribe करें।

#Isomerism #Class11Chemistry #NEET2027 #HindiMedium #FirozSir
```

**L08-specific fix:** the current description says Isomerism "की dhamakedar shuruat ho rahi hai" (the chapter is starting), which is wrong for Lecture 08. It also mentions an App and Telegram without links. Replace it with the template above.

**Tags (L05 example, 12):** isomerism class 11, metamerism, metamerism class 11, isomerism neet, structural isomerism, समावयवता, isomerism hindi medium, class 11 chemistry, neet 2027 chemistry, organic chemistry class 11, firoz sir, atomic pathshala

**Playlist:** "Isomerism (समावयवता) | Class 11 Chemistry | NEET 2027 | Firoz Sir"
**End screen:** next lecture (left) + playlist (right) + subscribe.
**Cards:** at the point where the previous concept is referenced, card to the previous lecture.
**Pinned comment:** "आज का practice question 👇 {one question from the class}. Answer comment करो – कल class में discuss करेंगे। अगला lecture: {link}"

**Optimise now or leave?** Optimise now. The series is active and will be the target of the Isomerism one-shot and the chapter test this weekend.
**Expected metric:** YouTube Search and Suggested share for the Isomerism videos (baseline: Search 3% channel-wide) and impressions CTR (baseline still needed from Studio).
**Confidence:** medium. Titles help search and suggested matching, but traffic is 76% Browse, so the effect will be modest until the one-shot exists.

---

## C. Human Health and Disease L02–L09 (Class 12 Biology, Sonu Bhaiya)

The current titles all say "Introduction". The proposed sub-topics come from each video's own tags. **Sonu Bhaiya to confirm.**

| Video | Lecture | Proposed title |
|---|---|---|
| `PzEpPRzN9_g` | L02 | Human Health and Disease (मानव स्वास्थ्य और रोग) L02: {sub-topic} \| Class 12 Biology \| NEET 2027 \| Sonu Bhaiya |
| `Qktxp57G3QQ` | L03 | …L03: Infectious Diseases – {Common Cold, …} \| Class 12 Biology \| NEET 2027 \| Sonu Bhaiya |
| `s-62G9OfB5c` | L04 | …L04: Infectious Diseases – Malaria (Plasmodium) & {…} \| … |
| `qVIXyEKFmps` | L05 | …L05: {sub-topic} \| … |
| `AtJLdzzakvM` | L06 | …L06: Acquired Immunity – Active vs Passive \| … |
| `RWUhfuPx0s4` | L07 | …L07: Immune System – B & T Lymphocytes, Antigen \| … |
| `VZB9hv9kUQs` | L08 | …L08: Humoral vs Cell-Mediated Immunity \| … |
| `E2SfRbGoQlI` | L09 | …L09: Lymphoid Organs – Thymus & {…} \| … |

**Search intent:** "{sub-topic} class 12", "human health and disease class 12" (a search term that already reaches the channel: 12 views), "active and passive immunity".
**Description, links, end screen and pinned comment:** same pattern as §B, with the Biology green template.
**Expected metric:** Suggested and Search views on the HHD playlist. **Confidence:** medium.

---

## D. Tag hygiene (about 25 videos; low impact, low risk)

| Defect | Videos | Fix |
|---|---|---|
| Literal placeholder tags "ChapterName", "TopicName" | Biological Classification L03–L07 (`5TNrPiVywlg`, `QCEnL2fKZuw`, `wUY2VtyM4nI`, `vv6fjyDpWpg`, `YyBHMLG2kqA`) | Remove both |
| "Atomic Structure Lecture 10" on other lectures | `ZRLj5ImpQpA`, `p0_7-oox2bE`, `D8pgxuDHdxk`, `-z1Ku6lsh2E` | Use the correct lecture number |
| "Atomic Structure Lecture 05" plus Isobar tags on L07/L08 | `7jEY7Zl8M-o`, `XrlJ4QJ2M-E` | Replace with that lecture's topic |
| "Solution Lecture 01", "Lecture 01" on L02/L03 | `1Fc1beSGXJA`, `HhPaTyhVWIU` | Correct lecture number |
| "neet 2026 physics" on 2027 content | `TN9pGJzF9FQ` | Change to "neet 2027 physics" |
| "PYQ NEEET", "COOMPLETE PYQ…" | `j_qJxFCHPNM` | Fix spelling |
| "jee", "jee thermal properties…" on a NEET Hindi series | Thermal Properties L01–L05 | Remove; YouTube says tags have a minor role, and these signal the wrong audience |
| Sonu Bhaiyya tags on a Yaman Sir video | `PuHKNj7DO3Y` | Replace with Yaman Sir |
| No tags | `a24TjaoASLU`, `L8RkYsdqe6E`, `-UyCGqkdDGs` | Add 10–12 chapter tags |

---

## E. Opening trim / chapter-marker test (5 videos)

Choose 5 recordings with decent views where the transcript shows housekeeping at the start: `kzc7LGDyHNA` (IUPAC 13), `3zxAjnRlM1Q` (HHD 11), `NBHYzRsoffg` (IUPAC 04), `wq_CBZcQLJ4` (HHD 01), `kebWkzFwjKw` (Isomerism 02).

1. Use each video's transcript to find the exact second the teaching starts. For IUPAC 13, the transcript shows greetings and attendance for about the first 4 minutes, then homework checking. I'll find the exact timestamp in Studio's player before proposing it.
2. **Option 1 (reversible):** add chapters in the description, starting `0:00 Attendance & homework` and `MM:SS {Today's topic}`. At least 3 chapters are needed, the first at 0:00, each ≥10 s.
3. **Option 2 (stronger, not reversible once saved):** Studio Editor → Trim the opening housekeeping. The URL, views and comments are kept.
4. Compare non-subscriber AVD and the 1-minute retention for 28 days before vs after. The other 5 comparable videos are the control.
