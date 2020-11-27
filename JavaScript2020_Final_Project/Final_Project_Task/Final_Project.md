# JavaScript final work

Create JS quizz game:

- Choose two languages:

### 1. database

Create 3 arrays of JSON items(3 categories of words. for example: Food, Street, People).
Each database will have at least 10 items.
Each item will include:

- id - must be unique
- word
- options - at least three. (array format)
- image
- right answer (one from the options)

for example (english-russian quizz):

```js
{
  ID:1,
  word:'City',
  options:['город','ответ','название'],
  img:'https://backiee.com/static/wpdb/wallpapers/1000x563/202222.jpg',
  rightAnswer:'город'
}
```

### 2. Game-flow:

1. homepage: will have a button - **Start the quizz**. When user clicks the button - it redirects to the game page.
2. choose category : the user can choose category to play.
3. each round the items's data will be presented. (word, image). options will be buttons.
4. if user clicks the wrong answer - message : "wrong answer, please try again" will be presented.
5. if user clickes the right answer - message of success with the answer will show up, and move to the next question.
6. two buttons of **next** and **previous** will change questions correspondingly.

### 3. Score:

- for each right answer in the first try - add 1 point to the final score.
- for each wrong answer - remove 0.5 points from the final score.

the final score will be shown on the screen the entire game.

### Design

- The entire game must be designed with CSS + Bootstrap.
- The structure of the program must be as follows:
  - homepage (html)
  - game (html)
  - one file of css to all the files (css)
  - js - database + functionality. (can be in two separated files)
  - images: can be from the internet(as url), or local. (if local - must be in folder: IMG)

### Bonus

1. add more categories of words.
2. add voice to hear the words.
