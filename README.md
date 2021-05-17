<!DOCTYPE html>
  <html>
    <head>
      <title>3D imager Hover Css</title>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <link rel="stylesheet" href="style.css"/>
      <style>
@import url("https://fonts.googleapis.com/css?family=Muli");

* {
  margin: 0;
  padding: 0;
}

h1 {
  color: #ff6d39;
  font-family: "muli";
  font-weight: bold;
  font-size: 26px;
  margin-top: 21px;
  display: inline-block;
}

.product-name i {
  color: #ffffff;
  transition: 0.3s all ease;
  margin: 0px 12px;
}

.product-name i:hover {
  color: #ff6d39;
  cursor: pointer;
}

h3 {
  color: #fec60f;
  font-family: "muli";
  margin-top: 84px;
  font-size: 20px;
  font-weight: 500;
}

h2 {
  color: #ffffff;
  font-family: "muli";
  margin-top: 10px;
  font-weight: 800;
  font-size: 29px;
}

h4 {
  display: inline-block;
  color: #ffffff;
  font-family: "muli";
  margin-top: 10px;
  font-weight: bold;
  font-size: 20px;
}

h4.dis {
  display: inline-block;
  color: #ffffff;
  font-family: "muli";
  font-weight: 400;
  font-size: 17px;
  margin-left: 30px;
  text-decoration: line-through #ea3201;
}

h4.dis span {
  text-decoration: line-through #ea3201;
}

.discount {
  display: inline-block;
}

ul {
  list-style-type: none;
}

li {
  display: inline-block;
  margin-right: 25px;
}

ul li {
  color: #ffffff;
  font-family: "muli";
  margin-top: 20px;
  font-weight: 500;
  font-size: 11px;
}

.bg {
  width: 15px;
  height: 15px;
  text-align: center;
  padding: 2px;
  margin-right: 20px;
  transition: 0.3s all ease;
  border-radius: 50%;
}

.bg:hover {
  background-color: #ff6d39;
  border-radius: 50%;
  width: 15px;
  height: 15px;
  cursor: pointer;
}

.yellow {
  content: "";
  width: 13px;
  height: 13px;
  background-color: #fec60f;
  border-radius: 50%;
  border: 2px solid rgba(0, 0, 0, 0);
  transition: 0.3s all ease;
}

.black {
  content: "";
  width: 13px;
  height: 13px;
  background-color: #000000;
  border-radius: 50%;
  border: 2px solid rgba(0, 0, 0, 0);
  transition: 0.3s all ease;
}

.blue {
  content: "";
  width: 13px;
  height: 13px;
  background-color: #02a2ca;
  border-radius: 50%;
  border: 2px solid rgba(0, 0, 0, 0);
  transition: 0.3s all ease;
}

.yellow:hover,
.black:hover,
.blue:hover {
  border: 2px solid #f76b39;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  cursor: pointer;
}

.foot {
  color: #ffffff;
  font-family: "muli";
  margin-top: 20px;
  margin-right: 50px;
  font-weight: 500;
  font-size: 11px;
  float: left;
  transition: 0.3s all ease;
}

.foot i:nth-child(1) {
  margin-left: 0;
  margin-right: 15px;
}

.foot:hover {
  color: #f76b39;
  cursor: pointer;
}

/shoe slider indicator/

.left i {
  color: #ffd5c6;
  margin-top: 260px;
  transition: 0.3s all ease;
}

.fa-long-arrow-left {
  margin-left: -275px;
}

.fa-long-arrow-right {
  margin-left: 15px;
}

.left i:hover {
  cursor: pointer;
  color: #2a2f40;
}

.underline {
  width: 10rem;
  height: 0.25rem;
  margin-bottom: 1.25rem;
  background: #f5f2f2;

  margin-right: 3rem;
}
/main card/

.card {
  display: flex;
  align-items: center;
  background: #757b8d;
  height: 600px;
  width: 800px;
  margin: 0 auto;
  box-shadow: 0px 15px 50px 10px rgba(0, 0, 0, 0.4);
  margin-top: 2%;
}
.img {
  margin-bottom: 5rem;
  margin-left: 2opx;
}
.left {
  content: "";
  height: 405px;
  width: 330px;
  display: flex;
  align-items: center;
  background-color: #8d0b14;
  margin-left: 93px;
  border-radius: 0% 50% 50% 0%;
  position: absolute;
  z-index: 5;
}

.left img {
  margin-left: -88px;
  margin-top: 60px;
}

