---
layout: default
---

<div class="section top-section home">
  <div class="container">
    <h1 class="text-center heading">
      <img src="/assets/images/infinity.png" height="45">
    </h1>
    <h4 class="subheading">
      Secure collaboration and task management for modern healthcare teams.
    </h4>

    <div class="hero-screenshot text-center">
      <img src="assets/images/iphone_notes.png" height="400px">
    </div>

    <!--div class="col-sm-6 text-center text-sm-right">
      <a href="/signup" class="btn btn-signup">Sign Up Free</a>
    </div-->

    <div class="device-carousel">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-pause="hover" data-interval="">
      <div class="text-center carousel-buttons">
        <button type="button" data-target="#carouselExampleIndicators" data-slide-to="0" class="active btn">Iphone</button>
        <button type="button" data-target="#carouselExampleIndicators" data-slide-to="1" class="btn">Ipad</button>
        <button type="button" data-target="#carouselExampleIndicators" data-slide-to="2" class="btn">Desktop</button>
        <br>
      </div>
      <div class="carousel-inner" role="listbox">
        <div class="carousel-item active">
          <img class="d-block img-fluid iphone-image" src="assets/images/iphone_details_text.png" alt="Iphone App">
          <img class="d-block img-fluid iphone-image" src="assets/images/iphone_tasks_text.png" alt="Iphone App">
          <img class="d-block img-fluid iphone-image" src="assets/images/iphone_caseload_text.png" alt="Iphone App">
          <img class="d-block img-fluid iphone-image hideimage" src="assets/images/iphone_notification_text.png" alt="Iphone App">
        </div>
        <div class="carousel-item">
          <img class="d-block img-fluid ipad-image text-center" src="assets/images/ipad_details.png" alt="Ipad App">
          <img class="d-block img-fluid ipad-image text-center" src="assets/images/ipad_caseload.png" alt="Ipad App">
          <img class="d-block img-fluid ipad-image text-center hideimage" src="assets/images/ipad_notifications.png" alt="Ipad App">
        </div>
        <div class="carousel-item">
          <img class="d-block img-fluid desktop-image text-center" src="assets/images/framed-devices.png" alt="Desktop">
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>
  </div>
</div>

<div class="container-fluid signup2">
  <div class="row">
    <div class="col-md-6 text-center text-md-right collab">
      Sign Up Free And Start Transforming<br>The Way Your Team Collaborates.
    </div>
    <div class="col-md-6 text-center text-md-left">
      <a href="/signup" class="btn btn-signup">Sign Up Free</a>
    </div>
  </div>
</div>

<br>

{% include testimonials.html %}
{% include security.html %}
