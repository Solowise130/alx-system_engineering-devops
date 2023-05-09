API ADVANCED

Background Context

Questions involving APIs are common for interviews. Sometimes they’re as simple as ‘write a Python script that queries a given endpoint’, sometimes they require you to use recursive functions and format/sort the results.

A great API to use for some practice is the Reddit API. There’s a lot of endpoints available, many that don’t require any form of authentication, and there’s tons of information to be parsed out and presented. Getting comfortable with API calls now can save you some face during technical interviews and even outside of the job market, you might find personal use cases to make your life a little bit easier.

RESOURCES

* Reddit API Documentation

* Query String.

LEARNING OBJECTIVES

-How to read API documentation to find the endpoints you’re looking for.

-How to use an API with pagination.

-How to parse JSON results from an API.

-How to make a recursive API call.

-How to sort a dictionary by value.

FILES AND EXPECTED OUTPUTS

0-subs.py - Writes a function that queries the Reddit API and returns the number of subscribers (not active users, total subscribers) for a given subreddit. If an invalid subreddit is given, the function should return 0.

Hint: No authentication is necessary for most features of the Reddit API. If you’re getting errors related to Too Many Requests, ensure you’re setting a custom User-Agent.

1-top_ten.py - Writes a function that queries the Reddit API and prints the titles of the first 10 hot posts listed for a given subreddit.

2-recurse.py - Writes a recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit. If no results are found for the given subreddit, the function should return None.

Hint: The Reddit API uses pagination for separating pages of responses.

100-count.py - Writes a recursive function that queries the Reddit API, parses the title of all hot articles, and prints a sorted count of given keywords (case-insensitive, delimited by spaces. Javascript should count as javascript, but java should not).
