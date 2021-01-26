# JS_scraping_tutorials

Followed https://hackernoon.com/a-guide-to-web-scraping-with-javascript-and-nodejs-i21l3te1 tutorial 

to run and view the scraped details:

`npm install`
`node index.js`


first website scraped : https://www.forextradingbig.com/instaforex-broker-review

returns 87

second website scraped: https://www.reddit.com/r/scraping/?ref=hackernoon.com

returns
`
{
  redditPosts: [
    {
      postTitle: 'Is creating tutorials about web scraping a good idea?',
      postDescription: 'Hi guys!'
    },
    { postTitle: 'Scraping IMDB PRO?', postDescription: '' },
    {
      postTitle: 'Web scraping 101: The Ultimate Beginner’s Guide',
      postDescription: "Getting started with web scraping? We've got a guide prepared for you. How it works, is it legal, what are the best practices and other questions answered here: https://proxyway.com/guides/what-is-web-scraping"
    },
    {
      postTitle: 'Housing details scrape - returns blank dictionary',
      postDescription: "Hi, I'm relatively new to scraping, so any help would be very gratefully received."
    },
    {
      postTitle: 'Scraping Google Product Listing Ads',
      postDescription: 'Hi! Was wondering if anyone has had any success or seen any third party services that scrape Google Product Listing ads that show up on Google Search? They are the google shopping ads at the top of the page.'
    },
    {
      postTitle: 'Google Ads Scraping',
      postDescription: 'Hi! I am trying to scrape Google (image) ads. When I use my regular hope IP and a user agent, I am able to get the ads rendered but the second I use a residential proxy and the same headers, there are no ads.'
    },
    { postTitle: 'Medium Design', postDescription: '' }
  ]
}`
