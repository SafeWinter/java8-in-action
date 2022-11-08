# 《Java 8 in Action》Learning Notes



## 1. Profiles

![Java 8 in Action cover](assets/cover.png)



|    **Title**    |    **Java 8 in Action** [ISBN: 9781617291999]     |
| :-------------: | :-----------------------------------------------: |
|   **Author**    | **RAOUL-GABRIEL URMA, MARIO FUSCO, ALAN MYCROFT** |
| **Publication** |                **Manning, 2014.8**                |
|    **Pages**    |                      **424**                      |

> **Introduction**
>
> Back in 1998 when I was eight years old, I picked up my first book on computing—on JavaScript and HTML. Little did I know that opening that book would transform my life by exposing me to programming languages and the amazing things I could do with them. I was hooked. Every so often I still find a new programming language feature that revives this excitement because it enables me to write clearer, more concise code in half the time. I hope that the new ideas in Java 8, incorporated from functional programming and explored in this book, inspire you in the same way.
>
> So, you may wonder, how did this book come about?
>
> Well, back in 2011, Brian Goetz (the Java Language Architect at Oracle) was sharing various proposals to add lambda expressions to Java, with the aim of getting the community involved. These rekindled my excitement, and I started to evangelize the ideas, organizing Java 8 workshops at various developer conferences and giving lectures to students at the University of Cambridge.
>
> By April 2013, word had spread, and our publisher at Manning emailed asking whether I was interested in writing a book about lambdas in Java 8. At the time I was a “humble” second-year PhD candidate, and that seemed to be a bad idea because it would interfere with my thesis submission schedule. On the other hand, carpe diem; I thought writing a short book shouldn’t be too much work, right? (It was only later that I realized I was utterly wrong!) So I sought advice from my PhD supervisor, Professor Alan Mycroft, who, it turned out, was ready to support me in this adventure (even offering to help in such non-PhD work—I’m forever in his debt). A few days later we met fellow Java 8 evangelist Mario Fusco, who had vast professional experience and had become well known for his talks on functional programming at major developer conferences.
>
> We quickly realized that by combining our energy and diverse backgrounds we could deliver, not just a short book on Java 8 lambdas, but instead a book that, we hope, the Java community will still be reading in five or ten years. We had a unique opportunity to discuss in depth many topics that will benefit Java programmers and open doors to a new universe of ideas: functional programming.
>
> Now—July 2014, 15 months later, after many long nights, endless edits, and an unforgettable experience—you have our work in your hands and we hope you will enjoy it!
>
> RAOUL-GABRIEL URMA
> UNIVERSITY OF CAMBRIDGE



## 2. Outlines

Status available：:heavy_check_mark: (Completed) | :hourglass_flowing_sand: (Working) | :no_entry: (Not Started) | :orange_book: (Finish reading)

| No.  |                        Chapter Title                         |       Status       |
| :--: | :----------------------------------------------------------: | :----------------: |
| Ch00 |                     [Preface](./Ch00.md)                     | :heavy_check_mark: |
|      |                  **Part 1 -- Fundamentals**                  |                    |
| Ch01 |          [Java 8: why should you care?](./Ch01.md)           | :heavy_check_mark: |
| Ch02 |   [Passing code with behavior parameterization](./Ch02.md)   | :heavy_check_mark: |
| Ch03 |               [Lambda expressions](./Ch03.md)                | :heavy_check_mark: |
|      |        **Part 2 -- Functional-style data processing**        |                    |
| Ch04 |               [Introducing streams](./Ch04.md)               | :heavy_check_mark: |
| Ch05 |              [Working with streams](./Ch05.md)               |     :no_entry:     |
| Ch06 |          [Collecting data with streams](./Ch06.md)           |     :no_entry:     |
| Ch07 |    [Parallel data processing and performance](./Ch07.md)     |     :no_entry:     |
|      |          **Part 3 -- Effective Java 8 programming**          |                    |
| Ch08 |       [Refactoring, testing, and debugging](./Ch08.md)       |     :no_entry:     |
| Ch09 |                 [Default methods](./Ch09.md)                 |     :no_entry:     |
| Ch10 | [Using Optional as a better alternative to null](./Ch10.md)  |     :no_entry:     |
| Ch11 | [CompletableFuture: composable asynchronous programming](./Ch11.md) |     :no_entry:     |
| Ch12 |              [New Date and Time API](./Ch12.md)              |     :no_entry:     |
|      |                 **Part 4 -- Beyond Java 8**                  |                    |
| Ch13 |              [Thinking functionally](./Ch13.md)              |     :no_entry:     |
| Ch14 |        [Functional programming techniques](./Ch14.md)        |     :no_entry:     |
| Ch15 | [Blending OOP and FP: comparing Java 8 and Scala](./Ch15.md) |     :no_entry:     |
| Ch16 |       [Conclusions and where next for Java](./Ch16.md)       |     :no_entry:     |



Powershell script for generating markdown files in batch:

```powershell
# Create 16 empty markdown files named Ch##.md:
for($i=1; $i -le 16; $i=$i+1){ New-Item -Name "Ch$('{0:d2}' -f $i).md"; }
```

