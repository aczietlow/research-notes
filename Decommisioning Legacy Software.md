Sources:
- "An Agile Approach to a Legacy System" -Chris Stevenson and Andy Pols
- Strangler Fig Pattern - Martin Fowler


Rules

- Don't reproduce all legacy code.
	- Not all of the legacy code is used, not to mention that it includes bugs
	- By drawing bounds around active value add functionality and migrating that into new application the legacy app can eventually be deleted
		- Do this by getting good customer proxies
			- Identify key problems being solved
- Always ask the users what the actual problem they're trying to solve is
	- Users of our apps know better than us
	-  work with customer teams in validating changes
		- builds trust while also validating our assumptions
- Refactor legacy applications by delivering new business value
	- only extract relevant data
	- gain understanding of the important parts of the legacy system
- Incrementally build trust - prove that you can do the hardest part of the system
	- Cusotmer Empathy
- Involve the whole team with larger refactor changes
- Treat politics as a user requirement
	- Don't avoid fear, plan for it
		- "don't say no, say later"
- A system that connects to a legacy system must be tested with live feeds
	- This is the only way to tease out business rule bugs
- Engage users and they not only won't they turn it off, they'll fight some of your battles for you
- Keep giving a good team motivated by giving them new hard problems - don't waste a good team
	- Focus on delivering business value
