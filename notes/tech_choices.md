# overview / context

so basically i need to decide what to use to write this miscellaneous data processing application. the obvious choice would be to write it in python (based off of casper guo's f1 viewer, this certainly seems possible), although it seems to me like python tends to be more suited towards one and done data visualisation situations as opposed to something like js which seems more suited to eg a dashboard / data viewer. with that said, there totally exists modules (eg dash, whatever i tried to use etc) for making simple dashboards in python. i do **not** know what the situation is wrt performance with these, however (since that was my major issue with my first attempt at data vis)

## dash (python)
pypi: https://pypi.org/project/dash/
docs: https://dash.plotly.com/layout

this is built on *plotly.js* (also maintained by the plotly team), *react*, and *flask*. as a result, the only sensible plotting module seems to be *plotly.py*

## pandas (python)
