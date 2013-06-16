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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotAustria () {
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
function drawChartCountryAndDomainPlotAustria() {
  var data = gvisDataCountryAndDomainPlotAustria();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotAustria')
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
  callbacks.push(drawChartCountryAndDomainPlotAustria);
})();
function displayChartCountryAndDomainPlotAustria() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotAustria"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotAustria"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Soil water content </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Bulgaria

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotBulgaria () {
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
function drawChartCountryAndDomainPlotBulgaria() {
  var data = gvisDataCountryAndDomainPlotBulgaria();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotBulgaria')
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
  callbacks.push(drawChartCountryAndDomainPlotBulgaria);
})();
function displayChartCountryAndDomainPlotBulgaria() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotBulgaria"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotBulgaria"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotFinland () {
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
function drawChartCountryAndDomainPlotFinland() {
  var data = gvisDataCountryAndDomainPlotFinland();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotFinland')
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
  callbacks.push(drawChartCountryAndDomainPlotFinland);
})();
function displayChartCountryAndDomainPlotFinland() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotFinland"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotFinland"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> None </TD> <TD> N/A </TD> </TR>
   </TABLE>



---
## Germany

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotGermany () {
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
function drawChartCountryAndDomainPlotGermany() {
  var data = gvisDataCountryAndDomainPlotGermany();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotGermany')
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
  callbacks.push(drawChartCountryAndDomainPlotGermany);
})();
function displayChartCountryAndDomainPlotGermany() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotGermany"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotGermany"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotHungary () {
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
function drawChartCountryAndDomainPlotHungary() {
  var data = gvisDataCountryAndDomainPlotHungary();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotHungary')
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
  callbacks.push(drawChartCountryAndDomainPlotHungary);
})();
function displayChartCountryAndDomainPlotHungary() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotHungary"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotHungary"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotItaly () {
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
function drawChartCountryAndDomainPlotItaly() {
  var data = gvisDataCountryAndDomainPlotItaly();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotItaly')
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
  callbacks.push(drawChartCountryAndDomainPlotItaly);
})();
function displayChartCountryAndDomainPlotItaly() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotItaly"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotItaly"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotLithuania () {
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
function drawChartCountryAndDomainPlotLithuania() {
  var data = gvisDataCountryAndDomainPlotLithuania();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotLithuania')
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
  callbacks.push(drawChartCountryAndDomainPlotLithuania);
})();
function displayChartCountryAndDomainPlotLithuania() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotLithuania"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotLithuania"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotPoland () {
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
function drawChartCountryAndDomainPlotPoland() {
  var data = gvisDataCountryAndDomainPlotPoland();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotPoland')
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
  callbacks.push(drawChartCountryAndDomainPlotPoland);
})();
function displayChartCountryAndDomainPlotPoland() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotPoland"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotPoland"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotRomania () {
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
function drawChartCountryAndDomainPlotRomania() {
  var data = gvisDataCountryAndDomainPlotRomania();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotRomania')
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
  callbacks.push(drawChartCountryAndDomainPlotRomania);
})();
function displayChartCountryAndDomainPlotRomania() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotRomania"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotRomania"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotSpain () {
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
function drawChartCountryAndDomainPlotSpain() {
  var data = gvisDataCountryAndDomainPlotSpain();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotSpain')
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
  callbacks.push(drawChartCountryAndDomainPlotSpain);
})();
function displayChartCountryAndDomainPlotSpain() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotSpain"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotSpain"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
<!-- Sun Jun 16 20:54:06 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotSweden () {
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
function drawChartCountryAndDomainPlotSweden() {
  var data = gvisDataCountryAndDomainPlotSweden();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotSweden')
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
  callbacks.push(drawChartCountryAndDomainPlotSweden);
})();
function displayChartCountryAndDomainPlotSweden() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotSweden"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotSweden"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:06 2013 -->
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
## Stat aggregate per dominio






---
## Terrestrial

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:07 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotTerrestrial () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 52.2983,
20.808964,
"Kampinos" 
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
 47.9,
20.45,
"Síkfőkút " 
],
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
 49.66861,
18.943611,
"Brenna" 
],
[
 45.43333,
25.333333,
"Bucegi Piatra Craiului" 
],
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
],
[
 46.8,
19.38333,
"Kiskun" 
],
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
 42.626364,
-0.00379,
"Ordesa" 
],
[
 47.56667,
11.63333,
"Achenkirch-Mühlegger Köpfl" 
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
 51.50833,
22.415,
"West Polesie Biosphere Reserve" 
],
[
 55.45955,
21.078057,
"Curonian Spit National Park" 
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
function drawChartCountryAndDomainPlotTerrestrial() {
  var data = gvisDataCountryAndDomainPlotTerrestrial();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotTerrestrial')
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
  callbacks.push(drawChartCountryAndDomainPlotTerrestrial);
})();
function displayChartCountryAndDomainPlotTerrestrial() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotTerrestrial"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotTerrestrial"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:07 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Annual mean temperature and precipitation (snow where relevant) </TD> <TD align="right">  20 </TD> </TR>
  <TR> <TD> Monthly precipitation and mean temperature (min, max mean temperature) </TD> <TD align="right">  19 </TD> </TR>
  <TR> <TD> Other main meteorological variables </TD> <TD align="right">  16 </TD> </TR>
  <TR> <TD> Soil C/N </TD> <TD align="right">  14 </TD> </TR>
  <TR> <TD> Vascular plant coverage </TD> <TD align="right">  13 </TD> </TR>
  <TR> <TD> Vascular plant species list </TD> <TD align="right">  13 </TD> </TR>
  <TR> <TD> Atmospheric deposition of main nutrients/pollutants </TD> <TD align="right">  12 </TD> </TR>
  <TR> <TD> Chemistry of precipitation and snow </TD> <TD align="right">  12 </TD> </TR>
  <TR> <TD> Vascular plant abundance </TD> <TD align="right">  12 </TD> </TR>
  <TR> <TD> Cover of CORINE/EUNIS land uses and habitats </TD> <TD align="right">  11 </TD> </TR>
  <TR> <TD> Global radiation reaching the site </TD> <TD align="right">  11 </TD> </TR>
  <TR> <TD> Health status of ecosystem (e.g. crown transparency, defoliation, more complex assessment) </TD> <TD align="right">  11 </TD> </TR>
  <TR> <TD> Within habitat diversity </TD> <TD align="right">  10 </TD> </TR>
  <TR> <TD> Soil water content </TD> <TD align="right">   9 </TD> </TR>
  <TR> <TD> Aboveground Net Primary Production </TD> <TD align="right">   8 </TD> </TR>
   </TABLE>



