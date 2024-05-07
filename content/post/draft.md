+++
title = "Summary of On Intelligence by Jeff Hawkins"

date = 2020-02-15T00:00:00
lastmod = 2020-02-29T00:06:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Common Knowledge", "Book Summary"]
summary = "From biological brain to artificial general intelligence. Description of the whole framework as described by Jeff Hawkins in his book \"On intelligence\"."

[header]
image = ""
caption = ""

+++

## Introduction

In this post, I have tried to condense the knowledge presented in the book "On Intelligence" by "Jeff Hawkins". This might be helpful for people who have read this beautiful book, but like me, have too forgetful of a memory to retain all the treasures within.

I have started with a brief definition of intelligence. Then, quickly moved onto Neo-Cortex, which is one of the key structures behind the intellectual superiority of mammalian brains. I tried to touch the major functionalies of neo-cortex that are essential for forming intelligence in section 4. Later, the algorithm and architecture of human neo-cortex has been described in section 5, 6. Section 7, 8, 9 describe some of the ingenious solutions applied by neo-cortex, thalamus and hippocampus to solve problems like associative memory system, hierarchical representation, learning from scratch and future prediction. Finally, in section 10, I have listed out some of my own proposals and thoughts for future references.


## 1. Intelligence and Biological Brain

The key concept in understanding intelligence is that understanding is an intrinsic concept happens within the agent who is trying to understand something. External behavious is not a good indicator of understanding or intelligence. 

Three major things are essential to understanding the brain. 

1. Inclusion of Temporal Aspect to data
2. Importance of Feedback
3. Physical architecture of the brain

## 2. Neo-Cortical Memory

It is because biological brains retrives answer of a problem from memory rather than computing the solution everytime, it seems so fast compared to conventional computers. This neocortical memory is different than computer memory in the following aspects:

1. The neocortex stores sequences of patterns.
2. The neocortex recalls patterns auto-associatively.
3. The neocortex stores patterns in an invariant form.
4. The neocortex stores patterns in a hierarchy.

## 3. Neo-Cortex

The neocortex is the part that probably contributes the most to our human-level intelligence. This thin multi-layer structure that encompasses the old brain is the place where learning takes place. It is mainly consisted of columns of neuron cells (6 cells per column in human neo-cortex) stacked tightly. Cells of same column has both feed-forward and feedback connections, usually feedback connection outnumbering feed-forward by a factor of 10. Also there are lateral connection among cells of the same hierarchy level. The notion of hierarchy and majority-feedback connections are of utmost importance. 

In an usual human brain, different regions of neo-cortex are assigned with different tasks, like region for processing auditory signal, region for processing visual signal etc. However, it has been proven that all the regions have the same hierarchical structure and have the capability to process different signals if they were connected with different signals/sensors. There are also higher level association regions that receive input from different sensors.


## 4. Major Functionalities of Neo-cortex

### 4.1 Invarient Representation of Our Experiences

Neo-cortex uses heirarchical memory storage system with feedback signals to predict about our next experience. This predictions process is never-ending but our attention is drawn towards them when the prediction do no meet the experience (input through sensors). As the signal travels up the hierarchy, the signal gets converted from being spatially variant, fast changing, small-scale-features into spatially invariant, slow changing, large-scale-features.

{{< figure src="./img/Alche.jpg" title="Forming invariant representations in hearing, vision, and touch. Images from On Intelligence (2004).  " numbered="true" lightbox="true" width="50%">}}
