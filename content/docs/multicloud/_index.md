+++
title = "Mutlicloud Test cases"
weight = 1
[dataset1]
  fileLink = "testcases/soda-multi-cloud-test-case-sheet.csv" # path to where csv is stored
  colors = ["#ef7f1a", "#627c62", "#11819b", "#4e1154"] # chart colors
  columnTitles = ["Feature Scenario","Testcase Title","Testcase Precondition","Testcase steps","Expected Result"] # optional if not table will be displayed from dataset
  baseChartOn = 3 # number of column the chart(s) and graph should be drawn from # can be overridden directly via shortcode parameter # it's therefore optional
  title = "Mutlicloud Test Cases"
+++

#### __Show Table at once__


{{< grid "3" >}}
  {{< chart "dataset1" "table" >}}
{{< /grid >}}


