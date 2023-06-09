
<template>
    <VueEcharts :option="option" style="height: 370px" ref="chart" />
  </template>
    
  <script setup>
  import { VueEcharts } from 'vue3-echarts';
  import { ref } from '@vue/reactivity';
  
  const option = {
    title: {
      text: 'Stacked Line'
    },
    tooltip: {
      trigger: 'axis'
    },
    legend: {
      data: ['Email', 'Union Ads', 'Video Ads', 'Direct', 'Search Engine']
    },
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
      data: ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    },
    yAxis: {
      type: 'value'
    },
    series: [
      {
        name: 'Email',
        type: 'line',
        stack: 'Total',
        data: [80, 132, 145, 150, 160, 170, 200]
      },
      {
        name: 'Union Ads',
        type: 'line',
        stack: 'Total',
        data: [50, 122, 135, 144, 150, 165, 190]
      },
    ]
  };
  
  </script>
  