# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL
AviationAPI
> https://pokeapi.co/api/v2/

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API All the Pokémon data you'll ever need in one place,
easily accessible through a modern RESTful API.

- What is the URL of the documentation?

> https://pokeapi.co/docs/v2/

- What is the full URL of one endpoint?

> https://pokeapi.co/api/v2/berry/1/

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "firmness": {
        "name": "soft",
        "url": "https://pokeapi.co/api/v2/berry-firmness/2/"
    },
    "flavors": [
        {
            "flavor": {
                "name": "spicy",
                "url": "https://pokeapi.co/api/v2/berry-flavor/1/"
            },
            "potency": 10
        },
        {
            "flavor": {
                "name": "dry",
                "url": "https://pokeapi.co/api/v2/berry-flavor/2/"
            },
            "potency": 0
        },
        {
            "flavor": {
                "name": "sweet",
                "url": "https://pokeapi.co/api/v2/berry-flavor/3/"
            },
            "potency": 0
        },
        {
            "flavor": {
                "name": "bitter",
                "url": "https://pokeapi.co/api/v2/berry-flavor/4/"
            },
            "potency": 0
        },
        {
            "flavor": {
                "name": "sour",
                "url": "https://pokeapi.co/api/v2/berry-flavor/5/"
            },
            "potency": 0
        }
    ],
    "growth_time": 3,
    "id": 1,
    "item": {
        "name": "cheri-berry",
        "url": "https://pokeapi.co/api/v2/item/126/"
    },
    "max_harvest": 5,
    "name": "cheri",
    "natural_gift_power": 60,
    "natural_gift_type": {
        "name": "fire",
        "url": "https://pokeapi.co/api/v2/type/10/"
    },
    "size": 20,
    "smoothness": 25,
    "soil_dryness": 15
}


```

- What status code did you get back?

> 200 ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`application/json; charset=utf-8

> `Content-Length`

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ...many different attributes the pokimon universe has within its characters.

- How could you use this data in an application?

> I could imagine integrating this API into an app that ... stores data or a video game

- What did you like about the documentation?

> The documentation was ... interesting because of the information about the pokimon universe was easliy assessable 

- What did you find challenging about the documentation?

> I found the documentation ...just understanding how the pathways towards the data are layered.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...yes there were other API sites I grew fond of the tittle but did  not accuatually work.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...switching

- In your own words, summarize the request-response cycle.

> The request-response cycle ...in which user decives send out signals to servers, servers return signals to said device which happens when a page is refreshed.

- In your own words, describe what an API is.

> An API is ...rules for building and intergrating apps

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
