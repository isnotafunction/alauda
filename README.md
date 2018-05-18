[![Build Status](https://travis-ci.org/fac-13/allauda.svg?branch=master)](https://travis-ci.org/fac-13/allauda)

# Alauda 
![Alauda logo](https://github.com/fac-13/allauda/blob/master/public/images/icons/icon-384x384.png)



### Problem statement
Our user needs a way to have access to positive and inspiring content in the morning so that they don't have to search it themselves. 

### Our solution
[Alauda](https://alauda.herokuapp.com/) is a Progressive Web App which, every day, present users with a selection of articles matching their interests, using the News API.

### From a music app to new(s) internet in a few pivots
The original idea was to build an alarm clock that is linked with the clock of one's mobile and plays different music or sounds every morning. We planned to make it a progressive web app. We then realised that PWA is not fit for purpose and changed the app idea.

### Screenshot

![Alauda screenshot](https://i.imgur.com/OmC6MKa.gifv)

### Who - our team

|   Name   |                                                          Github                                                                                                      |                                   Twitter                                    |
| :------: | :----------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
|  Giulia - **DevOps**   | [![Foo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/GiuliaTeggi) |
|  Ivi - **UX**  | [![Foo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/isnotafunction) | [![Foo](https://twitter.com/favicon.ico)](https://twitter.com/isnotafunction)|
|   Katia - **Scrum Master**  |   [![Foo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/missKatiaPunter)   |   [![Foo](https://twitter.com/favicon.ico)](https://twitter.com/4theLoveOfCode)  |                                                                              |
| Parissa - **QA** | [![Foo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/Parissai)  | [![Foo](https://twitter.com/favicon.ico)](https://twitter.com/Sottotitolato)  |

## HOW to run the app locally

* Fork the repo and navigate to your local folder where you would like to store its local copy
* Clone the repo
`git clone git@github.com:fac-13/allauda.git`
* Set up the API keys. This projects uses .env file where you should store YOUR News API key. You can [get the API key here](https://newsapi.org/).



## Tech stack
 

| Front end             | Backend              | Testing    | 
|:---------------------:|:--------------------:|:----------:|
| HTML5                 | Node.js              | Jest       | 
| CSS3 (BEM)            | Express              | Travis CI  | 
| Javascript            | Handlebars           |            |                    
|                       | MongoDB              |            |                    
