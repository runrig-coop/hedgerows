---
path: "/hedgerows-draft"
date: "2023-10-08"
title: "Hedgerows in the Sky"
subtitle: "Concerning knowledge enclosures and how they may be truly leveled"
---

# Hedgerows in the Sky
When I tell people I make free and open source software (FOSS) for farmers...

<!-- TODO: Introduction -->

## The Gathering for Open Agricultural Technology
A little over a year ago, I sat with a dozen or so engineers, agronomists,
designers and soil scientists, clustered around a couple hastily arranged
tables. It was an "unconference"[^unconf] session titled "Justice for
Nature."[^J4N] Across the wide, high-ceilinged hall and its adjoining patios,
three or four similar groups convened on topics ranging from semantic data
formats to climate resilience. Two or three people would periodically split off
to pursue a tangent idea before rejoining the larger group, while others hung in
loose orbit between the scattered tables, occasionally leaning in to pick up the
main thread of one conversation or another. Two days earlier we had all
converged on the Omega Center in Rhinebeck, NY for the second ever large-scale
Gathering for Open Agricultural Technology — GOAT 2022, for short.

[^unconf]: https://web.archive.org/web/20191208123152/http://unconference.net/unconferencing-how-to-prepare-to-attend-an-unconference/
[^J4N]: https://forum.goatech.org/t/session-J4N/1340

I had been there for the first such gathering in 2018. It had a profound effect
on me, the kind of "found my people" moment you're lucky to have only once or
twice in a lifetime. Back then, our talk centered around how best to convince
farmers of the benefits of open source software, along with perennial issues
like interoperability and design methods. When I arrived this time, I didn't
expect a second life-altering event, but in those three days I had witnessed a
new shared awareness emerging about the role of the commons in both agriculture
and technology. Four years of accelerating climate change, ongoing police
violence, supply chain disruptions, housing shortages, and a global pandemic had
clearly shifted our attentions.

It was during the Justice for Nature session that Samuel Oslund, an independent
researcher then at the CAPÉ[^CAPE] farming cooperative in Île de Montréal,
directed the conversation towards the Amish _Ordnung_. In essence, _Ordnung_ is
a code of conduct or rules each community formulates for itself. It does not ban
technology outright, but prescribes a selection process that may include
evaluation by community elders, probationary trial periods, and group consensus.
From our superficial understanding, we saw it as a means of socializing
technology adoption, with localized control and intent. The entire community
took ownership of any externalities (if they could still be called that), and
through collective action they could adjust course at any time. Sam's comments
yielded the following prompt from our facilitator, Dr. LaKisha Odom, Scientific
Program Director at FFAR:[^LaKisha] "Could GOAT develop a technological
assessment framework to help developers consider the impacts of their
technologies on nature?"

[^LaKisha]: https://foundationfar.org/about/people/lakisha-odom/
[^CAPE]: https://cape.coop/

The response that stood out to me most came from Genna Fudin, an OpenTEAM Fellow
working with Quivira Coalition and Point Blue Conservation Science.[^Genna] She
proposed that technology should seek to expand access to nature and never
restrict it. That did not mean access solely for the individual user, or even
all humanity, but for every living thing on the planet. Her remarks struck me
like a bolt, catalyzing an array of ideas that had been swimming around my head
over the last three days, finally snapping them into place. I struggled to
articulate it, so I asked to read aloud some antiquated English folk poetry,
which I'd been mulling over earlier in the week.

[^Genna]: https://openteam.community/genna-fudin-openteam-fellow-shares-reflections-thus-far/

> The law locks up the man or woman  
> Who steals the goose from off the common  
> But leaves the greater villain loose  
> Who steals the common from off the goose.  

I'd first heard these anonymous lines in an interview with historian Peter
Linebaugh, commemorating the 800th anniversary of _Magna Carta_. He was
discussing its lesser known companion, the _Charter of the Forest_, which
protected the peasantry's rights to forage and graze their animals on common
lands. It was the first time I'd heard the longer history of the English
commons, how it was enshrined in the English constitution and only phased out by
a gradual process called enclosure that took centuries to complete. Enclosure is
exactly what it sounds like: closing off common pasture or forest by means of
fences, hedges or by blocking roads so that it's no longer accessible to the
common peasantry. More recently I was reminded of the poem when Linebaugh
recited it once again in an interview with David Bollier, a fact I would soon
come to realize was no coincidence.

Genna's comments fused together the final conceptual links between enclosure and
the more erudite legal and socioeconomic theories I'd been reading about
recently. There is a strain of communitarian thought, often associated with
Murray Bookchin's theory of social ecology, that draws upon the legal principle
of "usufruct" as an alternative to absolute property rights. It was a concept I
was still struggling to grasp, particularly how the rights of usufruct were
distinguished from real property rights (_jus in re propria_). How I understood
it was that usufruct grants the rightsholder both the free use of an asset as
well as the profits or other material gains that arise from it. These are termed
_usus_ and _fructus_ in civil law, hence _usufruct_. Real property ownership
grants all of that plus the right to the disposal (_abusus_) of the asset. That
can include consuming, selling, irrevocably altering or destroying it.[^jus]

What I struggled with most was this: If someone is entitled to use an asset and
its produce however one saw fit, how did that differ substantially from the
right to sell or consume it? Weren't those just other ways to use it? It seemed
redundant. Perhaps _abusus_ meant the right to "transfer" the other two rights,
_ususus_ and _fructus_, or to otherwise fundamentally alter their terms — was
that it? If so, it seemed an unnecessarily roundabout way to formulate it. Was
it some kind of "meta-right" then, if it was not held with regard to the asset
directly, but was in fact the _right to the rights_ to the asset? That made even
less sense.

