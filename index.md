---
path: "/hedgerows-draft"
date: "2023-10-08"
title: "Hedgerows in the Sky: A Tale of Two Commons"
---

# Hedgerows in the Sky
Today in 2023, the food sovereignty and tech sovereignty movements are united in
the call for more cooperative production methods and a commitment to common-pool
resources. There is an increasing degree of interchange and direct collaboration
between their communities, and clear parallels can be drawn between their
respective practices. One can compare collectivized farm management to
cooperative data trusts; free fridges and other mutual aid food programs to the
communal administration of decentralized social media networks; sliding scale
food coops or CSA solidarity shares to software projects sponsored through
Liberapay, OpenCollective, donate buttons or some combination of crowdfunding
mechanisms.

Turn back the clock by ten or twenty years, however, and those correspondences
were not as conspicuous. While notions of collective autonomy can be insinuated
from the local food and free-culture movements of that era, and indeed many
practitioners were already formulating those concepts within their respective
disciplines, neither food sovereignty nor tech sovereignty had yet gained much
popular recognition. Accordingly, there was very little dialogue between the two
movements, with few opportunities for their divergent fields to collaborate,
share resources or swap notes. The small farming and local food movements of
that era fixated on what was near-at-hand, low-tech, organic, provincial and
professedly slow. Meanwhile, the free-culture and open source movements set
their gaze on global streams of non-rivalrous information, liberated by their
abstractness and cutting-edge technology to travel across all borders,
effortlessly and instantaneously.

This article will examine the convergent evolution of these two movements by
surveying the relevant technological milestones and sociopolitical developments
of the intervening years. For a more subjective view, I offer the story of my
own encounters with each of these movements, while also situating them within
the longer history of agriculture, information technology and the Commons.
Finally, I'll reflect on the latest initiatives that have emerged through their
union and what synergies remain to be explored.

## The Commons Lost
A little over a year ago, I sat with a dozen or so engineers, agronomists,
designers and soil scientists, clustered around a couple hastily arranged
tables. It was an "unconference"[^unconf] session titled "Justice for
Nature."[^J4N] Groups of two or three would periodically split off to pursue a
tangent then rejoin the rest, while others hung in loose orbit around the edges
occasionally leaning in to pick up the main thread of conversation. Across the
wide, high-ceilinged hall and its adjoining patios, three or four similar groups
convened on topics ranging from semantic data formats to climate resilience. Two
days earlier we had all converged on the Omega Center in Rhinebeck, NY for the
second ever large-scale Gathering for Open Agricultural Technology — GOAT 2022,
for short.

[^unconf]: https://web.archive.org/web/20191208123152/http://unconference.net/unconferencing-how-to-prepare-to-attend-an-unconference/
[^J4N]: https://forum.goatech.org/t/session-J4N/1340

I had been there for the first such gathering in 2018. It had a profound effect
on me, the kind of "found my people" moment you're lucky to have only once or
twice in a lifetime. Back then, our conversations centered around how best to
convince farmers of the benefits of open source software, along with perennial
issues like interoperability and design methods. When I arrived this time, I
didn't expect a second life-altering event, but in those three days I had
witnessed a new shared awareness emerging about the role of the commons in both
agriculture and technology. Four years of accelerating climate change, ongoing
police violence, housing shortages, supply chain disruptions and a global
pandemic had clearly shifted our attentions.

Samuel Oslund, then at CAPÉ[^CAPE] and the University of Quebec, directed the
conversation towards the Amish _Ordnung_, in essence a code of conduct or rules
each community formulates for itself. _Ordnung_ does not ban technology
outright, but prescribes a selection process that may include evaluation by
community elders, probationary trial periods, and group consensus. From our
superficial understanding, we saw it as a means of socializing technology
adoption, with localized control and intent. The entire community took ownership
of any externalities (if they could still be called that), and through
collective action they could adjust course at any time. Sam's comments yielded
the following prompt from our facillitator, Dr. LaKisha Odom, Scientific Program
Director at FFAR:[^LaKisha] "Could GOAT develop a technological assessment
framework to help developers consider the impacts of their technologies on
nature?"

[^LaKisha]: https://foundationfar.org/about/people/lakisha-odom/
[^CAPE]: https://cape.coop/

