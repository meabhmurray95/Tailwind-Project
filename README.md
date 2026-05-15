Home and Gallery pages created using Tailwind CSS. tailwindproject.html is the homepage and you can get to the gallery page 
by clicking the 'Gallery' in the nav bar. I used the grid utility to create the gallery of images. I used the bg (background)
for the background colours and the image on the homepage. I also used the border utility for around the images and navigation 
buttons. I used 'p' for padding and 'mx' and 'my' for margins. For the footer I used the 'fixed' and 'bottom-0' to ensure the 
footer was always at the bottom of the page.
[tailwindproject.html](https://github.com/user-attachments/files/27800199/tailwindproject.html)
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
    />
    <title>Homepage</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>
  <body class="bg-no-repeat bg-cover bg-[url(Images/photographer.jpg)]">
    <div class="text-center">
      <header class="bg-white p-3 flex justify-between font-serif">
        <i>Meabh Murray Photography</i>
      </header>
      <br />
      <div class="flex justify-center">
        <nav>
          <a
            href="tailwindproject.html"
            class="border rounded-md text-sky-900 bg-white p-4"
            >Home</a
          >
          <a href="#home" class="border rounded-md text-sky-900 bg-white p-4"
            >About</a
          >
          <a href="#contact" class="border rounded-md text-sky-900 bg-white p-4"
            >Contact</a
          >
          <a
            href="tailwindgallery.html"
            class="border rounded-md text-sky-900 bg-white p-4"
            >Gallery</a
          >
        </nav>
      </div>
    </div>
    <br />
    <div class="flex items-center justify-center w-64 h-64 mx-130 my-30">
      <p class="text-center text-white">
        Welcome to my portfolio! I'm a passionate photographer with a keen eye
        for detail and a deep love for capturing lifes moments. Whether it's a
        photo of your big day or imagery for your brand I strive to capture the
        moment and what it's try to say. Explore my work and see how I can
        capture a joyful moment or help bring your ideas to life.
      </p>
    </div>

    <div class="fixed bottom-0">
      <div class="justify">
        <footer class="bg-white p-3 flex justify-between">
          &copy; Meabh Murray Photography. 44 Yellow Brick Road Liberal Kansas
        </footer>
        <div class="icon bg-white">
          <a href="https://www.instagram.com/">
            <i class="fa-brands fa-square-instagram"></i
          ></a>
          <a href="http://www.facebook.com">
            <i class="fa-brands fa-square-facebook"></i
          ></a>
        </div>
      </div>
    </div>
  </body>
</html>
