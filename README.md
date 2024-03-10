# News-Wave-Web-API

- Headlines: Clear and concise summaries of the most important stories.
- Quotes: Direct statements from relevant individuals involved in the story.
- Facts vs. Opinions: Distinguishing between factual reporting and editorial/opinion pieces.
- Multimedia Elements: Incorporating images, videos, infographics, and interactive elements to enhance understanding.

# API-Key

- Moving to actual implementation we store the API key in the file ‘api-key.js’.
- Then create the function ‘getNews’ to make a request to the API and get a response with all news articles or an error.
- In case of an error we display a message and stop code execution else we call the function ‘generateUI’. 
- In the ‘generateUI’ function we create a card for each article and append it to our container to display all the news articles.
