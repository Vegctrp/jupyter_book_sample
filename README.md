# jupyter-book-sample

Describe your project here.


## howto

### build repo
```
rye init jupyter_book_sample
cd jupyter_book_sample
rye pin 3.10.15
rye sync
rye add --dev jupyter-book
source .venv/bin/activate

jb create myfirstbook
```