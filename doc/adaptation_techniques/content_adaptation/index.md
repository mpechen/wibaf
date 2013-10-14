# Content Adaptation
According to [Brusilovsky 96](http://dx.doi.org/10.1007/BF00143964) content adaptation techniques are those whose goal is to hide fragments of the content which are not relevant to the user or to highlight those which are relevant.
## Inserting/Removing fragments
Inserting or removing fragments technique consists on specify a set of optional fragments for each page and at runtime, those fragments can be rendered or not, according to boolean expressions related to user features.
## Altering fragments
When using the altering fragments technique, a page is written as a set of components, where every component is a set of fragments. When the page is rendered, for each component, the most appropiate fragment is selected.
## Dimming fragments
Dimming fragments is less aggresive than the removing fragments technique. The fragment is not removed, but instead made less visible so that the user is not stimultated to read the text although he could do it.
## Sorting fragments
Sorting fragments can be done when a set of independent fragments can be presented in any order. As user focus decreases after being reading for a long time, the most relevant or interesting fragments can be rendered first, to catch the attention of the user.
## Stretchtext
Stretchtext technique is similar to the inserting/removing fragments technique, but the fragments are not really removed, instead they are opened or closed. The system decides which fragments are opened and which are closed when the page is rendered, then, the user can open or close fragments at will, and when doing so, the system receives feedback.
## Zoom/Scale
Zoom/Scale techniques are those which make something larger or smaller. Those can be divided in three subtechniques.
### Conventional scaling/zooming
The conventional scaling/zooming technique fits in the previous definition. Some ways of achieving it is to change the text font or the text size, scaling images, etc...
### Fisheye view
According to Tsandilas 03, fisheye view techniques assume that there is a single focal point with the maximum degree of interest (DOI) and the value of DOI decreases with the distance to that point. Therefore, fisheye view techniques implement a zoom function that is linearly dependent to the DOI.
### Fragment summarization
Fragment summarization requires natural language processing techniques to summarize text or other kind of summarization techniques when the elements are not textual. It is therefore a complex technique, since the result of the summarization has to be coherent and cohesive.