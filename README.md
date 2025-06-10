# image-gallery
image gallery where users can view a  collection of images. Use HTML/CSS for layout  and JavaScript for image navigation and any  interactive features.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Image Gallery</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="gallery-container">
    <div class="main-image">
      <img id="current-image" src="images/img1.jpg" alt="Gallery Image" />
    </div>
    <div class="thumbnail-container">
      <img src="images/img1.jpg" onclick="setImage(this)" />
      <img src="images/img2.jpg" onclick="setImage(this)" />
      <img src="images/img3.jpg" onclick="setImage(this)" />
      <img src="images/img4.jpg" onclick="setImage(this)" />
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
