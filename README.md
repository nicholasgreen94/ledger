# Ledger
### 🎬 🎥
_Implementing native array methods from scratch_

## Setup/Usage
Going through this setup will give you a preview of what it is like to work on a group projects.

1. Fork and clone repo
  - **Fork:** forking the repo will allow you to have a personal copy of the repo in which you can push your code and not disrupt the original codebase.
2. Open the `index.html` file in the root folder on your favorite browser.
  - The index page will show you the multiple tests you need to pass for each method.
3. The `src` folder will contain the files you will be working on.
4. As you start implementing your methods refresh the index page and you will start to see your tests pass (or fail _-be careful_).
5. Once you make progress make sure to commit and push your changes to your repo so your code is saved and you can show it off in the future.

As you work through your code always remember these important 3 questions when debugging:

>  - What do I expect this code to do?
>  - What is my code doing instead?
>  - What may be causing the disconnect?

When using `console.log` adding a string with labeling as the first argument will help out figuring out where in your codebase you are:

``` js
const dessert = [
  {
    name: 'Pumpkin Pie',
    holiday: 'Thanksgiving'
  },
  {
    name: 'Gingerbread',
    holiday: 'Christmas'
  },
  {
    name: 'Buche de Noel',
    holiday: 'Christmas'
  }
]

const christmasGoodies = dessert.filter(dessert => dessert.holiday === 'Christmas')

console.log('XMAS YUM YUM', christmasGoodies)
// There will automatically be a space added between
// 'XMAS YUM YUM' and whatever christmasGoodies represents
```
