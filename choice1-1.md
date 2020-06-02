---
layout: page
title: Will you change your mind?
subtitle: There is a slight increase in sales, but not enough.
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


<p></p>
<div class="container">
    <div class="row">
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text1'>
            <div style="text-align: center;">
              <h3>Choice 1 </h3>
              <img src="https://images.unsplash.com/photo-1575043627654-ef061bd7700f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" height = "250" style = "margin-bottom: 5px">
              <div class='button'><a href="../choice1-2" class="btn btn-primary"><span>Choose choice 1</span></a></div>
            </div>
              You decide to track the pages visited by each client and recommend related products.
          </div>
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="text-align: justify;">
          <div class='text2'>
            <div style="text-align: center;">
              <h3>Choice 2</h3>
              <img src="https://images.unsplash.com/photo-1565598469107-2bd14ae7e7e4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1096&q=80" height = "250" style = "margin-bottom: 5px">
              <div class= 'button'><a href="../choice1-1-2" class="btn btn-primary"><span>Choose choice 2</span></a></div>
            </div>
              You refuse to use tracking to increase sales.
          </div>
        </div>
    </div>
</div>
