# 100 Days Of Code - Log

### Day 0: January 14, 2017

**Today's Progress**: Worked on Show Local Weather on FreeCodeCamp. Chained Promises with [axios](https://github.com/mzabriskie/axios)

**Thoughts:** Started with separated request, but had difficulties on retrieving `lat` and `lon` from first request(for location) on second request(for weather based on current location). Figured out through chaining method. Struggled alot on the figuring part, indicates more in-depth understanding on the syntax is needed.

**Link to work:** [Show Local Weather](http://codepen.io/vizFlux/pen/pyzNmr)

### Day 1: January 15, 2017

**Today's Progress**: Worked on Show Local Weather on FreeCodeCamp. Failed in attempt of adding function to convert weather from metric to imperial.

**Thoughts:** Struggled hours to add conversion function on `this.setState` in `handleClick()`.
```JavaScript
handleClick() {
    this.setState(prevState => ({
      isMetric: !prevState.isMetric,
      unit: !prevState.unit,
      temp: () => {
        if (prevState.isMetric === true) {
          return {
            temp: prevState.temp * 9/5 + 32,
          }
        }
      }
    }));
```
Failed and will try to fix it by tomorrow again.

**Link to work:** [Show Local Weather](http://codepen.io/vizFlux/pen/pyzNmr)

### Day 3: January 16, 2017

**Today's Progress**: Skipped a day for work.

**Thoughts:** Caught up with work, needed to skip a day of code to cope with due date.

**Link to work:** [Show Local Weather](http://codepen.io/vizFlux/pen/pyzNmr)

### Day 4: January 17, 2017

**Today's Progress**: Setting up a new page on my personal gatsby-powered blog

**Thoughts:** Decided to add a new page on my personal blog [alvisng.me](http://alvisng.me/) to help sharing my #100DaysOfWork log with others.

**Link to work:** [alvisng.me](http://alvisng.me/)

### Day 5: January 18, 2017

**Today's Progress**: Added #100DaysOfCode log to my blog.

**Thoughts:** Decided to add a new page on my personal blog [alvisng.me](http://alvisng.me/) to help sharing my #100DaysOfWork log with others.

**Link to work:** [alvisng.me](http://alvisng.me/)

### Day 6: January 20, 2017

**Today's Progress**: Fulfilled all the User Stories of [FCC's Show The Local Weather](https://www.freecodecamp.com/challenges/show-the-local-weather).

**Thoughts:** Achieved better understanding on React's state, and learned to manipulate it to achieve user stories in a more efficient and understandable manner. Proceeding to make things more presentable in the next session.

**Link to work:** [FCC weather app](https://codepen.io/vizFlux/pen/pyzNmr)

### Day 7: January 21, 2017

**Today's Progress**: Skipped a day for work.

### Day 8: January 22, 2017

**Today's Progress**: Skipped a day for work.

### Day 9: January 23, 2017

**Today's Progress**: Redoing FreeCodeCamp from zero.

**Thoughts:** I've been inactive in FreeCodeCamp since June 2016, decided to redo the entire program from zero. This decision is made to approach the DONES with a better workaround, meanwhile to develop a stronger foundation in JS.

### Day 10: January 24, 2017

**Today's Progress**: Completed 12 challenges in "Basic Javascript"

**Thoughts:** I've been inactive in FreeCodeCamp since June 2016, decided to redo the entire program from zero. This decision is made to approach the DONES with a better workaround, meanwhile to develop a stronger foundation in JS.

**Link to workd:** [FCC Basic JS](https://www.freecodecamp.com/vizflux)

### Day 11: January 25, 2017

**Today's Progress**: Completed 12 challenges in "Basic JavaScript"

**Thoughts:** Revised on `.push()`, `.pop()`, `.shift()`, `.unshift()`. Programming is like workout, you need to practice it regularly to reach beyond what you were capable of yesterday.

**Link to workd:** [FCC Basic JS](https://www.freecodecamp.com/vizflux)

### Day 12: January 26, 2017

**Today's Progress**: Skipped for festive preparation.

### Day 13: January 27, 2017

**Today's Progress**: Completed 11 challenges in "Basic Javascript"

**Thoughts:** [Stand In Line](http://bit.ly/2jkrVse), challenged by this particular task, but managed to solve it by going back to basic. It's solved by `.push()` and `.shift()`.

**Link to workd:** [FCC Basic JS](https://www.freecodecamp.com/vizflux)

### Day 14: March 21, 2017

**Today's Progress**: Completed 8 challenges in Basic Javascript

### Day 15: March 22, 2017

**Today's Progress**: Completed 3 challenges in Basic Javascript

### Day 16: March 27, 2017

**Today's Progress**: Completed 6 challenges in Basic Javascript

### Day 17: March 30, 2017

**Today's Progress**: Completed 16 challenges in Basic Javascript

### Day 18: April 02, 2017

**Today's Progress**: Completed 6 challenges in Basic Javascript

### Day 19: April 03, 2017

**Today's Progress**: Completed 1 challenges in Basic Javascript

### Day 20: April 04, 2017

**Today's Progress**: Completed 2 challenges in Basic Javascript
