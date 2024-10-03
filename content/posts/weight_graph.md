---
date: 2024-02-02
draft: true
params:
  author: Jonas Niklasson
title: My first post
---
{{< chart >}}

type: 'line',
data: {
  const labels = Utils.months({count: 7});
  labels: ['39', '40', '41', '42', '43', '44','45','46'],
  datasets: [{
    label: 'Weight',
    data: [59, 60, 61, 62, 65],
    tension: 0.25
  }]
}
{{< /chart >}}
