# tribute-page
<!-- This is the tribute page for Justin Vernon
-->

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="Tribute to Justin Vernon"     content="Tribute Website">

    <style>

    body {
      font-size: 1.6rem;
      line-height: 1.5;
      text-align: center;
      color: #333;
      margin: 0;
    }

    h1 {
      font-size: 4rem;
      margin-bottom: 0;
      font-family: Helvetica;

    }

    h2 {
      font-size: 3.25rem;
      text-align: center;
    }

    media (max-width: 460px) {
      h1 {
        font-size: 3rem;
        line-height: 1.2;
      }
    }

    h3 {
      text-align: center;
      font-size: 2rem;
      font-family: Helvetica;
    }

    h5 {
      text-align: center;
      font-size: 1rem;
      font-family: Helvetica;
    }

    #main {
      background-color: #C8C1C0;
      margin: 30px 8px;
      padding: 15px;
      border-radius: 5px;
      background: #EEE

    }

    #title {
      margin: 50px 0;
      text-align: center;
    }

    a {
      color: #477ca7;
    }

    #tribute-link {
      color: #1A64F0;
    }

    img {
      max-width: 100%;
      display: block;
      height: auto;
      margin: 0 auto;
      filter: gray;
      -webkit-filter: grayscale(1); 
      filter: grayscale(1); 
    }

    #img-div {
      background-color: white;
      padding: 15px;
      margin: 0;
    }

    #img-caption {
      margin: 15px 0 5px 0;
      text-align: center;
      font-size: 1rem;
      font-color: #A7AAB0;
    }

    media (max-width: 460px) {
      #img-caption {
        font-size: 1.4rem;
      }
    }

    #tribute-info {
      max-width: 550px;
      margin: 0 auto 50px auto;
      text-align: left;
      line-height: 1.6;
    }

    li {
      margin: 16px 0;
    }


    </style>

  </head>

  <body>
    <main id="main">
      <h1 id="title"> Justin Vernon </h1>

      <p id="title">The front-man to the band <i>Bon Iver</i>.</p>

      <figure id="img-div">
        <img id="image" src="https://media.pitchfork.com/photos/592c6dd7c0084474cd0c7d6b/2:1/w_648/86f9142c.jpg"
      </figure>
      <figcaption id="img-caption"> Justin Vernon has been in the spotlight since 2008 with his break-out album <i>For Emma, Forever Ago</i>.                 </figcaption>

   <section id="main">
     <h3>Overview of Vernon's Career</h3>
     <ul id="tribute-info">
       <li> <b>1981</b> - Born in Eau Claire, Wisconsin.</li>
       <li> <b>2001</b> - Forms the band <i>DeYarmond Edison</i>.</li>
       <li> <b>2006</b> - Leaves Wisconsin following a breakup with his band and his girlfriend.</li>
       <li> <b>2006-2007</b> - Writes the crically acclaimed album "<i>For Emma, Forever Ago</i>" in his remote cabin. </li>
       <li> <b>2012</b> - Wins <i>Best New Artist</i> at the 2012 Grammy Awards for his 2011 self-titled album "<i>Bon Iver, Bon Iver</i>"</li>

     </ul>

        </section>

        <h5>Further reading on Justin Vernon can be found at this wiki <a id="tribute-link" href="https://en.wikipedia.org/wiki/Justin_Vernon" target="_blank">link</a> </h5>

    </main>


  </body>

</html>
