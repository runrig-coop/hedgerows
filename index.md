---
path: "/hedgerows-draft"
date: "2023-10-08"
title: "Hedgerows in the Sky"
subtitle: "Concerning knowledge enclosures and how they may be truly leveled"
---

# Hedgerows in the Sky
When I tell people I make free and open source software (FOSS) for farmers...

<!-- TODO: Introduction -->

## The Stolen Commons
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
directed the conversation towards the Amish _Ordnung_, in essence a code of
conduct or rules each community formulates for itself. _Ordnung_ does not ban
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
grants all of that plus the right to dispose of the asset (_abusus_). That can
include consuming, selling, irrevocably altering or destroying it.[^jus]

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
invariably to prison yard.[^vagrancy]

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

While the plight of peasants hundreds of years in the past may seem remote to
our modern sensibilities, I think we can still empathize with their position
when we consider how the enclosure of digital spaces has been used to alienate
us from our social relations and the natural world. The natural world is not
limited to the merely physical, but includes things like knowledge, cultural
practices, mental abstractions, and emotional affect states. When these parts of
nature are enclosed by Big Data corporations or the aptly named "walled gardens"
of social media conglomerates, we feel alienated. This is what James Muldoon
calls _data commodity fetishism_, defining it as "the perception of certain
digital relationships between people [...] as having their value based not on
the social relationships themselves but on the data they produce."[^muldoon] But
it goes further than that. Digital enclosures certainly alienate us from our
social relations, but that is just one aspect of the larger process of our
alienation from the natural world as a whole.[^social-ecology] This extension of
data commodification, as applied to nature, could not be more relevant to
agriculture and technology. It gets to the heart of what I think Genna meant
when she suggested farming technology should not restrict "access to nature."

[^muldoon]: _Platform Socialism_ (Pluto Press, 2022), p. 18. Muldoon explicitly
    refers to the Marxian concept of commodity fetishism, and I am also drawing
    heavily on Marx's theory on the alienation (or estrangement) of labor. The
    _Economic and Philosophic Manuscripts of 1844_ are especially ripe for
    application to today's forms of digital enclosure, and I hope to provide a
    more thorough exploration of those themes in a subsequent essay.

[^social-ecology]: Social ecologists like Murray Bookchin would contend, and I
    agree, that nature does indeed contain both society and technology, though
    it may seem less and less apart of nature today.

The enclosure of the commons in centuries past was achieved partly by acts of
Parliament, in larger part by state-sanctioned violence, but its most visible
manifestation lay in the hedgerows planted around common pastures and fields.
Hedgerows evoke bucolic scenes of the English countryside today, but in their
time they were at once an unmistakable symbol of class hierarchy and a physical
line of defense. They represented the alienation of common people from their
land, their social relations, and their traditional ways of farming and
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

## The Forgotten Enclosures
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
this was largely on account of the numerous amicus briefs they filed in support
of defendants in copyright infringement cases. Later on, their published books
and several widely viewed TED Talks extended their reach to a larger audience.
For a few short years, concepts like "remix culture" and "network neutrality"
enjoyed a glimmer of popular recognition. In the first decade of the new
millennium, their work certainly raised public awareness of "the commons" and
why it was important. This was particularly true among the more technologically
savvy, but not exclusively. On the other hand, it does not seem that enclosure
enjoyed any wider awareness during that period, at least not commensurate with
the commons. Speaking for myself, I remained oblivious to the term until I
learned it from Linebaugh in 2015. That was a decade after Lessig cofounded
Creative Commons and Benkler had popularized the notion of "commons-based peer
production." For his part, Benkler put both the commons and enclosure front and
center in his earliest essays on the topic, such as "The Commons As A Neglected
Factor of Information Policy" and "Free as the Air to Common Use: First
Amendment Constraints on Enclosure of the Public Domain," from 1998 and 1999,
respectively. I haven't found anything more than passing references to enclosure
in Lessig's works. Regardless, it didn't seem to make as many inroads with
technologists the way the commons had.

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
early days of the "blogosphere" and advocating for Internet freedom. While he
was not an IP lawyer, he was the co-founder of the advocacy organizations Public
Knowledge and Commons Strategies Group, and today is Director of the Reinventing
the Commons Program at the Schumacher Center for a New Economics. In these
roles, he has advanced a much broader vision for the commons, not just for
information but for the commons in all its forms. Accompanying this, he has
articulated a thorough critique of enclosure, in all its own manifestations. A
slightly different version of "stealing the commons from off the goose" shows up
as the epigraph to Bollier's _Silent Theft: The Private Plunder of Our Common
Wealth_ in 2002, the same year Boyle published an early draft of his own essay
featuring the poem. As it turns out, Peter Linebaugh also found it "too
succulent to resist" and recycled it once more in the introduction to his 2014
book _Stop, Thief!_. Linebaugh was winking at Bollier when he recited it back to
him in their interview, I'm sure.

