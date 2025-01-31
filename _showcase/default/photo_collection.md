---
show: true
width: 4
date: 2026-09-12 00:01:00 +0800
height: 250px
images:
- src: /assets/images/photos/photo_jeju.jpg
  desc: Jeju, South Korea
- src: /assets/images/photos/photo_boston.jpg
  desc: Boston, US (during MIT visit)
- src: /assets/images/photos/photo_ubicomp.jpg
  desc: Cancun, Mexico (Ubicomp '23)
- src: /assets/images/photos/photo_chi24.jpg
  desc: Hawaii, US (CHI '24)
- src: /assets/images/photos/photo_stage.jpg
  desc: Shredding on Festival Night :)

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
