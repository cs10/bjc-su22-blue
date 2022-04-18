---
layout: default
title: Lab Check-Off Questions
description: A list of all labs and associated check-off questions.
nav_order: 3
lab_course: cs10_fa21.html
labs:
  - lab_name: Welcome to Snap!
    lab_no: 1
    topic_file: berkeley_bjc/intro_pair/1-introduction.topic
    questions:
      - No checkoff needed for Lab 1!
  - lab_name: Build Your Own Blocks
    lab_no: 2
    topic_file: berkeley_bjc/intro_pair/2-loops-variables.topic
    questions:
      - Show your Field of Flowers.
      - Why should you Build Your Own Blocks? Give a reason that someone may create a custom block.
      - What are some different ways to achieve repetition? Name at least 2.
      - Show your random-walk sprite.
      - Show your "draw square-leaved flower..." block.
  - lab_name: Conditionals, Reporters & Testing
    lab_no: 3
    topic_file: berkeley_bjc/intro_pair/2-conditionals-testing-su21.topic
    questions:
      - What is a Boolean? Explain why we use them, and give examples of functions that report a Boolean value.
      - Show us your traffic signal and letter grade blocks.
      - Explain the difference between a command and a reporter block.
      - Show us the `is _ between _ and _ ?` block.
      - What does the mystery reporter (at the bottom of the “Reporter Blocks” page) report when run with the inputs hello and 5?
      - Name a few of the input types. Why is it important that we specify input types?
      - How are global variables different from script variables?
      - Show and explain your sum of two smallest block.
  - lab_name: Lists and HOFs
    lab_no: 4
    topic_file: berkeley_bjc/lists/lists-I.topic
    questions:
      - What is a list? Why would we use a list of 10 elements instead of just making 10 variables?
      - What do `map`, `keep`, and `combine` each do?
      - Show us your `acronym` block.
      - Show us your `expand` block.
      - What is the difference between the `for each (item)` loop and the `for (i)` loop we have used in previous labs?
  - lab_name: Algorithms
    lab_no: 5
    topic_file: berkeley_bjc/areas/algorithms.topic
    questions:
      - What is an algorithm? Please give an example both in real life and from class.
      - Please show both your "findNumberInUnsortedList" and "findNumberInSortedList" functions and describe the difference in the algorithms used.
      - Are algorithms which are (on average) faster always "better"? Why or why not?
      - What might some "trade-offs" to different computer science algorithms be?
      - How can abstraction and algorithms relate in computer science?
  - lab_name: Algorithmic Complexity
    lab_no: 6
    topic_file: berkeley_bjc/areas/algorithm-complexity.topic
    questions:
      - Please show me your Non-Gauss and Gauss Add all numbers in. Which was faster? Why?
      - Of all the runtimes you have discovered thus far, can you rank them from “fastest” to “slowest”? Why is runtime important for the programs that we create?
      - Name the logarithmic time algorithm that we implemented in Lab 5. Explain why this algorithm runs in logarithmic time.
      - What is the difference between “Worst-Case” and “Best Case” Runtimes when running the Are the numbers of (LIST) distinct block? Why?
      - What happened with the time it took for your computer to counter up the numbers between 1 and x when you started doubling the numbers? Tripling the numbers? What do you think would happen with the time I multiplied your top number by 8?
      - What is an example of an algorithm that we have seen that has an exponential runtime?
  - lab_name: Testing + Project 1
    lab_no: 7
    topic_file: berkeley_bjc/2048-testing/2048.topic
    questions:
      - How does the test block work? What is its domain and range?
      - Show us the output of your test block on the merge column. Explain why this output makes sense.
      - How will writing tests help you for the 2048 assignment?
      - How do merge up and merge column work? What is the domain/range of each block?
      - What is the domain and range of the update display block?
  - lab_name: Boards (Optional)
    lab_no: 8
    topic_file: berkeley_bjc/lists/tic-tac-toe.topic
    questions:
      - Why did we have variables like “Size”, “Start”, and “Display Width” when designing our board and what do they do?
      - Show your working board game by moving the sprite around the board.
      - Explain an advantage of using an underlying board structure when designing a game.
  - lab_name: Trees and Fractals
    lab_no: 9
    topic_file: berkeley_bjc/recur/recursion-trees-fractals.topic
    questions:
      - Why is it important that the inputs to a recursive call be smaller than the original inputs to the function?
      - Please show me your “crazy-tree” block.
      - Why is it important that the sprite face the same direction at the end of a recursive function as it faced initially?
      - What defines a recursive block? What are the two necessary “cases” that a recursive block must consider? Name and define them.
      - Please show me your “snowflake” block.
  - lab_name: Recursive Reporters
    lab_no: 10
    topic_file: berkeley_bjc/recur/recursive-reporters-part1.topic
    questions:
      - Why do we map the first item of the set in front of a recursive call of subsets over the rest of the list?
      - Explain why the second version of subsets only makes 7 calls instead of 64.
      - Explain how the sort block works, how the merge block works, and how they work together.
      - Show us the recursive numbers block.
      - Show us the recursive ends-e block.
  - lab_name: HOFS and Functions as Data
    lab_no: 11
    topic_file: berkeley_bjc/hofs/hofs-practice.topic
    questions:
    - What is a higher-order function?
    - Show us your pandigital block and explain how it works.
    - Show us your factorion block and explain how it works.
    - Show us your list all factorions function. How does this compare to the list all pandigital numbers function?
  - lab_name: Welcome to Python
    lab_no: 12
    topic_file: berkeley_bjc/python/besides-blocks-welcome-parsons.topic
    questions:
    - What is the difference between the "python", "python file.py", and "python -i file.py" terminal commands?
    - What is the difference between the "print" and "return" python commands?
    - Show your "reverse_string(string)" function. If you did it iteratively, explain the recursive solution. If you did it recursively, explain the iterative solution.
    - Show your "palindrome(string)" function.
    - Show your c-curve function and its output.
  - lab_name: Data Structures in Python
    lab_no: 13
    topic_file: berkeley_bjc/python/besides-blocks-data-struct.topic
    questions:
    - What is the difference between = and == in python?
    - Show us the result of running the autograder.
    - What is a dictionary?
    - What does 0-indexing mean?
  - lab_name: Object-Oriented Programming
    lab_no: 14
    topic_file: berkeley_bjc/python/besides-blocks-oop-joshhug-edition.topic
    questions:
    - Describe the purpose of an "init" function.
    - To access a class attribute, should you use the class name or an instance name?
    - Name two different ways to assign instance attributes.
    - Show us your "outdated" and "add_genre" methods.
    - Show us your completed MemePage and Member classes.
  - lab_name: Text Processing in Python
    lab_no: 15
    topic_file: berkeley_bjc/python/besides-blocks-text-processing.topic
    questions: 
    - What are the arguments of the "open" function and what does it return?
    - Show us your "izzle" function.
    - How do we choose how something is sorted when using the "sorted" function in Python?
    - Show us your "top_n_words" and "print_top_n_words" functions.
    - Show us your "apply_language_game" function.
  - lab_name: Data Science
    lab_no: 16
    topic_file: berkeley_bjc/python/data-lab.topic
    questions:
    - What are some important commands that you can use to keep only certain rows in a table?
    - Describe the three main steps of working with data as per this lab.
    - What commands did you use to find the price of the most expensive listing in San Francisco?
    - Show us your scatter plot.What are some things you notice from this plot?
  - lab_name: Concurrency
    lab_no: 17
    topic_file: berkeley_bjc/areas/concurrency.topic
    questions:
    - What is a race condition?
    - Is it always true that splitting a task among 10 “workers” is better than splitting it among 5 “workers”?
    - What is the difference between determinism and nondeterminism, in the context of concurrency?
    - How does Snap! handle concurrency?
