# stock-analysis


## Overview:
### Steve wants to analyze stock performances to find a good investment opportunity for his parents. We had previously written a subroutine which returns the sum of the total daily traded volume of each particular stock, as well as the yearly return. This was accomplished using variables alone, so the challenge here was to refactor the code to make use of arrays instead in obtaining these values. The use of arrays would make the process of looping through the data more efficient, leading to a shorter runtime. While Steve is only concerned with 12 stocks in particular, the refactored code would allow him to more efficiently analyze a large number of stocks.

## Results:
### While the original code produces the same output as the refactored code, the runtime is close to a full second. Meanwhile, the refactored code has a runtime of approximately a tenth of a second. These images show the differences in code and the outputs:

## Original:

![screen1](https://user-images.githubusercontent.com/104467100/168975578-a33c19b4-e06f-45e9-b4c8-a3fc1ef43877.png)
![screen4](https://user-images.githubusercontent.com/104467100/168975711-d297b1e0-7e7d-41ec-b691-f0049319230d.png)

## Refactored:

![screen3](https://user-images.githubusercontent.com/104467100/168975773-b9001018-1e4d-4d35-97b4-2a87349a91f6.png)
![screen2](https://user-images.githubusercontent.com/104467100/168975783-3841e948-1fe9-41a9-a165-a9dad7f0da2d.png)

## Summary:
### Refactoring code can be advantageous in the sense that it can make a program more efficient in terms of runtime and processing. The code may also be easier to understand and more generally applicable to different situations. However, refactoring code takes time and there is the potential to generate new bugs and issues when attempting to refactor.

### The original code is somewhat simpler than the refactored version, however the refactored code has the clear advantage of being faster and more efficient. Due to the use of arrays, the refactored code only has to loop through the data once. Meanwhile, the original subroutine has to loop through the data individually for each distinct ticker in the dataset. While the code may appear simpler, this bloats the runtime considerably and would be far less efficient in the face of larger datasets. 
