# Tumblr 4Chan Bot
When trolls engage in public discourse with the expressed goal of making the world worse, democracy loses. The goal of this bot is simple, create a Tumblr bot that finds things that came from 4chan, a popular hangout site for these trolls, and reblog them with their source on 4chan, keeping the public informed.

# News
Trying to pick a language
[Python](https://github.com/tumblr/pytumblr)
[Ruby](https://vaporsoft.net/creating-a-tumblr-bot-from-scratch/)
[C#](https://vaporsoft.net/creating-a-tumblr-bot-with-c/)
Even though Python doesn't have a clear tutorial like Ruby or C#, Python has libraries for Machine Learning algorithms, meaning, room for growth.

The basic gist is that we'll need to use Tumblr's API to get Tumblr posts, take the images and text in those posts and run them through [Google's Search API](https://developers.google.com/custom-search/json-api/v1/overview), and search 4Chan for the images and text, then use whatever URLs are generated to make a Tumblr post. We'll probably want to make restrictions for the bot, for example, we probably don't care about when 4chan people pirate Tumblr stuff (though adding that as a feature might make artists happy?), so the date of the Tumblr post should probably be after the date of the 4chan post. Also, we'll need our program to be very secure and robust for obvious reason. If it's successful, it will be a great program for improving our skills as programmers! 