[^jus]: In civil or Roman law, the Latin terms would translate:
    [_jus in re propria_](https://www.lsd.law/define/jus-in-re-propria),
    "right to [one's] own thing";
    [_jus utendi_](https://www.lsd.law/define/jus-utendi), "right to use" or literally "the using";
    [_jus in fructu_](https://www.lsd.law/define/in-fructu), "right to the fruit [of a thing]";
    [_jus abutendi_](https://www.lsd.law/define/jus-abutendi), "right to use up" as in "to expend"

Now when I thought about it in the light of universal access to nature, I
remembered the other term for this third right: _alienation_. In a strictly
legal sense, to alienate an asset carries little further significance than to
"dispose of" it, but in a sociological context or in plain parlance, alienation
imbues a psychological or almost spiritual quality. That sense seems all the
more acute when the thing you are alienating is nature itself, even if just a
part of it. There is reciprocity between us and nature, a two-way subjectivity
that transcends the mere owner/asset duality. I belong to nature as much as (or
even more than) nature belongs to me, and to sever that tie would constitute a
terrible injury. A free-market economy, however, requires that elements of
nature comply with the rules of commodity exchange and fungibility. To enclose
nature, therefore, means to fundamentally _set it apart_. Nature becomes an
asset or commodity. It is demoted to an insensible object and is no longer an
equal or true subject. Meanwhile, anyone tied to that chunk of nature is in
essence commodified too. It is a process that cuts both ways, alienating one
from the other. This was certainly the experience of English peasants who were
driven off the commons by enclosure. They were forced to move to urban centers
and sell their labor for a wage in the emerging industrial economy. So not only
was the _ecological value_ of the land commodified and sold, but the very
_social value_ of the peasantry was itself made into a commodity, measured out
by the punch clock and made divisible as wage shares. Wherever the commons was
enclosed, the commoners were duly confined, if not to the factory yard then
invariably to the prison yard.[^vagrancy]

[^vagrancy]: It cannot be overemphasized that this migration was anything but
    voluntary. Already faced with poverty and imminent starvation, landless
    peasants were further compelled into the cities and factories by a series of
    laws known as the Vagabonds Acts (later the Vagrancy Acts). These laws,
    passed in lockstep with enclosure between the 14th and 19th centuries, found
    persons guilty for the crime of "idleness" if they had no deed of property,
    no employer who would vouch for them, and if they could not present any
    other proof of lawful income. Their stipulated punishments ranged from
    imprisonment to whipping, branding, and even death for repeated offenses,
    though prison or execution sentences might be commuted if they agreed to a
    period of indentured servitude. As enforcement became increasingly difficult
    through the course of the Industrial Revolution, they were a significant
    factor contributing to the creation of modern police forces in England and
    elsewhere in Europe, wherever similar legislation prevailed.

## And Geese Will Still a Common Lack...
While the plight of peasants hundreds of years in the past may seem remote to
our modern sensibilities, I think we can still empathize with their position
when we consider how the enclosure of digital spaces has been used to alienate
us from our social relations and the natural world. The natural world is not
limited to the merely physical, but includes things like knowledge, cultural
practices, mental abstractions, and emotional affect states. When these parts of
nature are enclosed by Big Data corporations or the aptly named "walled gardens"
of social media conglomerates, we feel alienated. This alienation, at least
according to one interpretation, can be attributed to the mechanism James
Muldoon calls _data commodity fetishism_, defining it as "the perception of
certain digital relationships between people [...] as having their value based
not on the social relationships themselves but on the data they
produce."[^muldoon] But it goes further than that. Digital enclosures certainly
alienate us from our social relations, but that is just one aspect of the larger
process of our alienation from the natural world as a whole.[^social-ecology]
This extension of data commodification, as applied to nature, could not be more
relevant to agriculture and technology. It gets to the heart of what I think
Genna meant when she suggested farming technology should not restrict "access to
nature."

[^muldoon]: _Platform Socialism_ (Pluto Press, 2022), p. 18. Muldoon explicitly
    refers to the Marxian concept of commodity fetishism, and I am also drawing
    heavily on Marx's theory on the alienation (or estrangement) of labor. The
    _Economic and Philosophic Manuscripts of 1844_ are especially ripe for
    application to today's forms of digital enclosure, and I hope to provide a
    more thorough exploration of those themes in a subsequent essay.

[^social-ecology]: Social ecologists like Murray Bookchin would contend, and I
    agree, that nature does indeed contain both society and technology, though
    it may seem less and less apart of nature today.

The enclosure of the commons in centuries past was achieved in part by acts of
Parliament — in larger part by state-sanctioned violence — but its most visible
manifestation lay in the hedgerows that hemmed in the former commons. Some of
them even persist to this day, emblematic of the English countryside and the
imagined idylls of yesteryear. In their own time, however, they were at once a
symbol of class hierarchy and a physical line of defense, keeping the commoners
off their erstwhile commons, thenceforth the exclusive property of a rising
class of wool barons. Hedgerows represented the alienation of common people from
their land, their social relations, and their traditional ways of farming and
husbandry. I would argue that the most effective means of enclosing knowledge
today — intellectual property, or IP, as it is often called — has been to
consolidate it in vast data centers and server farms owned by just a few tech
monopolies. Property rights can be legislated and service contracts agreed to,
but their final implementation is only achieved in these physical constructs.
Digital enclosure comprises all the silicon, cables, metal, and concrete of
those facilities, just as much as the abstract services and data they carry.
Only then can access be effectively commodified in the form of subscriptions or
advertising fees. The IP owner retains maximum control, with the ability to
revoke access or modify the terms of service at any time, often outpacing legal
authority to do so. This practice goes by many names. The industry jargon is
Software-as-a-Service, or SaaS, while it is marketed to lay users in more poetic
terms: _the cloud_. Opponents of cloud computing and proprietary software have
quipped that this is just a euphemism for "someone else's computer." I would
propose that, trading one grandiose metaphor for another, we instead rebrand the
cloud as the modern form of enclosure it truly is: _hedgerows in the sky_.

The hedgerows that enclosed the English commons of the 16th through 18th
centuries did not go unopposed but were actively resisted over many generations.
The Levellers were among the earliest dissidents for whom any records survive.
They earned that name during the Midland Revolt of 1607 by "leveling" hedgerows
in protest. Though some were drawn and quartered for their actions, they were
never entirely suppressed. Some 40 years later, they were revived as the True
Levellers, or Diggers, led by Gerrard Winstanley to establish a commune on St.
George's Hill in the waning years of the English Revolution. Winstanley's
pamphlets and tales of the Diggers would in turn serve as inspiration to social
movements for centuries to come. The anonymous bard I quoted above, whoever they
might have been, surely knew something of this struggle, and perhaps even
participated in it. Therefore, it's not hard to hear both a warning and a
call-to-arms in their final stanza:

> The law locks up the man or woman  
> Who steals the goose from off the common  
> And geese will still a common lack  
> Till they go and steal it back.  

If we were to heed their call, how would we begin leveling today's hedgerows?

## From Rhinebeck to Durham
I was a bit surprised to realize my ignorance of the parallels between modern
software commons and premodern agricultural commons, but after speaking to
others at GOAT, it became clear I was not alone. This was doubly true with the
concept of enclosure. What was especially embarrassing to me was how many of us
had carved out niche careers straddling both open technology and small-scale
agriculture, spanning decades in some cases, yet few of us had more than a
cursory knowledge of the history of the commons predating the Information Age.

The metaphor of "the commons" has become so pervasive in technology today. The
first time I recall encountering it was from the Free Culture Movement of the
early and mid-2000's. Its most prominent manifestation came in the form of
Creative Commons, but the commons had also become a familiar means of
characterizing crowd-sourced projects like Wikipedia, Flickr and the World Wide
Web itself. The Free Culture Movement first gained momentum in the wake of the
US Copyright Term Extension Act (aka, the Sonny Bono Act) and Digital Millennium
Copyright Act (DMCA), both enacted in 1998. These drew immediate outcry from a
clique of law professors at Duke and Harvard Universities, who specialized in
intellectual property. The outcry became more public and vociferous when the
DMCA was used first to pull the plug on Napster in 2001, followed by its many
file-sharing successors in a decade-long game of whack-a-mole with the RIAA and
MPAA. This was the heyday of the Free Culture Movement. Its unofficial motto,
"Information wants to be free," resonated with anyone who got a cease-and-desist
letter from their Internet provider (myself included) or who merely saw the
futility of police raids on sites like The Pirate Bay, when they'd just be back
up and running within a day or two.

Among the Free Culture Movement's coterie of legal scholars, Lawrence Lessig and
Yochai Benkler were arguably its most visible champions, both hailing from
Harvard's Berkman Klein Center for Internet & Society. In the first few years
their reputations stemmed primarily from the numerous amicus briefs they filed
in support of defendants in copyright infringement cases. Later on, their
published books and several widely viewed TED Talks extended their reach to a
larger audience. For a few short years, concepts like "remix culture" and
"network neutrality" enjoyed a glimmer of popular recognition. In the first
decade of the new millennium, their work certainly raised public awareness of
"the commons" and why it was important. This was particularly true among the
more technologically savvy, but not exclusively. On the other hand, it does not
seem that enclosure enjoyed any wider awareness during that period, at least not
commensurate with the commons. Speaking for myself, I remained oblivious to the
term until I learned it from Linebaugh in 2015. That was a decade after Lessig
cofounded Creative Commons and Benkler had popularized the notion of
"commons-based peer production." For his part, Benkler put both the commons and
enclosure front and center in his earliest essays on the topic, such as "The
Commons As A Neglected Factor of Information Policy" and "Free as the Air to
Common Use: First Amendment Constraints on Enclosure of the Public Domain," from
1998 and 1999, respectively. I haven't found anything more than passing
references to enclosure in Lessig's works. Regardless, it didn't seem to make as
many inroads with technologists the way the commons had.

There were other figures, however, who I don't personally recall from the Free
Culture Movement's highpoint of popularity, and who didn't receive as much
limelight, but who nevertheless turned out to be consequential to the history of
the knowledge commons. First was James Boyle, one of the Duke Law professors
specializing in IP and building on the work of his colleagues at Duke, such as
David Lange and Jerome Reichman. I don't believe I'd encountered Boyle's work
until after GOAT 2022, when I went looking for a deeper understanding of how the
language of the commons came to be embraced by free culture and open source
advocates of the last two decades, while enclosure went comparatively ignored.
As early as 1996, Boyle penned a pivotal work in the study of information
commons, _Shamans, Software, and Spleens_, but it was a later title that jumped
out to me from all the rest: "The Second Enclosure Movement and the Construction
of the Public Domain." The paper began with the epigraph:

> The law locks up the man or woman [...]

Now the pieces were starting to fall into place. I tracked the discourse of
enclosure through Boyle's footnotes, where he acknowledges that "the analogy to
the enclosure movement has been too succulent to resist," and proceeds to give a
laundry list of names from that scholarly milieu who had used it too. Yochai
Benkler was listed there, of course, along with a few more names I was hitherto
unaware of, like Hannibal Travis, whose 1999 _Pirates of the Information
Infrastructure_ is the best combined survey of the pre-industrial enclosure
movement together with this "second enclosure movement," as Boyle calls it.

Boyle also names the aforementioned David Bollier, who would eventually
reintroduce me to Peter Linebaugh's work, but who was also quite active in the
early days of the "blogosphere" and advocating for Internet freedom. He was not
an IP lawyer but rather a co-founder of the Public Knowledge and Commons
Strategies Group. He continues that work at the Schumacher Center for New
Economics where today he directs their Reinventing the Commons Program. In these
roles, he has advanced a much broader vision for the commons, not just for
information but for the commons in all its forms. Accompanying this, he has
articulated a thorough critique of enclosure, in all its manifestations. A
slightly different version of "stealing the commons from off the goose" shows up
as the epigraph to Bollier's _Silent Theft: The Private Plunder of Our Common
Wealth_ in 2002, the same year Boyle published an early draft of his own essay
featuring the poem. As it turns out, Peter Linebaugh also found it "too
succulent to resist" and recycled it once more in the introduction to his 2014
book _Stop, Thief!_. I realize now that Linebaugh must have been winking at
Bollier when prefaced his recitation of the poem as "what you and I know in our
bones."

Apart from being the object in this game of epigraphic hot potato, it's not
surprising that the poem rose to the surface as a shared metaphor in such an
atmosphere of cross-disciplinary collaboration. Looking at the participants list
from the _Conference on the Public Domain_ that was held at Duke Law School in
2001,[^conf-pub-dom] I can't help but speculate who might have first quoted the
goose poem there, and how I may have unwittingly parodied that scene two decades
later in Rhinebeck. Bollier or Boyle were both listed among the participants,
but if it wasn't them there was no shortage of usual suspects. The list also
include Elinor Ostrom, Charlotte Hess, Eben Moglen, John Perry Barlow, Yochai
Benkler, "Larry Lessig," and even Mark Hosler of the band Negativland, who
facilitated a round-table discussion titled "Art Crime / Crime Art." Yet I doubt
it was either Benkler or Lessig who first brought the goose poem to the others'
attention.[^jpb] In those heady post-Cold War days, even liberals like Lessig
and Benkler took Francis Fukuyama's "end of history" as practically axiomatic,
at least in any _serious_ political discourse. With its distinctly revolutionary
tone and the memory of bourgeois enclosures it chronicled, I suspect the poem
may have seemed either too radical or too ridiculous to many in attendance. In
any event, the more celebrated proponents of free culture seem to have shied
away from the metaphors of enclosure, let alone any notion of the commons as
_actual communal land tenure_. Enclosure never gained a foothold in the popular
imagination like the commons did at the height of the Free Culture Movement, no
matter how "irresistibly succulent" it may have first appeared.

[^conf-pub-dom]: The [_Conference on the Public
    Domain_](https://www.tech-insider.org/internet/research/2001/1109.html).
[^jpb]: Nor do I suspect it was John Perry Barlow, but more on that later.

As Bollier points out in _Silent Theft_, by omitting enclosure from the metaphor
of the commons, the adversarial role of markets is conveniently ignored:

> It is important to speak of market enclosure because it reframes the economic
> narrative of the market. What the market considers incidental externalities
> (toxic waste, species extinction, safety hazards), the narrative of the
> commons regards as an assault on the community. Marketeers presume an
> entitlement to privatize clean air and water, public spaces, and even shared
> images and words.

I would go even further to say that this subtle omission of enclosure — and with
it the more tangible aspects of the commons — erases the acts of violence and
the sheer _physical force_ that was required to enclose the commons. Skipping
over that transgenerational struggle not only does an injustice to those who
fought and died for the commons, but also limits our imaginations for what is
possible in our own time.

I want to be clear that neither Benkler nor Lessig were arguing that these
physical aspects did not matter. In _The Wealth of Networks_, Benkler provides a
truly insightful table that breaks down different forms of enclosure in terms of
its physical, logical, and content layers, explicitly borrowing from the OSI
Model for computer networks. And it was Lessig's arguments for the end-to-end
architecture of the Internet, in both physical and logical terms, which first
led me to Boyle's essay on enclosure.

## Free as the Air to Common Use
Nevertheless, today's advocates for free culture and open source software are
still mostly concerned with commoning what is abstract and ephemeral, though
there are significant exceptions I will address later on. The hardware and
infrastructure required to store, process and move information around are
treated as mere accidents or technical details. If they're considered at all
they're taken as inconveniences to be worked around in policy, possibly
subsidized, but never as substantive elements of the knowledge commons in their
own right. Information acquires a supernatural character in this formulation. It
is beyond the encumbrances of the physical world. Even the Swedish police who
raided The Pirate Bay in 2006 had to concede that there were limits to what
could be done to physically impede the flow of information. Information, after
all, wants to be free.

Yet the cost of disregarding information's earthly trappings is borne out by the
way private streaming platforms have nonetheless managed to enclose the
knowledge commons, quite thoroughly and in relatively short time. Jump ahead
twenty years from when it seemed like Napster and torrenting would spell the
death of copyright, we see subscription rates for platforms such as Netflix
steadily rising every year, while fewer titles are available outside premium
plans and mid-roll ads become longer and more frequent. This is how today's big
platforms rake in more revenue than the premium cable channels of yesteryear
ever dreamed was possible. It's also how our common cultural heritage continues
to be enclosed. The DMCA, takedown notices and high profile raids played their
role in all this, of course, but the commons was not lost due to licensing and
regulation alone. In many ways it was precisely because the call for a knowledge
commons stopped there. Beyond the fiber lines and standards like TCP/IP, it fell
short of demanding any kind of public infrastructure that might have held such
enclosures in check. Even the FCC's classification of Internet service providers
(ISPs) as "common carriers," thereby subject to net neutrality regulation, has
been stripped away in the last decade. Meanwhile, physical servers, databases,
and most of all the considerable administration required to maintain those
systems have largely been taken for granted, almost as a fact of nature.

## From Uttar Pradesh to Seattle
Designating something _a fact of nature_ may just as readily cast disdain as
demonstrate reverence. There is no paradox or dialectic at play here, just a
double standard, which is precisely why it has been a favorite rhetorical device
of colonialist projects throughout history. The weaponization of nature in this
way, with dire consequences for property rights, technology, land use, and
agriculture, has been established most conclusively in the writing and activism
of Dr. Vandana Shiva.

Nearly a decade before Benkler, Boyle and Bollier drew the comparison between
copyright expansion and enclosure — reacting as they were to the passage of the
DMCA and Sonny Bono Act of 1998 — Shiva cited the history of enclosure in
response to an even more sweeping expansion of IP rights. Between 1989 and 1993,
a whole suite of international laws, treaties, and free trade agreements were
negotiated that would expand IP rights across borders and around the world. This
was the legal and financial framework that created the World Trade Organization
(WTO), heralding a new era of globalization and unfettered neoliberalism. Shiva
represented the Research Foundation for Science, Technology & Ecology (RFSTE),
an organization comprised of scientists, conservationists, feminists, and
peasant farmers from Uttar Pradesh, India. They resolutely opposed the
environmental degradation and capitalist appropriation the WTO was poised to
accelerate, as the effects were already apparent in their cities and villages.
Among the agreements was a treaty obligation to uphold IP rights granted by
other signatory nations. This was of particular concern to Shiva because
chemical companies were seeking patents that would privatize the genotypes of
plants that Indian farmers had previously bred and cultivated.

The threat was first revealed in the case of neem, a plant endemic to Southeast
Asia. The neem seed produces an oil that can be used as a natural and highly
effective insect repellent, potentially replacing synthetic pesticides. Having
already wreaked ecological havoc upon India, from the Bhopal Disaster to
pesticide-resistant bollworms, U.S. chemical companies now wanted to patent this
plant-based alternative (with active support from the USDA, I might add). When
W.R. Grace & Co. applied, the European Patent Office was only too happy to
oblige and upheld the corporation's claim to the innovation. Despite 2,000 years
of independent seed development by Indian plant breeders, the U.S. conglomerate
would enjoy a monopoly to sell it back to them like coals to Newcastle. In the
process, Grace & Co. would enjoy a hefty profit, while also offsetting any
decline in revenue from their other pesticides due to environmental regulations
or competition from safer alternatives like neem. The patent was eventually
revoked, but only after ten years of relentless legal battles and grassroots
campaigning by Shiva and Navdanya, the successor organization to the
RFSTE.[^biopiracy-campaign]

[^biopiracy-campaign]: Navdanya, ["Biopiracy
    Campaign"](https://navdanya.org/biopiracy-campaign-1). See also _BBC News_,
    ["India wins landmark patent
    battle"](http://news.bbc.co.uk/1/hi/sci/tech/4333627.stm), 2005.

Shiva did not mince words in her denunciation of this new form of enclosure and
the global policy regime that protected it. In her 1997 book, _Biopiracy_, she
decried the inherent hostility to life that hid behind globalization's facade of
free trade, free enterprise, and free markets:

> The freedom that transnational corporations are claiming through intellectual
> property rights protection in the GATT agreement on Trade Related Intellectual
> Property Rights (TRIPs) is the freedom that European colonizers have claimed
> since 1492. Columbus set a precedent when he treated the license to conquer
> non-European peoples as a natural right of European men. The land titles
> issued by the pope through European kings and queens were the first patents.
> The colonizer's freedom was built on the slavery and subjugation of the people
> with original rights to the land. This violent takeover was rendered "natural"
> by defining the colonized people as nature, thus denying them their humanity
> and freedom.

I draw attention to this episode and Shiva's analysis for several reasons. It's
an early instance of the enclosure metaphor being applied to IP rights; that
much is clear:

> Patents on life enclose the creativity inherent to living systems that
> reproduce and multiply in self-organized freedom. They enclose the interior
> spaces of the bodies of women, plants, and animals. They also enclose the free
> spaces of intellectual creativity by transforming publicly generated knowledge
> into private property. Intellectual property rights on life-forms are supposed
> to reward and stimulate creativity. Their impact is actually the opposite — to
> stifle the creativity intrinsic to life-forms and the social production of
> knowledge.

The fact that this enclosure lies at the intersection of agriculture and
technology, settler colonialism and IP rights should also banish any residual
notion that small-scale farming and open source software are unrelated concerns.
The ideological connection between food sovereignty and technology sovereignty
turns out to be nothing new. We may be just now rediscovering that here in
America's coastal cities, but in some parts of the world, and perhaps in farming
communities not so far from our urban centers, that understanding was never
lost.

The precise framing of her analysis, however, carries an insight far more
profound, far more _ontological_ in character, than anything subsequent
commentators on free culture were ready to claim. Shiva certainly acknowledges
the value of the natural world and humanity's ties to it, but she also
highlights how nature itself, at least in its canonically Western conception,
has been used by colonial forces to dispossess indigenous peoples of their land
and resources all across the globe. This "conquest by naturalization," as she
calls it, can be observed as far back as the Papal Bulls of Donation in 1493. To
settle colonial disputes between the Catholic Monarchs of Spain and the King of
Portugal, Pope Alexander VI drew a longitudinal line running down the middle of
the Atlantic Ocean, just slicing off the Nordeste region of modern-day Brasil.
He then "donated" all non-christian peoples and their lands on the left and
right sides of that line to Spain and Portugal, respectively. The papal bulls,
the treaties later negotiated between European courts, and the charters they
granted to private joint stock companies were all the direct predecessors to the
patents and other IP rights recognized by GATT and TRIPs, as Shiva points out.

The contempt European colonialists held for non-christian and indigenous peoples
is abhorrent enough, but Shiva's analysis delves even deeper still. She examines
the metaphysical assumptions, held both then and now, which underpin the moral
arguments used to justify such wide-scale dehumanization. Not only were the
people of the Americas, Africa, Asia, and Oceania relegated to mere _things of
nature_, but nature itself was demoted to an unensouled object, to be set apart
from and dominated by Christ-fearing white men.[^lib-theo]

[^lib-theo]: Varying forms of moral dualism such as this have underpinned
    Western ethics and epistemology since at least the Enlightenment, but it is
    not particular to Christian theology or any other faith system for that
    matter. Known in antiquity as Manichaeism, today it is a common tendency
    among proponents of New Atheism as much as it is among Christian or Hindu
    nationalist sects. On the other hand, a more concordant view of Christian
    society's relationship to both nature and non-believers can be traced from
    the Brethren of the Free Spirit of the High Middle Ages through to Latin
    American liberation theology and the closely related Dalit theology of the
    Indian subcontinent. It has also been expressed by modern European
    theologians, such as Paul Tillich and Elisabeth Schüssler Fiorenza.

To an extent, this Cartesian dualism was quite rigid, with the dividing line
between subject and object hewn razor-thin, but that is not to say it was
immovable. Just like the lines of longitude demarcating colonial holdings were
redrawn over time, from the Bulls of Donation in 1493 to the Treaty of Zaragoza
in 1529, the bounds of what can be deemed insensate nature have shifted ever
since. Today those lines are being redrawn to encompass knowledge and the code
of life itself:

> The assumption of empty lands, _terra nullius_, is now being expanded to
> "empty life," seeds and medicinal plants. The takeover of native resources
> during colonization was justified on the ground that indigenous people did not
> "improve" their land. [...] The same logic is now used to appropriate
> biodiversity from the original owners and innovators by defining their seeds,
> medicinal plants, and medical knowledge as nature, as nonscience, and treating
> the tools of genetic engineering as the yardstick of "improvement." Defining
> Christianity as the only religion, and all other beliefs and cosmologies as
> primitive, finds its parallel in defining commercialized Western science as
> the only science, and all other knowledge as primitive.

Compare this with James Muldoon, writing in 2022, starting from the very next
line I cited above where he defines his concept of "data commodity fetishism:"

> When we understand data as a natural resource we mystify the true source of
> its value in the human activity required to produce it. [...] Data is often
> thought of as an unclaimed good ‘out there’ in a digital _terra nullius_ – an
> empty space in which tech entrepreneurs can assert their rights over this
> seemingly free resource.

Shiva's and Muldoon's observations are divided by a quarter century of
technological development, including the advent of "Big Data" and
multibillion-user social media networks. They address disparate facets of IP
rights, too, from biotech patents to data use agreements. Yet they both identify
these as clear instances of enclosure. Muldoon again:

> There is a historical analogy between the early capitalist enclosure of the
> commons and the digital enclosure of the internet by venture capitalists.
> [...] In the case of the digital sphere, Facebook claims ownership over the
> data produced from the daily interactions of our social lives. This data,
> which is co-created by communities of individuals on the social network,
> becomes the exclusive property of Facebook to be analysed and sold as
> advertising commodities. Facebook takes unfair advantage of their position by
> capturing this resource from a digital commons. At the time of the digital
> enclosure, the loss of public goods that would occur was not immediately
> obvious. But as these networks have grown within a privatised system of
> commodification, the extent of the theft is becoming more apparent.

What brings these two perspectives into alignment is a willingness to critique
the neoliberal assumptions underlying these two forms of capital accumulation.
Shiva was a prominent anti-globalization activist. The history of this movement,
sometimes called counter-globalization, was partially obscured after the 2001
attacks on the World Trade Center, despite being so recent, but for roughly a
decade it was perhaps the largest worldwide movement on the left, filling the
breach between the end of the Cold War and the beginning of the so-called "War
on Terror." Shiva was in Seattle on November 30, 1999 when the movement
ostensibly reached its high-water mark. It was certainly the largest upwelling
of anticapitalist sentiment in the U.S. during that decade, the likes of which
would not be seen again until Occupy Wall Street.[^seattle] Muldoon, for his
part, is writing from a distinctly Marxian and autonomist perspective, informed
by the several major financial crises that have taken place since then, as well
as the Occupy and Black Lives Matter movements. He argues to revive the
principles of guild socialism, as formulated by G.D.H. Cole roughly a century
ago, and apply them to modern technology in what Mulddon calls _Platform
Socialism_, which is also the title of his book.

[^seattle]: _Democracy Now!_, ["20 Years After the Battle of Seattle: Vandana
      Shiva & Lori Wallach on Historic 1999 WTO
      Protests"](https://www.democracynow.org/2019/11/27/1999_wto_protests_20_years_later),
      2019 Nov 27.

The 1999 Seattle WTO Protests also stand as a critical inflection point where
the interests and organizing base of technology and farming activists
momentarily fused into a single, coherent political force that acted decidedly
against further enclosure of the global commons. Shiva and the RFSTE were joined
by a wide array of supporters for organic food, small farming, and peasant
rights, all marching to halt the WTO Ministerial Conference. The diversity of
agricultural concerns represented is noteworthy. U.S.-based groups like the Pure
Food Campaign and Family Farm Defenders were mobilized against GMO foods while
also championing small family farms from the Midwest and coastal exurban farming
communities. La Via Campesina was also there in force, demanding equitable land
distribution, fairer wages, and safe working conditions. They were joined by
other groups from the global south like the Food and Allied Workers Union of
South Africa, as well as the Black Farmers and Agriculturalists Association,
hailing from the American South. These last three groups were far more concerned
with issues of social justice, rather than the previous groups' interests in
consumer protections and agrarianism. Nevertheless, they presented a united
front against the powers of global capital and trade. Shiva herself was uniquely
poised to represent a broad spectrum of those interests, as she did the night
after the first day of protests in a packed Seattle Town Hall. She sat
shoulder-to-shoulder with Ralph Nader as they debated against White House Under
Secretary of Commerce David Aaron and Procter and Gamble Director of Global
Policy Scott Miller. The event reached a national audience by means of a live
broadcast on C-SPAN, re-aired periodically over the following days. This is
where many organic food advocates in the U.S. were first introduced to Shiva's
work, as she fired a cascade of withering rebukes at these grandees of
government and industry, all to thunderous applause.

At the same time, a group of independent journalists, media activists, hackers,
and free speech advocates setup shop as the Independent Media Center (IMC) in a
donated storefront at 1415 3rd Avenue. Meanwhile on the web, they made their
home at indymedia.org. While news coverage coming from major U.S. newsrooms was
either non-existent or heavily biased against the protesters, the IMC was
critical in disseminating reports of what was actually taking place. They also
presented this wide swath of environmentalists, trade unionists, and civil
liberty activists for who they really were and what they were demanding, rather
than the image of looters and provocateurs that was shown on the nightly news.
At one point, indymedia.org was receiving more traffic than cnn.com, with 1.5
million unique visitors in its first week. The legacy of the IMC would live on
in the influence it had on the digital media tactics of later movements, and the
IMC itself would continue as an activist hub in Seattle for several years.
Arguably its most lasting influence, however, was in the establishment of sister
IMC's in cities and regions around the world. This was the birth of the
Indymedia network, which at its peak in 2010 comprised as many as 175 centers.
They shared some common open source publishing tools and many were provided with
subdomains, such as barcelona.indymedia.org, but otherwise they were largely
autonomous projects run by local activists in those regions.

## From Davos to the Lacandon Jungle
Indymedia was not principally concerned with open source or free culture issues,
but a few of the individual IMCs offered a glimpse of how the cross-pollination
of free software and food sovereignty could yield unique outcomes. In 2005, some
software developers affiliated with the Portland IMC and People's Food Co-op,
building on the prior work of another engineer/member of The Wedge Co-op in
Minneapolis, open sourced a point-of-sale system dubbed Information Systems 4
Co-ops, or IS4C. As the Portland IMC reported at the time:

> This past Saturday morning, a group of co-op geeks gathered at People's Food
> Co-op and successfully ran IS4C on a Linux box running Ubuntu using MySQL 5
> and PHP 5. Stop the presses. History has been made.[^is4c]

A fork of IS4C is still actively maintained to this day as CORE-POS, stewarded
by the Tech Support Cooperative.[^tech-support-co-op]

[^is4c]: https://web.archive.org/web/20071218073332/http://portland.indymedia.org/en/2005/08/322550.shtml
[^tech-support-co-op]: https://github.com/CORE-POS/IS4C

Apart from forging more diverse alliances, Indymedia also represents an
_ideological_ alternative to the centrist political leanings of free culture,
open source, and online privacy movements. April Glaser, writing for _Logic(s)_
magazine in 2019, places Indymedia and its legacy in stark contrast to advocacy
groups like the Electronic Frontier Foundation (EFF), founded by John Perry
Barlow, the Grateful Dead lyricist turned dotcom bubble booster. She points out
how in the same year that Barlow penned his techno-libertarian manifesto, "A
Declaration of the Independence of Cyberspace," a very different sort of
declaration was being promulgated concerning the potential of cyberspace, this
one coming from the balaclava and bandolier bedecked Subcommandante Marcos of
the Zapatista Army of National Liberation (EZLN). Both the literal and political
climate surrounding their authorship could not have been more dissimilar. Barlow
signed his declaration from Davos in the Swiss Alps on February 8, 1996, having
ostensibly found inspiration in the World Economic Forum he had attended two
days before. On the other hand, the _2nd Declaration of La Realidad_ was Marcos'
valediction to the 42 delegates and roughly 5,000 other activists and
journalists who came from around the world to the "First Intercontinental
Encounter for Humanity and Against Neoliberalism," held in the Lacandon Jungle
of Chiapas, Mexico on August 3, 1996.

Marcos called for "a collective network" of resistance against neoliberalism,
linking  activists from all parts of the globe in these early days of the World
Wide Web. He had already shown himself so adroit at mobilizing international
support through the online publishing of communiques such as this one.[^EZLN]
Glaser observes how "the organizers who went on to build Indymedia heard this
call," some three years prior to the Battle of Seattle. She continues:

> The Indymedia organizers would be the children of Marcos, not Barlow. While
> the two philosophies had points of contact, they came from different places of
> concern. Indymedia activists would agree with the techno-libertarians that
> politicians and police couldn’t be trusted in their networks. But they didn’t
> see cyberspace as an open frontier of _individuals unhindered by governments_.
> Rather, the activists saw cyberspace as a place for _communities_.[^Glaser]

[^EZLN]: https://web.archive.org/web/20181015082155/http:/www.csuchico.edu/zapatist/HTML/Archive/Communiques/ccri_encount_aug.html
[^Glaser]: https://logicmag.io/bodies/another-network-is-possible/

Techno-libertarians, then and now, claim to be building political power from the
ground up, but it's for the sole benefit of isolated individuals. The complete
atomization of society into self-interested agents is not the same as bottom-up
organization. It's a lie that merely enables the top-down exploitation of the
many by the few. Coincidentally, it is the same Balkanized condition that the
thought leaders at Davos tend to mistake for "freedom." It's a corollary of the
_Homo economicus_ fallacy first espoused by utilitarian philosophers almost two
centuries ago and roundly discredited ever since. Dressing the old notion up in
transhumanist cyber-lingo doesn't render it any less fictitious than it makes it
less exploitative.

The anti-globalization organizers, on the other hand, came from small, localized
bases of power, but they also knew that no individual could seriously challenge
the centralized power of global capital alone. Instead, they leveraged their
collective agency and organized their communities. They unequivocally championed
autonomy for individuals at all levels of society, but they would not sacrifice
the autonomy of the _community_ just to preserve some rarefied ideal of absolute
individualism. The activists in Seattle, Chiapas, and Uttar Pradesh wanted
something more than individual freedom; they sought _collective liberation_, and
that meant defending whatever commons still remained, while restoring any that
had already been enclosed.

## Tierra y Libertad
Although the commons had become a byword for free culture and open source
software by the early 2000s, it was a hollow shell of the more ambitious program
for the commons that persisted in other times and places. Perhaps it is to be
expected that Silicon Valley privacy advocates and East Coast legal scholars
dialed back their rhetoric, at least in comparison to the more radical vision of
the commons espoused by anti-imperialist thinkers at the time. By omitting
enclosure and all its antagonisms, however, this anemic account of the commons
lost all its countervailing force and dynamism. The new digital commons was
static, politically neutral, and devoid of material consequence. Immaterial as
it was, it acquiesced so easily to the prevailing neoliberal order, essentially
just another "free gift of nature," as Adam Smith might have called it.

There was surely no want of critical discourse on the commons in other fields at
this time. One only needs to look at how Elinor Ostrom rose to prominence in
those same years, beginning with her highly praised _Governing the Commons_ in
1990, and culminating with the 2009 Nobel Prize in economics for her analysis of
common-pool resources. In 2006 Silvia Federici's groundbreaking work, _Caliban
and the Witch_, forever linked the history of the commons and enclosure to her
Marxist feminist theories of social reproduction and primitive accumulation. It
should also come as no great shock that a wealth of contemporary literature on
the commons emerged from the fields of social ecology and degrowth economics.

Conspicuously absent from this discourse, however, were the local food and
organic farming movements that reached their zenith in the U.S. during this very
same period. Although the free culture and open source movements' conception of
the commons might have been some pretty weak tea, it was at least a vision. To
find any mention of the commons or enclosure from self-proclaimed locavores of
that time would have been a distinct challenge. There certainly wasn't anything
like the rich historical commentaries or nuanced discourse that permeated the
anti-globalization movement.

What's confounding about all of it is that the history of the commons is
essentially an _agrarian history_, yet at the same moment when a revitalized
image of agrarianism was emerging from the organics movement, it was the
technologists, _not_ the agriculturalists, who embraced the metaphor. It
shouldn't be presumed that the proponents of organic food and agriculture lagged
behind the technologists in political sensibility or acumen — far from it. Their
political savvy and organizing ability is attested by the massive public
awareness campaigns they launched[^food-docs] and significant legislative
victories they achieved all throughout the 2000's[^organic-regs]. It's
debateable whether open source and free culture advocates could claim anything
comparable in terms of legislation.[^RHAT]

[^food-docs]: Between 2001 and 2009, _Fast Food Nation_ and _Omnivore's Dilemma_
    both ranked in the top 10 on the NY Times Best Sellers for Non-Fiction while
    their respective film adaptations each enjoyed a major theatrical release.

[^organic-regs]: Looming large among these victories at the dawn of the
    millennium, the USDA's National Organic Program was entered into the
    [Federal Register] on December 21, 2000, with its full suite of regulatory
    measures becoming effective law on February 20, 2001. While it displeased
    many grassroots organic activists for its concessions to Big Ag, it was
    undeniably a win. There were also modest achievements in various Farm Bills
    during this time, though also some setbacks in court, such as the multiple
    rulings in favor of Monsanto's seed patents.

[Federal Register]:
    https://www.federalregister.gov/documents/2000/12/21/00-32257/national-organic-program

[^RHAT]: Apart from the antitrust ruling against Microsoft in 1998, which was
    something of a Pyrrhic victory for open source in the Browser Wars, the most
    significant successes for FOSS were achieved not in Washington, but on Wall
    Street. Red Hat's fabled IPO in 1999 was a bellweather for the eventual
    dominance that Linux would achieve in the realm of cloud computing and other
    technologies deployed at-scale and industry-wide. It's also debateable
    whether free culture made significant gains beyond generally raising
    awareness. Despite a modicum of publicity, the majority of their legal
    battles were still losses.

This may be where the cognitive dissonance arises between these two seemingly
sympathetic movements. In an era of tepid U.S. politics, predicated largely on
consumer protection, both have been portrayed as more or less progressive
movements. This broad assessment, however, smooths over their rugged political
contours. Upon closer inspection, each was internally quite diverse, containing
fractious constituencies who held disparate motivations that were sometimes
directly opposed to one other. Situated amidst the broader context of
contemporary geopolitics, its even harder to ignore the diversity of ideology.
For the technologists, we see this most evidently in the contrasts between
Indymedia and the EFF. If the organic and local food movements correspond to one
of these two fronts, it's undoubtedly the techno-libertarianism side of the
schism. Virginia farmer Joel Salatin, the self-described "Christian libertarian
environmentalist capitalist" and darling of the local food world back then,
makes an excellent stand-in for John Perry Barlow in this regard.

This still begs the question: was there a corresponding collectivist movement in
food and agriculture during this period in the U.S., something analogous to
Indymedia? And if so, where? I've given short shrift to the recent history of
sustainable farming in this essay, and I will have to address those details in a
subsequent essay, since this one is already three times the length I'd
originally intended. For my own understanding, I needed to bring these two
movements to account before I could begin grappling with the more nuanced
aspects of the commons and enclosure. Because I first encountered the commons
through open source software, that's where it made the most sense to begin
unravelling my own associations with the concept.

My personal exploration of the commons is also situated within a specific
community of practice, principally the Gathering for Open Agricultural
Technology, but also Social.Coop and the Skywoman community. I think it's
critical to acknowledge this, because my own understanding, and in fact the very
content of this essay, has proceeded directly from the conversations I've shared
with the people in those communities. Those conversations began long before the
gathering in Rhinebeck in 2022, and have continued right up through the time of
writing this. Whatever criticism I may have expressed regarding sustainable
agriculture or open technology, they did ultimately bring me to this time and
place where such a dialogue was possible. All navel-gazing aside, it's not lost
on me that this environment, the set of social relations, professional ties, and
the friendships of many years that comprise this network of practitioners, is
just as much a part of the commons as anything that can be pushed to a public
GitHub repository or licensed as free software under the GPL.

In the end, the substance of the commons — whether it is physical or abstract,
rivalrous or non-rivalrous, information or land — plays far less a role in
making it a commons than we might think. What matters more is the quality of our
social bonds, how our obligations to each other also strengthen our commitment
to preserve the commons. Enclosure, too, is more than just a simple barrier,
boundary, or hedgerow: it is a severing of the ties that connect us to other
people and to life more generally, while uprooting us from the land and our
sense of place within it. The same is true with the enclosure of knowledge,
which estranges us from the markers of culture and our shared ways of doing
things.

The commons comes about wherever we collectively acknowledge that although we
may use a thing, care for it, and maintain it, that does not give us sole
dominion over it, nor over how others may wish to use it. Saying it like that,
it comes across as a bit of a platitude, but there's a subtly there that eluded
me when I first showed up at GOAT 2022, still struggling to make sense of such
high concepts as usufruct and alienation. The commons is not ours to dispose of
as we wish. We cannot alienate it from ourselves, nor us from it. We partake of
the land or knowledge commons, but ultimately it is something we must give back
to the whole.
