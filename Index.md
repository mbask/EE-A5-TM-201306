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





---
## Austria

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:32:41 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotAustria () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 47.56667,
11.63333,
"Achenkirch-Mühlegger Köpfl" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotAustria() {
  var data = gvisDataCountryPlotAustria();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotAustria')
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
  callbacks.push(drawChartCountryPlotAustria);
})();
function displayChartCountryPlotAustria() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotAustria"></script>
 
<!-- divChart -->
  
<div id="CountryPlotAustria"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:32:41 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Soil water content </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Bulgaria

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:32:41 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotBulgaria () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 44.1,
27.07,
"Srebarna" 
],
[
 42.41707,
27.695955,
"Sozopol" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotBulgaria() {
  var data = gvisDataCountryPlotBulgaria();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotBulgaria')
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
  callbacks.push(drawChartCountryPlotBulgaria);
})();
function displayChartCountryPlotBulgaria() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotBulgaria"></script>
 
<!-- divChart -->
  
<div id="CountryPlotBulgaria"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:32:41 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass of phytoplankton) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: conductivity </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: nutrients (N, P) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: pH </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: salinity </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: transparency (Secchi disk) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Transparency (Secchi disk) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Water depth </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>





---
## Finland

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:32:41 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotFinland () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 null,
null 
] 
];
data.addColumn('string','latLong');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotFinland() {
  var data = gvisDataCountryPlotFinland();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotFinland')
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
  callbacks.push(drawChartCountryPlotFinland);
})();
function displayChartCountryPlotFinland() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotFinland"></script>
 
<!-- divChart -->
  
<div id="CountryPlotFinland"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:32:41 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> None </TD> <TD> N/A </TD> </TR>
   </TABLE>



---
## Germany



---
## Hungary


---
## Italy


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



