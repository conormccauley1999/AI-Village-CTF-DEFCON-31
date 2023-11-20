# AI Village CTF - DEFCON 31

This repository contains my solution notebooks for the 24 problems that I solved during the [AI Village Capture the Flag @ DEFCON31](https://www.kaggle.com/competitions/ai-village-capture-the-flag-defcon31/overview) competition on Kaggle. I finished in 6th place and my full write-up can be found [here](https://www.kaggle.com/competitions/ai-village-capture-the-flag-defcon31/discussion/454471).

The `submission.ipynb` notebook submits hard coded solutions for the 24 solved problems and saves the returned flags to a CSV file. Code to generate a number of these hard coded solutions can be found in the various directories within this repository.

Brief outlines of all of the solutions are provided below but additional details can be found in the aforementioned write-up:

| Problem | Solution |
| --- | --- |
| 1. Test | Toy problem. |
| 2. Cluster - Level 1 | Find entries incorrectly predicted as high-income, select tech-support and run hill climbing algorithm. |
| 3. Cluster - Level 2 | Brute force. |
| 4. Cluster - Level 3 | TSNE to reduce dimensions then plot coordinates and overlay tokens. |
| 5. Count MNIST | Colour counts (first column is the colour). |
| 6. Count CIFAR | n/a |
| 7. Granny - Level 1 | Same as Granny 2. |
| 8. Granny - Level 2 | Black box genetic algorithm. |
| 9. Granny - Level 3 | n/a |
| 10. Passphrase | Hill climbing algorithm using local model (only use English words of the same length as original) - keep running even if score is very small until flag is received. |
| 11. Pixelated | Image with XML exploit as text, adjust spacing and size to circumvent problematic OCR. |
| 12. Spanglish | Manual guessing. |
| 13. Hush | n/a |
| 14. Pirate Flag | Manual guessing. |
| 15. Semantle | Manual guessing. |
| 16. Semantle - Level 2 | Submit 10k English words, manual trial and error with highest scoring words, brute force permutations of five best candidates. |
| 17. Inversion | Model inversion, mean probability for characters (accounting for outliers), some guesswork. |
| 18. What is the Flag - Level 1 | Manual guessing. |
| 19. What is the Flag - Level 2 | Manual guessing. |
| 20. What is the Flag - Level 3 | Manual guessing. |
| 21. What is the Flag - Level 4 | Manual guessing. |
| 22. What is the Flag - Level 5 | Manual guessing. |
| 23. What is the Flag - Level 6 | Manual guessing. |
| 24. Guess Who's Back? | Clip values between increasingly tighter ranges until flag is visible. |
| 25. Pickle | Used GPT4 to generate potential solutiosn. |
| 26. What's my IP? | Manual guessing. |
| 27. What's my IP - Level 2 | Manual guessing. |
