# index.html
Practica ejercicio IronSkydive
<html>
  <head>
    <meta charset="utf-8">
    <title>IronSkydive</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <nav class="nav-bar">
      <ul class="nav-bar-ul">
        <li> <a class="nav-bar-item" href="#structure"> Day Structure </a> </li>
        <li> <a class="nav-bar-item" href="#team"> Team </a> </li>
        <li> <a class="nav-bar-item" href="#schedule"> Schedule </a> </li>
      </ul>
    </nav>
    <header class="header">
      <h1><img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png" alt="IronSkydive Logo"> IronSkydive </h1>
      <br>
      <h2>Let the trip begin</h2>
      <aside class="quote">
        <i> “The best experience of our lives” </i>
        <p> Ariel Quiñones & Gonzalo Manrique, Ironhack Founders </p>
      </aside>
    </header>
    <section class="dark-background" id="general-information">
      <article class="container">
        <h3> Hello! </h3>
        <p class="text"> Welcome to IronSkydive, the best adventure you will ever have. </p>
        <a class="link-btn" href="#"> Learn More </a>
      </article>
      <article class="container">
        <h3> About us </h3>
        <p class="text"> We like a lot of programming websites, but we also love to practice sports. </p>
        <a class="link-btn" href="#"> Watch Video </a>
      </article>
      <article class="container">
        <h3> Wanna Join? </h3>
        <p class="text"> Join our fitness program to be in good shape while learning. </p>
        <a class="link-btn" href="#"> Register </a>
      </article>
    </section>
    <section class="container" id="structure">
      <h3> How do we structure the day? </h3>
      <div>
        <article class="service-box">
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png" alt="Training Logo">
          <h4> Training </h4>
          <p> We teach all the necessary things to jump from the plane without any kind of problem. </p>
        </article>
        <article class="service-box">
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png" alt="Get Ready Logo">
          <h4> Get Ready </h4>
          <p> You are already prepared, you just need to suit up and parachute. All sizes available. </p>
        </article>
        <article class="service-box">
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png" alt="IronSkydive Fly Logo">
          <h4> Fly </h4>
          <p> You are ready, and the plane is waiting for us in the hangar. Let's fly! </p>
        </article>
        <article class="service-box">
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png" alt="IronSkydive Jump Logo">
          <h4> Jump! </h4>
          <p> You have done the most complicated part. Just one step left...jump! </p>
        </article>
      </div>
    </section>
    <section class="dark-background" id="team">
      <h3> Team </h3>
      <p class="section-text"> Our team collectively has 75 years of experience. Odds are, when you jump out of the plane with these professionals, you won't go splat. </p>
      <hr> 
      <div>
        <article>
          <h4 class="member-name" > Harold Rothstein </h4>
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c18b1c463b80090894237a262dfdfbad.jpg" alt="Harold Rothstein Image">
        </article>
        <article>
          <h4 class="member-name" > Susan Phillips </h4>
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a18d6123a7c8e75f7e70a4e59b941093.jpg" alt="Susan Phillips">
        </article>
        <article>
          <h4 class="member-name" > Taylor Roberts </h4>
          <img src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7104a331530d1b0611da55093b7dc421.jpg" alt="Taylor Roberts Image">
        </article>
      </div>
    </section>
    <section class="container" id="schedule">
      <h3> Schedule </h3>
      <table class="schedule-table" cellpadding="0" cellspacing="0">
        <thead>
          <th> time </th>
          <th> Monday </th>
          <th> Tuesday </th>
          <th> Wednesday </th>
          <th> Thursday </th>
          <th> Friday </th>
          <th> Saturday </th>
        </thead>
        <tbody>
          <tr>
            <td> 9:00 - 11:00 </td>
            <td>  </td>
            <td>  </td>
            <td> X </td>
            <td>  </td>
            <td> X </td>
            <td> X </td>
          </tr>
          <tr>
            <td> 12:00 - 14:00 </td>
            <td>  </td>
            <td>  </td>
            <td>  </td>
            <td>  </td>
            <td> X </td>
            <td> X </td>
          </tr>
          <tr>
            <td> 15:00 - 17:00 </td>
            <td>  </td>
            <td>  </td>
            <td> X </td>
            <td> X </td>
            <td> X </td>
            <td> X </td>
          </tr>
        </tbody>
      </table>
     <h3> Schedule a Time Slot </h3>
      <form class="slot-form" action="/register" method="post">
        <div class="slot-form-container">
          <label> Email </label>
          <input type="email" placeholder="Enter your email">
        </div>
        <div class="slot-form-container">
          <label> Participants </label>
          <input type="Number" placeholder="Number of participants">
        </div>
        <div class="slot-form-container">
          <label> Date </label>
          <input type="date">
        </div>
        <div class="slot-form-container">
          <label> Time </label>
          <select>
            <option value="early"> 9:00 - 11:00 </option>
            <option value="mid"> 12:00 - 14:00 </option>
            <option value="late"> 15:00 - 17:00 </option>
          </select>
        </div>
        <div class="slot-form-container">
          <button type="submit"> Reserve Your Slot! </button>
        </div>
      </form>
    </section>
    <footer class="dark-background footer">
      <section>
        <h5> Contact Information </h5>
        <address class="address">IronSkydive <br /> 33 Rue la Fayette, <br /> 75009 Paris, <br /> France <br /> +33 (0) 619 193 088</address>
        <h5> Follow Us </h5>
        <ul>
          <li> <a href="#"> Twitter </a> </li>
          <li> <a href="#"> Facebook </a> </li>
          <li> <a href="#"> Instagram </a> </li>
        </ul>
      </section>
<iframe src=
    </footer>
  </body>
</html>
