# Goal
My newsletter has to be ported from [Revue](https://harsh17.in/next) to a seperate website, preferably with automatic scrapping and publishing cabailities. 

Internally, I'm conflicted if this should be done or not. Revue already hosts it well; why take up the additional hassle? Revue will protect it against other minor things. On the other hand, I'm not comfortable with other service hosting most of writing. So the question, how much control am I willing to give up?

# How?
- Scrap pages based on a link provided at the [editions website](https://docs.google.com/spreadsheets/d/1jT8qyDzAok7lr23Vb1nRIU8c0vYgwvjRMHktMwFyuKo/edit#gid=0).
- Create R Markdown documents from them automatically maybe using Github Actions.
- Publish R Markdown documents automatically into a new website.

# Some resources that will help:
- [Building an R Markdown website: How to get all your knitted .Rmd files onto a website really fast!](https://lisalendway.netlify.app/posts/2021-08-18-quicksite/?utm_source=pocket_mylist)
- [Tidy Web Scrapping](https://towardsdatascience.com/tidy-web-scraping-in-r-tutorial-and-resources-ac9f72b4fe47) -- is this better than rvest?
