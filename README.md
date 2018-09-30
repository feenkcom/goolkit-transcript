## GT Transcript

GT Transcript is the reinvention of the classic transcript. It offers a rich and interactable text interface for displaying live information coming from a system.

The API is backward compatible with the existing transcript. To enable the new features, we introduced a builder. For example, `transcript nextPutAll: 'something'` becomes `transcript next putAll: 'something'`, and after `next` we can add multiple attributes that we want to affect the following insertion of a text. 

To get an idea of how this tool can be useful, take a look at the following video showing the visual logging of a Bloc animation:

[![GT Transcript: logging an animation](https://img.youtube.com/vi/9VATYNaLwJY/0.jpg)](https://youtu.be/9VATYNaLwJY "GT Transcript: logging an animation")
