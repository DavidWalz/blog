See [Writing Blog Posts With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter) for more details.

## File naming
You must save your notebook with the naming convention `YYYY-MM-DD-*.ipynb`.
If you fail to name your file correctly, `fastpages` will automatically attempt to fix the problem by prepending the last modified date of your notebook. However, it is recommended that you name your files properly yourself for more transparency.


## Front matter
```
# "Title"
> "Awesome summary"

- toc: false
- branch: master
- badges: true
- comments: true
- categories: [fastpages, topic two]
- image: images/some_folder/your_image.png
- hide: false
- search_exclude: false
- metadata_key1: metadata_value1
- metadata_key2: metadata_value2
```

## Links

## Citations
Cite with "{% cite some_citation_key %}".  
Create ordered list of all citations with "{% bibliography --cited %}".
