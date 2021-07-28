What is transfer learning. A brief explanation
============================================================================================================

autor: Barbara Jastrzebska

To answer this question, let\'s take an example. We all learned to
recognize colours by being introduced to the objects in those colours
first. Strawberry, tomato, pepper and fire truck were probably enough to
understand the concept of *redness*. Once we catch what the red colour
is we can correctly identify it on flowers, cars, abstract paintings and
also on many real-world objects that we've never come across before.
This is transfer learning.

Applying skills learned from a particular experience on the other tasks,
instead of trying to solve this new task from scratch. To distinguish
red roses from white ones you apply your knowledge gained on plenty of
examples of what red colour is.

![unnamed.jpg](https://images.squarespace-cdn.com/content/v1/5b4dba1c372b9677b7cf4abd/1541778846872-K24T2Q7CE5XEA3EAAPOK/ke17ZwdGBToddI8pDm48kMCof9kTSISDMe-s5TZm_N1Zw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PITC5ngm61Fcyr-PVq05xb0CRWN6r5QkXuDUuicFx3E8wKMshLAGzx4R3EDFOm1kBS/unnamed.jpg)

Humans and animals continuously use transfer learning to solve problems.
Just to mention little kittens hunting on your socks, skill that in
wildlife would get them a good chance for real prey. (The fact that
domestic kittens will never found themselves in wildlife doesn't matter.
They will surely find some objects at your house to transfer
sock-hunting skill elsewhere, curtains maybe?). However, what interests
us is how transfer learning is applied to computers and how deep
learning benefits from it.

![Screen Shot 2018-11-07 at
18.12.54.png](https://images.squarespace-cdn.com/content/v1/5b4dba1c372b9677b7cf4abd/1541611074119-QNOITTUJ5V36N2K5WCXR/ke17ZwdGBToddI8pDm48kHRGbr-gVeMAxec1FSvtSYMUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKc8jcMYAW_hbNYC4tp3QJwOEpZL0P6XsM4FK1bb4hFv6DxPW7b56uXKWY9Et9IdzOf/Screen+Shot+2018-11-07+at+18.12.54.png)

### Transfer learning in deep learning 

The mechanism of transfer learning in case of computers is not so
different from the one regarding kittens and humans. We use a model
designed for one task as a starting point for another task. It is a
technique to try if we can indicate a related task with an extensive
data set and we design a model for that task and re-apply it to our
target problem. There is a good chance that we will be able to find
adequate data sets to the problem we are looking to solve. This year
Google launched dataset search so that journalists, scientists, students
and anyone who needs particular data to their work can find it. More
information about Google dataset search you'll find here:
[[https://www.blog.google/products/search/making-it-easier-discover-datasets/]](https://www.blog.google/products/search/making-it-easier-discover-datasets/)

Another possibility is to benefit from available, pre-trained models
shared by research institutions.

Examples of such models are
[[Resnet]](https://pytorch.org/docs/stable/torchvision/models.html)
for computer vision available in all deep learning frameworks or in case
of NLP
[[ULMFiT]](http://nlp.fast.ai/)
available in FastAI library [[(which recently graduated to version
v1.0)]](fastai-v1.html).

### From cucumbers to Cougars: what kind of problems can be solved with transfer learning? 

On some problems where we cannot collect enough data, transfer learning
let us design models impossible to develop without it. Here are some
examples of fast.ai students that applied transfer learning to design
models that:

-   recognize cucumbers from zucchinis using only 86 pictures of both
    with an accuracy 100%

-   were used to build an application that correctly identifies the
    image of the Cougars for the  cougarnet.org so the population of
    these animals can be tracked (normally task done by human experts)

-   use classification of satellite images to automatically recognize
    the country from which the image was collected,

-   more examples can be found on [[yesterday's presentation by Jeremy
    Howard:
    ]](https://twitter.com/PiotrCzapla/status/1059876446687166466)

###  Transfer learning in Natural Language Processing tasks

The year 2018 is significant in applying transfer learning to Natural
Language Processing. In the past, a minimal way of transfer learning was
used. Instead of the whole models, only first small layers were
reapplied for the other tasks. In January 2018 Jeremy Howard and
Sebastian Ruder introduced a first successful usage of the complete
models to do transfer learning in a very similar way as in Computer
Vision. They exceeded the state of the art in document classification,
reducing error in some tasks even by 24% (this kind of improvements does
not happen often). In June, OpenAI used the same concept of transfer
learning and applied it to a resource hungry, but powerful architecture
[[achieving state of the art in 12
tasks]](https://blog.openai.com/language-unsupervised/).
In August we (n-waves) adopted the ULMFiT Architecture to
morphologically rich languages such as Polish and German exceeding
previous state of the art for [[German sentiment analysis by
12%]](https://forums.fast.ai/t/ulmfit-german/22529)
and in [[Polish language
modeling]](http://poleval.pl/results/).
In October 2018 Google extended the architecture of OpenAI and trained
it on a massive dataset, exceeding Open AI results in nearly every task.
In addition they managed to beat human accuracy on question answering
task (SQUAD v1)

This week Google released a pre-trained version of their model that
works on combined 102 languages, including most of the European
languages. They showed that their multilingual model can be used as a
base for transfer learning to beat state of the art in SNI (an abstract
NLP task that tries to measure language understanding).

How does Transfer Learning work in NLP? Especially, how does
pre-training work in case of words and sentences? For instance, base
task allows a model to grasp such language phenomena as negation from a
huge-scale dataset, for example, Wikipedia. Now we can use this as a
starting point for training another model to do some specific NLP task,
such as [[sentiment
analysis]](9/28/business-applications-of-natural-language-processing-nlp.html).
But it requires less data points because If the base model learned on
Wikipedia what is a negation, it does not have to learn that concept
again on a smaller data set. Negation is, of course, just one example,
the model trained on Wikipedia learns grammar, semantic relations among
words, etc.

\
Given the time, vast computing and data demands for creating some neural
network models, the idea of transfer learning is quite practical. It
revolutionised computer vision and now it is doing the same to natural
language processing. If you want to learn more, feel free to drop us a
line, we can talk about this for hours :).
