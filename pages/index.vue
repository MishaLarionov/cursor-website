<template>
  <div>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top"><img src="~/static/rasterizedwordmark.png" alt="Cursor" /></a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fa fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#events">Events</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#team">Team</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-heading"><img src="~/static/rasterizedwordmark.png" alt="Cursor" /></div>
          <a class="btn btn-xl js-scroll-trigger" href="#events"><em>click</em> into tech</a>
        </div>
      </div>
    </header>

    <!-- About -->
    <section id="about" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">About</h2>
            <h3 class="section-subheading text-muted">Why we're here</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <p class="text-muted text-center">
              We are an organisation dedicated to helping passionate youth to learn about tech and programming through mentoring and by experience. We strive to create a rich high school tech culture in and throughout the GTA by hosting hackathons, workshops, tech talks, and other in-person events.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Events -->
    <section id="events">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Events</h2>
            <h3 class="section-subheading text-muted">We host unique workshops, hackathons and more to help build our local tech community.</h3>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-12">
            <span class="fa-stack fa-4x">
              <i class="fa fa-circle fa-stack-2x text-primary"></i>
              <i class="fa fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Coming Soon</h4>
            <p class="text-muted"></p>
          </div>
        </div>
      </div>
    </section>

    <!-- Team -->
    <section class="bg-light" id="team">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Our Planning Team</h2>
            <h3 class="section-subheading text-muted">We're working hard to build new events.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-6">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/nicholas.jpg" alt="">
              <h4>Nicholas Carr</h4>
              <p class="text-muted">Co-Founder</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/nicholas_carr1">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/profile.php?id=100009871454553">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/nicholas-carr-729a95143">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="cursor-website/img/team/2.jpg" alt="">
              <h4>Misha Larionov</h4>
              <p class="text-muted">Co-Founder</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/Misha_Larionov">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/mishalarionov2">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/misha-larionov-617289b9/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="cursor-website/img/team/3.jpg" alt="">
              <h4>Samyar Vahid</h4>
              <p class="text-muted">Head of Marketing</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/plethorum">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/samyarv">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/feng.jpg" alt="">
              <h4>Feng Guo</h4>
              <p class="text-muted">Head of Logistics</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/Feggle_Blast">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/profile.php?id=100009677594415">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/feng-guo-546a84143/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/bill.jpg" alt="">
              <h4>Bill Liu</h4>
              <p class="text-muted">Head of Finance</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/penguinofwinter">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/penguinofwinter">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/bill-liu-a89a52142/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/yash.jpg" alt="">
              <h4>Yash Arora</h4>
              <p class="text-muted">Marketing</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://www.twitter.com/yasharora0606">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/yasharora6">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/yasharora0606/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="cursor-website/img/team/2.jpg" alt="">
              <h4>Joey Chik</h4>
              <p class="text-muted">Logistics</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/joey.chik.75">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/joey-c-1319b7151/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/nikhil.jpg" alt="">
              <h4>Nikhil James</h4>
              <p class="text-muted">Finance</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/profile.php?id=100011524212064">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/nikhil-james-805129150/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/aaron.jpg" alt="">
              <h4>Aaron Yee</h4>
              <p class="text-muted">Marketing</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/AaronYee7">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/ayyy.ron">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/arjun.jpg" alt="">
              <h4>Arjun Pillai</h4>
              <p class="text-muted">Logistics</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="https://twitter.com/ArjunPillai9">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/arjun.pillai.31">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/arjun-pillai-268860145/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="~/static/humans/jonathan.jpg" alt="">
              <h4>Jonathan Xu</h4>
              <p class="text-muted">Logistics</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fa fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.facebook.com/jonathan.xu.50">
                    <i class="fa fa-facebook"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="https://www.linkedin.com/in/jonathanxu01/">
                    <i class="fa fa-linkedin"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy; Cursor 2017</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="https://twitter.com/cursorclub">
                  <i class="fa fa-twitter"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://facebook.com/cursor.club">
                  <i class="fa fa-facebook"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://instagram.com/cursor.club">
                  <i class="fa fa-instagram"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://www.linkedin.com/company/18284485">
                  <i class="fa fa-linkedin"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
