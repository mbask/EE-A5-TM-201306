---
title       : A5 Technical meeting
subtitle    : Jyväskylä (Finland), June 18, 2013
author      : Giorgio Matteucci, Marco Bascietto
job         : CNR - IBAF
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: mbask
  repo: EE-A5-TM-201306
---







## Statistiche generali

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

---
## Andamento della sottomissione



---
## Problemi incontrati nella sottomissione

* FTP
* DEIMS
* Data tool
* Google Drive



---
## Proposte di soluzioni

* FTP
* DEIMS
* Data tool
*publish("mbask", "EE-A5-TM-201306")
 Google Drive



---
## Statistiche per Nazione

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 17:59:39 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotPoland () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 49.19159399,
20.07261086,
"Czarny Staw" 
],
[
 49.19159399,
20.07261086,
"Morskie Oko" 
],
[
 52.2983,
20.808964,
"Kampinos" 
],
[
 49.66861,
18.943611,
"Brenna" 
],
[
 52.75,
23.866667,
"Primaeval Bialowieza Forest" 
],
[
 54.695575,
17.46695,
"Slowinski National Park" 
],
[
 49.19667,
19.890833,
"Tatrzański National Park" 
],
[
 51.43333,
19.916667,
"Sulejowski Reservoir" 
],
[
 51.50833,
22.415,
"West Polesie Biosphere Reserve" 
],
[
 51.50833,
22.415,
"West Polesie Biosphere Reserve" 
],
[
 53.77094,
21.603756,
"Mikołajskie" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotPoland() {
  var data = gvisDataCountryPlotPoland();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotPoland')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "map";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartCountryPlotPoland);
})();
function displayChartCountryPlotPoland() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotPoland"></script>
 
<!-- divChart -->
  
<div id="CountryPlotPoland"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 17:59:39 2013 -->
<TABLE >
<TR> <TH> Parameter Name </TH> <TH> Count </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Secondary producers: zooplankton </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Cover of CORINE/EUNIS land uses and habitats </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> History of growth by tree ring widths </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">   3 </TD> </TR>
   </TABLE>



---
## Austria

* Mappa siti
* Stat per singolo sito


---
## Bulgaria








---
## Finland



---
## Germany



---
## Hungary



---
## Lithuania



---
## Poland



---
## Romania



---
## Spain



---
## Sweden




---
## Stat aggregate oer dominio



---
## I parametri più misurati per dominio


---
## Kick off discussion

1. Obiettivo: pubblicazione peer-review
2. Analisi spaziale (non temporale)

* Panel esperti di dominio? -> 3 progetti
* Singolo panel inter-domain? -> 1 progettone
* 



