# Pie Chart
## Introduction

A pie chart is a circular graphic divided into slices, with each slice representing a proportion of the whole.


Pie charts are especially useful for visualizing smaller datasets where understanding the relative proportions between categories is key. They excel at displaying categorical data in a way that emphasizes percentages or proportions, making it easy for viewers to quickly grasp scale and relative sizes.


With PureChart, you gain extensive styling flexibility for creating fully customized pie charts that fit seamlessly into your application’s design. Each chart also includes a corresponding legend that clearly lists the categories represented.


## Usage
Adding a pie chart is simple:

```erb
<%= pie_chart @data %>
```

Here's an example of some data you could pass in:

```rb
@data = [
    {
        name: "Dogs",
        color: "blue",
        value: 150
    },
    {
        name: "Cats",
        color: "purple",
        value: 135
    },
    {
        name: "Parrots",
        color: "orange",
        value: 70
    },
]
```
And here is the corresponding chart:
