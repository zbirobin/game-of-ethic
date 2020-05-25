---
layout: page
title: Was it the right choice?
subtitle: Will you change your mind?
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

One of your colleagues speaks with you after the meeting and says that he agrees with you on the matter.
<p></p>
<div class="container">
    <div class="row">
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text1'>
            <div style="text-align: center;">
              <h3>Choice 1 </h3>
              <img src="https://images.unsplash.com/photo-1542744095-fcf48d80b0fd?ixlib=rb-1.2.1&auto=format&fit=crop&w=1055&q=80" height = "250" style = "margin-bottom: 5px">
              <div class='button'><a href="../choice1-2-1" class="btn btn-primary"><span>Choose choice 1</span></a></div>
            </div>
              You feel reassured and decide to go to the higher ups and inform them.
          </div>
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text2'>
            <div style="text-align: center;">
              <h3>Choice 2 </h3>
              <img src="https://images.unsplash.com/photo-1461988625982-7e46a099bf4f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" height = "250" style = "margin-bottom: 5px">
              <div class= 'button'><a href="../choice1-2-2" class="btn btn-primary"><span>Choose choice 2</span></a></div>
            </div>
              You still don’t feel confident enough to go to the higher ups to inform them, as you are worried about keeping your job.
          </div>
        </div>
    </div>
</div>
