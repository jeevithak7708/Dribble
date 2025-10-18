# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
boot.html

<html>
<head>
  <meta charset="UTF-8">
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      
      <a class="navbar-brand" href="#">Dribble</a>

      
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav ms-3">
          <li class="nav-item">
            <a class="nav-link active" href="#">Shots</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Designers</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Teams</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Community</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Jobs</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">...</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div class="d-flex justify-content-end p-3 bg-white">
  <a href="#" class="btn btn-primary">Sign in</a>
  <a href="#" class="btn btn-info ms-2">Sign up</a>
</div>

  
  <div class="text-center my-1">
    <h4 class="fw-bold">What are you working on?</h4>
    <p class="subtext">Dribbble is show and tell for designers.</p>
    <button class="btn btn-learn me-2">Learn more</button>
    <button class="btn btn-signup">Sign up</button>
  </div>

  
  <div class="container">
   
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="img1.png" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 1</div>
      </div>
      <div class="col-2 text-center">
        <img src="img2.webp"  width="50" height="50" class="img-fluid rounded">
        <div class="image-label">Image 2</div>
      </div>
      <div class="col-2 text-center">
        <img src="img3.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 3</div>
      </div>
      <div class="col-2 text-center">
        <img src="img4.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 4</div>
      </div>
      <div class="col-2 text-center">
        <img src="img5.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 5</div>
      </div>
      <div class="col-2 text-center">
        <img src="img6.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 6</div>
      </div>
    </div>

    
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="img7.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 7</div>
      </div>
      <div class="col-2 text-center">
        <img src="img8.png" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 8</div>
      </div>
      <div class="col-2 text-center">
        <img src="img9.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 9</div>
      </div>
      <div class="col-2 text-center">
        <img src="img10.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 10</div>
      </div>
      <div class="col-2 text-center">
        <img src="img11.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 11</div>
      </div>
      <div class="col-2 text-center">
        <img src="img12.png" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 12</div>
      </div>
    </div>

   
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="img13.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 13</div>
      </div>
      <div class="col-2 text-center">
        <img src="img14.jpg" width="50" height="50" class="img-fluid rounded">
        <div class="image-label">Image 14</div>
      </div>
      <div class="col-2 text-center">
        <img src="img15.webp" width="50" height="50" class="img-fluid rounded">
        <div class="image-label">Image 15</div>
      </div>
      <div class="col-2 text-center">
        <img src="img16.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 16</div>
      </div>
      <div class="col-2 text-center">
        <img src="img17.webp"width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 17</div>
      </div>
      <div class="col-2 text-center">
        <img src="img18.webp" width="100" height="100" class="img-fluid rounded">
        <div class="image-label">Image 18</div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center">
    <p>&copy; designed by jeevitha k(25016606)</p>
  </footer>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (42).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
