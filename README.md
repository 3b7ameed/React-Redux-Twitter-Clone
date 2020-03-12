# Twitter Clone Using React + Redux

A Twitter clone where users can post tweets and like & replay to other tweets!

## Project Setup

- install the dependencies - `npm install`
- Run the app - `npm start`

## Backend

I used "json-server" npm backage to mimic a backend for the app but ofcourse feel free to use a real backend , what matters is offering same endpoints.

App is currently listening for

- http://localhost:4000/users
- http://localhost:4000/tweets

in this format :
Users is an Array of objects where each object looks like this :

```
  {
      "id": "abdelhameedgamal",
      "name": "Abdelhameed Gamal",
      "avatarURL": "http://pics.com/abdelhameed.jpg",
      "tweets": [
        "8xf0y6ziyjabvozxxx3nd",
        "hbsc73kzqi75rg7xxxx0i6a",
        "2mb6re13q842wu8xxx6bhk",
        "6h5ims9iks66d4mxxxizmv"
      ]
    }
```

and tweets is and array of objects where each object looks like this :

```
{
      "text": "بسم الله الرحمن الرحيم",
      "author": "abdelhameedgamal",
      "timestamp": 1584037885585,
      "likes": [],
      "replies": [],
      "replyingTo": null,
      "id": "cAGS1_6"
    }
```
