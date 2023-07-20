# Gallery
In this project use of image gallery is implemented using grid 
brief about GRID
**Grid in HTML**

The CSS grid layout module is a powerful tool for creating complex and responsive layouts on the web. It allows you to divide your page into a grid of rows and columns, and then place your content in specific locations within the grid.

To use grid layout, you first need to set the `display` property of your container element to `grid` or `inline-grid`. This will make the element a grid container, and its children will become grid items.

You can then use the `grid-template-columns` and `grid-template-rows` properties to define the number and width of columns and rows in your grid. For example, the following code will create a grid with 3 columns and 2 rows:

```
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
}
```

The `grid-template-columns` property defines the width of each column, and the `grid-template-rows` property defines the height of each row. The `fr` unit represents a fraction of the available space, so in this example, each column will be 1/3 of the width of the container, and each row will be 1/2 of the height of the container.

Once you have defined the grid, you can use the `grid-column` and `grid-row` properties to place your content in specific locations within the grid. For example, the following code will place a red box in the first column of the first row of the grid:

```
.grid > .red {
  grid-column: 1;
  grid-row: 1;
  background-color: red;
}
```

You can also use the `grid-area` property to place your content in a specific area of the grid. The `grid-area` property takes a string as its value, and the string must be a comma-separated list of column and row names. For example, the following code will place a green box in the "header" area of the grid:

```
.grid > .green {
  grid-area: header;
  background-color: green;
}
```

The `grid-area` property is a more flexible way to place your content in the grid, as it allows you to define areas that span multiple columns and rows.

Grid layout is a powerful tool that can be used to create complex and responsive layouts on the web. By understanding the basic concepts of grid layout, you can create beautiful and functional web pages that will look great on any device.

Here is an example of a web page that uses grid layout:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid Layout Demo</title>
</head>
<body>
  <div class="grid">
    <div class="red">
      <h1>This is a red box</h1>
    </div>
    <div class="green">
      <h1>This is a green box</h1>
    </div>
    <div class="blue">
      <h1>This is a blue box</h1>
    </div>
  </div>
</body>
</html>
```

This web page uses grid layout to create a grid of 3 columns and 1 row. The red box is placed in the first column, the green box is placed in the second column, and the blue box is placed in the third column.

You can try this example yourself by opening it in a web browser. You should see a grid of 3 boxes, one in each column.
