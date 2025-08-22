# MyGuap

## PLAN FOR THIS APP

I plan on using this app to record my trading journey:

As of today, it will track my weekly trades including a written summary in Markdown, with plans to automatically receive trade info from MT5 (or wherever I place trades).

08/21 TODO LIST:  
(These are inevitably subject to iteration in the future, with expanded explanations and fully fleshed-out concepts. This is just an outline of an idea currently in my brain.)

- [] Create Bun application to serve Markdown
- [] Create Vue application to show:
  - Stats
    - Section for weekly performance
    - Section for trends (ex: average R:R)
  - Calendar
    - 1 month on 1 page
    - Every day will have a square that will take up the entire page
    - Every trading day will be clickable, which will open an in-depth look at the trade, including the long Markdown summary
    - Every clickable day will have a hover that will show the setup
    - Every trading day will have stats including (will look to expand this list eventually):
      - Win/Loss
      - % profit
      - $ profit
      - Setup type
      - R:R

