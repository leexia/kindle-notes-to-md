# Kindle Notes to MD

Convert an HTML file of book notes exported from an Amazon Kindle to a Markdown document.

The output format is particularly suitable for copy-pasting into
[Roam Research](https://roamresearch.com):

![Screenshot](screenshot.png)

# Update

- 修改支持中文笔记和标注


# Quickstart

Install python packages:

    pip install -r requirements.txt

Convert the example notes:

    kindle_notes_to_md.py example_notebook.html

You can then open `converted.md` in your favorite text editor.

If you copy-paste the contents of that file into
[Roam Research](https://roamresearch.com), you'll get a nicely organized note as shown in the screenshot above.


# How to get your notes in HTML format

I generally read and take notes on my Kindle e-ink reader. When I finish a book, I open the same book on the Kindle app on my phone, go to "My Notebook" for the book (the icon looks like a page with lines), then Export Notebook. This saves the HTML file you can convert.

