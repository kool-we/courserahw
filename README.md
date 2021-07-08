# courserahw
+<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    
    /* base styling */
* {
  box-sizing: border-box;
  margin: 0px;
  padding: 0px;
  font-family: Comic Sans, Comic Sans MS, cursive;
}

h1 {
  text-align: center;
  margin: 15px;
}

.row {
  width: 100%;
}

.menu-item {
  border: 2px solid black;
  padding: 5px 10px 5px 10px;
  margin: 10px;
  background-color: gray;
}

.menu-item-header {
  border: 2px solid black;
  width: 30%;
  float: right;
  position: relative;
  top: -7px;
  right: -12px;
  text-align: center;
  font-size: 125%;
}

#item-header-1{
  background-color:wheat;
  color:black;
}

#item-header-2{
  background-color:brown;
  color:white;
}

#item-header-3{
  background-color:antiquewhite;
  color:black;
}

.menu-item-text {
  clear: right;
}

/* desktop query */
@media (min-width: 992px) {
  .col-lg-1,
  .col-lg-2,
  .col-lg-3,
  .col-lg-4,
  .col-lg-5,
  .col-lg-6,
  .col-lg-7,
  .col-lg-8,
  .col-lg-9,
  .col-lg-10,
  .col-lg-11,
  .col-lg-12 {
    float: left;
  }
  .col-lg-1 {
    width: 8.3%;
  }
  .col-lg-2 {
    width: 16.6%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.3%;
  }
  .col-lg-5 {
    width: 41.6%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.3%;
  }
  .col-lg-8 {
    width: 66.6%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-10 {
    width: 83.3%;
  }
  .col-lg-11 {
    width: 91.6%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/* tablet query */
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1,
  .col-md-2,
  .col-md-3,
  .col-md-4,
  .col-md-5,
  .col-md-6,
  .col-md-7,
  .col-md-8,
  .col-md-9,
  .col-md-10,
  .col-md-11,
  .col-md-12 {
    float: left;
  }
  .col-md-1 {
    width: 8.3%;
  }
  .col-md-2 {
    width: 16.6%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.3%;
  }
  .col-md-5 {
    width: 41.6%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.3%;
  }
  .col-md-8 {
    width: 66.6%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-10 {
    width: 83.3%;
  }
  .col-md-11 {
    width: 91.6%;
  }
  .col-md-12 {
    width: 100%;
  }
}

/* mobile query */
@media (max-width: 767px) {
  .col-sm-1,
  .col-sm-2,
  .col-sm-3,
  .col-sm-4,
  .col-sm-5,
  .col-sm-6,
  .col-sm-7,
  .col-sm-8,
  .col-sm-9,
  .col-sm-10,
  .col-sm-11,
  .col-sm-12 {
    float: left;
  }
  .col-sm-1 {
    width: 8.3%;
  }
  .col-sm-2 {
    width: 16.6%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.3%;
  }
  .col-sm-5 {
    width: 41.6%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.3%;
  }
  .col-sm-8 {
    width: 66.6%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-10 {
    width: 83.3%;
  }
  .col-sm-11 {
    width: 91.6%;
  }
  .col-sm-12 {
    width: 100%;
  }
}

  </head>
  <body>
    <h1 class="main-header">Our Menu</h1>
    <div class="row">
        <div class="menu-item-col col-lg-4 col-md-6 col-sm-12">
          <div class="menu-item">
            <h3 class="menu-item-header" id="item-header-1">Chicken</h3>
            <p class="menu-item-text">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima rem
              at quaerat, error eos obcaecati doloribus provident harum, possimus
              voluptatum hic temporibus non doloremque, dolor quod. Aut veritatis
              repudiandae vel!
            </p>
          </div>
        </div>
        <div class="menu-item-col col-lg-4 col-md-6 col-sm-12">
          <div class="menu-item">
            <h3 class="menu-item-header" id="item-header-2">Beef</h3>
            <p class="menu-item-text">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam
              consequuntur magnam alias. Fugit fugiat maiores placeat cum
              consectetur porro dolorum delectus architecto voluptate dolore atque
              error harum, vitae animi? Dignissimos?
            </p>
          </div>
        </div>
        <div class="menu-item-col col-lg-4 col-md-12 col-sm-12">
          <div class="menu-item">
            <h3 class="menu-item-header" id="item-header-3">Sushi</h3>
            <p class="menu-item-text">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus
              ducimus, labore doloribus provident cupiditate sapiente quos nihil
              quidem, fugiat quia voluptatem, tempora explicabo sunt! Placeat
              praesentium sit omnis. Eius, magnam!
            </p>
          </div>
        </div>
    </div>
  </body>
</html>