Apart from being the object in this game of epigraphic hot potato, it's not
surprising that the poem rose to the surface as a shared metaphor in such an
atmosphere of cross-disciplinary collaboration. Looking at the participants list
from the _Conference on the Public Domain_ that was held at Duke Law School in
2001,[^conf-pub-dom] I can't help but speculate who might have first quoted the
goose poem there, and how I may have unwittingly parodied that scene two decades
later in Rhinebeck. If the culprit wasn't Bollier or Boyle, there was certainly
no shortage of other suspects, including Elinor Ostrom, Charlotte Hess, John
Perry Barlow and even Mark Hosler of the band Negativland, who facilitated a
round-table discussion titled "Art Crime / Crime Art." The list also includes
Yochai Benkler and "Larry" Lessig, but somehow I doubt it was either of them who
first brought the goose poem to the others' attention. In those heady post-Cold
War days, even liberals like Lessig and Benkler took Francis Fukuyama's "end of
history" as practically axiomatic, at least in _serious_ political discourse.
With its distinctly revolutionary tone and the memory of bourgeois enclosures it
chronicled, I suspect the poem may have seemed either too radical or too
ridiculous to many in attendance. In any event, the more celebrated proponents
of free culture seem to have shied away from the metaphors of enclosure or
_actual communal land tenure_ when discussing the commons. As the Free Culture
Movement grew over the next decade, the commons may have gained a hold in
popular imaginations, but enclosure decidedly did not, no matter how
"irresistibly succulent" it may have seemed at first.

[^conf-pub-dom]: The [_Conference on the Public
    Domain_](https://www.tech-insider.org/internet/research/2001/1109.html).

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

## The Commons Yet to Be Enclosed
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
peasant farmers. They resolutely opposed the environmental degradation and
capitalist appropriation the WTO was poised to accelerate, as the effects were
already apparent in their cities and villages. Among the agreements was a treaty
obligation to uphold IP rights granted by other signatory nations. This was of
particular concern to Shiva because chemical companies were seeking patents that
would privatize the genotypes of plants that Indian farmers had previously bred
and cultivated.

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
process, global capital would enjoy a hefty profit, while also offsetting any
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
> into private property.

The fact that this enclosure lies at the intersection of agriculture and
technology should also banish any residual notion that small-scale farming and
open source software are unrelated concerns. The ideological connection between
food sovereignty and technology sovereignty turns out to be nothing new. We may
be just now rediscovering that here in America's coastal cities, but in some
parts of the world, and perhaps in farming communities not so far from our urban
centers, that understanding was never lost.

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

[^lib-theo]: It is an unspoken tenet of Western metaphysics that is not particular
to Christian theology or any other faith system, and in fact many streams of
liberation theology within the Catholicism and other sects reject this dualistic
conception of divinely ruled hierarchy.

To an extent, this Cartesian duality was quite rigid, with the dividing line
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
line I cited above, after he defines his concept of "data commodity fetishism:"

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
Shiva was a prominent voice in the strong anti-globalization movement that
filled the breach between the end of the Cold War and the beginning of the
so-called War on Terror. She was in Seattle when it ostensibly reached its
high-water mark in November of 1999, a massive upwelling of anticapitalist
sentiment the likes of which would not be seen again in the U.S. until Occupy
Wall Street.[^seattle] Muldoon, for his part, is writing from a distinctly
Marxian and autonomist perspective. He argues to revive the principles of guild
socialism, as formulated by G.D.H. Cole roughly a century ago, and apply them to
modern technology in what Mulddon calls _Platform Socialism_, adopting that in
fact as the title of his book.

[^seattle]: _Democracy Now!_, ["20 Years After the Battle of Seattle: Vandana
      Shiva & Lori Wallach on Historic 1999 WTO
      Protests"](https://www.democracynow.org/2019/11/27/1999_wto_protests_20_years_later),
      2019 Nov 27.

## Whither the Agricultural Commons?

__MAIN ARC__: Steer this all back to the question: "Even if the open source
community was not so alert to the full dimensionality of the enclosure of
ecological knowledge that was underway at the turn of the millennium, why were
small farmers in the U.S. almost entirely oblivious?"
