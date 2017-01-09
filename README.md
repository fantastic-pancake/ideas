# Capstone project ideas

## Sentiment analysis

* Financial
  - Search by stock ticker (or maybe stock name)
  - Display graph of sentiment
   - Use python, D3?
  - Over last 1-7 days
   - Historical data from twitter rest api
   - Maybe include data from one or more news sources?
  - Realtime update of sentiment
   - Realtime data from twitter streaming api

* Interactive anatomy & physiology tutorial
 - User clicks on part of human body image
 - Information about A + P of clicked area is displayed
  - Pull information from
   - Wikipedia
   - Pubmed
   - WebMd
   - Recent news articles from google news

* Tic Tac Toe with chat
 - Using websockets:
  - Users play one another remotely in real time
  - Users can message in accompanying chatroom in real time

* Smart Home App
 - Control virtual home using voice, text or GUI
  - https://cloud.google.com/speech/ for voice to text
  - virtual home is cartoon house with lights, thermostat, appliances, etc that can be visibly adjusted
   - proof of concept, stands in for actual house
   - other users with same virtual home see changes in real time using websockets
 - Record change events in virtual home
  - display home statistics visually
   - e.g.
    - hours of lights on per day/week
    - electric or gas usage per day/week
