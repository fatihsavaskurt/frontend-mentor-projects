# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Red: hsl(0, 78%, 62%)
- Cyan: hsl(180, 62%, 55%)
- Orange: hsl(34, 97%, 64%)
- Blue: hsl(212, 86%, 64%)

### Neutral

- Very Dark Blue: hsl(234, 12%, 34%)
- Grayish Blue: hsl(229, 6%, 66%)
- Very Light Gray: hsl(0, 0%, 98%)

## Typography

### Body Copy

- Font size: 15px

### Fonts

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 200, 400, 600


body{
    margin: 0;
    padding: 0;
    background-color: hsl(0, 0%, 98%);
}

.container{
    margin-top: 150px;
}

.titles{
    justify-content: center;
    align-items: center;
    text-align: center;
}

.cards-container{
    display: flex;
    justify-content: center;
    gap: 20px;
    width: 100%;
    
}


.cards-container .card-box{
    height: 290px;
    background-color: white;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 12px;
    border-radius: 10px;
    
}

.cards-container .flex{
    margin-top: 90px;
    background-color: white;
}



.cards-container .card-content{
    width: 300px;
    height: 200px;
    margin: 32px;
}



  <div class="container">
    <div class="titles">
      <p class="title-1">Reliable, efficient delivery</p>
      <p class="title-2">Powered by Technology</p>
      <p class="title-text">Our Artificial Intelligence powered tools use millions of project data points 
        to ensure that your project is successful</p>
    </div>
    <div class="container-content">
      <div class="cards-container">
        <div class="card-supervisor card-box flex">
          <div class="card-content">
            <p class="card-title">Supervisor</p>
            <p class="card-text">Monitors activity to identify project roadblocks</p>
            <img class="card-icon"src="images/icon-supervisor.svg" alt="">
          </div>
        </div>
        <div class="cards-wrap">
          <div class="card-builder wrap card-box">
           <div class="card-content">
            <p class="card-title builder">Team Builder</p>
            <p class="card-text">Scans our talent network to create the optimal team for your project</p>
            <img class="card-icon"src="images/icon-team-builder.svg" alt="">
           </div>
          </div>
          <div class="card-karma wrap card-box">
            <div class="card-content">
              <p class="card-title karma">Karma</p>
              <p class="card-text">Regularly evaluates our talent to ensure quality</p>
              <img class="card-icon"src="images/icon-karma.svg" alt="">
            </div>
          </div>

        </div>
        <div class="card-calculator card-box flex">
         <div class="card-content">
          <p class="card-title">Calculator</p>
          <p class="card-text">Uses data from past projects to provide better delivery estimates</p>
          <img class="card-icon"src="images/icon-calculator.svg" alt="">
         </div>
        </div>
      </div>
    </div>
  </div>

  
  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </p>
  </footer>