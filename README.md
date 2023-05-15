
###### Link to codecademy lesson

https://www.codecademy.com/courses/learn-intermediate-css/lessons/css-grid-essentials/exercises/creating-columns

# GRID ESSENTIALS

## Creating Columns

By default, grids contain only one column. If you were to start adding items, each item would be put on a new row; that’s not much of a grid! To change this, we need to explicitly define the number of rows and columns in our grid.

We can define the columns of our grid by using the CSS property grid-template-columns. Below is an example of this property in action:


```
.grid {
  display: grid;
  width: 500px;
  grid-template-columns: 100px 200px;
}

```

This property creates two changes. First, it defines the number of columns in the grid; in this case, there are two. Second, it sets the width of each column. The first column will be 100 pixels wide and the second column will be 200 pixels wide.

We can also define the size of our columns as a percentage of the entire grid’s width.


```
.grid {
  display: grid;
  width: 1000px;
  grid-template-columns: 20% 50%;
}

```

In this example, the grid is 1000 pixels wide. Therefore, the first column will be 200 pixels wide because it is set to be 20% of the grid’s width. The second column will be 500 pixels wide.

We can also mix and match these two units. In the example below, there are three columns of width 20 pixels, 40 percent, and 60 pixels:

```
.grid {
  display: grid;
  width: 100px;
  grid-template-columns: 20px 40% 60px;
}

```
# Instructions

![](./screen_shot.jpg)

Notice that in this example, the total width of our columns (120 pixels) exceeds the width of the grid (100 pixels). This might make our grid cover other elements on the page! In a later exercise, we will discuss how to avoid overflow.

In style.css, inside the .grid ruleset, use the grid-template-columns property to create three columns. Set the first column to be 100px wide, the second to be 50% of the grid, and the third to be 200px wide.
```
.grid {
  border: 2px blue solid;
  width: 400px;
  height: 500px;
  display: grid;
  grid-template-columns: 100px 50% 200px;
}

.box {
  background-color: beige;
  color: black;
  border-radius: 5px;
  border: 2px dodgerblue solid;
}
```


### HINT

You should have 3 values after grid-template-columns, each separated by a space.

###### NG:memory aid
/c/Users/glads/Documents/PROJECTS_AT_CODECADEMY/GRID_ESSENTIALS/lesson3_of_15_Creating_Columns





