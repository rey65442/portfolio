
html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="gallery">
        <img src="image1.jpg" alt="Photo 1" class="photo" data-description="Description of Image 1">
        <img src="image2.jpg" alt="Photo 2" class="photo" data-description="Description of Image 2">
        <img src="image3.jpg" alt="Photo 3" class="photo" data-description="Description of Image 3">
    </div>
    
    <div id="lightbox" class="hidden">
        <img id="lightbox-img" src="" alt="">
        <p id="lightbox-desc"></p>
        <span id="close">&times;</span>
    </div>

    <script src="script.js"></script>
</body>
</html>
