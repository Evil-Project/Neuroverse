# Repository Guidelines

## Project Structure & Asset Organization

This repository is a collection of Neuroverse character reference images. Root-level `.png` and `.jpg` files are source/reference images, such as `Illustration_Neuro_v3.png`. Matching directories contain four turnaround views: `front.png`, `right.png`, `back.png`, and `left.png`. A directory with the suffix ` (Stockings)` holds that outfit variant. `README.md` is the visual catalog and should link to every published image set. There is no application source tree or test directory.

## Development and Validation

No build, package manager, or automated test command is configured. Preview changes by opening `README.md` in a Markdown renderer and checking the linked images. Before committing, run `git diff --check` to catch whitespace errors and `git status --short` to confirm that only intended files are included. Check that each new turnaround directory contains all four expected view files, for example:

```sh
for view in front right back left; do test -f "Illustration_Neuro_v3/$view.png" || echo "Missing $view"; done
```

## Naming and Editing Conventions

Follow the existing character and outfit name when adding assets; keep the root reference image and its turnaround directory names aligned. Use lowercase view names exactly as shown above. Preserve existing spelling in published paths, because `README.md` links depend on it. For Markdown edits, use descriptive headings and relative links; URL-encode spaces and parentheses in links to variant directories. Avoid committing editor or operating-system files such as `.DS_Store`.

## Review Guidelines

There is no coverage target or test framework. Inspect every changed view at full size against its root reference and neighboring views. Check proportions, clothing and footwear details, orientation, background consistency, and whether stocking variants differ only where intended. Confirm that all new links and preview images render in `README.md`.

## Character Illustration Workflow

Work as a professional character illustrator creating and refining multi-view designs from client-supplied front references. Existing sets vary in quality; use the original image in this folder as the source of truth. Imagine unseen angles creatively but plausibly, without departing from the character's design. Prefer a high-quality canvas; use 9:16 (1080 × 1920) when appropriate. For full-body art at that size, preserve a transparent background, sharp details, accurate proportions, and consistent character scale and centering across all four views. Refine blurry references into clear artwork rather than carrying blur into the result.

Compare each view with the source and its neighboring views before finishing. Inspect hair shape and color, ears, tails, facial features, outfit parts, sock color and opacity, shoes or boots, bare feet, fingers and finger counts. Distinguish sheer from opaque stockings, tall boots from stockings with shoes, and heels from standard shoes. When removing footwear, distinguish shoe material, hosiery, and skin tone. Check perspective: feet visible from behind must remain visible, hands and sleeves must appear on the correct side, and no component may disappear, clip through the body, or appear behind it when it belongs in front. Respect specific annotations exactly; do not add conflicting details.

Use the same neutral, standing-at-attention pose for standard front, right, back, and left views; avoid tiptoe or staggered stances. If a reference uses a different pose, retain it where requested. If its eyes are closed, use other references to depict open eyes when a standard view requires them. When a detail cannot be resolved from the supplied images, consult any provided links or request another reference, such as a doll's back view. Save each revision as a separate file, compare it with the previous version, and tell the client what changed outside the image. If differences are subtle, ask which version to keep before discarding the old one. Rework distorted, blurry, off-center, incorrectly scaled, or inconsistent output before delivery.

## Consistency Prompt

Apply this prompt when creating or editing a view: “Maintain consistency in character, outfit, and art style; do not alter the face, hairstyle, clothing, or accessories; do not change the body type, age, material, color scheme, or art style; avoid incorrect angles or merely tilting the head without rotating the camera view; and ensure there are no extra limbs, malformed hands, text, or watermarks. Keep the background clean and simple so as not to distract from the character.” For assets that require transparency, keep the background transparent.

## Commits and Pull Requests

Recent commits use `feat:`, `fix:`, `docs:`, and `chore:` prefixes with short imperative summaries (for example, `fix: correct turnaround details`). Keep asset changes and catalog updates in the same commit. In pull requests, describe the characters and views changed, explain the visual reason, and include before/after previews or screenshots for image edits. Note any intentionally missing views or variants.
