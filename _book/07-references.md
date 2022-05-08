
I can only see the world as it should be.

I can not see into people’s hearts.

But I know in my heart, I see, you, Manjot Kaur Rekhi.

<center>

![December 31, 2021](mimages/15.1 12-31-2021.jpg){length=1000px, width=500px}

</center>

`**Feel free to skip this part**`

## Set up 

I used the tutorial from *https://www.youtube.com/watch?v=_ptrgqx2zUs&ab_channel=AlisonHill*

- I ran the function `create_bs4_book` in the `bookdown` package.

- I opened `_output.yml` file and changed the repo name to my Github repository URL.

- I changed the color theme- `primary` by searching colors in *https://coolors.co/*

- I used `4A8FE7` - United Nations Blue

- Each **bookdown** chapter is an .Rmd file, and each .Rmd file can contain one (and only one) chapter. A chapter *must* start with a first-level heading: `# A good chapter`, and can contain one (and only one) first-level heading.

- Use second-level and higher headings within chapters like: `## A short section` or `### An even shorter section`.

- The `index.Rmd` file is required, and is also your first book chapter. It will be the homepage when you render the book.

## Render book

You can render the HTML version of this example book without changing anything:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:


```r
bookdown::render_book()
```

## Preview book

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


```r
bookdown::serve_book()
```




## Website Publishing 

After adding the poems and pictures, I uploaded the book to Netlify. 

- I used the `_book` folder for the website

Happy reading!



