# hpes_test
## Generate HTML
```shell
./otl2html.py -s zufass.css zufass.otl > zufass.html
```
## Generate PDF
[I recommend wkhtmltopdf](http://wkhtmltopdf.org/)
```shell
wkhtmltopdf -s A5 zufass.html zufass.pdf
```
