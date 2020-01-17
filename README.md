# Friday tv shows twitter analysis
Analysis of twitter activity of NTV, Citizen and K24 tv shows.

## Files
### streaming.py
>all important packages are imported including tweepy and sqlalchemy.
>protocolError and urllib3.exceptions are also imported so that the app can resume streaming when a connection error occurs.
>slistener and keysecret objects are two other python scripts in the same folder.
>The collected tweets are stored in an sqlite database then visualized using plotly dash.
