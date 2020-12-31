+++
title = "SODA HotPot API Test cases"
weight = 1
[dataset1]
  fileLink = "testcases/api.csv" # path to where csv is stored
  colors = ["#ef7f1a", "#627c62", "#11819b", "#4e1154"] # chart colors
  columnTitles = ["TestCase Type","Testing Method","Feature Scenario","Description","TestcaseId","Testcase Criticality","Testcase Precondition","Testcase steps","Expected Result"] # optional if not table will be displayed from dataset
  baseChartOn = 2 # number of column the chart(s) and graph should be drawn from # can be overridden directly via shortcode parameter # it's therefore optional
  title = "API Test Cases"
+++

This page contains the testcases run against the API repository

#### Testcase breakdown

{{< grid "3 mt-2 mb-2" >}}
  {{< chart "dataset1" "pie" "1" >}}
  {{< chart "dataset1" "doughnut" "2" >}}
  {{< chart "dataset1" "bar" "2" >}}
{{< /grid >}}

#### All testcases

{{< grid "3" >}}
  {{< chart "dataset1" "table" >}}
{{< /grid >}}



