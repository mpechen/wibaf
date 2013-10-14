# Adaptive navigation
According to [Brusilovky07](http://dx.doi.org/10.1007/978-3-540-72079-9_8), adaptive navigation support is a specific group of technologies that support user navigation in hyperspace, by adapting to the goals, preferences and knowledge of the individual user.
## [Zoom/Scale](../content_adaptation/index.md#zoomscale-fragments)
### [Conventional scaling/zooming](../content_adaptation/index.md#conventional-scalingzooming)
### [Fisheye view](content_adaptation/index.md#fisheye-view)
### [Fragment summarization](content_adaptation/index.md#fragment-summarization)
## Link sorting/ordering
Link sorting or ordering technique consists of reordering links to give priority to the most relevant or interesting. This cannot be done on links that appear in paragraphs or any other textual fragments, but it is done with menus.
## Link annotation
Link annotation keeps all the links accessible and annotates them in order to indicate how interesting is the link for a user. This can be done by changing the colour of the link anchor, adding an icon in front of it, etc...
## Combinatorial techniques
A combination of the adaptive navigation techniques can be used in order to increase their effectiveness. [Brusilovky07](http://dx.doi.org/10.1007/978-3-540-72079-9_8) proposes the following table according to the applicability of each technique.

 | Direct guidance | Sorting | Hiding    | Annotation | Generation
-| --------------- | ------- | --------- | ---------- | ----------
Contextual links          | OK |    | Disabling | OK |
Non-contextual links      | OK | OK | OK        | OK | OK
Table of contents / index | OK |    |           | OK |
Hyperspace maps           | OK |    | OK        | OK |
## Link generation
This technique consists of the creation of new non-authored links on a page. This can be done discovering page or item similarities, or recommending useful links according to the user model.
### Anchor adaptation
Anchor adaptation not only adapts the destination of a link as the other two link generation techniques, but also generates the link anchor.
### URL adaptation
This technique selects the link destination when the page is rendered.
### Destination adaptation
This technique always shows the same link in the client, but the server selects which page should be displayed when the link is accessed.
## Guidance
The guidance technique consists of offering a guided tour for the user, recommending always the best next page to visit.
### Direct (local) guidance
Direct guidance is an explicit guidance. The system offers a next button that takes the user to the next most recommended page according to the user model.
### Global guidance
Global guidance is more subtle than direct guidance. It can be seen as a URL/destination adaptation, where the links may not lead where the user thinks but to a page most recommended for him.
## Link hiding
Link hiding is used to obscure the presence of links that are not recommended for the user. It can be done in three ways that can be combined.
### Hiding
Hiding a link means that it is rendered as plain text, but the link is still working. The user may not identify the link but if he does, he can use it.
### Disabling
Disabling a link means that the link will not work anymore, this does not imply that the link is shown as plain text, and that can confuse the user, so whenever disabling is used, it should be combined with hiding.
### Removal
The removal technique deletes the anchor and therefore the link cannot be used. This technique should not be used when the link is part of a textual fragment because it might lose coherence, but it can be used in menus.