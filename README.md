<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Flag Project</title>
  <style>
    /* Write your CSS Code here */
    .flag {
      height: 600px;
      width: 900px;
      background-color: red;
      position: relative;
           
    }

     .flag > div {
      background-color:  #002868;
      height:300px;
      width: 100%;
      position: absolute;
      top: 150px;

     }

      p {
        font-size: 5rem;
        color:white;
        text-align:center;
        padding:0;
        margin: 0; 
      }

      .flag > div > div {

        background-color: white;
        position: absolute;
        height:200px;
        width:200px;
        border-radius:50%;
        top:50px;
        left:350px;
      }
      .flag>div>div>p {
        color: black;
      }
  </style>
</head>

<!-- 
  IMPORTANT! Do not change any HTML
Don't add any classes/ids/elements 
Use what you know about combining selectors 
and CSS specificity instead.
Hint 1: The flag is 900px by 600px and the circle is 200px by 200px.
Hint 2: You can use CSS inspection to get the colors from
https://appbrewery.github.io/flag-of-laos/
-->

<body>
  <div class="flag">
    <p>The Flag</p>
    <div>
      <div>
        <p>of Laos</p>
      </div>
    </div>
  </div>
</body>

</html>
