---
title: "Community College Attendance in Massachusetts by Race"
author: "Swaha Bhattacharya, Naylynn Tañón Reyes, Tint Tha Ra Wun"
date: "04 May, 2023"
---

<script src="{{< blogdown/postref >}}index_files/htmlwidgets/htmlwidgets.js"></script>
<script src="{{< blogdown/postref >}}index_files/plotly-binding/plotly.js"></script>
<script src="{{< blogdown/postref >}}index_files/typedarray/typedarray.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/jquery/jquery.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/crosstalk/css/crosstalk.min.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/crosstalk/js/crosstalk.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/plotly-htmlwidgets-css/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/plotly-main/plotly-latest.min.js"></script>

A [plotly](https://plotly.com/) graph visualizing enrollment at community colleges
in Massachusetts by race.

<div class="plotly html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-1" style="width:672px;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"visdat":{"fcc85951c698":["function () ","plotlyVisDat"]},"cur_data":"fcc85951c698","attrs":{"fcc85951c698":{"x":{},"y":{},"mode":"lines+markers","hoverinfo":"text","text":{},"color":{},"colors":["turquoise3","orchid2","tan2"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":{"text":"<b>MA Community College Enrollment<b>","x":0.5,"y":0.975},"legend":{"title":{"text":"Student Race"},"x":100,"y":0.15},"xaxis":{"domain":[0,1],"automargin":true,"title":"","type":"category","categoryorder":"array","categoryarray":["Fall 2013","Fall 2014","Fall 2015","Fall 2016","Fall 2017","Fall 2018","Fall 2019","Fall 2020","Fall 2021","Fall 2022"]},"yaxis":{"domain":[0,1],"automargin":true,"title":"Student enrollment"},"shapes":[{"type":"line","y0":0,"y1":1,"yref":"paper","x0":"Fall 2020","x1":"Fall 2020","line":{"color":"black","dash":"dash"}}],"annotations":[{"x":"Fall 2020","y":20000,"text":"COVID-19 affects <br>enrollment numbers","ax":-70}],"hovermode":"closest","showlegend":true},"source":"A","config":{"modeBarButtonsToAdd":["hoverclosest","hovercompare"],"showSendToCloud":false},"data":[{"x":["Fall 2013","Fall 2014","Fall 2015","Fall 2016","Fall 2017","Fall 2018","Fall 2019","Fall 2020","Fall 2021","Fall 2022"],"y":[38510,38863,38373.5,37040,36333,35961.5,34995.5,30298.5,30477.5,30346],"mode":"lines+markers","hoverinfo":["text","text","text","text","text","text","text","text","text","text"],"text":["Term:  Fall 2013 <br> Enrollment: 38,510 <br> Race: POC","Term:  Fall 2014 <br> Enrollment: 38,863 <br> Race: POC","Term:  Fall 2015 <br> Enrollment: 38,373.5 <br> Race: POC","Term:  Fall 2016 <br> Enrollment: 37,040 <br> Race: POC","Term:  Fall 2017 <br> Enrollment: 36,333 <br> Race: POC","Term:  Fall 2018 <br> Enrollment: 35,961.5 <br> Race: POC","Term:  Fall 2019 <br> Enrollment: 34,995.5 <br> Race: POC","Term:  Fall 2020 <br> Enrollment: 30,298.5 <br> Race: POC","Term:  Fall 2021 <br> Enrollment: 30,477.5 <br> Race: POC","Term:  Fall 2022 <br> Enrollment: 30,346 <br> Race: POC"],"type":"scatter","name":"POC","marker":{"color":"rgba(0,197,205,1)","line":{"color":"rgba(0,197,205,1)"}},"textfont":{"color":"rgba(0,197,205,1)"},"error_y":{"color":"rgba(0,197,205,1)"},"error_x":{"color":"rgba(0,197,205,1)"},"line":{"color":"rgba(0,197,205,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Fall 2013","Fall 2014","Fall 2015","Fall 2016","Fall 2017","Fall 2018","Fall 2019","Fall 2020","Fall 2021","Fall 2022"],"y":[4444.5,4763.5,4363.5,4362,4506.5,4091.5,4276,3834,3556,4178],"mode":"lines+markers","hoverinfo":["text","text","text","text","text","text","text","text","text","text"],"text":["Term:  Fall 2013 <br> Enrollment: 4,444.5 <br> Race: Unkown","Term:  Fall 2014 <br> Enrollment: 4,763.5 <br> Race: Unkown","Term:  Fall 2015 <br> Enrollment: 4,363.5 <br> Race: Unkown","Term:  Fall 2016 <br> Enrollment: 4,362 <br> Race: Unkown","Term:  Fall 2017 <br> Enrollment: 4,506.5 <br> Race: Unkown","Term:  Fall 2018 <br> Enrollment: 4,091.5 <br> Race: Unkown","Term:  Fall 2019 <br> Enrollment: 4,276 <br> Race: Unkown","Term:  Fall 2020 <br> Enrollment: 3,834 <br> Race: Unkown","Term:  Fall 2021 <br> Enrollment: 3,556 <br> Race: Unkown","Term:  Fall 2022 <br> Enrollment: 4,178 <br> Race: Unkown"],"type":"scatter","name":"Unkown","marker":{"color":"rgba(238,122,233,1)","line":{"color":"rgba(238,122,233,1)"}},"textfont":{"color":"rgba(238,122,233,1)"},"error_y":{"color":"rgba(238,122,233,1)"},"error_x":{"color":"rgba(238,122,233,1)"},"line":{"color":"rgba(238,122,233,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Fall 2013","Fall 2014","Fall 2015","Fall 2016","Fall 2017","Fall 2018","Fall 2019","Fall 2020","Fall 2021","Fall 2022"],"y":[56828,53259,49930,46122,42554,39895,37053,33551,30954,27815],"mode":"lines+markers","hoverinfo":["text","text","text","text","text","text","text","text","text","text"],"text":["Term:  Fall 2013 <br> Enrollment: 56,828 <br> Race: White","Term:  Fall 2014 <br> Enrollment: 53,259 <br> Race: White","Term:  Fall 2015 <br> Enrollment: 49,930 <br> Race: White","Term:  Fall 2016 <br> Enrollment: 46,122 <br> Race: White","Term:  Fall 2017 <br> Enrollment: 42,554 <br> Race: White","Term:  Fall 2018 <br> Enrollment: 39,895 <br> Race: White","Term:  Fall 2019 <br> Enrollment: 37,053 <br> Race: White","Term:  Fall 2020 <br> Enrollment: 33,551 <br> Race: White","Term:  Fall 2021 <br> Enrollment: 30,954 <br> Race: White","Term:  Fall 2022 <br> Enrollment: 27,815 <br> Race: White"],"type":"scatter","name":"White","marker":{"color":"rgba(238,154,73,1)","line":{"color":"rgba(238,154,73,1)"}},"textfont":{"color":"rgba(238,154,73,1)"},"error_y":{"color":"rgba(238,154,73,1)"},"error_x":{"color":"rgba(238,154,73,1)"},"line":{"color":"rgba(238,154,73,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>