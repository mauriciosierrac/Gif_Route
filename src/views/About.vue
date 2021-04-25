<template>
  <div class="containter m-3 text-center">
    <h1>Mauricio Sierra C</h1>
    <img src="./logos/yo.jpg" alt="MauricioS" class="img-fluid mb-5" />
    <br />
    <div class="btn-group mt-3" role="group" aria-label="Basic example">
      <div class="social-media">
        <ul>
          <li><a href="https://github.com/mauriciosierrac" target="_blank"><i class="fab fa-github mt-3 fa-2x"></i> </a></li>
          <li><a href="https://twitter.com/SierraCode" target="_blank"><i class="fab fa-twitter mt-3 fa-2x"></i> </a></li>
          <li><a href="https://www.linkedin.com/in/mauriciosierrac/" target="_blank"><i class="fab fa-linkedin mt-3 fa-2x"></i> </a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style>
img {
  border-radius: 50%;
}
i {
  color:black
}

.social-media ul{
  position: absolute;
  top: 50%;
  left: 50%;
  padding: 0;
  margin: 0;
  transform: translate(-50%, -50%);
  display: flex;
}
.social-media ul li{
  list-style: none;
  margin: 0 15px;
}
.social-media ul li .fa{
  font-size: 30px;
  line-height: 60px;
  transition: .6s;
  color: #000;
}
.social-media ul li .fa:hover{
  color: #fff;
}

.social-media ul li a{
  position: relative;
  display: block;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: #fff;
  text-align: center;
  transition: .6s;
  box-shadow: 0 5px 4px rgba(0, 0, 0, .5);
}
.social-media ul li a:hover{
  transform: translate(0, -10px);
}
.social-media ul li:nth-child(1) a:hover{
  background-color: #555557;
}
.social-media ul li:nth-child(2) a:hover{
  background-color: #55acee;
}

.social-media ul li:nth-child(3) a:hover{
  background-color: #0077b5;
}

</style>
