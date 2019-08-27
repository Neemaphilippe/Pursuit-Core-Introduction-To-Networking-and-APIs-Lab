# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
1. 301
1. 400
1. 401
1. 403
1. 404
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
``` https://catfact.ninja/facts

"data": [
{
"fact": "Cats, just like people, are subject to asthma. Dust, smoke, and other forms of air pullution in your cat's environment can be troublesome sources of irritation.",
"length": 160
}
]
```
1. A list of 150 random users in English.
```
https://api.github.com/users
{
"login": "bmizerany",
"id": 46,
"node_id": "MDQ6VXNlcjQ2",
"avatar_url": "https://avatars2.githubusercontent.com/u/46?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/bmizerany",
"html_url": "https://github.com/bmizerany",
"followers_url": "https://api.github.com/users/bmizerany/followers",
"following_url": "https://api.github.com/users/bmizerany/following{/other_user}",
"gists_url": "https://api.github.com/users/bmizerany/gists{/gist_id}",
"starred_url": "https://api.github.com/users/bmizerany/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/bmizerany/subscriptions",
"organizations_url": "https://api.github.com/users/bmizerany/orgs",
"repos_url": "https://api.github.com/users/bmizerany/repos",
"events_url": "https://api.github.com/users/bmizerany/events{/privacy}",
"received_events_url": "https://api.github.com/users/bmizerany/received_events",
"type": "User",
"site_admin": false
}
```
1. The current stock price of Microsoft. (IEX API)
```

```
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name
1. A list of all Pokemon
```
https://pokeapi.co/api/v2/pokemon

{
"count": 964,
"next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
"previous": null,
"results": [
{
"name": "bulbasaur",
"url": "https://pokeapi.co/api/v2/pokemon/1/"
},
{
"name": "ivysaur",
"url": "https://pokeapi.co/api/v2/pokemon/2/"
},
{
"name": "venusaur",
"url": "https://pokeapi.co/api/v2/pokemon/3/"
},
{
"name": "charmander",
"url": "https://pokeapi.co/api/v2/pokemon/4/"
},
{
"name": "charmeleon",
"url": "https://pokeapi.co/api/v2/pokemon/5/"
},
{
"name": "charizard",
"url": "https://pokeapi.co/api/v2/pokemon/6/"
},
{
"name": "squirtle",
"url": "https://pokeapi.co/api/v2/pokemon/7/"
},
{
"name": "wartortle",
"url": "https://pokeapi.co/api/v2/pokemon/8/"
},
{
"name": "blastoise",
"url": "https://pokeapi.co/api/v2/pokemon/9/"
},
{
"name": "caterpie",
"url": "https://pokeapi.co/api/v2/pokemon/10/"
},
{
"name": "metapod",
"url": "https://pokeapi.co/api/v2/pokemon/11/"
},
{
"name": "butterfree",
"url": "https://pokeapi.co/api/v2/pokemon/12/"
},
{
"name": "weedle",
"url": "https://pokeapi.co/api/v2/pokemon/13/"
},
{
"name": "kakuna",
"url": "https://pokeapi.co/api/v2/pokemon/14/"
},
{
"name": "beedrill",
"url": "https://pokeapi.co/api/v2/pokemon/15/"
},
{
"name": "pidgey",
"url": "https://pokeapi.co/api/v2/pokemon/16/"
},
{
"name": "pidgeotto",
"url": "https://pokeapi.co/api/v2/pokemon/17/"
},
{
"name": "pidgeot",
"url": "https://pokeapi.co/api/v2/pokemon/18/"
},
{
"name": "rattata",
"url": "https://pokeapi.co/api/v2/pokemon/19/"
},
{
"name": "raticate",
"url": "https://pokeapi.co/api/v2/pokemon/20/"
}
]
}
```
1. A list of all items in Fortnite
```
https://fortnite-api.theapinetwork.com/store/get

{
"success": false,
"error": "Please add your Authorization token.",
"eCode": "authorization.empty",
"_console": "https://console.fortniteapi.com"
}
```
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
