# wcpgw

**What Could Possibly Go Wrong** is a catalog of error conditions

A language agnostic guide based on what you are trying to do and what can go wrong.

Should be useful regardless of OS, langauge or platform.
May grow into platform or language specific guides also.

## Format

Every error can have the following pieces

* Placed into a folder for a specific family of errors (files, network, http, flow, etc)
* Title
* Common error codes in the wild (can be platform specific)
* priority in this guide (how frequently does it occur in the wild)
* Description of why error occurs
* Notes on how to diagnose (by platform)
* Notes on how to create an environment to reproduce the issue (by platform)

## Specificity

Here do HTTP GET errors go? They are a network, possibly file and specifically
an HTTP problem.

Items should be documented at the most general area that makes sense.
More specific items can cross-reference the more general description.

So maximum URL length or HTTP Caching should be documented in the HTTP area,
but slow network timeouts could be covered in the network area.

The goal would be that a casual reader could learn a lot of useful information
by browsing the most general cases,
without wading through obscure gopher protocol specific issues.

## Format
Error conditions are captured in semantic HTML with metadata.
This will allow programs to parse them and create easy to use websites.

## License

Please re-mix this guide! [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)