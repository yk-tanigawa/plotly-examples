# example 1 : scatter plot from csv file

### procedure

- Read csv file as text
- Parse the text as 2d array
- Transpose 2d array to get list of column vectors
- Select y-value column and label column
- Pass the data to plotly

### testing on your local environment

- You may need to host a local HTTP server to load csv file

```
$ python -m SimpleHTTPServer
```

- Open the html file with `http://` instead of `file://`
  - `http://localhost:8000/<path to your local copy of the repository>/plotly-examples/example1/plot.html`

