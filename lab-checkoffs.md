---
layout: default
title: Lab Milestones
description: A list of milestones for every lab
nav_order: 3
lab_course: cs10_fa21.html
labs:

---

# Lab Milestones

On this page, you will find a list of questions related to each lab. These questions highlight
what we think are the most important questions / takeaways from the lab and are meant for you to
check your understanding.


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

**Lab 1**{: .label .label-lab}[Introduction to Programming](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/1-building-an-app/1-creating-a-snap-account.html?topic=nyc_bjc%2F1-intro-loops.topic&course=bjc4nyc.html&novideo&noassignment)
- How do you ensure you are logged into Snap!?
- Show us that you've saved this lab to your Snap! account. This is important so you can refer back to your work for future assignments!
- Show us your Alonzo game.
- Is there anything you found interesting or challenging about Snap!?

**Lab 2**{: .label .label-lab}[Gossip](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/2-gossip-and-greet/1-pair-programming.html?topic=nyc_bjc%2F1-intro-loops.topic&course=bjc4nyc.html&novideo&noassignment)
- Why do we create our own blocks (or procedures)?
- What is the difference between a reporter and a command block? What is an example of each?
- Show us your "more complicated gossip" block. 
- In the last exercise, we asked you to have "more complicated who" call itself. What do you think is happening here? Don't worry if you don't fully understand this; we will formalize this in a few days!

**Lab 3**{: .label .label-lab}[Modern Art with Polygons](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/3-drawing/1-exploring-motion.html?topic=nyc_bjc%2F1-intro-loops.topic&course=bjc4nyc.html&novideo&noassignment)
- In this lab you learned a few blocks that achieve repetition. Which blocks are these, and when might you use them?
- How do you add an input to a block (or procedure)? Why might you do want to do this?
- Show your most recent pinwheel block. What do the different inputs (or argumnets) control?
- Show us your squiral block.

**Lab 4**{: .label .label-lab}[Lists and Higher Order Functions](https://cs10.org/bjc-r/topic/topic.html?topic=berkeley_bjc/lists/lists-I.topic&course=cs10_su19.html&novideo&noreading&noassignment)
- What is a list? Why would we use a list of 10 elements instead of just making 10 variables?
- What do `map`, `keep`, and `combine` each do?
- Show us your `acronym` block.
- Show us your `expand` block.
- What is the difference between the `for each (item)` loop and the `for (i)` loop we have used in previous labs?

**Lab 5**{: .label .label-lab}[Tic-Tac-Toe](https://cs10.org/bjc-r/topic/topic.html?topic=berkeley_bjc/lists/tic-tac-toe-advanced.topic&course=bjc-su22-blue.html&novideo&noreading&noassignment)
- Show us your winning triple block.
- How did you program the computer strategy? Show us your "next move" block.

**Lab 6**{: .label .label-lab}[Testing and 2048](https://cs10.org/bjc-r/llab/html/topic.html?topic=berkeley_bjc%2F2048-testing%2F2048.topic&course&novideo&noreading&noassignment)
- How does the test block work? What is its domain/range?
- Show us the output of your test block on merge column. Explain why this output makes sense, and how the test block is checking this block.
- How will writing tests help you for the 2048 assignment?
- How do merge up and merge column work? What are the domain/range of each block?

**Lab 7**{: .label .label-lab}[Trees and Fractals Using Recursion](https://cs10.org/bjc-r/topic/topic.html?topic=berkeley_bjc/recur/recursion-trees-fractals.topic&course=&novideo&noreading&noassignment)
- Please show me your “crazy-tree” block.
- Why is it important that the inputs to a recursive call be smaller than the original inputs to the function?
- Why is it important that the sprite face the same direction at the end of a recursive function as it faced initially?
- What defines a recursive block? What are the two necessary “cases” that a recursive block must consider? Name and define them.
- Please show me your “snowflake” block.

**Lab 8**{: .label .label-lab}[Recursive Reporters](https://cs10.org/bjc-r/topic/topic.html?topic=berkeley_bjc/recur/recursive-reporters-part1.topic&course=&novideo&noreading&noassignment)
- Why do we map the first item of the set in front of a recursive call of subsets _ over the rest of the list?
- Explain why the second version of subsets _ only makes 7 calls instead of 64.
- Explain how the sort _ block works, how the merge _ block works, and how they work together.
- Show us the recursive numbers _ block.
- Show us the recursive ends-e _ block.

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
