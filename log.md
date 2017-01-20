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