.right {
  content: "";
  height: 405px;
  width: 550px;
  background-color: #2a2f40;
  z-index: 3;
  margin-left: 200px;
}

.product-info {
  position: absolute;
  margin-left: 245px;
  height: 394px;
  width: 305px;
  z-index: 10;
}
</style>
    </head>
    <body>
        <div class="card">
            <div class="left">
                <img src="main.png" width="400" height="300" alt="shoe"/>
                </div>

                <div class="right">
                    <div class="product-info">
                        <div class="product-name">
                            <h1>Nike Sneakers</h1>
                            <div class="underline"></div>
                            <i class="fa fa-search"></i>
                            <i class="fa fa-user"></i>
                            <i class="fa fa-shopping-cart"></i>
                        </div>
                        <div class="card-details">
                            <h3>winter Collection</h3>
                            <h2>Men Black Sneakers</h2>
                            <h4>Rs.1500</h4>
                            <h4 class="dis">Rs.2000</h4>
                        </div>
                        <ul>
                            <li>SIZE</li>
                           <li class="bg">7</li>
                           <li class="bg">8</li>
                           <li class="bg">9</li>
                           <li class="bg">10</li>

                        </ul>
                        <ul>

                            <li>color</li>
                            <li class="yellow"></li>
                            <li class="blue"></li>
                            <li class="black"></li>
                        </ul>
                        <span class="foot">
                            <i class="fa fa-shopping-bag"></i>Buy now
                        </span>
  <div class="Amazon">
            <a href="https://amazon.com/>target="_blank"><img src="https://www.amazon.com/ref=nav_logo" alt="Amazon"/></a>
          </div>
          <div class="contact-me-link">
            <a href="https://linkedin.com/in/ashutosh-kumar-8183381aa" target="_blank" id="profile-link">
<img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0%0D%0Ab3I6IEFkb2JlIElsbHVzdHJhdG9yIDE2LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZl%0D%0AcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8v%0D%0ARFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQv%0D%0Ac3ZnMTEuZHRkIj4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4bWxucz0iaHR0cDov%0D%0AL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5%0D%0AL3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgd2lkdGg9IjUxMHB4IiBoZWlnaHQ9IjUxMHB4IiB2%0D%0AaWV3Qm94PSIwIDAgNTEwIDUxMCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEw%0D%0AIDUxMDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPGc+DQoJPGcgaWQ9InBvc3QtbGlua2VkaW4i%0D%0APg0KCQk8cGF0aCBkPSJNNDU5LDBINTFDMjIuOTUsMCwwLDIyLjk1LDAsNTF2NDA4YzAsMjguMDUs%0D%0AMjIuOTUsNTEsNTEsNTFoNDA4YzI4LjA1LDAsNTEtMjIuOTUsNTEtNTFWNTFDNTEwLDIyLjk1LDQ4%0D%0ANy4wNSwwLDQ1OSwweg0KCQkJIE0xNTMsNDMzLjVINzYuNVYyMDRIMTUzVjQzMy41eiBNMTE0Ljc1%0D%0ALDE2MC42NWMtMjUuNSwwLTQ1LjktMjAuNC00NS45LTQ1LjlzMjAuNC00NS45LDQ1LjktNDUuOXM0%0D%0ANS45LDIwLjQsNDUuOSw0NS45DQoJCQlTMTQwLjI1LDE2MC42NSwxMTQuNzUsMTYwLjY1eiBNNDMz%0D%0ALjUsNDMzLjVIMzU3VjI5OC4zNWMwLTIwLjM5OS0xNy44NS0zOC4yNS0zOC4yNS0zOC4yNXMtMzgu%0D%0AMjUsMTcuODUxLTM4LjI1LDM4LjI1VjQzMy41SDIwNA0KCQkJVjIwNGg3Ni41djMwLjZjMTIuNzUt%0D%0AMjAuNCw0MC44LTM1LjcsNjMuNzUtMzUuN2M0OC40NSwwLDg5LjI1LDQwLjgsODkuMjUsODkuMjVW%0D%0ANDMzLjV6Ii8+DQoJPC9nPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0K%0D%0APGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxn%0D%0APg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4N%0D%0ACjwvZz4NCjxnPg0KPC9nPg0KPC9zdmc+DQo=" alt="linkedin"/></a></a>
          </div>
                        <span class="foot">
                            <i class="fa fa-shopping-cart"></i>Add to cart
                        </span>
                    </div>
                </div>
            </div>
        </div> 
    </body>
  </html>
