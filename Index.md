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
<!-- Sun Jun 16 18:45:36 2013 -->


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
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Soil water content </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Bulgaria

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


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
<!-- Sun Jun 16 18:45:36 2013 -->
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
<!-- Sun Jun 16 18:45:36 2013 -->


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
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> None </TD> <TD> N/A </TD> </TR>
   </TABLE>



---
## Germany

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotGermany () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 54.43333,
12.7,
"Darss-Zingst Bodden" 
],
[
 54.43333,
12.7,
"Zingst" 
],
[
 50.58333,
6.43333,
"NP Eifel" 
],
[
 52.5,
14.13333,
"Uckermark" 
],
[
 50.15997,
9.000495,
"Rhine-Main-Observatory" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotGermany() {
  var data = gvisDataCountryPlotGermany();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotGermany')
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
  callbacks.push(drawChartCountryPlotGermany);
})();
function displayChartCountryPlotGermany() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotGermany"></script>
 
<!-- divChart -->
  
<div id="CountryPlotGermany"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass of phytoplankton) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Input of major macronutrients (N, P, Si) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Other main meteorological variables </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: pH </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: salinity </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: transparency (Secchi disk) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Aboveground Net Primary Production </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly mean temperatures </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Depth of water table </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>




---
## Hungary

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotHungary () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 47.9,
20.45,
"Síkfőkút " 
],
[
 46.8,
19.38333,
"Kiskun" 
],
[
 46.83333,
17.7,
"Balaton" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotHungary() {
  var data = gvisDataCountryPlotHungary();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotHungary')
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
  callbacks.push(drawChartCountryPlotHungary);
})();
function displayChartCountryPlotHungary() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotHungary"></script>
 
<!-- divChart -->
  
<div id="CountryPlotHungary"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Other main meteorological variables </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Soil water content </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Aboveground biomass by indirect methods </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Aboveground Net Primary Production </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: additional climatic variables (add if necessary) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual mean temperature </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Direct measurements of aboveground biomass (sampling) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>




---
## Italy

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotItaly () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 45.72361,
8.911367,
"Lake Maggiore" 
],
[
 44.3819,
10.0457,
"Lake Scuro Parmense" 
],
[
 44.4025,
10.29,
"Lake Santo Parmense" 
],
[
 40.54483333,
8.94383333,
"Lake Cedrino" 
],
[
 40.54483,
8.943833,
"Lake Temo" 
],
[
 45.30747,
12.814541,
"Gulf of Venice and Trieste" 
],
[
 45.695,
13.705,
"Gulf of Trieste" 
],
[
 44.44,
12.52,
"Po Delta and Romagna Coast" 
],
[
 40.78386,
14.070619,
"LTER Marechiara" 
],
[
 45.33702,
12.274708,
"Lagoon of Venice" 
],
[
 42.04166667,
14.83888889,
"Foce Trigno-Marina di Petacciato (Campobasso)" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotItaly() {
  var data = gvisDataCountryPlotItaly();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotItaly')
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
  callbacks.push(drawChartCountryPlotItaly);
})();
function displayChartCountryPlotItaly() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotItaly"></script>
 
<!-- divChart -->
  
<div id="CountryPlotItaly"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">  10 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">  10 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: pH </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: salinity </TD> <TD align="right">   7 </TD> </TR>
  <TR> <TD> Primary producers diversity: phytoplankton (list, abundance, groups) </TD> <TD align="right">   7 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass of phytoplankton) </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: conductivity </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Transparency (Secchi disk) </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: nutrients (N, P) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: transparency (Secchi disk) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual mean temperature </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual precipitation </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Input of major macronutrients (N, P, Si) </TD> <TD align="right">   3 </TD> </TR>
   </TABLE>




---
## Lithuania

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotLithuania () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 55.4408,
26.0681,
"Aukstaitija" 
],
[
 56.0117,
21.8758,
"Zemaitija" 
],
[
 55.45955,
21.078057,
"Curonian Spit National Park" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotLithuania() {
  var data = gvisDataCountryPlotLithuania();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotLithuania')
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
  callbacks.push(drawChartCountryPlotLithuania);
})();
function displayChartCountryPlotLithuania() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotLithuania"></script>
 
<!-- divChart -->
  
<div id="CountryPlotLithuania"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Soil C/N </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Leaf Area Index </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Number, type and coverage of layers (vertical, horizontal) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Other main meteorological variables </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Vascular plant abundance </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Vascular plant coverage </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Vascular plant species list </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Within habitat diversity </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Aboveground biomass by indirect methods </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Cover of CORINE/EUNIS land uses and habitats </TD> <TD align="right">   2 </TD> </TR>
   </TABLE>



---
## Poland

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


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
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
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
  <TR> <TD> Soil C/N </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Soil type </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Transparency (Secchi disk) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Biomass of consumers </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Macrophytes (structural measurements, presence/absence, cover) </TD> <TD align="right">   2 </TD> </TR>
   </TABLE>



---
## Romania

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotRomania () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 45.43333,
25.333333,
"Bucegi Piatra Craiului" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotRomania() {
  var data = gvisDataCountryPlotRomania();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotRomania')
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
  callbacks.push(drawChartCountryPlotRomania);
})();
function displayChartCountryPlotRomania() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotRomania"></script>
 
<!-- divChart -->
  
<div id="CountryPlotRomania"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Aboveground biomass by indirect methods </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> History of growth by tree ring widths </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Main soil features </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Other main meteorological variables </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Soil C/N </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Soil type </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Vascular plant abundance </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Vascular plant coverage </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Vascular plant species list </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Spain

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotSpain () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 37.08553,
-3.187476,
"Sierra Nevada" 
],
[
 36.97,
-6.39,
"Doñana" 
],
[
 36.97,
-6.39,
"Doñana" 
],
[
 42.626364,
-0.00379,
"Ordesa" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotSpain() {
  var data = gvisDataCountryPlotSpain();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotSpain')
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
  callbacks.push(drawChartCountryPlotSpain);
})();
function displayChartCountryPlotSpain() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotSpain"></script>
 
<!-- divChart -->
  
<div id="CountryPlotSpain"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Cover of CORINE/EUNIS land uses and habitats </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> History of growth by tree ring widths </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Presence and type of natural disturbances </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Vascular plant abundance </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Aboveground biomass by indirect methods </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Aboveground Net Primary Production </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual mean temperature </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Sweden

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 18:45:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryPlotSweden () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 57.0833,
14.5333,
"Aneboda" 
],
[
 63.85,
18.1,
"Gammtratten" 
],
[
 58.05,
12.0167,
"Gårdsjön" 
],
[
 59.75,
14.9,
"Central Swedish uplands spruce forest – Kindla" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','siteName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCountryPlotSweden() {
  var data = gvisDataCountryPlotSweden();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryPlotSweden')
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
  callbacks.push(drawChartCountryPlotSweden);
})();
function displayChartCountryPlotSweden() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryPlotSweden"></script>
 
<!-- divChart -->
  
<div id="CountryPlotSweden"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 18:45:36 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Aboveground Net Primary Production </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Cover of CORINE/EUNIS land uses and habitats </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Depth of water table </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Direct measurements of aboveground biomass (sampling) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Leaf Area Index </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Litterfall (aboveground) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Main soil features </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Net Primary Production </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Net radiation </TD> <TD align="right">   4 </TD> </TR>
   </TABLE>



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



