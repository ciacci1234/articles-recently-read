https://www.fastly.com/blog/network-automation-helps-support-worlds-biggest-live-streaming-moments
Cool overview of how fastly uses a couple of automated systems so that a team of 12 engineers can handle the huge traffic coming through their network during big events like the super bowl

https://discord.statuspage.io/incidents/62gt9cgjwdgf
Good technical write-up of an incident discord experience. Highlight: Discord relied on Go's standard library net/http to process requests and the client did not accurately respond to HTTP requests that had a specified Content-Length header but an empty body. Surprising and Interesting! Vaguely reminds me of this guy's rant where he mentions some networking weaknesses with golang https://fasterthanli.me/blog/2020/i-want-off-mr-golangs-wild-ride/


http://calpaterson.com/activerecord.html
I didn't like his tone, and I could've used more evidence for his position, but overall good thoughts about the problems
accessing data through objects versus queries of a relational database

https://robertheaton.com/2020/03/18/yourself-happier-iphone-worse/
I include this one only to self-affirm the fact that I also purposefully have safari several screens away and my friends
make fun of me for it

https://boringrails.com/articles/spring-cleaning/ - good tips on cleaning up old stuff in a rails codebase, adding to my 20% time list

https://schneems.com/2020/03/17/lies-damned-lies-and-averages-perc50-perc95-explained-for-programmers/
A very simple and clear explanation of some basic statistics concepts in the context of commonly used metrics
to describe web application performance

https://blog.appsignal.com/2020/03/18/facade-pattern-in-rails-for-performance-and-maintainability.html
Discussion on using PORO's that take care of complex logic that the rails views would otherwise have to take care of.
Seems very similar to ViewModels except perhaps that Facades are tied more closely to controllers?
Also, I deeply hate the name choice of Facade. Makes no sense to me!

https://engineering.shopify.com/blogs/engineering/refactoring-legacy-code-strangler-fig-pattern
Discussion of what Martin Fowler calls the Strangler Fig pattern where you incrementally create new components
of your system to replace old parts of your system. Shopify uses a decent real-world example where they used this
pattern in their own system. There's a TLDR summary at the bottom of article if you don't feel like reading it

https://github.com/simplabs/ast-workshop - didn't go through it myself but a neat-looking workshop explaining Abstract Syntax Trees using Javascript
