# guided-notes-using-TeX

## What is this?

This is the LaTeX source code for a set of Algebra 2 guided notes.

## Why?

Many teachers collect resources from various sources and distribute 
them to their classes during the year. 
As a result, the students have a set of handouts in various formats
without a coherent layout or approach to presenting the information.

This project is a LaTeX-based system for generating handout notes 
that follow a consistent format in the hope that the consistency 
helps the students understand the larger structure of the course and where each 
lesson handout fits in.

## Some details

This project started during the Spring 2020 pandemic as part of producing 
materials to send home to the remote students.
In the early days, there was still a lot of cutting and pasting.

In the years that followed, the notes evolved into a single, consistent 
format was ready to handout after printing. 
I chose a format based on these ideas:

* each lesson should have the same general visual appearance
* every lesson should be explicit about what the students should learn (so-called "I can" statements)
* vocabulary should be summarized up front to enable pre-teaching
* the key concepts (e.g., step-by-step procedures for, say, synthetic division) should be visually highlighted
* there should be some I-DO examples where the students would fill in the empty space with me as we worked together
* and there should be some WE-DO or YOU-DO examples, also with empty space that the students would work on in groups or individually

Although the first set of lessons were designed to be compiled into a large take-home 
packet for remote students at home,
eventually the focus changed to individual lessons
to be handed out to the students at the beginning of a teaching day.
(Teaching days were typically followed by practice days, but the practice worksheets 
are not generally captured in these notes, rather I used Kuta to generate them.
Consequently, these notes are in a sense only 50% of what I hand out to the students.)


## Some quirks (or warnings?)

* This was not a group project. I am the only developer. I am not under any illusion that it is easy to understand the LaTeX infrastructure that I've assembled over time. Sorry.
* These notes evolved over several years. Typically I began the next year by improving the "common" infrastructure over the summer and then creating new lessons incrementally during the school year. Thus each year's content grew day-by-day as the year progressed. If I was lucky, I was able to copy large portions of the previous year's work, but even when this was the case, I almost always tweaked the details enough that there was never 100% reuse.
* The folders v1, v2, etc... are where each year's lessons are located. The LaTeX source in each of these folders is completely self-contained. Thus it should be possible to rebuild last year's lessons and then compile this year's even though the underlying infrastructure has typically evolved incompatibly from year to year. Because there was so much copying as each year progressed, I chose _not_ to use git branches to capture each year.
* To be honest, this repo is mainly useful to me only as a offsite backup of my LaTeX source.

## Some comments about the folder structure

* the "common" directory is where the common structure of the lessons is defined.
* `v1 (paper packets)` is what I put together for the Algebra 2 paper packets for Fall 2020 (my initial effort for using memoir for guided notes)
* `v2` is what I used for the remote/in-person notes for 2020-2021. It was a ``better version'' of using memoir (better factoring into files, cleaner implementation).
* Subsequent years are in similarly names vX folders.