---
## Freshwater-lake

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:07 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotFreshwater-lake () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 44.1,
27.07,
"Srebarna" 
],
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
 46.83333,
17.7,
"Balaton" 
],
[
 36.97,
-6.39,
"Doñana" 
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
function drawChartCountryAndDomainPlotFreshwater-lake() {
  var data = gvisDataCountryAndDomainPlotFreshwater-lake();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotFreshwater-lake')
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
  callbacks.push(drawChartCountryAndDomainPlotFreshwater-lake);
})();
function displayChartCountryAndDomainPlotFreshwater-lake() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotFreshwater-lake"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotFreshwater-lake"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:07 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Chlorophyll a (connected to biomass in lakes) </TD> <TD align="right">  11 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">  11 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">  10 </TD> </TR>
  <TR> <TD> Transparency (Secchi disk) </TD> <TD align="right">  10 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: conductivity </TD> <TD align="right">   9 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: pH </TD> <TD align="right">   9 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: nutrients (N, P) </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual mean temperature </TD> <TD align="right">   6 </TD> </TR>
  <TR> <TD> Basic climate at the site: annual precipitation </TD> <TD align="right">   6 </TD> </TR>
  <TR> <TD> Primary producers diversity: phytoplankton (list, abundance, groups) </TD> <TD align="right">   6 </TD> </TR>
  <TR> <TD> Secondary producers: zooplankton </TD> <TD align="right">   4 </TD> </TR>
  <TR> <TD> Macrophytes (structural measurements, presence/absence, cover) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Radiation </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Secondary producers: fish </TD> <TD align="right">   3 </TD> </TR>
   </TABLE>



---
## Freshwater-river

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:07 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotFreshwater-river () {
  var data = new google.visualization.DataTable();
  var datajson =
[
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
function drawChartCountryAndDomainPlotFreshwater-river() {
  var data = gvisDataCountryAndDomainPlotFreshwater-river();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotFreshwater-river')
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
  callbacks.push(drawChartCountryAndDomainPlotFreshwater-river);
})();
function displayChartCountryAndDomainPlotFreshwater-river() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotFreshwater-river"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotFreshwater-river"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:07 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Basic climate at the site: monthly temperature and precipitation </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Main hydrological parameters: gauge level </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Main hydrological parameters: turbidity </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Microhabitat diversity, coverage of microhabitats </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Primary producers diversity: macrophytes (list, abundance) </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Secondary producers: macroinvertebrates </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Marine

<!-- Map generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Sun Jun 16 20:54:07 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCountryAndDomainPlotMarine () {
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
function drawChartCountryAndDomainPlotMarine() {
  var data = gvisDataCountryAndDomainPlotMarine();
  var options = {};
options["showTip"] = true;
options["mapType"] = "terrain";
options["useMapTypeControl"] = true;
options["width"] =    800;
options["height"] =    200;

     var chart = new google.visualization.Map(
       document.getElementById('CountryAndDomainPlotMarine')
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
  callbacks.push(drawChartCountryAndDomainPlotMarine);
})();
function displayChartCountryAndDomainPlotMarine() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCountryAndDomainPlotMarine"></script>
 
<!-- divChart -->
  
<div id="CountryAndDomainPlotMarine"
  style="width: 800px; height: 200px;">
</div>
<!-- html table generated in R 3.0.1 by xtable 1.7-1 package -->
<!-- Sun Jun 16 20:54:07 2013 -->
<TABLE >
<TR> <TH> Parameter name </TH> <TH> Sites </TH>  </TR>
  <TR> <TD> Chlorophyll a (connected to biomass of phytoplankton) </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: salinity </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: temperature </TD> <TD align="right">   8 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: oxygen </TD> <TD align="right">   7 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: transparency (Secchi disk) </TD> <TD align="right">   7 </TD> </TR>
  <TR> <TD> Input of major macronutrients (N, P, Si) </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: pH </TD> <TD align="right">   5 </TD> </TR>
  <TR> <TD> Primary producers diversity: phytoplankton (list, abundance, groups) </TD> <TD align="right">   3 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly mean temperatures </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Physical/chemical characteristics: light quantity-quality (euphotic depth) </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Secondary producers: zooplankton </TD> <TD align="right">   2 </TD> </TR>
  <TR> <TD> Basic climate at the site: monthly mean relative humidity </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Biomass of consumers </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Secondary producers: fish </TD> <TD align="right">   1 </TD> </TR>
  <TR> <TD> Total irradiance </TD> <TD align="right">   1 </TD> </TR>
   </TABLE>



---
## Kick off discussion

1. Obiettivo: pubblicazione peer-review
2. Analisi spaziale (non temporale)

* Panel esperti di dominio? -> 3 progetti
* Singolo panel inter-domain? -> 1 progettone
* 



