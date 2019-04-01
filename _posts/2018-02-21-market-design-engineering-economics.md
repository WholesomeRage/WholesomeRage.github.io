---
layout: "post"
title: "Market Design: Engineering Economics"
date: 2018-02-21 09:02:00 -0700
author: Wholesome Rage
categories: [Economics]
excerpt_separator: <!--more-->

# Contributor stuff
contributor: false
---

I’ve had a hard time figuring out what I want WholesomeRage to be about, really. Generalize or specialize? And the more I think about it, the more I come to the conclusion that my skillset is just… being very interested in things most people would find boring, and making them interesting for you as well.

Economics is a wonderfully rich field for that.

I’ve found over the last year or so that more than any other field, more than communications or politics, economics seems to be the best at explaining human behavior at the macro level. At explaining why _cities_ feel like they have distinct personalities, why _countries_feel like they have moods.

In the words of an economist I know; “It turns out that “Don’t hate the player, hate the game” is one of the most important insights to have to really understand society."

<!--more-->

Everything we see as a society seems to spring forth from a central premise; _Who gets What and Why_.

This is the title of a book by Alvin E Roth, a Nobel Prize winner of Economics. His work is largely on matchmaking marketplace design, that is, designing markets where money is not an option. If you’ve read the book, then a lot of this article might end up seeming familiar to you, because it’s been rather difficult for me to find better examples than he used… or worse still, papers on the subject that don’t have his name on it.

As a result, if this short summary I give ends up interesting you, I recommend the book itself for going into far more detail than this highlight reel.

His work is fascinating, to me, because Roth is what is in common between kidney transplants, school district management and medical internships.

All are marketplaces, and what is economics if not the allocation of scarce resources?However, no money can change hands to help sort these transactions. Matches need to be made.

Matchmaking is an interesting thing to study in economics. How does each vacancy find the best candidate to fill an open position, while every candidate finds the best open position that they can get?

When there are limited jobs, or limited applicants, then people who get matched by a system who could find a better match on their own are known as a blocking pair — they’re not only unhappy, but they’re preventing a happier match being made.

So how would you design a system that makes it so there are no blocking pairs? Everyone in the system has the best placement they could get? No employee could get a better job offer than the one they end up with, and no job could get a better employee than the one they’ve taken on?

Since the early 20th century, doctors have needed to go through an internship, or residency. There’s a lot of pressure on both sides, as the doctors want to get the best residency they can to start their career, and the hospitals want the most qualified medical students they can get to fill out their labour force.

The doctors want the best hospitals they can get. The hospitals want the best doctors they can get. And if either can find better outside of the matching system, the matching system will break down.

So why’s having that system important? Why not have everyone just find the best match they can make independently, like job hunters do in the open market?

It’s because it comes down to a matter of _timing_. When a market is time critical — like getting medical interns out of a graduation intake — then there becomes more and more advantage to individual actors making strategic choices in their own best interest.

Usually this takes place by the hospitals that aren’t _the best_, but very high up — consistently, people’s second or third preference — trying to give take-it-or-leave it offers to medical students _before_ graduation; If you take the offer now you get taken out of the matchmaking system, so you don’t have the opportunity to have a better position you _might_ get, but you’re guaranteed a ‘safe’ choice at an almost-as-prestigious institution.

The key point is that they’ve bypassed the system by picking students earlier, before graduation. The market, as this _is_ a market, reacts accordingly. Other schools start making offers earlier still, resorting to speculation: They’re willing to take more of a risk on earlier students if it means that otherwise all the good ones are taken by other institutions before graduation.

Eventually you get to a point where first and second year medical students are getting ‘exploding’ — that is, take-it-or-leave-it, time-restricted — offers before they even know if they’re going to make it through to graduation or not.

When this happens, it’s said that the market has _unravelled_. If there is no trust in the system, people resort to strategic choices, and while those strategic choices might benefit individual actors, it’s to the detriment of the marketplace.

