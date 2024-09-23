# obr-challenge
This is yet another version of the One Billion Row Challenge (https://www.morling.dev/blog/one-billion-row-challenge/)
  
The only differences are that: 
1) The output file uses newlines instead of commas and doesnt have the braces - like this:
```Abha=-8.1/17.8/43.5
Abidjan=-1.3/25.1/58.5
Abéché=7.1/29.0/50.9
Accra=-6.6/25.4/52.8
Addis Ababa=-18.6/15.7/41.9
Adelaide=-8.6/17.0/46.0
```
2) None of the IEEE 754 rounding shenanigans - its irrelevant to the main challenge. 

The sample data from https://github.com/gunnarmorling/1brc/tree/main/src/test/resources/samples is included with suitable changes, and the rounding based ones removed.

Submit your solution as a PR

Each language will have a folder for serial and parallel implementations e.g cpp, cpp-parallel. Benchmarking will be done on my machine or maybe on some cloud machine and leaderboards will be updated once in a while

TODO: Add more instructions for testing/verifying/timing
