---
layout: page
title: Congratulations,
subtitle: you are now an enginner!
---
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    .text1 {
      transition: 0.5s;
      opacity:0.5;
    }

    .text2 {
      transition: 0.5s;
      opacity: 0.5;
    }
    .text1:hover {
      opacity:1;
      font-size: 110%;
      transition: 0.5s;

    }
    .text2:hover {
      opacity: 1;
      font-size: 110%;
      transition: 0.5s;
    }

    .button span {
      cursor: pointer;
      display: inline-block;
      position: relative;
      transition: 0.5s;
    }

    .button span:after {
      content: '\00bb';
      position: absolute;
      opacity: 0;
      top: 0;
      right: -20px;
      transition: 0.5s;
    }

    .button:hover span {
      padding-right: 25px;
    }

    .button:hover span:after {
      opacity: 1;
      right: 0;
    }

  </style>
</head>
<body>
You have been working for a little over a year at your firm. The most recent project is new for all and is about making a machining stand to be used by workers. During a meeting with your coworkers who are all more experienced than you, you bring up that they seem to favor the use of bolted joints over welded joints for price reasons. You mention that welded joints would be more reliable and safer for the employees but your coworkers don’t agree.
<p></p>
<div class="container">
    <div class="row">
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text1'>
            <div style="text-align: center;">
              <h3>Choice 1 </h3>
              <img src="https://images.unsplash.com/photo-1579256945823-f007794790df?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" height = "250" style = "margin-bottom: 5px">
              <div class='button'><a href="../choice1-1" class="btn btn-primary"><span>Choose choice 1</span></a></div>
            </div>
              You insist on your position that bolted joints are unsafe in this case.
          </div>
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text2'>
            <div style="text-align: center;">
              <h3>Choice 2</h3>
              <img src="https://images.unsplash.com/photo-1556761175-b413da4baf72?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=967&q=80" style = "margin-bottom: 5px">
              <div class= 'button'><a href="../choice1-2" class="btn btn-primary"><span>Choose choice 2</span></a></div>
            </div>
              You accept they know better and don’t say anything.
          </div>
        </div>
    </div>
</div>
</body>
