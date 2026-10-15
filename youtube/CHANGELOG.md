# YouTube Change Log: Atomic Pathshala (AP)

Every change made to the channel is recorded here: what, where, old value, new value, how it was verified, and when (IST). Changes not confirmed by re-reading the channel through the API or Studio are **not** logged as done.

| ID | Date & time (IST) | Change | Where | Old value | New value | Verified? | Approved by |
|---|---|---|---|---|---|---|---|
| — | 2026-10-15 | Initial audit (read-only) | — | — | — | n/a | — |
| A1-1 | 2026-10-15 | Title, description, tags | `-z1Ku6lsh2E` | Title "Bohr Atomic Model \| Atomic Structure Class 14 \| Lecture 11 \| NEET 2027"; description began "…Class 14 \| Lecture 10…"; tag "Atomic Structure Lecture 10" | Title "Bohr Atomic Model (Short Clip) \| Class 11 Chemistry \| Full Lecture 11 Link in Description"; description opens with a link to the full lecture https://youtu.be/ZRLj5ImpQpA; tag changed to "Atomic Structure Lecture 11". Visibility unchanged. | YouTube API returned `updated` for all 3 fields. Independent re-read **pending**: vidIQ credits ran out, and vidIQ's public cache still showed the old title. Check in Studio. | Owner ("approve a1") |
| A1-2 | 2026-10-15 | Title, description, tags | `-UyCGqkdDGs` | Title "Motion in Straight Line \| Lec : 04 \| NEET 2027 Physics \| Sashan Yadav Sir"; description claimed "One Shot Revision"; no tags | Title "Motion in a Straight Line L04 (Partial Recording) \| Class 11 Physics \| NEET 2027 \| Sashan Sir"; description states the recording is partial; 9 chapter tags added. Visibility unchanged. | Same as A1-1 | Owner |
| A1-3 | 2026-10-15 | Title only | `oLhq_3-h4ps` | "ठोस के यांत्रिक गुण \| Mechanical Properties of Fluids \| Lec-01 \| NEET 2027 Physics \| Mukul Sir #neet" | "तरलों के यांत्रिक गुण \| Mechanical Properties of Fluids \| Lec-01 \| NEET 2027 Physics \| Mukul Sir". The video's own description and the next video (Fluids Lec-02) both say Fluids. "#neet" was removed because the title exceeded the 100-character limit. | Same as A1-1 | Owner |

## Awaiting approval
See `proposed-metadata-changes.md`: batches A (3 defective videos), B (Isomerism L01–L08), C (HHD L02–L09), D (tag hygiene), E (opening trim / chapters test), plus homepage and playlists (AUDIT §4).

## Baselines recorded before any change (for before/after comparison)
- Channel, 15 Sep–14 Oct: engaged views 5,346; Browse 3,554; Suggested 504; Search 190; non-subscriber AVD (90 d) 125 s.
- Per-video baselines: `data/video-inventory-2026-10-15.csv`.
