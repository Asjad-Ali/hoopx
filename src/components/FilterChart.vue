
<template>
    <VueEcharts :option="option" style="height: 330px" ref="chart" />
  </template>
    
  <script setup>
  import { VueEcharts } from 'vue3-echarts';
  
  const option = {
    // title: {
    //   text: 'Stacked Line',
    // },
    tooltip: {
      trigger: 'axis',
      backgroundColor: 'rgba(0, 0, 0, 0.7)', // Set the background color to a dark shade (adjust the alpha value as needed)
      textStyle: {
        color: '#fff' // Set the text color to white
      }
    },
    // legend: {
    //   data: ['Email', 'Union Ads', 'Video Ads', 'Direct', 'Search Engine']
    // },
    grid: {
      left: '3%',
      right: '4%',
      bottom: '3%',
      containLabel: true
    },
    toolbox: {
      feature: {
        saveAsImage: {}
      }
    },
    xAxis: {
      type: 'category',
      boundaryGap: false,
      data: ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun'],
      axisLabel: {
        textStyle: {
          color: '#fff' // Set the x-axis label text color to white
        }
      },
    },
    yAxis: {
      type: 'value',
      axisLabel: {
        textStyle: {
          color: '#fff' // Set the x-axis label text color to white
        }
      },
    },
    series: [
      {
        name: 'Email',
        type: 'line',
        stack: 'Total',
        data: [80, 132, 145, 150, 160, 170, 200]
      },
    ]
  };
  
  </script>
  