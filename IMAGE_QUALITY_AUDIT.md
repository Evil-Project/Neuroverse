# Image quality audit

Scanned the 168 directional PNGs (`front`, `right`, `back`, `left`) for pure red, yellow, magenta, blue, cyan, or green pixels at alpha values 1–3. This is a measurable source of colored specks in some image previews. It is not a score of illustration quality or evidence that every listed image has visibly broken hair.

- 76 PNGs contain at least one such pixel.
- 44 PNGs contain at least 1,000.
- Stockings variants account for all 76 flagged PNGs.
- Source illustrations and existing directional renders were not replaced.

## Highest-count files (at least 1,000 pixels)

| File | Pixels |
| --- | ---: |
| `Anny_Model_Showcase (Stockings)/back.png` | 3,027 |
| `Anny_Model_Showcase (Stockings)/front.png` | 2,044 |
| `Anny_V3_fullbody (Stockings)/front.png` | 2,349 |
| `Anny_V3_fullbody (Stockings)/left.png` | 1,533 |
| `Anny_V3_fullbody (Stockings)/right.png` | 1,652 |
| `Filian_Portrait_Sailor_Outfit (Stockings)/back.png` | 1,189 |
| `Full_model_Cerbervt (Stockings)/front.png` | 6,674 |
| `Full_model_Cerbervt (Stockings)/left.png` | 3,478 |
| `Full_model_Cerbervt (Stockings)/right.png` | 1,847 |
| `Illustration_Anny_1 (Stockings)/back.png` | 1,530 |
| `Illustration_Anny_1 (Stockings)/front.png` | 1,167 |
| `Illustration_Anny_1 (Stockings)/right.png` | 1,779 |
| `Illustration_Camila (Stockings)/back.png` | 7,104 |
| `Illustration_Camila (Stockings)/front.png` | 5,451 |
| `Illustration_Camila (Stockings)/left.png` | 5,789 |
| `Illustration_Camila (Stockings)/right.png` | 3,903 |
| `Illustration_Camila_V3 (Stockings)/back.png` | 6,516 |
| `Illustration_Camila_V3 (Stockings)/front.png` | 5,342 |
| `Illustration_Camila_V3 (Stockings)/right.png` | 3,810 |
| `Illustration_Evil_Cyber_Knight (Stockings)/back.png` | 3,725 |
| `Illustration_Evil_Cyber_Knight (Stockings)/front.png` | 6,935 |
| `Illustration_Evil_Cyber_Knight (Stockings)/left.png` | 2,021 |
| `Illustration_Evil_Cyber_Knight (Stockings)/right.png` | 6,957 |
| `Illustration_Evil_v2_04 (Stockings)/front.png` | 2,973 |
| `Illustration_Evil_v2_Clown (Stockings)/back.png` | 6,360 |
| `Illustration_Evil_v2_Clown (Stockings)/front.png` | 5,882 |
| `Illustration_Evil_v2_Clown (Stockings)/left.png` | 2,432 |
| `Illustration_Evil_v2_Clown (Stockings)/right.png` | 1,827 |
| `Illustration_Miniko (Stockings)/back.png` | 4,480 |
| `Illustration_Miniko (Stockings)/front.png` | 5,444 |
| `Illustration_Miniko (Stockings)/left.png` | 3,216 |
| `Illustration_Miniko (Stockings)/right.png` | 5,226 |
| `Illustration_Neuro_v2 (Stockings)/front.png` | 3,688 |
| `Illustration_Neuro_v2 (Stockings)/right.png` | 2,795 |
| `Illustration_Neuro_v2_Clown (Stockings)/back.png` | 9,046 |
| `Illustration_Neuro_v2_Clown (Stockings)/front.png` | 11,330 |
| `Illustration_Neuro_v2_Clown (Stockings)/left.png` | 5,511 |
| `Illustration_Neuro_v2_Clown (Stockings)/right.png` | 5,041 |
| `Illustration_Neuro_v3 (Stockings)/back.png` | 3,546 |
| `Illustration_Neuro_v3 (Stockings)/front.png` | 3,379 |
| `Neuro_V3_cyberpunk_princess (Stockings)/back.png` | 4,297 |
| `Neuro_V3_cyberpunk_princess (Stockings)/front.png` | 3,595 |
| `Neuro_V3_cyberpunk_princess (Stockings)/left.png` | 1,976 |
| `Neuro_V3_cyberpunk_princess (Stockings)/right.png` | 3,114 |

## Regenerated transparent previews

These are review candidates only. Image generation changed some character details and introduced new low-opacity edge specks, so they were not promoted to directional render files.

- `Anny_V3_fullbody/left-regenerated-preview.png`
- `Illustration_Camila/right-regenerated-preview.png`
- `Illustration_Evil_v2_Witche/left-regenerated-preview.png`
- `Illustration_Neuro_v2_Clown/right-regenerated-preview.png`

Further transparent regeneration attempts on `Illustration_Miniko (Stockings)/right.png` and `Illustration_Evil_Cyber_Knight (Stockings)/right.png` retained colored edge fragments and changed image dimensions. Those outputs were rejected, and their original files remain unchanged.