The response that stood out to me most came from Genna Fudin, an OpenTEAM Fellow
working with Quivira Coalition and Point Blue Conservation Science.[^Genna] She
proposed that technology should seek to expand access to nature and never
restrict it. That did not mean access solely for the individual user, or even
all humanity, but for every living thing on the planet. Her remarks struck me
like a bolt, catalyzing an array of ideas that had been swimming around my head
over the last three days, finally snapping them into place. As I struggled to
articulate all of it, I asked to read aloud some antiquated English folk poetry,
which I'd been mulling over earlier in the day.

[^Genna]: https://openteam.community/genna-fudin-openteam-fellow-shares-reflections-thus-far/

> The law locks up the man or woman  
> Who steals the goose from off the common  
> But leaves the greater villain loose  
> Who steals the common from off the goose.  

I'd first heard these anonymous lines in an interview with historian Peter
Linebaugh, commemorating the 800th anniversary of _Magna Carta_. He was
discussing its lesser known companion, the _Charter of the Forest_, which
enshrined the peasantry's rights to forage and graze their animals on common
lands. It was the first time I'd heard the longer history of the English commons
and its eventual enclosure. More recently I was reminded of the poem when
Linebaugh recited it once again in a 2021 podcast interview. The podcast was
_Frontiers in Commoning_, hosted by David Bollier, a fact I would soon come to
realize was no coincidence.

Genna's comments fused the final conceptual linkage between enclosure, as a
plain matter of historical record, and the more erudite legal and socioeconomic
theories I'd been reading about but struggling to grasp. I couldn't really get
my head around the principle of usufruct and its distinction from real property
rights (_jus in re propria_). Usufruct grants the rightsholder both the free use
and the benefits (or "fruits") of an asset, what are termed _usus_ and _fructus_
in civil law, respectively. Real property ownership grants all of that plus the
right to dispose of (_abusus_) the asset however they see fit. That can entail
consuming, selling, irreversibly altering or destroying it.[^jus] This is
also known as the _alienation_ of property in English common law. Now when I
viewed these concepts in light of universal access to nature, I couldn't see how
any one person could be granted exclusive rights of alienation over anything in
nature — at least anything of substantial size — if it was not first enclosed.
The pronouncements of the law are critical to the enforcement of many rights,
but absolute property rights are seldom achieved by fiat alone. Some mechanism
for enclosing the asset almost always seems to accompany legal protections, or
even precede them. This holds true whether the "thing of nature" is a strip of
land closed off by a fence or hedgerow, or intellectual property (IP) like
software or digital media.

