# HortaTech Fullstack Challenge

Welcome to HortaTech coding challenge! We are currently looking for a junior rails fullstack developer and/or a junior front-end developer to join our team. Jump to the challenge of your choice.

### Word Recurrency

#### Back-end ->

Develop a simple API, that receives a text and returns a JSON with the number count of each word in the text.

[Bonus - Optional] The API must receive a token as a parameter and it will also return the number of API requests made with that token. There should be a limit of 10 API requests for the same token, after which the API returns an error message of your choice.

#### Front-end ->

Simple dashboard, where its possible to see all records of API requests ever made, and a page with all the details of each record.
( #INDEX, #SHOW )

[Bonus - Optional] Page to submit a text to the API and visualize the return. You form must use a javascript request to the API and render the response without reloading.

[Boss -> The floor is lava - Very Very Optional] [There will be cake] Search input where you can type a word and get all the texts submitted with that word, from the most recurrencies to the least.

#### Technologies

In this challenge you should use the following technologies:
* Ruby on Rails
* Relational Database
* HTML5
* CSS3 or SCSS
* Javascript / React (Optional)

#### Code API payload sample (Token optional)

```JSON
{
  'payload': 'the cake is a lie, the cake is a, the cake is, the cake, the',
  'token': 'a06de92c41655fe2'
}
```

#### Code API return example (Token optional)

```JSON
{
  'words': {
    'the': 5,
    'cake': 4,
    'is': 3,
    'a': 2,
    'lie': 1
    },
  'token': 'a06de92c41655fe2',
  'token_uses': 8
}
```

## User Stories [Mandatory]

* As a visitor, I want to visualize all the API call records, so i can keep track of it's usage.
* As a visitor, I want to access the page of each record, so i can see all its details, including the text sent and word count.
* As a 'machine', I want to send a text to the API and receive it's word count.

### What we expect
* Clean and well-organized code (DRY, manageable, maintanable)
* Good front-end practices

### What we DON'T expect
* Don't implement authorization or authentication
* Don't spend too much time on this challenge
* Don't worry about browser compatibility. We will use modern browsers
* Don't worry about creating the most beautiful design. Your components and code


### How to deliver

* Create a repository with your solution on Github
* The instructions must be clear and the solution must be ready to run
* Deploy your code using heroku (Optional)
