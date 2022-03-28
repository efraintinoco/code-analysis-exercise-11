# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (actualAge){
  if (actualAge == 1){
    return {
      humanYears: actualAge,
      catYears: 15,
      dogYears: 15,
    }
  }

  if (actualAge == 2){
    return {
      humanYears: actualAge,
      catYears: 24,
      dogYears: 24,
    }
  }

  return {
    humanYears: actualAge,
    catYears: (actualAge - 2) * 4 + 24,
    dogYears: (actualAge - 2) * 5 + 24,
  }
}
```

| Input | Output    |
| ----- | --------- |
| 1     | { humanYears: 1, catYears: 15, dogYears: 15 } | 
| 2     | { humanYears: 2, catYears: 24, dogYears: 24 } | 
| 3     | { humanYears: 3, catYears: 28, dogYears: 29 } | 
| 4     | { humanYears: 4, catYears: 32, dogYears: 34 } |
<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function is taking the actual age of human years and converting it
        to the equivlent in cat and dog years. The function will return 15 years for both
        dogs and cats if the actual human year is 1 , and will return 24  for both cat and dog years if the actual human year is 2.
        after that , what ever number is given for actual age it will return the actual age 
        for human years and run an Expression  for both dogs and cats respectively, to 
        determine the equivalent in dog and cat years.  
</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
