# ICLR Submission 11751 — Project Page

Anonymous project page, same layout as `neuralcinema.github.io` (Bulma + static HTML, no build step).
Open `index.html` directly or serve the folder with `python3 -m http.server`.

## Expected assets

Drop files at these paths; `index.html` already references them.

| Section | Path |
|---|---|
| Intact object thumbnails | `new_assets/intact/{green_cake,black_bread,red_cake,steamed_bun}.png` (first frame of the fracture video) |
| Hero panels (Setting 1 = vertical, Setting 2 = horizontal) | `results/{force,stress,strain,flow,damage,fracture}/{object}__{vertical,horizontal}__vel2__mat2__frac0.mp4` |
| Fracture Timing Condition section | `new_assets/intact/{bear,frog,kong}.png`, `results/fracture/{bear,frog,kong}__vertical__vel2__mat2__frac{0,1,2}.mp4` |
| Material Properties Condition section | `results/fracture/{object}__vertical__vel2__mat{0,1,2}__frac0.mp4` — only `mat2` exists so far |
| Teaser image | `new_assets/pdf_renders/teaser.png` |
| Qualitative results | `new_assets/all_qual_results/sample{1,2,3}_{force_conditions,prediction}.mp4` |
| Comparison columns | `new_assets/compare/{force_conditions,frame_videos_baseline1,frame_videos_baseline2,ground_truth_videos,frame_videos_ours}/sample{1,2,3}.mp4` |

Rename "Baseline 1/2" in the comparison header and the paper title in `<title>` / hero once known.