[^jus]: In civil or Roman law, the Latin terms would translate:
    [_jus in re propria_](https://www.lsd.law/define/jus-in-re-propria),
    "right to [one's] own thing";
    [_jus utendi_](https://www.lsd.law/define/jus-utendi), "right to use" or literally "the using";
    [_jus in fructu_](https://www.lsd.law/define/in-fructu), "right to the fruit [of a thing]";
    [_jus abutendi_](https://www.lsd.law/define/jus-abutendi), "right to use up" as in "to expend"

The most effective means of enclosing intellectual property, I would argue, has
been to consolidate it in vast data centers and relegate it to the server farms
of tech monopolies. Access can then be sold off in the form of subscriptions or
advertising fees. That way, the IP owner retains maximum control, with the
ability to revoke access or modify the terms of service at any time. This
practice goes by many names. The industry jargon is Software-as-a-Service, or
SaaS, while it is marketed to lay users in more poetic terms: _the Cloud_.
Opponents of cloud computing and proprietary software have quipped that this is
just a euphemism for "someone else's computer." I would propose that, trading
grandiose metaphor for grandiose metaphor, we instead rebrand the cloud as the
modern enclosure it really is: _hedgerows in the sky_.

The hedgerows that enclosed the English commons of the 17th century did not go
unopposed, but were actively resisted over many generations. Among the earliest
of these were the Levellers, who first earned that name during the Midland
Revolt of 1607 by "levelling" hedgerows in protest. Though some were drawn and
quartered for their conscience, their example inspired the True Levellers, and
the Diggers of the English Revolution over 40 years later. The anonymous bard I
quoted above, whoever they were, surely knew something of this resistance, and
perhaps they even participated in it. Therefore, it's not hard to hear both a
warning and a call-to-arms in their final stanza:

> The law locks up the man or woman  
> Who steals the goose from off the common  
> And geese will still a common lack  
> Till they go and steal it back.  

If we were to follow their example, too, how would we begin levelling today's
hedgerows?

## Free Culture
It's surprising I'd remained ignorant to the clear parallels between modern
software commons and premodern agricultural commons, but as I learned and shared
more of the history with my colleagues at GOAT, it became clear I was not alone.
This was doubly true with the concept of enclosure. What was especially
embarrassing to me was how many of us had carved out niche careers straddling
both open technology and small-scale agriculture, spanning decades in some
cases, yet few of us had more than a cursory knowledge of it.

The metaphor of "the commons" has become so pervasive in technology today. The
first time I recall encountering it was from the Free Culture Movement of the
early and mid-2000's. Its most notable manifestation came in the form of
Creative Commons, but the commons had also become a familiar means of
characterizing crowd-sourced projects like Wikipedia, Flickr and the World Wide
Web itself. The Free Culture Movement first gained momentum in the wake of the
US Copyright Term Extension Act (aka, Sonny Bono Act) and Digital Millennium
Copyright Act (DMCA), both enacted in 1998. These drew immediate outcry from a
clique of law professors at Duke and Harvard Universities, who specialized in
intellectual property. The outcry became more public and vociferous when the
DMCA was used first to pull the plug on Napster in 2001, followed by its
successors in a decade-long game of whack-a-mole with the RIAA and MPAA. This
was the heyday of the Free Culture Movement. Its unofficial motto, "Information
wants to be free," resonated with anyone who got a cease-and-desist letter from
their ISP (myself included) or saw the futility of police raids on sites like
The Pirate Bay, when they'd just be back up and running within a day or two.

Among the Free Culture Movement's coterie of legal scholars, Lawrence Lessig and
Yochai Benkler were arguably its most visible champions, both hailing from
Harvard's Berkman Klein Center for Internet & Society. In the first few years
this was largely on account of the numerous amicus briefs they filed in support
of defendants in copyright infringement cases. Later on, their published books
and several widely viewed TED Talks extended their reach to a larger audience.
For a few short years, concepts like "remix culture" and "network neutrality"
enjoyed a glimmer of popular recognition. In the first decade of the new
millennium, their work certainly raised public awareness of "the commons" and
why it was important. This was particularly true among the more technologically
savvy, but not exclusively. However, I don't believe the same was true for
enclosure. Speaking for myself, I remained oblivious to the term until I learned
it from Linebaugh in 2015. That was a decade after Lessig helped to found
Creative Commons and Benkler had popularized the notion of "commons-based peer
production." For his part, Benkler put both the commons enclosure front and
center in his earliest essays on the topic, such as "The Commons As A Neglected
Factor of Information Policy" from 1998 and "Free as the Air to Common Use:
First Amendment Constraints on Enclosure of the Public Domain" from 1999. I
haven't found anything more than passing references to enclosure in Lessig's
works. Regardless, it didn't seem to permeate the public awareness the way the
commons had.

I find the downplay of enclosure significant because it frames the argument for
the commons primarily in the terms of law and policy. With something so
seemingly abstract as the knowledge commons, its physical aspects were
diminished or left unconsidered. How information moved or what restricted it in
practice was left as a matter of nature or mere accident, something to be worked
around in policy. This seemed to be the case even in the enforcement and
extension of IP law, as the Swedish police who raided The Pirate Bay learned
soon after. Reading their work more closely now, I don't believe this was the
point either Benkler or Lessig was trying to make, but I found that sentiment to
be rather pervasive through at least the mid 2010's.

There were two other figures, however, who I don't personally recall from those
early days of the Free Culture Movement, but who turned out to be equally
consequential, even if they did not receive their fair share of the limelight.
First was the aforementioned David Bollier, not a lawyer but an activist and
blogger who would co-found the advocacy group Public Knowledge in 2001. While he
was very active in the early days of advocacy for internet freedoms and
commoning, he clearly had a much broader outlook of the commons and enclosure.
He continues to investigate and write about them to this day, though not
limiting himself to knowledge commons alone. So it is no wonder he was the
conduit that reintroduced me to Peter Linebaugh's work.

Second was James Boyle, one of the Duke Law professors who specialized in IP
jurisprudence along with David Lange and Jerome Reichman. I don't believe I'd
encountered his work until after GOAT 2022, when I went looking for a deeper
understanding of how the language of the commons came to be embraced by free
culture and open source advocates of the last two decades, while enclosure was
largely ignored. As early as 1996, Boyle penned a pivotal work in the study of
information commons, _Shamans, Software, and Spleens_. But after GOAT 2022,, one
title jumped out: "The Second Enclosure Movement and the Construction of the
Public Domain". It was not for the title alone, as much as the paper began with
the epigram:

> The law locks up the man or woman [...]

Now all the pieces were falling into place.
