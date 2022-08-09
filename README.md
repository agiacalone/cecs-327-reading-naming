# CECS 327 Reading Assignment: Naming

# Assignment Description
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

# Deliverables
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: plain text (\*.txt), Markdown (\*.md), PDF (\*.pdf) or web-renderable HTML (\*.html). Github will look for one of these file formats to confirm your "submission" of the assignment. Other formats will only be accepted with *explicit* approval. **NOTE: \*.docx is *not* acceptable. I will not make exceptions for this rule being violated**.