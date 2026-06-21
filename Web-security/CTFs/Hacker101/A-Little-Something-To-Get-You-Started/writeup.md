Hacker101 CTF - A Little Something To Get You Started
Challenge Information

Platform: Hacker101 CTF
Challenge: A Little Something To Get You Started
Difficulty: Trivial
Category: Web Security
Objective

Retrieve the hidden flag by performing basic web reconnaissance and source code analysis.

Methodology
- Step 1: Review Page Source
. Viewed the page source code and examined the HTML elements.
. During the review, the following resource reference was identified:
   background-image: url("background.png");

- Step 2: Resource Discovery
. The discovered resource patth indicated the existence of a hidden file named background.png.
The resource URL was manually accessed through the browser.

-Step 3: Flag Retrieval
Upon navigating to the discovered resource, the hidden flag was successfully obtained

-Skills Learned
Source Code Review
HTML Analysis
Resource Discovery
Information Gathering
Web Reconnaissance

-Key Takeaways
Source code should always be reviewed during reconnaissance.
Hidden resources can often be discovered through HTML, CSS, and JavaScript analysis.
Client-side code may expose information useful for further enumeration.
Outcome

Successfully identified a hidden resource through source code analysis and retrieved the challenge flag.
