<script>
  let title = "New Orleans Monk Runs";
</script>

<div class='titleContainer'>
  <div class='imageContainer'>
    <img src="src/stainedGlassRunningIconCroppedPNG.png" alt="" class="responsiveImage">
  </div>
  <h1 class='title'>{title}</h1>
</div>

<nav class='nav'>
  <div class="buttonContainer">
    <a href='/revelations' class="link">revelations</a>
  </div>
</nav>


<style>
  .title {
    text-align: center;
    display: block;
    font-family: "Georgia", Times, serif;
    font-size: 2rem;
    color: #87a8b1;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  }

  .titleContainer {
      background: radial-gradient(ellipse at top, rgba(255, 204, 0, 0.5) 0%, rgba(255, 102, 0, 0.5) 100%);
      border: 0.25em solid #1a1919fd; /* Solid black border */
      border-radius: 1rem;
      padding: 1.5rem;
      margin: 1rem;
      z-index: 10;
      backdrop-filter: blur(18px);
      -webkit-backdrop-filter: blur(18px);
    }

  .nav {
    margin: 2em; 
    color: #87a8b1;
  }
  
  .link {
    text-decoration: none; 
    color: inherit;
    background: radial-gradient(ellipse at top, rgba(255, 204, 0, 0.5) 0%, rgba(255, 102, 0, 0.5) 100%);
      border: 0.25em solid #1a1919fd; /* Solid black border */
      border-radius: 1rem;
      padding: 1.5rem;
      margin: 1rem;
      z-index: 10;
      backdrop-filter: blur(18px);
      -webkit-backdrop-filter: blur(18px);
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  }

  .imageContainer {
    text-align: center; /* Center the image horizontally */
  }

  .responsiveImage {
    max-width:  80%; /* Make the image responsive */
    max-height:  80%;
    height: auto; /* Maintain the aspect ratio */
  }

  .buttonContainer {
    display: flex;
    justify-content: center; /* Center the button horizontally */
    margin-top: 1rem; /* Add space between the image and button */
  }
</style>