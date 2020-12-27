# NBA-Injuries-Hotspot



<script src="https://www.example.com/javascripts/api/tableau-2.js"></script>
...
<div id="tableauViz"></div>

function initializeViz() {
  // JS object that points at empty div in the html
  var placeholderDiv = document.getElementById("tableauViz");
  // URL of the viz to be embedded
  var url = "https://public.tableau.com/profile/hhlamba#!/vizhome/NBAPlayerInjuries2010-2020/NBAInjuries2010-2020";
  // An object that contains options specifying how to embed the viz
  var options = {
    width: '600px',
    height: '600px',
    hideTabs: true,
    hideToolbar: true,
  };
  viz = new tableau.Viz(placeholderDiv, url, options);
}
