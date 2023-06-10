
<template>
    <VueEcharts :option="option" style="height: 400px" ref="chart" />
  </template>
    
  <script setup>
  import { VueEcharts } from 'vue3-echarts';
  
  const option = {
    tooltip: {
      trigger: 'item',
      backgroundColor: 'rgba(0, 0, 0, 0.7)', // Set the background color to a dark shade (adjust the alpha value as needed)
      textStyle: {
        color: '#fff' // Set the text color to white
      }
    },
    legend: {
      top: '5%',
      left: 'center',
      textStyle: {
        color: '#fff' // Set the text color to white
      }
    },
    series: [
      {
        name: 'Access From',
        type: 'pie',
        radius: ['50%', '70%'],
        avoidLabelOverlap: false,
        label: {
          show: false,
          position: 'center'
        },
        emphasis: {
          label: {
            show: true,
            fontSize: 40,
            fontWeight: 'bold'
          }
        },
        labelLine: {
          show: false
        },
        data: [
          { value: 1048, name: 'Search Engine' },
          { value: 735, name: 'Direct' },
          { value: 580, name: 'Email' },
          { value: 484, name: 'Union Ads' },
          { value: 300, name: 'Video Ads' }
        ]
      }
    ]
  };
  
  </script>
  