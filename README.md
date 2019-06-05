# XWiki Sports Skill

This XWiki Application has the objective to serve as a backend for the [Mycroft sports skill](https://github.com/ldubost/sports-skill)

The objective will be to be able to retrieve sports results gathered from Open Data sources and in particularly from Wikipedia sport events pages.

Right now there is experimental working code that will parse the Wikipedia French Open 2019 pages to retrieve Tennis results for a specific player. 

The code is here:

https://github.com/ldubost/xwiki-sports-skill/blob/master/src/main/resources/Players.ViewResults/JSON.xml

In the future, some caching might be implemented and also some decision mecanism to find the right source for the data based on a query (which sports) and on the period (to find out the proper tournament).
