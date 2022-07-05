# transcend
Imagine an open-source oscar-winning production...

The box office, triple platinum, and masterpiece of the future will be built by an open source hive mind. It will be bidirectional, iterative, generative, evolutionary and transcendent.

Great products are built by teams of dedicated people when multiple engineers find that hyper-generative frequency. Great artistic productions are no different.

Engineering = Art

Github = Art Version Control

# tldr
iF YOUR house doesn't look like this please leave![Google Chrome Screenshot on 07-03-2022 at 12 55PM](https://user-images.githubusercontent.com/24831146/177055329-1fc0dbf0-454e-4b7e-a85c-5189168184ab.png)

# Random Thinking
Evolution of multimedia goes from text to sound to image and then it's combined magically into movies/musical theater

Seems wise to start with music and as momentum builds incorporate more mediums meaningfully. Art is art, maximum generation is good though constraints need to be built such that energy isn't spread to thin. Can this be defined productively?

# Why GitHub
GitHub is where the worlds most influential products are built, soon it will be where the worlds most powerful productions are created. Imagine if creative people across the world could contribute piecemeal to an academy award caliber production. Open source has had some mind-boggling effects on the information sphere and the creative space is next. Aligning creative visions is a major challenge and the iteration process for creativity is particularly challenging. Using a version control system like git in combination with performing art is unconventional but could unlock a lot.

# ArtOps

DevOps and CI/CD really helps streamline the engineering process, imagine the same type of tooling and chained looping processes applied to the creative process. Automated A/B testing of lyrics run on music and computer vision algorithms trained to pre-identify which footage is likely to perform better that is then improved with real-world data based on deep analytics. The marginal return of some engineering to art could be tremendously high. GitHub actions is a great place to start with this, one idea of a small automation could be a GPT-3 fine tuned model that classifies which of two verses it thinks is better.

For example:
```
curl https://api.openai.com/v1/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -d '{
  "model": "text-davinci-002",
  "prompt": "Predict whether verse 1 or verse 2 is likely to perform better:\n\nVerse 1:\nToday is gonna be the day that they're gonna throw it back to you\nAnd by now, you should've somehow realised what you gotta do\nI don't believe that anybody feels the way I do about you now\n\nVerse 2:\nToday was gonna be the day, but they'll never throw it back to you\nAnd by now, you should've somehow realised what you're not to do\nI don't believe that anybody feels the way I do about you now\n\nThe verse that will perform better is:",
  "temperature": 0,
  "max_tokens": 2048,
  "top_p": 1,
  "frequency_penalty": 0,
  "presence_penalty": 0
}'
```

## DALL-E Generated Album Covers
Given some lyrics from a song an album/single cover can be generated such that music can be released with minimal investment in accessory artwork until it’s proven to have some traction after which the art may be revised.

For example, the following lyrics from wonderwall generated these potential covers:
> And backbeat, the word is on the street that the fire in your heart is out
> I'm sure you've heard it all before, but you never really had a doubt
> I don't believe that anybody feels the way I do about you now
![Marwan_And_backbeat_the_word_is_on_the_street_that_the_fire_in__bc685f53-9019-484c-9170-901ee0f7ae6e-1](https://user-images.githubusercontent.com/24831146/177431714-88ea3cb1-fe88-4695-acf5-abf79dd2a47d.png)

