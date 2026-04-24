# Images

## hero-bg.jpg
Replace with a high-quality photo of a completed paint job or Alfredo at work.
Recommended: landscape orientation, at least 1600×900px.
The dark CSS overlay ensures text stays readable over any photo.

## gallery/ (6 images)
Name them job1.jpg through job6.jpg (or any descriptive name).
Recommended: 4:3 aspect ratio, at least 800×600px each.

To wire up a gallery photo, replace a `.gallery-item` div in index.html:

Before (placeholder):
  <div class="gallery-item"><span>Before / After</span></div>

After (real photo):
  <div class="gallery-item">
    <img src="images/gallery/job1.jpg" alt="Exterior repaint — [house description]">
  </div>
