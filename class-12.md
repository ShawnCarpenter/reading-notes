# Chart.js
Chart.js has a ton of features, but is pretty easy to get going with the basics out of the box.
The options are set through js object literals.
```js
    options: {
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero:true
                }
            }]
        },
        legend: {
            display: false
        },
        layout: {
            padding: {
                left: 100,
                right: 100,
                top: 50,
                bottom: 50
            }
        }
    }
```
Sets the y axis to start at 0, removes the legend at the top, and sets the padding.

# Canvas

Canvas has a ton of options, you can draw boxes, lines, text, and even create 3-d objects.
