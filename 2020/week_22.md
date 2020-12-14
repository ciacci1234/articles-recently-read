- **Composite Primary Keys in Rails**
  - Useful explanation of optimizing db queries given some fundamental db principles concerning memory access and storage patterns
  - https://shopify.engineering/how-to-introduce-composite-primary-keys-in-rails
- **Big Technical Changes at Slack**
  - Insightful overview of some big projects Slack took on and how they evaluated and rolled out those projects
  - A good takeaway is that there is a middle phase of project adoption that is hard and will only work with very intentional efforts to make it happen.
  - https://slack.engineering/how-big-technical-changes-happen-at-slack/
- **How to Improve Incident Reports**
  - This article provides a useful example of how to improve incident reports, specifically when it comes to viewing incidents as consequences of complex sociotechnical systems rather than stopping at the superficial cause for an incident. 
  - https://medium.com/last9/root-cause-analysis-for-reliability-a-case-study-8a987ed3a31c
- **Capital Letter-Handling Oopsies**
  - A Client-Side web interface update related to Google Drive caused an outage, and the update had to do with mishandling capital letters in email addresses. Interesting!
  - https://static.googleusercontent.com/media/www.google.com/en//appsstatus/ir/0qduwf33xnjkxpl.pdf
- **Datadog Incident Report: Service Discovery Configs Problems**
  - One of the more interesting takeaways was to be mindful of scaling up external incident response efforts in addition to internal efforts. Making sure you are sufficiently communicating to your customers/users throughout the lifetime of the incident is just as important as having enough brains working on the actual problem.
  - Also, I enjoy any incident around service discovery and misconfiguration and systems being too dependent on one another. I feel like they bring up classic problems engineers have been dealing with forever.
  - https://www.datadoghq.com/blog/2020-09-25-infrastructure-connectivity-issue/
- **Bias in Machine Learning**
  - A good paper highlighting "bias in, bias out" concerns our industry and society as a whole would do well to appreciate and be cautious about when it comes to machine-learning and the AI it powers.
  - https://blog.acolyer.org/2020/12/08/bias-in-word-embeddings/
- **Interesting Writeup on SSH internals**
  - Written in the context of a forensic analysis of a cybersecurity attack
  - https://blog.fox-it.com/2020/11/11/decrypting-openssh-sessions-for-fun-and-profit/
- **Slack's Success with Vitess**
  - From the [Vitess](https://github.com/vitessio/vitess): Vitess is a database clustering system for horizontal scaling of MySQL through generalized sharding.
  - It was interesting to see how it fit Slack's needs.
  - https://slack.engineering/scaling-datastores-at-slack-with-vitess/
- **Simple Tutorial on the Basics of Recursion**
  - I like the emphasis on breaking down the main problem into smaller sub-problems, all of which should be solvable with the same solution until you hit the base case.
  - https://thevaluable.dev/recursion-guide-examples/