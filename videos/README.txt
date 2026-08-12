VIDEO FILES — HOW TO ADD YOUR VIDEOS
=====================================

Place your video files in this folder and update the src paths in index.html.

Supported formats: .mp4 (recommended), .webm, .mov

Example file names used in the portfolio:
  - video1.mp4  → Fashion Brand Reel
  - video2.mp4  → Podcast Episode Edit
  - video3.mp4  → Product Launch Ad
  - video4.mp4  → Music Video Cut
  - video5.mp4  → Travel Reel
  - video6.mp4  → Event Highlight

To add your own videos:
1. Copy your .mp4 files into this folder
2. Rename them (e.g. my-reel.mp4) OR update the src="videos/..." paths in index.html
3. Update the title, subtitle, and category for each video card in index.html

To change a video card title/details, find this pattern in index.html:
  onclick="openModal('videos/video1.mp4', 'YOUR TITLE', 'YOUR SUBTITLE')"
And update the title and subtitle text accordingly.

TIP: For best performance, compress your videos to under 20MB each.
Recommended tool: HandBrake (free) — use H.264 codec, CRF 23.
