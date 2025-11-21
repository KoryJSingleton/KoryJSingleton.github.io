[Back to Portfolio](./)

Sort Time Analyzer
===============

-   **Class: CSCI 315** 
-   **Grade: 100** 
-   **Language(s): CPP** 
-   **Source Code Repository:** [My repository](https://github.com/KoryJSingleton/Sort-Time-Analyzer)  
    (Please [email me](mailto:example@KorySingleton35@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

In this program, I seek to compile and display sort times from 3 different sorting algorithmns selectionSort and bubbleSort for arrays, as well as BubbleSort for a Singly-Linked List data structure). To do so, the program, upon startup, constructs a number of arrays and singly-linked lists with random inputs. It then begins to sort them, charting the amount of time needed for each sort to be completed being piped into a .csv file. This file is then used to generate a pdf like the one in the image, allowing viewers to track how exactly what the difference is for the timings of the sort as the size of the data structures increases.

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
make data
make plot data
```

If the programming language does not require compilation, the update the heading to be “How to run the program.” If your application is deployed on a remote service, including instructions on how to deploy it.

## UI Design

There is very little user input. All that the user is required to do is cd into the correct directory and then run the program  using the appropriate make commands. The make file will handle the running of the program from there. 

![screenshot](images/graph.png)  
Fig 1. Example sort output graphed

![screenshot](images/image1.png)  
Fig 2. Example output of main that is piped into csv file

![screenshot](images/image2.png)  
Fig 3. Displays algorithm that is used within main to generate timings

## 3. Additional Considerations

Creation of graphs is not currently possible without use of the make commands, thus on new occurances of the prorgam, it requires that the make commands be reinput on every subsequent run.

[Back to Portfolio](./)
