---
title: Literacy and Numeracy skills in the Arc Intro to Python - Vocabulary activities 
date: 2024-05-23 15:30:00 +0800
---

What are the literacy and numeracy expectations in the Vocabulary activities that are a part of the [Introduction to the Python programming lesson plan](https://arc.educationapps.vic.gov.au/learning/sites/digital-technologies-lesson-plans/10195/Introduction-to-Python-programming)?
And what improvements can be made to enhance support for the knowledge and skills required in your classroom?

## Inputs and outputs
### The examples

Input and output are *tier three* words that may be familiar to students in other contexts, but have specific meaning in a Digital Technologies classroom.
Together, they provide a conceptual framework for how programs (and thus Python Programming) work.

The fact that these concepts are introduced separately makes sense, however, there is a lack of symmetry in the visual explanations.

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/input.png" alt="A slide that describes input as 'data that goes into a system or process' with a diagram showing a keyboard with text and a mouse connected to a computer using red arrows">
    <img src="/assets/images/articles/Arc-literacy-numeracy/output.png" alt="A slide that describes output as 'data that comes out of a system or process' with a diagram showing abstract charts on a computer and speakers next to the computer emitting sounds">

    <figcaption>The two slides from Arc, describing the vocabulary words 'input' and 'output'.</figcaption>
</figure>

The arrows in the input example provide a visual marker to help students understand the process of inputting.
Mirroring these arrows in the output diagram –in the same way the text explanation is mirrored– would help students understand that the two concepts are opposites.

Adding in a third slide that combines the two concepts will scaffold student understanding of how input and output relate to the concept of a Python program.

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/output-modified.png" alt="A slide that describes output with a diagram showing visual and sound output connected to a computer using red arrows">
    <img src="/assets/images/articles/Arc-literacy-numeracy/program.png" alt="A slide that describes a 'system or process that transforms inputs into outputs' with a diagram of an arrow going from a computer mouse to a computer and another arrow leading to a speak making sound">

    <figcaption>New slides for definitions of output and program</figcaption>
</figure>

### Missing vocabulary

The words "data", "systems" and "processes" are left undefined.
These are *tier two* words that students may have encountered in other subjects like [maths](https://f10.vcaa.vic.edu.au/learning-areas/mathematics/curriculum?level=5&cd=VC2M6ST01), [science](https://f10.vcaa.vic.edu.au/learning-areas/science/curriculum?level=7–8&cd=VC2S8U15) and [history](https://f10.vcaa.vic.edu.au/learning-areas/humanities/geography/curriculum?level=7–8&cd=VC2HG8K14).

In Digital Technologies, "systems and processes", are usually referring to "*information* systems" and "*information* processes".
It is worthwhile exploring examples of other information systems and processes to engage the different prior knowledge systems some students might have due to culturally differences,
e.g., [gaming systems](https://blurbusters.com/human-reflex-input-lag-and-the-limits-of-human-reaction-time/), [weaving and knitting processes](https://uknowledge.uky.edu/edsc_etds/107/), [songline](https://www.abc.net.au/listen/programs/allinthemind/songlines-indigenous-memory-code/7581788) systems, etc.

### Checking for understanding

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/checking-old-1.png" alt="">
    <img src="/assets/images/articles/Arc-literacy-numeracy/checking-old-2.png" alt="">

    <figcaption>Old slides for checking understanding</figcaption>
</figure>

Instead of asking students to *classify* a process as input or output, we should be asking them to *identify* the inputs, outputs and types of data in a process.

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/checking-new-1.png" alt="">
    <img src="/assets/images/articles/Arc-literacy-numeracy/checking-new-2.png" alt="">

    <figcaption>New slides for checking understanding</figcaption>
</figure>

Based on [prior knowledge](https://f10.vcaa.vic.edu.au/learning-areas/technologies/digital-technologies/curriculum?level=5–6&cd=VC2TDI4D01) from the Digital Technologies curriculum, students should also be able to recognise data as numbers, text, and pictures (possibly even [binary](https://f10.vcaa.vic.edu.au/learning-areas/technologies/digital-technologies/curriculum?level=5–6&view=focus&cd=VC2TDI6D01)).

In addition to asking students to identify these components conversationally,
we can use ask students to label diagrams, sentences and even short form texts to build students' literacy skills across visual and textual domains.

## Variables

### From a spatial analogy...
The definition of a variable, as given in the Arc lessons, as a named bucket or box is a popular analogy because it is [genuinely useful](https://cs-blog.khanacademy.org/2013/09/teaching-variables-analogies-and.html).
However, it is also full of potential pitfalls for students.

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/variable.png" alt="A slide that describes a variable as 'a container for data' with a diagram showing values inside of tubs or buckets">
    <figcaption>There's a hole in the variable bucket analogy.</figcaption>
</figure>


For example, the analogy suggests a [spatial logic](https://efa.unisa.edu.au/2024/03/08/spatial-reasoning/) that doesn't necessarily apply (depending on the programming language).
For example, in Python, if a program stores a really large list in a variable can it overflow out of the variable like water from a bucket?
The answer is 'yes' for reality and 'no' for Python.

### ...To numerical concepts
Mathematics teachers and curriculums will often not give a [vocabulary definition of algebra](https://arc.educationapps.vic.gov.au/learning/sites/mathematics-lesson-plans/4702/Investigating-growing-geometric-patterns) when teaching it.
Instead they chunk algebraic thinking into defined sub-concepts like sequencing, terms, rules, patterns, generalising.
Similarly, we can chunk ['variable thinking'](https://books.google.com.au/books?hl=en&lr=&id=vFhEAgAAQBAJ&oi=fnd&pg=PA161&ots=W50lVEnHtW&sig=OMYfdv9QmUdafYLIKd2UEBxHjP4&redir_esc=y#v=onepage&q&f=false) into sub-concepts. 

<figure>
    <img src="/assets/images/articles/Arc-literacy-numeracy/variables.png" alt="">

    <figcaption>Examples of the sub-concepts of variables in Pascal</figcaption>
</figure>

You can use resources and activities that allow students simultaneously learn variables and practise and build their numeracy skills.
For example:

 * working through [a program](https://cscircles.cemc.uwaterloo.ca/visualize#code=%23+Reassignment%0Aage+%3D+26%0A%0Aage+%3D+27%0A%0Aprint(age)&mode=&raw_input=) (that uses *Referencing a variable* or *Reassignment of a variable*, for example) [step-by-step](https://cscircles.cemc.uwaterloo.ca/visualize#code=%23+Reassignment%0Aage+%3D+26%0A%0Aage+%3D+27%0A%0Aprint(age)&mode=display&raw_input=&curInstr=3) to teach procedural thinking as in the process of arithmetic calculation
 * giving students ["working backwards" problems](https://www.ck12.org/book/ck-12-algebra-i-second-edition/section/2.6/) that ask for variable *Assignment* values that will result in the given output which also checks for understanding of symbolic representation
 * using [virtual manipulatives](https://streamlit.io/playground?example=hello&code=H4sIAAAAAAAAA31SwW7bMAy96ytY7yC7DQy0vQ1IgKE9dLeddg1Ym3GEyZIh0U0CI_9eyolbt2l3kii-x8dHyrSdDwyRA2FrDQNGCZSKXLJhS3n2F4PBZ0vwK0bTuJYcg98AQoW26i0y1fCCtqesUOoH3Jbw2zEFrNi8EBjX9QzUPlNdC7A2gSq2hySDQjuVVk0gYuMaWEISpj2vR2KeTZmf2eKkstRPZK3XhXLY0iUhvc7AOx9sLeCudxX3yMa7S84sOaNe6dHQXQmPJnYWD6lBmRDtcbRgzT8SE6F3LmX-HHgrxTdG_HTjfd0F3wRsRTDLsrlJPUzBUU8-9JAuEquWYsQmvb1RbkAvQMsxgiUaZj0nTheM4_zMLFTS-9TFemd4u5aRRyn8MVVufGiR8-tr62WrMS-K9AEqX1P-XZEFWHRNL2rL7IRJ-5d53ZfwMP0MQJd2Pk4PeEsQKPaW1elIjQxHRXuq_iMzHBdnWnzvSq9WKxjOdo_63cCE_Kq9V5zgiZ_sAgAA) to explore the *Assignment of a calculated value* like you might do for exploring algebraic variable substitution
