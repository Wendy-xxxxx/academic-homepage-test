Wenyu Xu academic-homepage template migration package

1) Upload/replace files in academic-homepage-test:
- _config.yml
- _data/profile.yml
- _data/display.yml
- _data/authors.yml
- _publications/
- _news/

2) Delete template example files:
- Delete existing example files in _publications/2023 and _publications/2024 if you do not want demo papers.
- Delete existing example files in _news if you do not want demo news.

3) Upload images:
Profile photo:
  assets/images/photos/profile.png

Publication images:
  assets/img/publications/autcon2026-uav-mewp.png
  assets/img/publications/aei2026-visual-fatigue.png
  assets/img/publications/aei2026-ppe-vlm.png
  assets/img/publications/aei2026-scene-graph.png
  assets/img/publications/autcon2025-mep-ar.png
  assets/img/publications/ipc2025-uav-ppe.png
  assets/img/publications/autcon2024-defect-ar-bim.png
  assets/img/publications/ecam2024-ar-education.png
  assets/img/publications/buildings2022-arvr-review.png
  assets/img/publications/criocm2022-defect-tracking.png

4) For test repository, _config.yml uses:
  baseurl: "/academic-homepage-test"

When moving to official Wendy-xxxxx.github.io, change to:
  baseurl: ""

5) Commit changes and wait for GitHub Pages deployment.