Another example of market unravelling would be for college football. [Consider football scholarships from three competing universities being made to a 14 year old.](https://www.theroot.com/8th-grader-gets-football-scholarship-offers-to-alabama-1797274636)

There are other ways a market can fail when it forces its users to make strategic choices. One of the practical problems Roth solved was the New York school allocation system.

The system worked like this; Students put in their first preference, second preference, third, fourth and fifth for the school they wanted.

There was one round of intake. All schools took offers from first preference, and the more prestigious or desirable institutions filled their seats. Students either got their first preference, or they were moved on to their second.

Second round — but some schools had filled most of their seats with the first preference intake.

Third round, fourth round, fifth round…

And we find a lot of blocking pairs, and some 30,000 kids unallocated and needing to be placed by the administration in remaining open seats.

You see the problem, then. And, of course, principals frequently lied about the amount of seats they had and filled them outside the system, talking to parents directly. Other schools, like Aviation Academy — a dedicated school for those who wish to go into aviation, naturally — might not be someone’s first preference, but if they have any interest in it at all they _have_ to put it as first… and be snubbed by the better school they actually wanted, for not putting them as their real first preference.

Say you have a brilliant student who wants to take a shot at the best school they can, and they _just_ fall short. If they’d put their second preference first, they’d have gotten that instead. Now, though, at the second intake their second preference is already full. And their third preference fills in _this_ round…

It was a mess.

It wasn’t safe for students to put their true preferences down — they knew had to put ‘safe’ choices, and either settle or end up with even worse choices for their ambition.

In one year, Roth and his colleagues got that number of unassigned 30,000 down to just 3,000.

[Here’s a paper he did on it, it’s pretty swell.](https://dash.harvard.edu/bitstream/handle/1/2579651/Roth_Deferred%20Acceptance.pdf?sequence=2)

I’ll instead quote his summary from _Who Gets What and Why;_

> _Step 0. Applicants and employers privately submit preferences to a clearinghouse in the form of rank order lists._
>
> _Step 1. Each employer offers jobs to its top-choice candidates, up to the number of its available positions. Each applicant looks at all the offers he or she has received, tentatively accepts the best one (the one highest on her preference list), and rejects any others (including any offers of jobs that were judged unacceptable and left off the applicant__’s rank order list)._
>
> _Step n. Each employer that had a job offer rejected in the previous step offers that job to its next choice, if one remains. Each applicant considers the offer he or she has been holding together with his or her new offer(s) and tentatively accepts the most preferred (highest-ranked) of these. The applicant rejects any remaining offers — including possibly the one that had been tentatively accepted earlier but is no longer the best offer received. (Note that applicants take no account of the step of the algorithm in which an offer was received; they look only at whether they prefer it to their other offers.)_
>
> _The algorithm ends when no offer is rejected, so that no firm wants to make any additional offers. At that point, each applicant and employer is (finally) matched by having each applicant accept whatever offer he or she had most recently tentatively accepted. That is, all acceptances are deferred until the end, when no more offers are forthcoming._

Now, he said this about the residency matching program he helped redesign in 1999, which is why the keywords here are employers and applicants instead of students and schools…

But it’s the same underlying formula he used to help update the New York school system as well.

The important idea here is that this creates only stable pairs; any hospital that would prefer a better candidate doesn’t get him because he accepted a better offer, any candidate that would want a better hospital placement didn’t get the offer because that hospital filled all its openings before giving him one.

No doctor can find a better hospital that would _also_ prefer him. There are no blocking pairs, only stable matches.

Let’s use the school system as our example _here_ though.

Again, I’ll quote _Who Gets What And Why_, (pp. 155-157)

> _Consider two fictional brothers, Amos and Zach. Amos applied to enter high school in 2003, the last year of the old system, while Zach applied to enter in 2004, the first year the new system was used. Amos's first choice was Townsend Harris, in Queens, a selective high school that, under the old system, considered only applicants who ranked it first. Amos’s second choice was another selective school, the Beacon School, in Manhattan, near his mom’s office, which also considered only students who listed it first. His third choice was Cardozo, near his home in Queens. His fourth choice was Forest Hills, also in Queens._
>
> _Amos understood that he was wasting a choice if he applied to both Townsend Harris and Beacon, since whichever one he didn’t list first wouldn’t even consider him. So he listed Townsend Harris first, Cardozo second, and Forest Hills third. He just missed getting into Townsend Harris and was admitted to Cardozo, his third choice, which he listed second. Because his grades were high, he was spared the anxiety and uncertainty of being wait-listed into the summer._
>
> _Zach, applying the next year, knew that the schools wouldn’t see where he ranked them and couldn’t penalize him for not ranking them first. So he listed his choices in the true order of his preferences, which were the same as his brother’s: Townsend Harris, Beacon, Cardozo, and Forest Hills. (Just to be sure that he will be admitted somewhere, he listed a bunch more, although with his high grades, he wasn’t too worried.)_
>
> _Once again, Townsend Harris got many more applications than it had places, and Zach, like Amos, just missed the cut. So at the next step of the new algorithm, he automatically applied to Beacon. Beacon was also a very popular school, which under the old system used to receive about 1,300 applicants for its 150 places, so in the first step of the deferred acceptance algorithm, it rejected all but its top 150 applicants. But since acceptance was now deferred, Beacon didn’t yet accept those kids who applied in step 1. When Zach applied, it compared him with the 150 who hadn’t been rejected in step 1 and anyone else who applied in step 2, ranked them all, and rejected all but the top 150 of this new group._
>
> _Zach wasn’t rejected in the second step nor in any subsequent step. And when the algorithm ended, he was accepted by Beacon. Unlike his brother, he could safely list his true preferences, putting Beacon second. That didn’t interfere at all with his chance of getting admitted there after his rejection by Townsend Harris._
>
> _When students can list as many choices as they want, the deferred acceptance algorithm allows them to safely list schools in true order of preference; they won’t lose a place just because someone else applied earlier in the algorithm. This works because even if a student doesn’t get into her first-choice school, she has just as much chance of getting into her second-choice school as if she had listed it first._

Honestly, I feel bad about how much this article is just quoting Roth, but this one section here, more than any other, is when I decided I had to write this in the first place.

The original version of this algorithm was codified by David Gale and Lloyd Shapley, and David Gale is also known as one of the most important founding fathers of game theory.

Game theory is a bit like Nietzsche to me; Genuinely brilliant, important ideas that are unfortunately forever associated in my mind with assholes and teenagers misrepresenting them on the internet.

But game theory is important here, because it accounts for human behaviour in flawed algorithms like this. Looking at a purely logical model here would see Amos list his true preferences, and be punished for them.

Instead we see the behavior of people _in_ those systems change to accommodate those flaws, to make strategic choices; Putting his third choice as second. Gaming the system, as it were.

What’s interesting is that models and systems incentivize and reward different behaviours. Flawed systems will not only disenfranchise the people who it fails, but it will reward those who are willing to act outside the system.

The only way to ensure cheaters never prosper is to figure out how to _make_ cheating less prosperous.

In the above example, if Amos’ parents had called up Beacon, they might have found he was more desirable than another student they’d taken on. Amos would get his spot, in _spite_ of the system — a blocking pair has been unblocked. In turn, though, Beacon would have to clear one of its seats or, having no faith in the system itself, had simply withheld seats having predicted this situation.

This often turned out to be the case. Until the deferred-acceptance algorithm model was used, principals routinely lied about the places they had to fill in anticipation of these events. Afterwards they were far more forthcoming about the actual number of places for the simple reason that the system filled them better than they themselves could.

A good system rewards good behaviour and punishes bad behaviour, and a flawed system inverts that.

I think that’s the core of what I’m getting at here, and why economics has been so interesting to me recently. It studies the environment and incentive structure of society, and those incentives in turn shape what that society will become.

A Colonel I once talked to explained that the thing he learned most from the military was that you get what you incentivize.

He gave an example of… it’s not quite unravelling, like I talked about above, but it’s fairly similar to it in an interesting way.

You see, to get promoted to Colonel, you have to have a Masters degree in something. Anything. It was just important that you proved you could handle higher education, and to encourage a diverse range of specialties and general knowledge in officers. Overall a pretty cool initiative.

However, people started getting their degrees at lower ranks, like Captain. And soon you looked like the odd one out to be in the minority of your intake to not have your Masters yet, even though it was only intended for Colonels and above (O-6).

This trickled down, as if you don’t pass muster on your first round of promotion, then your odds drop _significantly, _sometimes less than a tenth of what they were the first time.

This led to a perverse incentive; At the lower ranks, more time was being spent on the degree than on their military career, since the degree was becoming the more visible metric of success.

So, now, you can’t see whether or not someone has their Masters _until_ their O-6 promotion, thus making the incentive to get it before then nullified.

Honestly, that’s a fantastic summary of why Roth’s work is so appealing to me.

What Roth boils down to is explaining why people behave badly in bad systems, and how instead of punishing people who act outside those systems, work out how that system has failed them and seek to fix it.

In the case of the school system, principals worked outside of it by withholding seats, and giving them to parents who placed direct calls when their more ‘desirable’ child got allocated their ‘safe’ preference. In the internship scheme, offers were made earlier and earlier to students until there was no certainty of what their abilities would be by the time they graduated, if they made it that far at all.

This doesn’t benefit anyone, but to _not_ cheat is to suffer worst.

Roth is very critical of what libertarians would call the free market. Indeed, he cites a quote by Friedrich Hayek, an incredibly influental libertarian economist;

> “Probably nothing has done so much harm to the liberal cause as the wooden insistence of some liberals on certain rules of thumb, above all the principle of laissez faire.”

Roth adds, critically; As in a garden, only some plants grow without any help at all, and some of those are weeds.

Working out the incentives society offers, and how to cultivate those incentives, seems to me to be one of the most important endeavours we as a society can undertake.

Science and industry have come a long way to reducing the scarcity of resources, of how we produce and reproduce them, but it is economics that dictates how those resources are allocated, and whose lives are actually improved (and by how much) by those resources.

Looking at Roth’s work is beautiful because it shows, at its core, why simply letting everyone be a free agent in a marketplace isn’t necessarily good — and is often terrible — market design, and why it harms the marketplace.

Scott Alexander, in his fantastic article “Non-Libertarian FAQ 2.0”, gives an evocative allegory on why every individual acting in their own best interest can be detrimental to the health of the marketplace;

> _As a thought experiment, let__’s consider aquaculture (fish farming) in a lake. Imagine a lake with a thousand identical fish farms owned by a thousand competing companies. Each fish farm earns a profit of $1000/month. For a while, all is well._
>
> _But each fish farm produces waste, which fouls the water in the lake. Let__’s say each fish farm produces enough pollution to lower productivity in the lake by $1/month._
>
> _A thousand fish farms produce enough waste to lower productivity by $1000/month, meaning none of the fish farms are making any money. Capitalism to the rescue: someone invents a complex filtering system that removes waste products. It costs $300/month to operate. All fish farms voluntarily install it, the pollution ends, and the fish farms are now making a profit of $700/month – still a respectable sum._
>
> _But one farmer (let__’s call him Steve) gets tired of spending the money to operate his filter. Now one fish farm worth of waste is polluting the lake, lowering productivity by $1. Steve earns $999 profit, and everyone else earns $699 profit._
>
> _Everyone else sees Steve is much more profitable than they are, because he__’s not spending the maintenance costs on his filter. They disconnect their filters too._
>
> _Once four hundred people disconnect their filters, Steve is earning $600/month – less than he would be if he and everyone else had kept their filters on! And the poor virtuous filter users are only making $300. Steve goes around to everyone, saying __“Wait! We all need to make a voluntary pact to use filters! Otherwise, everyone’s productivity goes down.”_
>
> _Everyone agrees with him, and they all sign the Filter Pact, except one person who is sort of a jerk. Let__’s call him Mike. Now everyone is back using filters again, except Mike. Mike earns $999/month, and everyone else earns $699/month. Slowly, people start thinking they too should be getting big bucks like Mike, and disconnect their filter for $300 extra profit…_
>
> _A self-interested person never has any incentive to use a filter. A self-interested person has some incentive to sign a pact to make everyone use a filter, but in many cases has a stronger incentive to wait for everyone else to sign such a pact but opt out himself. This can lead to an undesirable equilibrium in which no one will sign such a pact._

That’s the challenge of market design we’re up against here; How do you design a system that can’t be gamed. That is, how do you make it so that everyone acting within the system is more beneficial than anyone trying to find a better option outside of it?

So here we, again, come back to what I was saying at the beginning of this.

Economics, I think, is not only one of the most interesting ways to understand human nature at the macro scale, but when you look at examples of market design and the mathematics behind it, you also find that you have in it a toolset that can _influence_ behaviour as well, not just explain it. So economics becomes important and interesting to study when you can identify what behaviours are being incentivized in the society we live in, and why.

And with Roth’s works you can see that better systems that encourage better behaviour _are_ better for everyone.

I’ll be picking up on this another time, but understanding the cleverness of solutions to market design when money is off the table seems a good springboard to understanding why it should be seen as beneficial in circumstances where money _is_ involved.

There’s a currently growing segment of the population that believes in smaller government, less intervention, and a ‘hands off’ approach to the economy. Of running the government like a business.

But understanding the significance of market design in these smaller, simpler ways should show why that can be devastating or detrimental to the very economies you’re trying to bolster with these hands-off policies. It should also show off the absolute cleverness and brilliance engineers can have when it comes to implementing these solutions, when given the chance.

I think it’s also a good piece of advice to give writers, too, when worldbuilding. If you want your world to breathe, to feel lived in, what kind of people do you want in it? And how is the world encouraging or rewarding that behaviour?