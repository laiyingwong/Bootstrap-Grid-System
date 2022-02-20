# Bootstrap Grid System

This project illustrates the basic principles of **rows**, **columns** and **breakpoints** in Bootstrap's grid system and how to manipulate them to align content and create responsive layouts. One use case in the project is to make images responsive to three different screen sizes.


## 🎉 Demo 

![app demo](Assets/bootstrap-grid.gif)


## ✨ What I Have Learned

Bootstrap's grid system uses a series of containers, rows, and columns to align the layouts. A row is defined with a `row` class, and every row in Bootstrap has 12 units to divvy up. In other words, Bootstrap's grid system allows up to 12 columns horizontally. The columns are defined with the `col` class, and they should be placed within a certain `row` for grouping. The column width can be customized dynamically to specify how many units a column can take up in a row. For example, a column with a class of `col-6` will occupy 50% of a row.

Bootstrap classifies screen sizes ranging from extra small (`xm`) to extra large (`xll`) on the basis of pixels. The transition between the various screen sizes is known as breakpoints. Specifying the breakpoint for a column determines how responsive the content inside of that column will be. For instance, a column with `col-md-6` will take up 6 units in a row at the **medium** breakpoint.


## 👏 Credits

This project is based on the <a href="https://getbootstrap.com/docs/4.6/getting-started/introduction/">Bootstrap Documentation<a/> and the Bootstrap tutorial of <a href="https://www.udemy.com/course/the-web-developer-bootcamp/">The Web Developer Bootcamp</a> by Colt Steele.
