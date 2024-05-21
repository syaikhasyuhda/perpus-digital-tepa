<template>
  <div>
    <canvas id="myChart"></canvas>
  </div>  
</template>

<script setup>
import Chart from 'chart.js/auto'

const labels = [
  'January',
  'February',
  'March',
  'April',
  'May',
  'June',
];

const data = {
  labels: labels,
  datasets: [{
    label: 'My First dataset',
    backgroundColor: [
    'rgb(202, 166, 219)',
    'rgb(196, 138, 223)',
    'rgb(175, 140, 192)',
    'rgb(175, 135, 193)',
    'rgb(209, 149, 237)',
    'rgb(202, 166, 219)',
    ],
    borderColor: 'rgb(255, 99, 132)',
    data: [20, 10, 10, 15, 20, 30, 45],
  }]
};

const config = {
  type: 'bar',
  data: data,
  options: {}
};

onMounted(() => {
  const myChart = new Chart(
  document.getElementById('myChart'),
  config
);
})
</script>