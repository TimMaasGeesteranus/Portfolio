<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">     
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</head>
<style>
.carousel{
    width: auto;    
}

#textArea{
  width: 50%;
}

p{
  margin: 10px;
}

h1, h2, #topKnop{
  text-align: center;
}

</style>
<body>

<div class="container">
  <div class="row">
    <div class="col">
    </div>
    <div id="textArea" class="col-9">
      <h1 id="top">Tim Maas Geesteranus</h1>
      <ul>
        <li>
            <a href="#overMij">Over mij</a>
        </li>
        <li>
            <a href="#interestAR">InterestAR</a>
        </li>
        <li>
          <a href="#ideaBoard">IdeaBoard</a>
        </li>
        <li>
          <a href="#projectCloner">FullProjectCloner</a>
        </li>
      </ul>
      <a id="overMij"><h2>Over mij</h2></a>
      <p>
      In september 2017 ben ik gestart aan de opleiding HBO-ICT aan de HAN in Nijmegen. Binnen deze opleiding heb ik gekozen voor het profiel Web-Development. Als minor heb ik een pre-master Cyber Security gedaan aan de Radboud Universiteit. Op deze pagina is een overzicht te vinden van alle projecten waar ik aan gewerkt heb.
      </p>
      <a id="interestAR"><h2>InterestAR</h2></a>
      <p>InterestAR is een applicatie die op Android telefoons draait. Met behulp van augmented reality kan de gebruiker zijn omgeving scannen met de camera en meteen in beeld zien welke bezienswaardigheden er in de buurt zijn. Het is meteen duidelijk hoe ver weg de bezienswaardigheid is en ook kan de bijbehorende informatie worden bekeken in meerdere talen.</p>
      <p>De app is gemaakt tijdens mijn studie HBO-ICT met een team van 6 studenten. De app is gebouwd in C# met Unity en Mapbox. De code van dit project staat op <a href="https://github.com/TimMaasGeesteranus/AangevuldeRealiteit" target="_blank">Github</a>
      </p>
      <div id="interestARCarousel" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="InterestAR/InterestAR.gif" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="InterestAR/InterestAR2.jpg" alt="Second slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#interestARCarousel" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#interestARCarousel" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
      <br>
      <a id="ideaBoard"><h2>IdeaBoard</h2></a>
      <p>IdeaBoard is een webapplicatie gemaakt voor werkplekken waar mensen creatieve ideeën zichtbaar en bespreekbaar willen maken.
        Ideeën kunnen worden toegevoegd via de app. Ook kan hier op ideeën van anderen gestemd worden. De 5 ideeën met de 
        meeste stemmen worden weergegeven op een groot scherm.
      </p>
      <p>De app is gemaakt tijdens mijn studie HBO-ICT met een team van 5 studenten. De app is gebouwd in Javascript met het framework React.
      De code van dit project staat op <a target="blank" href="https://github.com/TimMaasGeesteranus/IdeaBoard">Github</a>.
      </p>

      <div id="ideaBoardCarousel" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="IdeaBoard/Ideaboard.jpg" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="IdeaBoard/Ideaboard2.jpg" alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="IdeaBoard/Ideaboard3.jpg" alt="Third slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#ideaBoardCarousel" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#ideaBoardCarousel" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
      <br>
      <a id="projectCloner"><h2>FullProjectCloner</h2></a>
      <p>Deze webapplicatie maakt het mogelijk om eenvouding Github-repositories te delen met anderen. Het concept is eenvoudig: log in met Github, kies een repository en verstuur in één keer een uitnodiging om de repository te clonen naar een lijst mailadressen.
        Heb je een uitnodiging ontvangen? Klik op de link om naar de applicatie te gaan. Daar log je in met Github en kun je het verzoek accepteren. Nu wordt de repository automatisch gecloned en is hij klaar voor gebruik! </p>
      <p>De app is gemaakt tijdens mijn studie HBO-ICT met een team van 5 studenten. De app is gebouwd in Typescript met het framework Angular.      
        De code van dit project staat op <a target="blank" href="https://github.com/TimMaasGeesteranus/FullProjectCloner">Github</a>.
      </p>

      <div id="fullProjectCloner" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="FullProjectCloner/Fullprojectcloner.gif" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="FullProjectCloner/FullProjectCloner.jpg" alt="Second slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#fullProjectCloner" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#fullProjectCloner" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

      <p id="topKnop"><a href="#top">Terug naar boven</a></p>
      

      
    </div>
    <div class="col">
    </div>
  </div>
</div>



</body>
</html> 