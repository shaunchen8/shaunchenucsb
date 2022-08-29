<template>
  <div style="padding-top:3em;">
    &nbsp;
  </div>
  <div class="title">projects</div>
  <div class="container">

    <router-link to="/">
      <div class="card-proj">
        <img src="https://b2h3x3f6.stackpathcdn.com/assets/landing/img/gallery/4.jpg" alt="Avatar" style="width:250px">
        <div class="content">
          <div  class="card-title">DeepDream Art</div>
          <p>
            This project uses convolutional neural networks to analyze patterns in an image to create a dreamy effect.
          </p>
        </div>
      </div>
    </router-link>
    
    <router-link to="/">
      <div class="card-proj">
        <img src="https://www.extremetech.com/wp-content/uploads/2011/10/patchmatch_rebuild-348x196.jpg" alt="Avatar" style="width:250px">
        <div class="content">
          <div  class="card-title">Content-Aware Image Fixing Tool</div>
          <p>
            This project implements computational photography methods including image resizing, content-aware hole-filling, and seam-carving and utilized the PatchMatch algorithm to optimize program runtimes by using random search and nearest neighbor correspondences.
          </p>
        </div>
      </div>
    </router-link>

    <router-link to="/ECE157A">
      <div class="card-proj">
        <img src="https://i0.wp.com/l3apq3bncl82o596k2d1ydn1-wpengine.netdna-ssl.com/wp-content/uploads/2019/02/LeBronJamesSnapImage-1.jpg?fit=836%2C479&ssl=1" alt="Avatar" style="width:250px">
        <div class="content">
          <div class="card-title">Machine Learning Analytical Website</div>
          <p>
            This project predicts top NBA players based on n-categories of their stats using various classification, regression, and outlier ML models from the Scikit Learn module.
          </p>
        </div>
      </div>
    </router-link>

    

    

  </div>
</template>

<style>

body{
  background-image: url("@/assets/background2.png");
}

@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&family=Poppins&display=swap');

.title{
    padding-top:5em;
    padding-bottom: 1em;
    font-family: Poppins;
    font-weight: bold;
    font-size: 24px;
}

.container{
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}

.card-proj {
  background: aliceblue;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px;
  width: 1000px;
  height: 300px;
  margin: 1em 2em;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card-proj:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.content {
  padding: 3em 5em;
  max-width: 500px;
  color: #2c3e50;
}

a { text-decoration: none; }

.card-title{
  font-weight: bold;
}
</style>
