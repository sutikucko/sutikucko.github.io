---
title: "Overview"
permalink: /
excerpt: ""
---

Quisque euismod lectus auctor enim rutrum congue. Quisque justo lacus, iaculis a nibh sit amet, viverra varius erat. Etiam auctor ligula ac risus rhoncus feugiat a at urna. Phasellus nisi enim, maximus sed ornare id, mattis a nulla. Morbi semper purus id commodo venenatis. Ut vitae tortor ex. Sed a blandit nulla.



<div id="mychart" style="width: 600px;height:400px;"></div>

<script type="text/javascript">
var myChart = echarts.init(document.getElementById('mychart'));

// Specify the configuration items and data for the chart
var option = {
title: {
    text: 'ECharts Example'
},
tooltip: {},
legend: {
    data: ['sales', 'others']
},
xAxis: {
    data: ['Shirts', 'Cardigans', 'Chiffons', 'Pants', 'Heels', 'Socks']
},
yAxis: {},
series: [
    {
    name: 'sales',
    type: 'bar',
    data: [5, 20, 36, 10, 10, 20]
    },
    {
    name: 'others',
    type: 'bar',
    data: [15, 2, 16, 20, 4, 12]
    }
]
};

// Display the chart using the configuration items and data just specified.
myChart.setOption(option);
</script>