---

# Lab Check-Offs

On this page, you will find a list of check-off questions for each lab.

{% for lab in page.labs %}
<details open>
  <a name="lab-{{ lab.lab_no }}"></a>
  <summary>
    <div class="label label-lab"><strong>Lab {{ lab.lab_no }}</strong></div>
    {{ lab.lab_name }}
  </summary>
  <br>
  <a href="https://cs10.org/bjc-r/topic/topic.html?topic={{ lab.topic_file |urlencode }}&course={{ page.course }}&novideo&noreading&noassignment" target="_bank">
  View Lab {{ lab.lab_no }}
  </a>
  <ul>
    {% for question in lab.questions %}
      <li>{{ question | markdownify}}</li>
    {% endfor %}
  </ul>
</details>
{% endfor %}

<!-- 
**Lab 12**{: .label .label-lab }[Welcome to Python!](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/besides-blocks-welcome-parsons.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- What is the difference between the "python", "python file.py", and "python -i file.py" terminal commands?
- What is the difference between the "print" and "return" python commands?
- Show your "reverse_string(string)" function. If you did it iteratively, explain the recursive solution. If you did it recursively, explain the iterative solution.
- Show your "palindrome(string)" function.
- Show your c-curve function and its output.

**Lab 13**{: .label .label-lab }[Data Structures in Python](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/besides-blocks-data-struct.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- What is the difference between = and == in python?
- Show us the result of running the autograder.
- What is a dictionary?
- What does 0-indexing mean?

**Lab 14**{: .label .label-lab }[Object-Oriented Programming](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/besides-blocks-oop-joshhug-edition.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- Describe the purpose of an "init" function.
- To access a class attribute, should you use the class name or an instance name?
- Name two different ways to assign instance attributes.
- Show us your "outdated" and "add_genre" methods.
- Show us your completed MemePage and Member classes.

**Lab 15**{: .label .label-lab }[Text Processing in Python](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/besides-blocks-text-processing.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- What are the arguments of the "open" function and what does it return?
- Show us your "izzle" function.
- How do we choose how something is sorted when using the "sorted" function in Python?
- Show us your "top_n_words" and "print_top_n_words" functions.
- Show us your "apply_language_game" function.

**Lab 16**{: .label .label-lab }[Data Science](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/data-lab.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- What are some important commands that you can use to keep only certain rows in a table?
- Describe the three main steps of working with data as per this lab.
- What commands did you use to find the price of the most expensive listing in San Francisco?
- Show us your scatter plot.What are some things you notice from this plot?

**Lab 17**{: .label .label-lab }[Concurrency](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/areas/concurrency.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- What is a race condition?
- Is it always true that splitting a task among 10 “workers” is better than splitting it among 5 “workers”?
- What is the difference between determinism and nondeterminism, in the context of concurrency?
- How does Snap! handle concurrency?

**Lab 18**{: .label .label-lab }[Debugging in OOP](https://beautyjoy.github.io/bjc-r/topic/topic.html?topic=berkeley_bjc/python/oop-debugging.topic&course=cs10_fa21.html&novideo&noreading&noassignment)
- Show us the result of running the docstring under the Account class in your terminal.
- Show us the result of running the docstring under each QuidditchPlayer subclass in your terminal.
- What is some information the terminal gives you when there's an error in your code? -->
