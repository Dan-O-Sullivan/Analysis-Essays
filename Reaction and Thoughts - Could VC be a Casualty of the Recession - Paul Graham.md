#PaulGraham #Startup #Venture 


> Could VC be a Casualty of the Recession?
> December 2008

Interesting to note the timing of the article, taking into consideration known outcomes.

> _(I originally wrote this at the request of a company producing a report about entrepreneurship. Unfortunately after reading it they decided it was too controversial to include.)_

> VC funding will probably dry up somewhat during the present recession, like it usually does in bad times. But this time the result may be different. 
> This time the number of new startups may not decrease. And that could be dangerous for VCs.

**"This time the number of new startups may not decrease."**

Will have to look for data on the number of new US startups
Current Proxies:
### [Projected Business Formations Within Four Quarters](https://fred.stlouisfed.org/series/BFPBF4QNAICS55NSAUS)
![[Pasted image 20230921140531.png]]
### [Business Applications: Retail Trade in the United States](https://fred.stlouisfed.org/series/BABANAICSRETSAUS)

![[Pasted image 20230921140713.png]]

Will have to do a separate deep-dive on the implications of the Business Applications: Retail Trade in the United States because that's a stark change in landscape.

Though we can't fully isolate startup creation rate looking at all NAICS applications, my current feeling is that using it as a crude proxy is fine.

Appears that new business creation had fallen off fairly substantially already at the time of Paul's writing of this article and did not begin to slowly increase until 2014 (eyeballed inflection point)

>When VC funding dried up after the Internet Bubble, startups dried up too. There were not a lot of new startups being founded in 2003. But startups aren't tied to VC the way they were 10 years ago. It's now possible for VCs and startups to diverge. And if they do, they may not reconverge once the economy gets better.

How can I model /approximate VC funding? How can I asses the validity of the statement "startups aren't tied to VC the way they were 10 years ago". What does "startups" mean in this context? Does it mean the existence of a startup, profitability regardless of size, impact of the startup? Even my verbiage here 'impact' is completely undefined at this point.

>The reason startups no longer depend so much on VCs is one that everyone in the startup business knows by now: it has gotten much cheaper to start a startup. 

I made the decision to introduce a break here, even though there isn't one in the article because the next point is important to the implications of the article.

>There are four main reasons: Moore's law has made hardware cheap; open source has made software free; the web has made marketing and distribution free; and more powerful programming languages mean development teams can be smaller. 

I'm having trouble with "Moore's law has made hardware cheap", this is probably due to a fundamental limitation in my understanding of chip manufacturing and Moore's law. What implication does Moore's law make about cost?
#### [Wikipedia - Moore's law](https://en.wikipedia.org/wiki/Moore%27s_law)
> **Moore's law** is the observation that the [number of transistors](https://en.wikipedia.org/wiki/Transistor_count "Transistor count") in an [integrated circuit](https://en.wikipedia.org/wiki/Integrated_circuit "Integrated circuit") (IC) doubles about every two years. Moore's law is an [observation](https://en.wikipedia.org/wiki/Observation "Observation") and [projection](https://en.wikipedia.org/wiki/Forecasting "Forecasting") of a historical trend. Rather than a [law of physics](https://en.wikipedia.org/wiki/Law_of_physics "Law of physics"), it is an [empirical relationship](https://en.wikipedia.org/wiki/Empirical_relationship "Empirical relationship") linked to [gains from experience](https://en.wikipedia.org/wiki/Wright%27s_Law "Wright's Law") in production.

Wikipedia also mentions 'Quality adjusted price of IT equipment'

> _Quality adjusted price of IT equipment_ – The [price](https://en.wikipedia.org/wiki/Price_index "Price index") of information technology (IT), computers and peripheral equipment, adjusted for quality and inflation, declined 16% per year on average over the five decades from 1959 to 2009.[154](https://en.wikipedia.org/wiki/Moore%27s_law#cite_note-ITprices-157)[155](https://en.wikipedia.org/wiki/Moore%27s_law#cite_note-NambiarPoess-158) The pace accelerated, however, to 23% per year in 1995–1999 triggered by faster IT innovation,[128](https://en.wikipedia.org/wiki/Moore%27s_law#cite_note-Jorgenson01-130) and later, slowed to 2% per year in 2010–2013.

Need to more fully understand what "Private fixed investment, chained price index" means/implies. For now I am trusting the Wikipedia source that this metric is good for assessing the relative cost of Information Technology, specifically computational IT capital.

![[Pasted image 20230921143503.png]]

Relatively immense drop off from the beginning of U.S. Bureau of Economic Analysis recording to approximately 1963. Dwarfs marginal gains as far back as 1968 and beyond.

![[Pasted image 20230921143239.png]]

Zooming in on 1980-Present, we can see again that marginal reduction in cost from 1995 onwards is dwarfed by reduction from 1980-1995.

![[Pasted image 20230921143419.png]]

Finally, zooming in on 2001 to present we can see that the marginal reductions of computing cost from 2002-2008, again, relatively dwarf the marginal reductions from 2002-Present, we even see (though perhaps subtle and attributable to noise) slight deviation upward in 2022.

What does this mean? Are we in a 'zero-cost' computing climate? Do externalities now represent the primary 'cost' of computing?

This crosses a lot of wires in my brain. On the one hand I anecdotally know -which is to say I really don't know at all, 'I've heard'- that compute resources have become cheap, or at least whatever we've defined as 'compute resources'... what have we defined that as? Measure of FLOP processing power?

#### Unanswered Questions, Unsupported Assertions, Vague Language:
"Taking into consideration known outcomes" - I mentioned known outcomes, but none specifically. This was mostly to imply 'we can perform retrospective analysis on specific outcomes we want to evaluate'

What constitutes Retail Trade in 'Business Applications: Retail Trade in the United States'? 
	Guess: NAICS groups

What constitutes 'Business Application'
	Answer: applications for an Employer Identification Number (EIN). Includes all applications for an EIN, except for applications for tax liens, estates, trusts, certain financial filings, applications outside of the 50 states and DC or with no state-county geocodes, applications with certain NAICS codes in sector 11 (agriculture, forestry, fishing and hunting) or 92 (public administration) that have low transition rates, and applications in certain industries (e.g. private households, civic and social organizations).

[[How can I model /approximate VC funding?]]

How can I asses the validity of the statement "startups aren't tied to VC the way they were 10 years ago"?

I fail to define 'Impact', but this is such a generality, I won't break it down into a single question like 'what is an impactful startup?', that would be a think piece on its own.

What precisely does "Private fixed investment, chained price index" measure?

I used 'marginal' incorrectly, maybe every time I used it. I was doing timeseries analysis, not marginal cost analysis. What verbiage makes sense to convey 'a drastic reduction in absolute change to cost over time'?

#### Tasks:
- Find an acceptable definition of compute resources, ideally from top educational institution, or top private sector institution.
