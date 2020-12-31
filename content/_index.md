+++
title = "Compose"
# define chart data here
[data]
  fileLink = "content/projects.csv" # path to where csv is stored
  colors = ["#627c62", "#11819b", "#ef7f1a", "#4e1154"] # chart colors
  columnTitles = ["Project", "No. of Test Cases", "URL"] # optional if no table will be displayed from dataset
  baseChartOn = 2 # number of column the chart(s) and graph should be drawn from # can be overridden directly via shortcode parameter # it's therefore optional
  title = "Projects"
+++

{{< block "grid-2" >}}
{{< column >}}
# Welcome to SODA QA.

SODA QA hopes to bring all the test cases and quality analytics under one roof.  

We hope to create this repository and use it for test case management.

{{< button "docs/compose/" "Read the Docs" >}}{{< button "https://github.com/onweru/compose" "Download Theme" >}}
{{< /column >}}

{{< column >}}

{{< /column >}}
{{< /block >}}
{{< column "mt-2" >}}
### An overview of the number of testcases in each repository 
{{< /column >}}
{{< grid "3" >}}
  {{< chart "data" "table" >}}
{{< /grid >}}

{{< button "docs/compose/graphs-charts-tables/" "Learn more" "mt-2" >}}
