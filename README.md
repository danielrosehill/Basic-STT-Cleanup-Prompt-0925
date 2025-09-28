# Basic Speech To Text (STT) Cleanup / Remediation Prompt

This is an updated version of my basic/foundational STT remediation prompt. 

This is my equivalent of what is often called in UIs a "cleanup" prompt.

It can be used effectively in two ways:

1) By itself as a general purpose "make this accurate but kind of ugly STT transcript more readable" 
2) More powerfully, by concatenating it with another text transformation prompt that defines a precise target format for the resulting text transformation. For example: add a "format this as an email" prompt on top of this. This combining approach is particulary effective as it both improves the text and then fits it to a common format (like a note, calendar entry, meeting minutes, etc). 