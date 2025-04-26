# Program 4: Benchmarking Heaps

- [X] A brief introduction to the assignment, including a description of the experiments being performed.
- [X] A description of your planned approach to benchmarking and predictions for the results. You should benchmark using three datasets:
  - [X] increasing sorted array
  - [X] decreasing reverse sorted
  - [X] random shuffled
- [X] For each approach to heapifying, predict which case will perform the best, and predict the asymptotic running time.
- [X] Source code for your heapification approachs, together with explanations of what each function does.
- [X] A brief narrative description of data used and the results from running the benchmarks. Make sure to have both sufficiently-large and sufficiently-many benchmarks.
- [X] A table and graph for each function, showing its results for each case.
- [X] A table and graph for each case, showing the results for each function
- [X] An analysis using the regression techniques from the second homework to estimate the asymptotic time complexity for each case.
- [ ] 1-2 paragraphs of text summarizing all interesting results.

Answers to the following:
* For each approach:
  - Does the empirically-determined runtime match the theoretic run time? *if not, what might have caused the discrepancy?
  - Was there a noticeable difference between sorted, reverse-sorted, and random data? *if so, describe the difference and explain why you think it exists
* What runtime effect do you get by using heapify vs. adding all elements to an empty heap? Explain!
* Compare bubbling down and stopping short to bubbling all the way down, then back up. When might each approach be better?
- [ ] An appendix containing all of your source code and test cases.
