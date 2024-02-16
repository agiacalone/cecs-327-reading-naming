# CECS 327 Reading Assignment: Naming

### Assignment Description
Answer the following questions from the Chapter 5 reading from your textbook. Be complete with your answers. You may work on these questions with one or two other partners, but all students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Would you consider a URL such as http://www.acme.org/index.html to be location independent? What about http://www.acme.co.uk/index.html?
2. Is an identifier allowed to contain information on the entity it refers to? Why?
3. Consider the Chord system and assume that a node 7 has just joined the network. What would its finger table be and would there be any changes to other finger tables?
4. If we insert a node into a Chord system, do we need to instantly update all the finger tables? Why?
5. Suppose that it is known that a specific mobile entity will almost never move outside domain D, and if it does, it can be expected to return soon. How can this information be used to speed up the lookup operation in a hierarchical location service?
6. Consider an entity moving from location $A$ to $B$, while passing several intermediate locations where it will reside for only a relatively short time. When arriving at $B$, it settles down for a while. Changing an address in a hierarchical location service may still take a relatively long time to complete, and should therefore be avoided when visiting an intermediate location. How can the entity be located at an intermediate location?
7. Give an example of how the closure mechanism for a URL could work.
8. Explain the difference between a hard-link and a soft-link in Unix systems. Are there things that can be done with a hard-link that cannot be done with a soft-link or vice versa?
9. Explain how DNS can be used to implement a home-based approach to locating mobile hosts.
10. Considering DNS. To refer to a node $N$ in a subdomain implemented as a different zone than the current domain, a name server for that zone needs to be specified. Is it always necessary to include a resource record for that server’s address, or is it sometimes sufficient to provide only its domain name?

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.