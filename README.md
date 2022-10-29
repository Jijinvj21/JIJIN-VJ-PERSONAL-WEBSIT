
    <!-- ======= Portfolio Section ======= -->
    <section id="portfolio" class="portfolio section-bg">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2 id="works">Works</h2>
           

        <div class="row">
          <div class="col-lg-12 d-flex justify-content-center" data-aos="fade-up" data-aos-delay="100">
            <!-- <ul id="portfolio-flters">
            
              <li data-filter=".filter-web">Web</li>
            </ul> -->
          </div>
        </div>

        <div class="row portfolio-container" data-aos="fade-up" data-aos-delay="200">

          

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="/Jijin-vj-personal-static-website--main/img/Apple-Logo.png" class="img-fluid mc-image" alt="">
              <div class="portfolio-info">
                <h4>Web </h4>
                <p>Web</p>
                <div class="portfolio-links">
                  </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="/Jijin-vj-personal-static-website--main/img/mc121.png" class="img-fluid itune-img" alt="">
              <div class="portfolio-info">
                <h4>Web </h4>
                <p>Web</p>
                <div class="portfolio-links">
                  </div>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section><!-- End Portfolio Section -->
  </div>






























/*--------------------------------------------------------------
# Portfolio
--------------------------------------------------------------*/
#works
{
  text-align: center;
}
/* .portfolio-wrap
{
  align-items: center;
  color: white;
  margin-top: 50px;
  font-family: 'Playfair Display', serif;
} */
/* .portfolio .portfolio-item {
  margin-bottom: 30px;
}

.portfolio #portfolio-flters {
  padding: 0;
  margin: 0 auto 25px auto;
  list-style: none;
  text-align: center;
  background: #fff;
  border-radius: 50px;
  padding: 2px 15px;
} */
/* 
.portfolio #portfolio-flters li {
  cursor: pointer;
  display: inline-block;
  padding: 10px 15px;
  font-size: 14px;
  font-weight: 600;
  line-height: 1;
  text-transform: uppercase;
  color: #ffffff;
  margin-bottom: 5px;
  transition: all 0.3s ease-in-out;
} */
/* 
.portfolio #portfolio-flters li:hover,
.portfolio #portfolio-flters li.filter-active {
  color: #0563bb;
}

.portfolio #portfolio-flters li:last-child {
  margin-right: 0;
}

.portfolio .portfolio-wrap {
  transition: 0.3s;
  position: relative;
  overflow: hidden;
  z-index: 1;
  background: rgba(255, 255, 255, 0.8);
} */
/* 
.portfolio .portfolio-wrap::before {
  content: "";
  background: rgba(255, 255, 255, 0.7);
  position: absolute;
  left: 30px;
  right: 30px;
  top: 30px;
  bottom: 30px;
  transition: all ease-in-out 0.3s;
  z-index: 2;
  opacity: 0;
} */

.portfolio .portfolio-wrap .portfolio-info {
  /* opacity: 0; */
  /* position: absolute; */
  /* top: 0;
  left: 0;
  right: 0;
  bottom: 0; */
  text-align: center;
  /* z-index: 3; */
  /* transition: all ease-in-out 0.3s; */
  /* display: flex; */
  /* flex-direction: column; */
  justify-content: center;
  align-items: center;
}

.portfolio .portfolio-wrap .portfolio-info::before {
  /* display: block; */
  /* content: ""; */
  width: 48px;
  height: 48px;
  /* position: absolute; */
  top: 35px;
  left: 35px;
  border-top: 3px solid #d7dce1;
  border-left: 3px solid #d7dce1;
  /* transition: all 0.5s ease 0s; */
  /* z-index: 9994; */
}

.portfolio .portfolio-wrap .portfolio-info::after {
  display: block;
  content: "";
  width: 48px;
  height: 48px;
  /* position: absolute; */
  bottom: 35px;
  right: 35px;
  border-bottom: 3px solid #d7dce1;
  border-right: 3px solid #d7dce1;
  /* transition: all 0.5s ease 0s; */
  /* z-index: 9994; */
}
/* 
.portfolio .portfolio-wrap .portfolio-info h4 {
  font-size: 20px;
  color: #45505b;
  font-weight: 600;
}

.portfolio .portfolio-wrap .portfolio-info p {
  color: #45505b;
  font-size: 14px;
  text-transform: uppercase;
  padding: 0;
  margin: 0;
} */
/* 
.portfolio .portfolio-wrap .portfolio-links {
  text-align: center;
  z-index: 4;
}

.portfolio .portfolio-wrap .portfolio-links a {
  color: #45505b;
  margin: 0 2px;
  font-size: 28px;
  display: inline-block;
  transition: 0.3s;
} */
/* 
.portfolio .portfolio-wrap .portfolio-links a:hover {
  color: #148af9;
}

.portfolio .portfolio-wrap:hover::before {
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
} */

.portfolio .portfolio-wrap:hover .portfolio-info {
  opacity: 1;
}

.portfolio .portfolio-wrap:hover .portfolio-info::before {
  top: 15px;
  left: 15px;
}
/* 
.portfolio .portfolio-wrap:hover .portfolio-info::after {
  bottom: 15px;
  right: 15px;
} */


