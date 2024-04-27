<style>
  /* Define custom cursor styles */
  .custom-cursor {
    position: absolute;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: rgba(255, 0, 0, 0.5); /* Initial color */
    pointer-events: none; /* Ensure cursor doesn't interfere with links */
    transition: background-color 0.3s ease; /* Smooth color transition */
    z-index: 9999; /* Ensure cursor stays on top */
  }

  /* Add animation to custom cursor */
  @keyframes changeColor {
    0% {
      background-color: rgba(255, 0, 0, 0.5);
    }
    50% {
      background-color: rgba(0, 255, 0, 0.5);
    }
    100% {
      background-color: rgba(0, 0, 255, 0.5);
    }
  }

  /* Apply animation to custom cursor */
  .custom-cursor.animated {
    animation: changeColor 2s infinite; /* Change color every 2 seconds */
  }
</style>

<script>
  // Add JavaScript to track cursor movement
  document.addEventListener('mousemove', function(e) {
    // Get cursor position
    const x = e.pageX;
    const y = e.pageY;
    
    // Update custom cursor position
    const cursor = document.querySelector('.custom-cursor');
    cursor.style.left = x + 'px';
    cursor.style.top = y + 'px';
  });
</script>

<!-- Add custom cursor element -->
<div class="custom-cursor"></div>





# Hi there! 👋 I'm Hussein Yussuf

I'm a fullstack Developer passionate about building innovative solutions. Currently focused on JavaScript, Python, SQL, C, HTML, and CSS.

## Skills

![JavaScript](https://img.shields.io/badge/-JavaScript-yellow?logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-blue?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-orange?logo=sql&logoColor=white)
![C](https://img.shields.io/badge/-C-blue?logo=c&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML-red?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS-blueviolet?logo=css3&logoColor=white)


## Projects

- [Airbnb Clone](link) - An Airbnb clone replicating the original website's design and functionality. I focused on the frontend development, implementing HTML, CSS, and JavaScript to create a user-friendly interface.

  ![Airbnb Clone Screenshot](screenshot_link)



## Connect with Me

- [LinkedIn](https://www.linkedin.com/in/hussein-garane-06967b26b/)
- [GitHub](https://github.com/GaraneHuzni)
- [Twitter](https://twitter.com/GaraneHuzni)
- [Personal Website]()
- Email: huznigarane@gmail.com
