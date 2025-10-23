---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.18.1
  kernelspec:
    display_name: Python [conda env:base] *
    language: python
    name: conda-base-py
---

<!-- #region citation-manager={"citations": {"": []}} editable=true slideshow={"slide_type": ""} tags=["title"] -->
# The secularisation of future expectations in practice.
### An empirical study of divine appeals in Early Modern English letters
<!-- #endregion -->

<!-- #region tags=["contributor"] -->
 ### \<author\> 
\<institution\>
<!-- #endregion -->

<!-- #region tags=["copyright"] -->
[![cc-by](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) 
© \<author\>. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY](https://creativecommons.org/licenses/by/4.0/)

<!-- #endregion -->

```python tags=["cover"]
from IPython.display import Image, display

display(Image("./media/glorification_of_st_ursula.jpg"))
# https://grants.fnl.org.uk/paston-letters
#https://artuk.org/discover/artworks/trompe-loeil-letter-rack-138390
```

<!-- #region tags=["keywords"] -->
secularisation, future, providence, letters, Early Modern England
<!-- #endregion -->

<!-- #region tags=["abstract"] -->
In the wake of Reinhart Koselleck’s seminal work on temporality (1979), historians studying past futures in Western Europe have argued that our current understanding of the future dates back to the period between 1500 and 1800. The medieval, Christian conception of time was largely cyclical in nature; the future was, above all, in the hands of God. By 1800 however, the future had become open, uncertain and constructible; people were left with the feeling that time had not only been accelerating, it had also become secularised.
As recent studies have emphasised the gradual nature of this shift, this paper zooms in on the pluritemporal mindscape of early modern societies by charting secular and religious types of future thought in a large body of English letters written between 1450 and 1700. Did fifteenth century people appeal to God more often than seventeenth century people did? In which domains of their lives was religious future thinking the strongest? Did the secularisation of time proceed at the same pace across all communities, despite their differences in religious practice?
We address these questions by querying nearly 5000 early modern letters for divine appeals and systematically annotating them for variables like human and divine agency, temporal orientation and domain of life. Our results indicate that while the more formulaic divine appeals found in the opening and closing sections of letters were growing less popular over time, the ones in the letter bodies fluctuated in particular with the religious denominations of the letter writers. The observed rise in mentions of divine entities in the first half of the seventeenth century is mainly caused by a small group of puritan letter writers whose involvement in the civil wars throughout the 1640 made their lives particularly perilous. The other letter writers in the corpus, by contrast, displayed progressively lower rates of divine appeals as time went by, a finding that is in line with previous research that saw the early modern period as one characterised by the increasing secularisation of future thought as well as a shift from religious practice to religious faith.
<!-- #endregion -->

## Introduction


The future is not doing well. The widespread optimism that characterised the years after the Second World War has made room for bleak prospects of climate disasters (<cite data-cite="9104992/565MC34S"></cite>) and fears of an artificial intelligence apocalypse (<cite data-cite="9104992/HAMQDNSD"></cite>). These bleak scenarios are not just passively anticipated, but they have sparked calls for action to undo existing damage and prevent further aggravations. Groups like Extinction Rebellion are advocating for immediate actions to cut fossil fuels (<cite data-cite="9104992/NLQ2BSM2"></cite>), and some founding fathers of AI are pleading for their inventions to be regulated more strongly (<cite data-cite="9104992/UJZPFUSC"></cite>). Although the idea that we can influence events in the future through our actions in the present seems quite obvious and incontestable to us now, this mindset is a product of its time just like any other cultural construct. The way in which people perceive their own agency in relation to the future is culturally (and therefore temporally) contingent and even has a history of its own.


In his "Futures Past", the German historian Reinhart Koselleck famously argued that our current understanding of the future dates back to the period between 1500 and 1800 (<cite data-cite="9104992/V7FP9RYF"></cite>). The medieval, Christian conception of time was largely cyclical in nature; the future was, above all, in the hands of God. By 1800 however, in the so-called _Sattelzeit_, West-European societies had witnessed a series of socio-political changes that had manifested themselves at an unprecedented pace. Scientific progress had gained ground at the expense of religion and the enlightenment had installed a firm belief that the condition humaine could be improved: the future had become open, uncertain and constructible; people were left with the feeling that time had not only been accelerating, it had also become secularised.


The present study zooms in on English letter writers in the three centuries leading up to Koselleck's _Sattelzeit_, a period characterised by unprecedented change in both political and religious terms. Against this backdrop of crisis and reform, we study the mindscapes of early modern English (wo)men by charting the evolution of religious future thinking in the personal correspondence of over 70 letter writers from roughly 1450 to 1700. Did sixteenth-century people appeal to God more often than their seventeenth-century descendants? In which domains of their lives was religious future thinking the strongest? Did the secularization of their future prospects proceed at the same pace across all writing communities, despite their differences in religious practices and beliefs?


## Who's in charge of the future?


### History/Histories of the future


Since Koselleck first provided the field with a theoretical basis and a terminological framework, the lion’s share of subsequent research on the history of the future has followed in his footprints, either expanding or adapting his  (for an overview, see <cite data-cite="9104992/II3MITMT"></cite>). While this has resulted in a large and valuable body of historical knowledge, it has inevitably left out other aspects that are essential for a profound understanding of how people in the past perceived (their grasp on) the future.


First, most research that has explicitly been embedded in the historiography of future thinking has focused on the distant future. From prophesies (<cite data-cite="9104992/T4P65SU6"></cite>) and predicted apocalypses (<cite data-cite="9104992/HCHHABPR"></cite>, <cite data-cite="9104992/D72XVHBJ"></cite>) over utopias (<cite data-cite="9104992/DXWHJ7J2"></cite>) and the new, statistically inspired economic models developed during the French Revolution (<cite data-cite="9104992/D4X2Y3H9"></cite>), what is at stake is “The Future” of humankind as a whole. The short-term future, by contrast, has only very recently been brought into the limelight of scholarly scrutiny. One notable example of this is Baker's study of the future perceptions of merchants in Renaissance Italy, which zooms in on the merchants' eschatological expectations just as well as on the short-term futures of their everyday life – planning for the next meal, travelling to a meeting, anticipating how a political event might affect one's business (<cite data-cite="9104992/4MVVYNRR"></cite>).


A second and related aspect pertains to the empirical foundations of the _Sattelzeit_ narrative. Many analyses, either by Koselleck himself or written in his aftermath, are underpinned by sources that were created explicitly with the future in mind. While the range of consulted sources is very broad (poetic literature (<cite data-cite="9104992/343VU3R4"></cite>), prophesies (<cite data-cite="9104992/T4P65SU6"></cite>), projects (<cite data-cite="9104992/WCST6SSF"></cite>), utopian literature (<cite data-cite="9104992/DXWHJ7J2"></cite>), testaments and wills (<cite data-cite="9104992/6N7JY7I6"></cite>) etc.), they poorly reflect the full range of people's attitudes towards their futures. The futures of daily life, for example, can be reconstructed more easily through a systematic analysis of source material that contains implicit references to people’s future perceptions, but that has not been developed with an eye on the future per se. Some, very recent works that do just that include Baker’s survey of Italian merchants (<cite data-cite="9104992/4MVVYNRR"></cite>), Dekker’s analysis of epidemics in chronicles (<cite data-cite="9104992/U4YDTWUS"></cite>) and Van Eijnatten and Huijnen’s digital study on the uses of the future in Dutch parliamentary debates (<cite data-cite="9104992/T46TCSEE"></cite>).


A third aspect that has been relatively unexplored so far is the social variation in future thinking. Even though the various textual sources that have been studied had been written with potentially very different audiences in mind, the future perceptions of  learned men have gained significantly more scholarly attention than the future thoughts and practices of everyone else.



Fourthly and finally, the Sattelzeit has been criticised for its (overly) strict timing. Recent studies have predominantly emphasised the gradual nature of this shift. The inescapability of the future in Marxist theory, for instance, clearly shows that millenarist and apocalyptic ideas lingered until well into the nineteenth century, even if they are secular ones (<cite data-cite="9104992/QKCHY66H"></cite>). Similarly, upon realising that the scientific innovations of the eighteenth century did not significantly reduce natural disasters, statisticians and scientists kept a religious faith in their work (<cite data-cite="9104992/KGBC99VK"></cite>). In the early modern period too, the majority of early modern chronicles reported both natural and divine explanations for epidemics, comfortably mixing religious and non-religious factors (<cite data-cite="9104992/U4YDTWUS"></cite>). In Alexandra Walsham’s words, "accepting a providential explanation for a devastating blaze or flood did not preclude the development of formal preventive measures, building by-laws, fire-fighting equipment, and other damage-limitation techniques. 'Religious' interpretations and ‘rationalist’ reactions were by no means incompatible (<cite data-cite="9104992/K6PCJNWF"></cite>, 148)."



On a theoretical level, this co-existence of a secular and religious understanding of the world ties in with the notion of pluritemporality, a concept that frames time as a constellation of coexisting and interpenetrating layers of temporal experience and, as such, urges the historian to study and chart the temporal experiences of people holistically, in all their variation (<cite data-cite="9104992/RE4HRMCE"></cite>, <cite data-cite="9104992/WBGD9IXK"></cite>). This approach underpins, for instance, Baker’s finding that the future orientation of merchants in renaissance Italy was an amalgam of various layers of future thinking (<cite data-cite="9104992/4MVVYNRR"></cite>).



### Secularisation and Reformation in early modern England


Few processes have been studied as extensively as secularisation, by sociologists, theologians and historians alike. While the concept of secularisation as a universal and linear movement towards less religiosity has been contested (<cite data-cite="9104992/CM8W4WS2"></cite>, <cite data-cite="9104992/DJG7VL7G"></cite>, <cite data-cite="9104992/KJY6LFDX"></cite> and <cite data-cite="9104992/6IX9C7NU"></cite>), a weaker version of the concept is indispensable to anyone who studies the future perceptions of early modern people and those of their medieval ancestors. 


Following Somerville, this paper understands secularisation as a process that operates at various layers of granularity, targeting societies as a whole as much as the individuals within them. The secularisation of a whole society involves a “process of institutional differentiation” (<cite data-cite="9104992/ZAW8JW29"></cite>, 5) whereby religion gets restricted to only a few domains of life. Quite paradoxically, societal secularisation generally begins with the creation of separate religious institutions: “marking off an area of the sacred - dramatising the fact that the sacred is something out of the ordinary." (<cite data-cite="9104992/ZAW8JW29"></cite>, 12-13) The secularisation of an institute takes place when an originally religious institution receives a more temporal purpose, like for instance the laicisation of government in late medieval England (13). Activities secularise when they are transferred from a more religious institution to a less religious one, like charity (5) or warfare (9). 


When applied to beliefs, mentalities or thoughts, secularisation involves a shift in focus from “ultimate ends” to “proximate, instrumental ones" (<cite data-cite="9104992/ZAW8JW29"></cite>, 5). This type of secularisation is particularly closely linked with the future outlook of individuals – it is even defined in temporal terms – and is therefore the one adhered to in this paper. A similar view of the process is adopted by Burke, whose pluritemporal take on Koselleck’s _Sattelzeit_ characterises the early modern period as one that saw a rise in “the number of pragmatic approaches to the future, reinforcing the idea of a secularisation of thought \[...\]. 'Secularisation', be it said, not in the strong sense of the replacement of religious by secular ideas but in the weaker sense of the coexistence of religious attitudes with an increasing variety of secular ones (<cite data-cite="9104992/QKCHY66H"></cite>, xiv)."


The secularisation of time in the early modern period can only be studied in relation to the Reformation. Although Henry VIII's dispute with the Pope over the annulment of his marriage famously culminated in the 1534 Act of Supremacy, it was only afterwards that the King's break with Rome  got tangled up with the reformation (<cite data-cite="9104992/QFIRD3FU"></cite>,153). Henry VIII’s early Anglican regime was maintained by Edward VI (1547-1553), forcefully reverted under Mary I (1553-1558) and reinstalled in a lay-dominated form by Elizabeth I (1558-1603). Along with the Stuarts’ reign – James I (1602-1625) and Charles I (1625-1649) – came an officially protestant but catholicly inclined regime so heavily contested that a series of civil wars broke out between the king’s supporters and the puritan parliamentarians in the 1640s. The unrest culminated in the execution of Charles I in 1649 and the instalment of the 10-year interregnum under the puritan leader Oliver Cromwell. Although the return of the monarchy under Charles II (1660-1685) restored the previous, more moderately protestant/Anglican regime, the political power of the restored church had suffered a great blow. When the regime was consolidated by the Glorious Revolution in 1688, government had become essentially laicised (<cite data-cite="9104992/ZAW8JW29"></cite>, 15).


Like the process of secularisation, the English reformation too has received a great deal of scholarly attention. While twentieth century historiography on the matter was dominated by the debate on whether the reformation was eagerly awaited by a lay population tired of catholic excesses (e.g. <cite data-cite="9104992/5UGP4SIX"></cite>) or characterised above all by a high degree of continuity backed up by government support (e.g. <cite data-cite="9104992/CFHKDQHU"></cite>), the past three decades of research have reframed the reformation as a process rather than an event and subsequently shifted the emphasis away from its onset and towards its unfolding on the long term. Subsequent research has not shed more light on the relations between English Protestantism and a variety of continental flavours of Christianity (e.g. <cite data-cite="9104992/YHPIDHJP">,</cite><cite data-cite="9104992/8CXEXVPY"></cite>), it has also unveiled the process itself as an oscillating rather than teleological one, characterised by accidents, rupture and setbacks for both parties rather than a carefully planned and implemented programme, which in turn has left more room for an exploration of catholic or otherwise dissenting voices instead (<cite data-cite="9104992/P7VW4LHD"></cite>, 350-352).







### Time and future in a reformed and/or secularised world


Processes like reformation and secularisation not only affect one's religious beliefs, they also impact the way in which people experienced and interacted with the fabric of time and, as a result, the extent to which they believed they could control their own future. Perhaps the best illustration of the close relation between temporality and secularisation is the word’s etymology: “secularisation” has been derived from the Latin “secularis”, a term that qualifies the progress of time as linear, as opposed to “aeturnus” or eternal. Even in the order of creation, time comes relatively late, eternity being the primordial state (<cite data-cite="9104992/ZAW8JW29"></cite>, 33).


A central concept that ties together religion and future thinking is the doctrine of providence. While providence already existed in pre-reformation Catholicism, it had become a highly politicised element of Protestantism too (<cite data-cite="9104992/K6PCJNWF"></cite>, 6). In Walsham’s view, providence is a combination of knowledge and power through which God determines what happens on Earth. The first aspect – power – points to God’s proclaimed ability to intervene with life on Earth, directly or indirectly, an aspect that distinguishes the early modern theology from the “watchmaker-god” of the Enlightenment era (<cite data-cite="9104992/K6PCJNWF"></cite>, 6). The second aspect – knowledge – refers to God’s programme for the evolution of the world and everyone in it, a “blueprint of human history drawn up in the beginning” (<cite data-cite="9104992/K6PCJNWF"></cite>, 9) where past, present and future are one.


In pre-reformation Catholicism, major divine interventions were thought of as rather common. God could intervene directly, through miracles (<cite data-cite="9104992/G8U2CWIU"></cite>, 93), or indirectly, in the shape of bizarre natural phenomena, epidemics or other kinds of catastrophes (130). Importantly though, providence was not the only explaining factor for bad luck: the misfortunes of everyday life were most commonly attributed to Fortuna instead (<cite data-cite="9104992/G8U2CWIU"></cite>, 130), both by lay people and the prominent theologians of the time. 


This belief changed with the Reformation. Protestant scholars believed that everything in the world was determined by God and wholly dismissed concepts like luck, fortune or chance: "Whereas Aquinas had stressed that the notion of Divine Providence did not exclude the operation of chance or luck, a sixteenth-century writer like Bishop Pilkington could declare categorically that there was no such thing as chance. Medieval Christians from Boethius to Dante had maintained the pagan tradition of the goddess Fortuna side by side with the belief in God's omnipotence, but for Tudor theologians the very idea of Fortune was an insult to God's sovereignty (<cite data-cite="9104992/G8U2CWIU"></cite>, 91)." The prevalent idea among the clergy was that miracles were mostly a phenomenon of the past, but that sinful behaviour could (and would) still be punished by indirect divine interventions like epidemics, which were intended as a wake-up call to live more pious lives (<cite data-cite="9104992/G8U2CWIU"></cite>, 93, 112-113).


Interestingly, however, when faced with actual crises, many early modern people, both lay and members of the clergy, responded in a much more eclectic way than the doctrine of providence warrants. The plague, for instance, was explained by Tudor and Stuart scholars with arguments drawn interchangeably from theology, astrology and galenic humour theory, a seemingly incongruent combination of explanatory frames that made sense only with providence as a binding agent (<cite data-cite="9104992/G8U2CWIU"></cite>, 156). Preachers stressed that the plague was a punishment for the community, but nevertheless that intermediary mechanisms like sanitary measures could help too. After all, such measures were part of the divine plan as much as the diseases themselves: medical cures worked because (or rather: if) God had written them into his blueprint of history (<cite data-cite="9104992/G8U2CWIU"></cite>, 158).


Other natural phenomena too were attributed at once to chance (or Fortuna), Providence, the planets or witchcraft.  "Certainly many parish registers, private diaries and journals record gale-force winds and hailstones 'as bigge as walnottes', tennis balls, or turkey's eggs without any pious comments whatsoever. Such entries are hardly evidence that an agnostic and morally neutral view of climatic anomalies prevailed, though they do beg questions about how many educated - and uneducated - people acknowledged a general providence without subscribing to the view that the hand of the Almighty could be traced in every particular terrestrial disaster" (<cite data-cite="9104992/G8U2CWIU"></cite>, 125).


This eclectic attitude towards misfortune and randomness ties in with a more general undercurrent rooted in (mythological) folk culture, science that had existed alongside and even in interaction with pre-reformation Christianity for centuries. The reformation, with its renewed interest in providence, did not replace these alternative frames of interpretation altogether, much to the chagrin of Tudor and Stuart clergy (<cite data-cite="9104992/K6PCJNWF"></cite>, 20-29). They complained, for instance, about a widespread belief in heathenish concepts like “fate”, “fortune” and “chance”, often personified in the goddess Fortuna. While medieval theology still embedded Fortuna as a subordinate figure to providence and God, protestant scholars strongly refuted her existence and explained randomness as humanity’s inability to see the full divine plan (<cite data-cite="9104992/K6PCJNWF"></cite>, 21-22). Other explanatory forces were based on a belief in (Dame) nature (23), in witches (26), in mythological creatures like ghosts, fairies, hobgoblins, elves and other spirits (28), in fortune tellers and almanacks (25) or judicial astrology. While it was recognised that celestial bodies were instruments of God, protestant clergy feared that too strong a belief in the influence of the stars and the moon would reduce moral responsibility (24-25).


While the belief the doctrine of providence as a whole started to fade from the seventeenth century onwards, providential explanations would linger on for centuries. Despite evolutions in natural sciences, many people would not believe, for instance, that the pestilence was by no means a divine punishment. In that respect: the difference between the sixteenth and the eighteenth or even nineteenth century was at most one of degree. "In the sixteenth and early seventeenth centuries we are confronted by a coherent theory to which most educated members of the community subscribed. In the nineteenth we meet only the survival of earlier assumptions, no longer fully compatible with the scientific principles of the day, and no longer accepted by many of the clergy themselves (<cite data-cite="9104992/G8U2CWIU"></cite>, 129)." Eighteenth century preachers argued that God had included such disasters in his original plans for the world because he knew that people would be sinful. In the seventeenth century, such argumentation is barely attested: the divine origin and punitive nature of catastrophes was simply so compatible with the prevalent world view that a rational defence – or even logical consistency - was hardly called for.


### Research questions


This study offers an empirical take on the secularisation of the future in Early Modern England, the period leading up to Koselleck's _Sattelzeit_. Most research carried out so far on providence or the history of the future more generally, has looked into sources that explicitly deal with people’s future expectations. Common sources are, for example, theological treatises, sermons, and pamphlets. While these are great sources to study an individual's providential and apocalyptic beliefs about the (distant) future, they reveal little about everyday hopes, worries and expectations. What is lacking, therefore, is a long-term, systematic study of divine control over future orientations in all its variety. 


A similar critique holds for studies into writing as a form of religous practice, a habit that held a particularly prominent place in puritan communities (<cite data-cite="9104992/S3LDXA42"></cite>, 298). Even before spiritual journalling was prescribed by preachers, puritans had long been keeping diaries in order to "learn to know oneself and therefore to learn to know religions" (<cite data-cite="9104992/ABCVJC7F"></cite>, 2). Many such diaries that have survived the period have later received a fair deal of attention in scholarly circles (e.g. <cite data-cite="9104992/SHZ9YPHS"></cite>, <cite data-cite="9104992/M7YH5R5F"></cite>). While this provides an excellent insight into the contemplations of the writers, they fail to capture the communal nature of religious practice. As previous research on letter-writing has emphasised, the rapid blooming of devotional identities in the sixteenth and seventeenth centuries (<cite data-cite="9104992/ABCVJC7F"></cite>, 3-4) had created a situation where people with similar beliefs were not necessarily geographically close to one another (<cite data-cite="9104992/7FR7VCTW"></cite>, 196). In such situations, letter-writing served the double purpose of strengthening the ties between people of the same denomination and jointly reworking or giving shape to religious concepts like piety and salvation. Following Fiona Counsell, this paper seeks to shift the emphasis from the contemplative to the interactive nature of religious practice in writing "by focusing on a collaborative genre as letter writing, which stresses the communal nature of piety and belief" (<cite data-cite="9104992/7FR7VCTW"></cite>, 197).




As religiosity is notoriously hard to get a grip on, let alone measure, the secularisation of thought and mentality among early modern people can only be studied by proxy, through religious practices (<cite data-cite="9104992/6IX9C7NU"></cite>, 180-182). One of these is like letter writing. Because personal letters have been produced in large quantities by people of various backgrounds throughout the period, a systematic search for divine appeals is hypothesised to get insight in the way the letter writers perceived their futures, big and small, far away and nearby, as well as the degree to which divine entities had control over it. The present study addresses this broad research question in two parts. 


First, the number of divine appeals in the correspondences as a whole is studied. To what extent did they think they think their lives were in the hands of God? Did that diminish over time – as the secularisation of time would suggest – or not? Were some people more likely than others to ascribe all agency in their lives to God? If so, what was their social profile. In the second part, we will zoom in on the divine appeals that are specifically concerned with future events or actions. Did people perceive these events as within their own sphere of control, or did they believe all agency rested in the hands of God? Which domains of their lives were they least in control of? Did these appeals for divine assistance or control show clear diachronic trends?


## Sources and Methods


### Corpus

<!-- #region -->
To chart the religious practices of a varied population - laypeople and religious professionals alike - in letter writing, we made use of the Parsed Corpus of Early English Correspondence, commonly abbreviated as PCEEC (<cite data-cite="9104992/IDVB5BT9"></cite>, available at https://ota.bodleian.ox.ac.uk/repository/xmlui/handle/20.500.12024/2510). This 2.2 million word corpus consists of 4970 personal letters, drawn from the edited publications of 84 different correspondences that took place between ca. 1410 and 1695. For a visual overview, we refer to our [timeline](#anchor-figure-timeline). Even though the wide-spread illiteracy at the time of writing restricts the corpus to the upper echelons of society, care has been taken to draw from as broad a pool of letter writers as possible. Nearly a fifth of the writers, for example, were women, and much effort has been spent on the collection and correction of the corpus' metadata, including biographical information on all letter writers and addressees.


Thanks to this extensive social documentation, the long diachronic range and the digital availability of the PCEEC, it is an excellent source to systematically study the extent to which divine interventions are invoked throughout the early modern period.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
In order to make the corpus digitally searchable, the PCEEC files were first reformatted into a single json file that collects all letters in a structured way, enriched with the available metadata. Because of some variation in the PCEEC file formatting, not all metadata was correctly extracted at once and a manual correction round was in place to make sure all letters had been properly separated and provided with the right metadata.
<!-- #endregion -->

```python tags=["hermeneutics"]
# Check your Python version
from platform import python_version
python_version()


#!python -V
```

```python tags=["hermeneutics"]
# pandas package needs to be added to the requirements.txt 's file 
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib
from matplotlib import pyplot as plt
import os, json, statsmodels

pd.__version__, np.__version__, sns.__version__, matplotlib.__version__, statsmodels.__version__
```

```python tags=["hermeneutics"]
author_index_to_meta = [None,"name","gender","relation_to_recipient","year_of_birth","age"]
recip_index_to_meta = [None,"name","gender","relation_to_addressee","year_of_birth","age"]
letter_index_to_meta = [None,"letter_id","period","year_of_writing","authenticity","relation"]

# define method to extract metadata from CEEC files
def extract_text(ipf):
    letters = []
    current_letter = {}
    for line in ipf.readlines():
        line = line.strip().replace("<paren>","(").replace("</paren>",")")
        if len(line) == 0:
            continue
        if line[0] in ["<","{"]:
            continue
        if line[:6] == "LETTER":
            letter_meta = line.split(":")
            letter_id = letter_meta[1]
            if (not "letter" in current_letter) or (letter_id != current_letter["letter_id"]) :
                if "new_author" in current_letter:
                    author_to_transfer = current_letter["new_author"]
                    del current_letter["new_author"]
                else:
                    author_to_transfer = None
                    
                if "new_recipient" in current_letter:
                    recip_to_transfer = current_letter["new_recipient"]
                    del current_letter["new_recipient"]
                else:
                    recip_to_transfer = None
                    
                if "letter" in current_letter:
                    current_letter["all_text"] = " ".join([p.strip() for p in current_letter["text"]])
                    letters.append(current_letter)
                
                current_letter = {"letter_id":letter_id,
                                "text":[""],
                                "letter":{}}
                if author_to_transfer:
                    current_letter["author"] = author_to_transfer
                if recip_to_transfer:
                    current_letter["recipient"] = recip_to_transfer
    
                for key,value in zip(letter_index_to_meta[1:],letter_meta[1:]):
                    current_letter["letter"][key] = value
        elif line[:6] == "AUTHOR":
                author_meta = line.split(":")
                if "new_author" in current_letter:
                    current_letter["author"] = current_letter["new_author"]
                current_letter["new_author"] = {}
                for key,value in zip(author_index_to_meta[1:],author_meta[1:]):
                    current_letter["new_author"][key] = value
        elif line[:6] == "RECIPI":
                recip_meta = line.split(":")
                if "new_recipient" in current_letter:
                    current_letter["recipient"] = current_letter["new_recipient"]
                current_letter["new_recipient"] = {}
                for key,value in zip(recip_index_to_meta[1:],recip_meta[1:]):
                    current_letter["new_recipient"][key] = value

        else:
            try:
                if len(line.split(" ")[-1].split(".")) == 3:
                    line = " ".join(line.split(" ")[:-1])
                    current_letter["text"][-1] += " " +line
                    current_letter["text"].append("")
                else:
                    current_letter["text"][-1] += " " +line
            except KeyError:
                continue
            
    if not len(current_letter) == 0:
        current_letter["all_text"] = " ".join([p.strip() for p in current_letter["text"]])
        if "new_author" in current_letter:
            del current_letter["new_author"]
        if "new_recipient" in current_letter:
            del current_letter["new_recipient"]
        letters.append(current_letter)
        
    return letters

# define corpus file
corpusfiles = os.listdir("./script/corpus")
letters = []

# read corpus file into memory and extract text
for cf in corpusfiles:
    ipf = open(os.path.join("./script/corpus",cf),"r",encoding="utf-8")
    letters.extend(extract_text(ipf))

# write metadata to outputfile
with open('./script/PCEEC_metadata.json', 'w') as outfile:
    outfile.write(json.dumps(letters,indent=4))
```

<!-- #region tags=["hermeneutics"] -->
The manually corrected json-file was then converted into a metadata sheet, which was further enriched with some additional metadata variables and subjected to a first round of exploration
<!-- #endregion -->

```python tags=["hermeneutics"]
df_social = pd.read_csv("./script/PCEEC_metadata.csv",sep="\t")
df_social
```

```python tags=["hermeneutics"]
# turn decade into half century
def half_century_mapping(decade):
    try:
        year = int(decade[:-1])
    except ValueError:
        return None
    if year < 1450:
        return 1400
    elif year < 1500:
        return 1450
    elif year < 1550:
        return 1500
    elif year < 1600:
        return 1550
    elif year < 1650:
        return 1600
    elif year < 1700:
        return 1650
    else:
        return 1700
    

def create_col_mapping(df,col):
    mapping = {}
    for i,row in df.iterrows():
        mapping[row["letter_id"]] = row[col]
    return mapping

def preprocess_corpus(df_social):
    for col in ["period","year_of_writing","authenticity","relation","author_age"]:
        mapping = create_col_mapping(df_social,col)
        df_social[col] = [mapping[lid] if lid in mapping else None for lid in df_social["letter_id"]]

    df_social["year_of_writing"] = [y.replace("?","").replace("S","") if y else None for y in df_social["year_of_writing"]]
    df_social["author_age"] = [y.replace("?","").replace("-","").replace("_CO","").replace("_COD","") if y else None for y in df_social["author_age"]]
    df_social['year_of_writing_N'] = [int(x) if not (pd.isnull(x) or any([c.isalpha() for c in x])) else None for x in df_social["year_of_writing"]]
    df_social["decade"] = ["%d0s"%(x//10) if not (pd.isnull(x)) else "NA" for x in df_social["year_of_writing_N"]]
    df_social["decade_N"] = [10*(x//10) if not (pd.isnull(x)) else "NA" for x in df_social["year_of_writing_N"]]
    df_social["author_age_N"] = [int(x) if not (pd.isnull(x) or any([(c.isalpha() or c == "_") for c in x])) else None for x in df_social["author_age"]]
    df_social['half_century'] = [half_century_mapping(x) for x in df_social["decade"]]
    df_social["author_age_bracket"] = ["%d0s"%(int(x)//10) if not (pd.isnull(x)) else "NA" for x in df_social["author_age_N"]]
    df_social["author_age_bracket_N"] = [10*(int(x)//10) if not (pd.isnull(x)) else "NA" for x in df_social["author_age_N"]]
    df_social["correspondence"] = [lid[:-4] for lid in df_social["letter_id"]]
    df_social["decadeXcorrespondence"] = df_social["decade"] + df_social["correspondence"]
    df_social["decadeXgender"] = df_social["decade"] + df_social["author_gender"]
    
    return df_social

df_social = preprocess_corpus(df_social)
```

```python tags=["hermeneutics"]
#count the words in the corpus and add word counts to the metadata

def parse_file(f):
    text_id=None
    wc = {}
    ipf = open(f,"r",encoding="utf-8")
    for line in ipf.readlines():
        if len(line.strip()) == 0:
            if text_id:
                wc[text_id] = wc[text_id][:-1]
            text_id = None
            continue
        elif line[:6] == "LETTER":
            text_id = line.split(":")[1]
            continue
        elif line[:2] in ["<Q","<A","<R","<P","<B","<S"]:
            continue
        elif line[:4] in ["AUTH","RECI"]:
            continue
        else:
            if text_id in wc:
                wc[text_id].extend(line.strip().split(" "))
            else:
                if not text_id:
                    continue
                else:
                    wc[text_id] = line.strip().split(" ")
    return wc

def clean_wordlists(wc,all_wordcounts):
    for text_id,wlist in wc.items():
        n_words = 0
        for w in wlist:
            if w[0] == "$":
                continue
            elif not any([c.isalpha() for c in w]):
                continue
            elif w[0] == "<" and w[-1] == ">":
                continue
            elif w[0] == "{":
                if w[-1] == "}" and w[1:6] == "TEXT:":
                    n_words += 1
            else:
                n_words += 1
        all_wordcounts[text_id] = n_words
    return all_wordcounts

all_wordcounts = {}
correspondences = os.listdir("./script/corpus")
for correspondence in correspondences:
    print(correspondence)
    wc = parse_file(os.path.join("./script/corpus",correspondence))
    all_wordcounts = clean_wordlists(wc,all_wordcounts)


```

```python tags=["hermeneutics"]
def add_wordcount(text_id):
    if text_id in all_wordcounts:
        return all_wordcounts[text_id]
    else:
        print(text_id)
        return(0)

df_social["wc"] = df_social["letter_id"].apply(lambda x:add_wordcount(x))
```

```python
df_social
```

```python tags=["hermeneutics"]

# get chronological order of the correspondences
df_correspondence_means = df_social.pivot_table(index="correspondence",values="year_of_writing_N",aggfunc="mean",fill_value=0,dropna=False)
correspondence_order = list(df_correspondence_means.sort_values("year_of_writing_N").index)
df_correspondence_means["year_of_writing_N"]

#create pivot table that reflects the activity of a correspondence per decade

pivot_timeline = df_social.pivot_table(index=["correspondence"],columns=["decade_N"],values="letter_id",aggfunc="count",dropna=False,fill_value=np.nan)
pivot_timeline_graphic = pd.DataFrame(index=pivot_timeline.index)
for decade in pivot_timeline.columns:
    pivot_timeline_graphic[decade] = [decade if x>0 else x for x in list(pivot_timeline[decade])]
pivot_timeline_graphic = pivot_timeline_graphic.loc[correspondence_order]
pivot_timeline_graphic.columns = [str(dec)[:4]+'s' for dec in pivot_timeline_graphic.columns]

# plot timeline

sns.set(rc={'figure.figsize':(7,20)})
plot = sns.heatmap(pivot_timeline_graphic,robust=True,cmap=sns.color_palette("husl",len(pivot_timeline.columns)),linewidths=0.5,linecolor="white",cbar=False,square=True)
plot.set_title("Correspondence coverage through time",size="20")
fig = plot.get_figure()
fig.tight_layout()

```

```python tags=["figure-timeline-*", "anchor-figure-timeline"]
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": ["Timeline of the correspondences in the CEEC corpus"
            ]
        }
    }
}
display(Image("media/timeline.png",height=50000), metadata=metadata)
```

### Data extraction and noise removal


To extract the divine appeals from the corpus, we first searched all letters for explicit mentions of divine entities. We queried the corpus for all mentions of "almighty", "father", "god", "dieu", "lord", "christ", "jesus", "mary", and "saint", making sure we preserved sufficient context for each term to be able to interpret the fragments afterwards. To minimise the impact of spelling variation, we also looked for spelling variations of these terms, i.e. "almightie", "dicu","j(h)esu(s)", "mer(r)y", "sa(i)n(c)t" and "st", and included partial matches: occurrences of "gode" and "lorde", for instance, were treated as hits because they include the queries "god" and "lord" respectively.

```python tags=["hermeneutics"]


def search_corpus(corpus):
    queries = ["god","jesus","jhesus","jhesu","christ","lord","almighty","father","saint","sant","dicu","dieu","mary","mery","merry"]
    hits = []
    window = 50
    for i,letter in enumerate(corpus):
        tokenpos = 0
        for line in letter["text"]:
            tokens = line.split(" ")
            for t,token in enumerate(tokens):
                for query in queries:
                    if query in token.lower():
                        index = tokenpos + t
                        hit = {"query":query,
                               "letter_id":"SB_C_%s"%(i+1),
                               "hit_id":"SB_C_%s.%s_%s"%(i+1,index,index),
                               "left":" ".join(tokens[max(0,t-window):t]),
                               "hit":token,
                               "right":" ".join(tokens[t+1:min(len(tokens),t+window)])
                              }
                        hits.append(hit)
            tokenpos += t
    return hits


corpus = json.load(open("./script/PCEEC_metadata.json","r",encoding="utf-8"))
hits = search_corpus(corpus)
df_hits = pd.DataFrame.from_dict(hits)
df_hits_with_meta=pd.merge(df_hits,df_social,on="letter_id",how="inner")
df_hits_with_meta.to_csv("dataset_paper.csv",sep="\t")
```

```python
len(df_hits)
```

```python tags=["hermeneutics"]
df_annotations = pd.read_csv("./script/dataset_paper_01_02_24.csv",sep="\t")
```

```python tags=["hermeneutics"]
query_map = {"almighty":"ALMIGHTY",
              "christ":"CHRIST",
              "dicu":"DIEU",
              "dieu":"DIEU",
              "father":"FATHER",
              "god":"GOD",
              "jesus":"JESUS",
              "jhesu":"JESUS",
              "jhesus":"JESUS",
              "lord":"LORD",
              "mary":"MARY",
              "merry":"MARY",
              "mery":"MARY",
              "sainct":"SAINT",
              "sanct":"SAINT",
              "sant":"SAINT",
              "saint":"SAINT",
              "st.":"SAINT"}

def standardise_query(query):
    return query_map[query]

df_annotations["query_standardised"] = df_annotations["query"].apply(lambda x:standardise_query(x))
dataset_overview = df_annotations.pivot_table(index="query_standardised",columns="LABEL",values="hit",aggfunc="count",fill_value=0,dropna=False)
dataset_overview["BODY"] = dataset_overview["BODY"] + dataset_overview["DUBBEL"]
dataset_overview.drop(["0","DUBBEL"],axis=1,inplace=True)
dataset_overview
```

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
This procedure resulted in a total of 20,281 hits, which was then subjected to a round of filtering to remove the attestations that did not actually refer to divine entities (i.e. "noise" in [Table 1](#anchor-table-overview)) . This includes, for instance, human lords and fathers, the partial matches of "Christ" in "Christmas" or "god" in "godfather", and the uses "merry" as the present-day adjective. In cases where the divine appeal consisted of several, consecutive queries (e.g. "Almighty God" or "Lord Jesus"), we preserved the first hit (respectively "Almighty" and "Lord") but discarded the others. This round of data cleaning reduced the size of the dataset to 7536 instances. Following Rutten and Van der Wal (<cite data-cite="9104992/CBNLU6T4"></cite>), we then labelled each attestation according to the part of the letter they were drawn from, distinguishing the (more formulaic) opening and closing statements from the letter body. 
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
[Table 1](#anchor-table-overview) shows an overview of the resulting dataset, broken down per query and letter part. As is apparent, the mentions of "God" outnumber the others by a large margin. Most terms were attested most frequent in the body of the letters, except for "Jesus" and "Almighty", which were more common in the closing parts. 
<!-- #endregion -->

<!-- #region tags=["table-overview-*", "anchor-table-overview"] -->
| query_standardised   |   BODY |   CLOSING |   NOISE |   OPENING |
|:---------------------|-------:|----------:|--------:|----------:|
| ALMIGHTY             |     89 |       120 |       0 |         6 |
| CHRIST               |    156 |        39 |     489 |        14 |
| DIEU                 |      0 |         0 |      54 |         0 |
| FATHER               |     17 |         3 |    1360 |         0 |
| GOD                  |   4511 |      1151 |     793 |       169 |
| JESUS                |    137 |       138 |       8 |        51 |
| LORD                 |    520 |       309 |    9050 |        34 |
| MARY                 |      7 |         0 |     543 |         0 |
| SAINT                |     58 |         4 |     457 |         0 |

<!-- #endregion -->

### Annotation


While the occurrences of divine entities in the opening and closing parts of the letters were highly formulaic, the ones in the letter bodies did display a large amount of variation. To gain insight in the contexts of and motivations for the divine appeals in the letter bodies, they were subjected to a structured discourse analysis by labelling them according to (1) the domain of the writers' lives to which the appeal pertains, (2) the temporal orientation of the appeal (past or future) and (3) the writers' perception of their own agency in the matter. It is important to note that this annotation scheme, which the next paragraphs expound on and is discussed in more detail in the appendix, did not exist prior to the analysis, but has been constructed along the way, in close interaction with the dataset. As this annotation procedure, known as Quantitizing Design (<cite data-cite="9104992/KXKA2IFT"></cite>, 3) has been carried out by a single annotator, its accuracy cannot be assessed by means of inter-annotator agreement scores. To overcome this limitation, however, the entire dataset has been made publically available along with this paper to enable the curious (or critical) readers to inspect the annotations, play around with the data and/or explore additional examples of the categories of divine appeals discussed here. 

```python tags=["hermeneutics"]
df_body = df_annotations[df_annotations["LABEL"] == "BODY"]
future_agency = ["DIVINE APPROVAL","CONFIDENCE","PRAYER","RESIGNATION"]
df_future = df_body[df_body["AGENCY"].isin(future_agency)]

domain_mapping = {
    "BIRTH":"SOCIAL LIFE",
    "COMMUNICATION":"TRAVEL, TRANSPORT AND COMMUNICATION",
    "DISEASE":"DISEASE AND DEATH",
    "DEATH":"DISEASE AND DEATH",
    "EPIDEMICS":"DISEASE AND DEATH",
    "GENERAL":"GENERAL",
    "GRACE":"GENERAL",
    "HEALTH":"SOCIAL LIFE",
    "HOUSEKEEPING":"SOCIAL LIFE",
    "LAW AND CRIME":"LAW, POLITICS AND WARFARE",
    "LEGAL":"LAW, POLITICS AND WARFARE",
    "MARKET":"MONEY, WORK AND FINANCES",
    "MARRIAGE":"SOCIAL LIFE",
    "MEETING":"TRAVEL, TRANSPORT AND COMMUNICATION",
    "MONEY":"MONEY, WORK AND FINANCES",
    "POLITICS":"LAW, POLITICS AND WARFARE",
    "PRESERVATION":"GENERAL",
    "RELIGION":"RELIGION",
    "RESIGNATION":"RELIGION",
    "SERVICE":"SOCIAL LIFE",
    "SOCIAL":"SOCIAL LIFE",
    "TRADE":"MONEY, WORK AND FINANCES",
    "TRANSPORT":"TRAVEL, TRANSPORT AND COMMUNICATION",
    "TRAVEL":"TRAVEL, TRANSPORT AND COMMUNICATION",
    "WARFARE":"LAW, POLITICS AND WARFARE",
    "WORK":"MONEY, WORK AND FINANCES",
    "0":"0",
    "X":"0"
}

df_future["DOMAIN_STANDARDISED"] = df_future["DOMAIN"].apply(lambda x:domain_mapping[x])
domain_overview = df_future.pivot_table(index="DOMAIN_STANDARDISED",values="hit",aggfunc="count",fill_value=0,dropna=True)
domain_overview = domain_overview.drop(["0"])
domain_overview

```

<!-- #region tags=["table-domains-*", "anchor-table-domains", "hermeneutics"] -->
| DOMAIN_STANDARDISED                 |   hit |
|:------------------------------------|------:|
| SOCIAL LIFE                         |   258 |
| LAW, POLITICS AND WARFARE           |   212 |
| TRAVEL, TRANSPORT AND COMMUNICATION |   188 |
| RELIGION                            |    96 |
| DISEASE AND DEATH                   |    70 |
| MONEY, WORK AND FINANCES            |    60 |
| GENERAL                             |     8 |
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
[Table 2](#anchor-table-domains) lists the domains of life in relation to which divine appeals have been attested. "Social life", the most frequent category attested in our dataset, covers fragments that relate to domestic family life in the broadest sense, including among others births, romances or marriages, health wishes, housekeeping issues and the more general and formulaic promises to be at someone's service. "Law, politics and warfare" includes, quite straightforwardly, all cases concerned with local, national or international politics, with conflicts and warfare or legal issues. "Travel, transport and communication" covers cases where people travel, objects are being transported, meetings are being arranged or letters are being sent back and forth. "Religion" comprises fragments where someone's relation with God or the divine is explicitly discussed apart from the divine reference itself. "Disease and death" includes all attestations where people are struck by, recovering from or succumbing to diseases or epidemics, or have deceased in another way. The category "Money, work and finance" collects the fragments that involve financial transactions, like payments and loans, or professional life more generally. The "general" category, finally, subsumes all attestations in which writers wish other people well without mentioning a specific context or sphere of life.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["hermeneutics"] -->
The second and third parameter that was annotated for, temporal orientation and agency, interact with each other. The temporal orientation of a divine appeal simply indicates whether a letter writer invokes or presupposes divine intervention for an event or situation that is yet to come (future-oriented) or one that has already happened (past-oriented). As the scope of this paper is limited to future-oriented events, only these events have been subjected to further annotation. The four different agency relations that have been discerned will be illustrated at the start of [Section 1.5](#anchor-chapter-agency), which then proceeds to discuss the semantic and pragmatic features of each of these agency relations in turn.
<!-- #endregion -->

<!-- #region tags=["hermeneutics"] -->
While this approach is excellent at combining qualitative and qualitative insights, its labour-intensiveness matches poorly with the size of the database, especially so with the 4454 hits yielded by "God" query. To decrease the labour intensiveness, we exhaustively analysed all hits obtained by means of the other queries and took a random sample of the divine appeals with "God". To ensure analytical rigour, we stratified our sample so that at least 50% of the hits for each correspondence, decade of writing, author and author gender had been analysed. We then extrapolated all in-sample counts for the "God" part of the database proportionally to obtain estimated for all "God" hits, which we then subjected to the same statistical analysis as the hits yielded by the other queries.
<!-- #endregion -->

## Quantitative analysis of divine appeals

<!-- #region editable=true slideshow={"slide_type": ""} -->
This section explores the distribution of divine appeals in our letters throughout the entire early modern period. First ([Divine appeals in letter opening, body and closing statements](#anchor-divine-appeals)), their dispersion through the letters is charted. Did the relative number of divine appeals increase or decrease as time progressed? Were they more common in the rather formulaic opening and closing statements of the letters? Second ([The centrality of (writing) communities](#anchor-communities)), we look at the social distribution of the appeals. Does every correspondence in the corpus yield the same (relative) number of divine appeals, or do some correspondents employ them more than others? If that is the case, what is their social profile?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["anchor-divine-appeals"] -->
###  Divine appeals in letter opening, body and closing statements
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As the leftmost plot in [Figure X](@figure-opening_body_closing-*) indicates, the practice of appealing to a divine entity in a letter’s heading or greeting (1a) or even its first paragraph (1b) is clearly on its way out. While the earliest correspondence in our corpus (the Signet letters of Henry V) contains divine appeals in about 40% of all letters, the amount systematically decreases and even virtually disappears by 1600, barring a few exceptions. 
<!-- #endregion -->

- (1a)  _**Jesus, Maria** , &c. Ryte reuerent sire, after dv recommendacyon, we sey in this cuntre that Heydon is for Barkschire in the Comon Hows._ (PASTON,II,210.365.9662; John Brackley to John Paston I; 1460)
- (1b)  _Right worshipfull Sir, in my best manner my dutie remembrid , I komend me vnto your good mastershippe , trustyng in **Almighty God** that you be in good helth & soo long to contynewe to Goddes pleasure, & your hartes desire ys, and shalbe, my dayle prayer._ (BRERETO,92.025.406; Richard Thomas to William Brereton; 1534)
- (2)   _And thus , in all dutifull sorte , most humbly intreating your Lo. to stand my honorable frind, in this my heavy fortune, I comitt my sute to your good remembrance, and your lordshipp to the tuition of **God**, this 12 of November. Your good Lo. poore frind, most unfortunate, Anne Arundell._ (ARUNDEL,11.001.6; Anne Howard to William Cecil, 1589)


```python tags=["figure-opening_body_closing-*"]
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": ["Average number of divine appeals per letter in opening (left) and closing (middle); average number of divine appeals (normalised per 10K words) in letter body (right)"
            ]
        }
    }
}

display(Image("./media/opening_body_closing.png"),metadata=metadata)
```

When it comes to the number of divine references in closing statements (2), the evolution is more complex. Despite a very gradual rise throughout the fifteenth and sixteenth centuries, their use drastically plummets from the mid-1600s onwards. The large disparity between the early and late correspondences from the seventeenth century needs further investigation.


A similar trend, albeit a weaker one, holds for divine appeals in letter bodies. While the first of the seventeenth century displays the highest rate of divine appeals in the entire dataset, the second half of the century is characterised by a remarkable lack of divine appeals instead. 
The pattern attested in both the letter bodies and the closing statements is clearly inconsistent with the idea of linear progress towards fewer divine appeals. Instead, it hints at an increase in variability: while fifteenth century correspondences consistently showed rather moderate rates of divine appeals, seventeenth century correspondences show either very high or very low rates of divine references.

```python tags=["figure-mean_std-*"]
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": ["Mean and standard deviation of divine appeals in letter bodies, stratified by decade (left) and correspondence (right)"
            ]
        }
    }
}
display(Image("./media/mean_std.png"), metadata=metadata)

```

[Figure X](#figure-mean_std) explores this trend in more detail, plotting the means and standard deviations of all letters involved, but grouped in different ways. The two leftmost plots group the letters according to the decades they have been written in, regardless of the correspondence they belonged to. The two rightmost plots group the letters by correspondence instead, using their average date of writing as temporal anchor.  As such, each dot in two leftmost plots row represents one decade of data, while each dot in the two rightmost plots represents one correspondence. 


Interestingly, the diachronic trends observed are different depending on the way the data are grouped. When aggregated by decade, the mean rate of divine appeals first levels at around 20 per 10K words in the fifteenth and sixteenth centuries but displays a steady rise from 1600 onwards. When the data are grouped by correspondence, by contrast, the means show a steady decline instead (barring a small surge around the 1630s). 


A less marked but still substantial difference is shown by the standard deviations. When grouped by decade, the standard deviations rise steeply until around 1600 but plummet almost immediately afterwards. The standard deviations per correspondence similarly rise first and then fall, but the fluctuations are less steep, smaller in size, and remain level rather than rise throughout the entire sixteenth century.


Above all, the disparity between the results obtained by the two aggregation types reveals something about the relation between inter- and intra-group variation. The standard deviation of a decade can be thought of as a measure of inter-group variation: if different groups active in the same decade act rather differently, the data of that decade will show a high amount of variation. On the other hand, the standard deviation of a correspondence serves as an indication of the amount of intra-group variation: if all people in the correspondence behave the same way, the variation will be low, and vice versa.


In this light, the present disparity between the standard deviations of decades and correspondences teaches us that while the differences between correspondence increase as time passes (cf. higher standard deviation in decades), the variability within correspondences decreases (cf. lower standard deviation in correspondences). Incidentally, this scenario also accounts for the opposite direction of the evolution of the means in the 17th century. It simply indicates that while a growing number of people had stopped using divine appeals in their letters, the few people that still used them, did it so often that the aggregated counts went up anyway.


What this observation highlights most of all is the centrality of (writing) communities, defined here pragmatically as a group of people who write letters to each other. Even if the language of letter-writing became more secular over time, it did not do so at a steady pace for the entire population. Moreover, a given individual’s inclination towards divine appeals in letters seems to have been impacted more by their social circle than by their year of birth.

```python tags=["hermeneutics"]
# add the number of hits in body, opening and closing section to the metadatasheet

def import_pivot(pivot):
    mapping = {}  
    for text_id,row in pivot.iterrows():
        mapping[text_id] = {}
        for col in pivot.columns:
            mapping[text_id][col] = row[col]
    return mapping

df_text_to_body = df_annotations.pivot_table(index="letter_id",columns=["LABEL"],aggfunc="count",values="hit",fill_value=0)
df_text_to_body

mapping = import_pivot(df_text_to_body)

df_social["BODY"] = [mapping[text_id]["BODY"] if text_id in mapping else 0 for text_id in df_social["letter_id"]]
df_social["OPENING"] = [mapping[text_id]["OPENING"] if text_id in mapping else 0 for text_id in df_social["letter_id"]]
df_social["CLOSING"] = [mapping[text_id]["CLOSING"] if text_id in mapping else 0 for text_id in df_social["letter_id"]]
```

```python tags=["hermeneutics"]
# aggregate the data by decade and correspondence and create different dataframes for each

def aggregate_df(df_social,outer_column,label):

    df = df_social.pivot_table(index=outer_column,values=label,aggfunc="sum")
    df_std = df_social.pivot_table(index=outer_column,values=label,aggfunc="std")
    df_count = df_social.pivot_table(index=outer_column,values="letter_id",aggfunc="count")
    df_wc = df_social.pivot_table(index=outer_column,values="wc",aggfunc="sum")
    df_time = df_social.pivot_table(index=outer_column,values="year_of_writing_N",aggfunc="mean")


    df["wc"] = df_wc["wc"]
    df["time"] = df_time["year_of_writing_N"]
    if "NA" in df.index:
        df = df.drop("NA")
    df["std"] = df_std[label]
    df["count"] = df_count["letter_id"]

    if label == "BODY":
        df["normalised_mean_per_10K_words"] = 10000*df[label]/df['wc']
    else:
        df["avg_per_letter"] = df[label]/df["count"]
    df["time"] = np.float64(df.time)

    return df


df_decade = aggregate_df(df_social,"decade_N","BODY")
df_correspondence = aggregate_df(df_social,"correspondence","BODY")
df_correspondence_opening = aggregate_df(df_social,"correspondence","OPENING")
df_correspondence_closing = aggregate_df(df_social,"correspondence","CLOSING")
```

```python tags=["hermeneutics"]
# plot no. divine appeals in OPENING
correspondence_order = df_correspondence_opening[df_correspondence_opening.wc > 10000]
correspondence_order = correspondence_order.sort_values(by="time")
correspondence_order["correspondence"] = correspondence_order.index

sns.set(rc={'figure.figsize':(8,10)})
sns.set(font_scale=2)
palette = sns.color_palette("husl")
p = sns.regplot(
    data=correspondence_order, x="time", y="avg_per_letter",lowess=True,truncate= False
)
plt.xlim((1400,1700))
plt.ylim((-0.1,1.1))

plt.title("Average no. divine appeals in letter opening\n",size=28)

plt.show()
```

```python tags=["hermeneutics"]
# plot no. divine appeals in CLOSING

correspondence_order = df_correspondence_closing[df_correspondence_closing.wc > 10000]
correspondence_order = correspondence_order.sort_values(by="time")
correspondence_order["correspondence"] = correspondence_order.index

sns.set(rc={'figure.figsize':(8,10)})
sns.set(font_scale=2)
palette = sns.color_palette("husl")
p = sns.regplot(
    data=correspondence_order, x="time", y="avg_per_letter",lowess=True,truncate= False
)
plt.xlim((1400,1700))
plt.ylim((-0.1,1.1))

plt.title("Average no. divine appeals in letter closing\n",size=28)

plt.show()
```

```python tags=["hermeneutics"]
# plot normalised no. divine appeals in BODY

correspondence_order = df_correspondence[df_correspondence.wc > 10000]
correspondence_order = correspondence_order.sort_values(by="time")
correspondence_order["correspondence"] = correspondence_order.index

sns.set(rc={'figure.figsize':(8,10)})
sns.set(font_scale=2)
palette = sns.color_palette("husl")
p = sns.regplot(
    data=correspondence_order, x="time", y="normalised_mean_per_10K_words",lowess=True,truncate= False
)
plt.xlim((1400,1700))

plt.title("Normalised no. divine appeals in letter body\n",size=28)

plt.show()
```

```python tags=["hermeneutics"]
#plot the mean and the standard variation for all correspondences with > 10K words

fig, axs = plt.subplots(1,4,
                      figsize=(20,8),
                      sharey=False)
sns.set(font_scale=1.5)
palette = sns.color_palette("husl")
fig.suptitle("Mean and standard deviation of divine appeals in letter bodies",size=28)
fig.text(0.2,0.85,"by time (one dot = one decade)",size=20)
fig.text(0.58,0.85,"by social group (one dot = one correspondence)",size=20)


counter = 0

for df in [df_decade,df_correspondence]:
    for i,col in enumerate(["mean","std"]):
        if col == "mean":
            ax=axs[counter].set_ylim(-2,120)
            df = df[df["wc"]>10000]
            color = palette[0]
            col = "normalised_mean_per_10K_words"
        elif col == "std":
            ax=axs[counter].set_ylim(-0.2,5)
            #ax = axs[(row_i,i)].set_ylim(0,2)
            color = palette[-2]
        axs[counter].set_title("  ",pad=40)
        p = sns.regplot(data=df, x="time",y=col,order=1,ax=axs[counter],color=color,lowess=True)
        counter += 1
        

plt.subplots_adjust(wspace=0.5,top=0.8)
```

<!-- #region editable=true slideshow={"slide_type": ""} tags=["anchor-communities"] -->
### The centrality of (writing) communities
<!-- #endregion -->

To gain more detailed insight in the behaviour of various communities, we looked into the social profile of the five correspondences that boasted the highest and the lowest rate of divine appeals per 10K words (put names of correspondences in footnote), marked respectively in green and red on the plots in [Figure X](#figure-communities).

```python editable=true slideshow={"slide_type": ""} tags=["anchor-figure-communities", "figure-communities-*"]
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": ["Normalised no. divine appeals in letter body"]
        }
    }
}
display(Image("./media/veelschrijvers_weinigschrijvers.png"), metadata=metadata)
```

<!-- #region tags=["hermeneutics"] -->
The red and green marks, lines and labels have been added to the plots manually in Microsoft PowerPoint.
<!-- #endregion -->

Perhaps the most striking feature of these plots is that there is a clear imbalance in the degree to which the correspondences at both ends of the scale diverge from the average: the positive outliers are much more marked than the negative ones. Moreover, none of these outliers is attested before the 1550s. The six correspondences with the most divine appeals predominantly stem from the (period leading up to) the Civil Wars in 1640 (Barrington, Ferrar and Harley). The five correspondences with the lowest rate of divine appeals are to be found more during the Interregnum in the 1650s (Chamberlaine and Edmondes) and in the aftermath of the Restoration in 1660 (Osborne, Marvell and Essex). Despite these temporal clusters however, neither group of correspondences has a designated period in time where the other does not feature, corroborating earlier evidence that the seventeenth century saw a diversification in the rates of divine appeals among letter writing communities rather than wholesale shifts in a single direction.


Regarding the social profile of the communities concerned, the common denominator among those with many divine appeals readily emerges to be puritanism. The Harleys were a prominent part of the Herefordshere gentry whose devoutly puritan convictions and parliamentarian support brought them in serious trouble during the civil wars (<cite data-cite="9104992/F8V9WGK2"></cite>, <cite data-cite="9104992/8NSJGSDV"></cite>). Especially the letters of Brianna Harley have been studied extensively in their relationship to puritan beliefs (e.g. <cite data-cite="9104992/IX2FY2UI"></cite>, <cite data-cite="9104992/XYB8PWVG"></cite>). John Jones Maesygarnedd, Oliver Cromwell's brother in law and one of the commissioners to sign King Charles I's death warrant, was a puritan Welsh politician who got executed after the Restoration (<cite data-cite="9104992/CDTZVSLN"></cite>). Sir William Masham, son-in-law of the wealthy Essex puritan Sir Francis Barrington, similarly was a puritan politician and active parliamentarian during the First Civil War, before being taken hostage by royalists in the Second Civil War (<cite data-cite="9104992/NCXLC5J3"></cite>, <cite data-cite="9104992/LI7U2LJZ"></cite>). Sir Francis Hastings was a puritan reformer and politician with a special interest for the interplay between religion and politics (<cite data-cite="9104992/5QRYMRF3"></cite>). The Ferrar correspondence is centered around Nicholas Ferrar, a son of a wealthy London merchant that became deacon in the Church of England before founding his own religious community in Liddle Gidding famous for its devotional discourse (<cite data-cite="9104992/9MECKTVA"></cite>, <cite data-cite="9104992/JPQDS7B3"></cite>). While the precise denomination of this community is not entirely clear, the importance of religion in Ferrar's life can hardly be contested.


The openly puritan convictions of these communities might also explain their temporal clustering in the first half of the seventeenth century: the (political tension preceding) the civil wars in the 1640s made this period a particularly perilous time to be puritan. The Harleys, Jones and Barringtons all faced severe persecution because of their religious inclination. This evidently increased their exposure to uncontrollable situations, which could have boosted the number of divine appeals. In that respect, it is unclear whether the elevated rate of divine appeals among these communities is of theological nature and caused directly by their religious convictions, or whether it has a more pragmatic cause and stems from the real-world hazards they faced because of these convictions.


The communities that used the fewest divine appeals vary considerably more in social profile. Thomas Edmondes was active as a diplomat in France under Elizabeth I and subsequently secured the position of Treasurer of the Royal Household under James I and Charles I (<cite data-cite="9104992/Y9J33D4W"></cite>). The Essex correspondence revolves around Arthur Capell, who was appointed Privy Councillor and Lord Lieutenant of Ireland in 1672, but got convicted for attempted regicide out of anti-catholic sentiments ten years later (<cite data-cite="9104992/YFZCRRNC"></cite>). Andrew Marvell was a protestant (though not puritan) poet and politician who pragmatically steered away from his republican views after the restoration (<cite data-cite="9104992/AGFPXITS"></cite>). John Chamberlain was the son of a well-to-do London ironmonger whose 71 letters with political news and gossip are considered highly representative of the late Elizabethan and early Stuart gentry (<cite data-cite="9104992/KABMSWCW"></cite>), and Dorothy Osborne, the youngest daughter in a committed royalist family, is known for the witty letters she wrote to her later husband, William Temple, during their courtship in the 1650s (<cite data-cite="9104992/AB9HZJ9D"></cite>).


Apart from the lack of puritans among them, it is hard to find a common denominator in the social profiles of these people. This ties in with their position in [Figure X](#figure-communities): even though they represent the endpoint of the continuum, their means were twice as close to the average as the outliers in the positive direction. Perhaps their rates of divine appeal were not that eccentric after all, and neither was their social background.


In sum, the exploration of the rate of divine appeal in the openings, bodies and closings of the letters in the CEEC has drawn our attention to three observations. 1) The formulaic divine appeals in opening and closing statements were slowly petering out, and the opening statements did so faster than the closing statements. 2) The variation between correspondences increases with time, but variation within correspondences decreases: as more (groups of) people stopped making divine appeals, the ones that did still make them, used them more than ever. This holds especially true for the first half of the seventeenth century, when the political tension was building up towards the Civil war. 3) The communities with the highest rates of divine appeal were puritans, whose elevated need for divine intervention can be due either to intrinsic, religious factors or to the political repercussions they faced because of their religious denomination. More generally then, it looks like the secularisation of letter writing is attested straightforwardly only in the formulaic opening and closing sequences of the letters, but not in their bodies. While there does appear to be a general trend towards fewer divine appeals, it is compensated for by the rapid surge in divine appeals in the correspondences of other communities, most notably puritans in times of extreme distress.

<!-- #region editable=true slideshow={"slide_type": ""} tags=["anchor-chapter-agency"] -->
## Human and divine agency over the future
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The previous section has demonstrated that the overall rate to which people appeal to divine entities in their letters is highly dependent on their social profile and the (writing) community they are part of. The current section zooms in on the semantics of the divine appeals themselves, with a special focus on the ones that deal with the future. How much agency did the letter writers think they had about their own future? For which aspects of their envisioned future did they appeal to divine powers? Did they ask God for assistance, did they simply assume that God would grant them whatever they wanted, or did they take a step back and trust the path that God had in mind for them?
<!-- #endregion -->

To investigate to what extent early modern people perceived their future to be controlled by divine entities, we annotated all future-oriented divine appeals by the distribution of agency between the letter writer and the divine entity that is appealed to. Four such types are distinguished. _Divine approval phrases_ frame an event as under the control of the letter writer, as long as God approves of its good outcome. _Confidence phrases_ attribute control to God, but at the same express that the writer is confident that the desired outcome will be realised. In _prayers_, the letter writers ask God to nudge a future event in their favour: they do not just assume that God will take care of it to their advantage, but they explicitly ask him to do so. The lowest degree of human agency, finally, is found in _resignation phrases_, where the letter writer resigns in whatever outcome God has in store for them, whether it be to their advantage or disadvantage.


The plots in [Figure X](#figure-agency) show how these four types of human-divine agency distribution, stratified by correspondence, evolved through time. As the data indicate, the number of divine appeals in the correspondences appears to go down as time progresses: all types of divine appeals apart from resignation have lower rates of use in the late seventeenth century than in the late fifteenth. 

```python tags=["figure-agency-*", "anchor-agency"]
metadata={
    "jdh": {
        "module": "object",
        "object": {
            "type":"image",
            "source": ["Diachronic evolution of agency"]
        }
    }
}
display(Image("./media/agency.png"), metadata=metadata)
```

In addition, the general declines in divine appeals are interrupted by brief surges of requests for religious favours in the early seventeenth century. This indicates that the more general increase in divine references in the period leading up to the civil war in the 1640s, as attested in [section X](#anchor-communities) of this paper, holds for virtually the entire range of use that such divine appeals cover: it is replicated a little bit in confidence statements, somewhat more in divine approval statements and most clearly in prayers. Interestingly, the only type of divine appeal that deviates from this pattern are the resignation statements, which appear to be consistently on the rise throughout the early modern period. 


To gain more insight in the nature of these changes, the four following sections zoom in on one type of divine appeal each, ordered by decreasing human control. For each type, the sections will discuss the type’s most common linguistic expressions, the domains of life they pertain to as well as their social and diachronic variation.

<!-- #region editable=true slideshow={"slide_type": ""} -->
### Divine approval phrases
<!-- #endregion -->

Divine approval phrases appear when a letter writer expresses their desire to perform an action as well as their expectation to succeed in their endeavour, as long as God permits them to do so. They are not only the type of divine appeal that imply the largest share of human agency, they also are the most consistent type from a linguistic point of view: they usually appear either as _“by the grace of \<divine entity\>”_ (3a) or _“(\<divine entity\> willing)”_ (3b) and often show up in contexts of travel (3b) or expressions of the writer’s intentions (3a) more generally. In fact, this phrase seems to be tied to the presence of explicit intention markers (e.g. "purposeth" in (3b)) rather than to a specific domain of life.

<!-- #region editable=true slideshow={"slide_type": ""} -->
- (3a)  _"And as I have more enknowliche of this mater, or of any other perteynyng unto you, y shal **by the grace of Jhesu** sende you worde, who kepe you, Amen."_ (STONOR_092.336; Richard Germyn to William Stonor; 1480)

- (3b)  _"My sonne Harrie came downe higher with his Lady about x daies agoe, verie well, and he purposeth **(God willinge)** about some busines of importance to set forward towards London againe uppon Tewsday or Wednesday next."_ (WENTWORTH_014.213; Francis Clifford to William Wentworth I; 1612)
<!-- #endregion -->

In terms of social variation, two clusters of particularly frequent use can be discerned. The earliest one, dated ca. 1500, consists of the Willough, Stonor and Plumpton correspondences and predominantly featured divine approval phrases in context related to either travel or intention. The second cluster appeared around 1630 in the writings of Wentworth, Harley, Barrington and Ferrar, who seemed to use the phrase much less for intention purposes and strongly tied it to travel. This increasing association with the domain of travel holds true for the other correspondences as well. Overall, it looks like the divine approval phrase – which was highly formulaic from the very start – gradually became restricted to contexts of travel, which probably solidified its status as a fixed phrase even more and as such caused its frequency to drop, along with those of the other fixed phrases.


### Confidence phrases


Confidence phrases express the writer’s assured beliefs that the divine entity at stake will fulfill their needs. Their reliance on the word “trust” makes them formally rather uniform, and therefore formulaic.


Apart from one early outlier, the Shilling correspondence in the mid fifteenth century (5a), all letter writers in the corpus tend to use confidence phrases in similar frequencies and contexts. It mainly serves interpersonal functions, where trust in a divine entity is used as a rhetorical device to give instructions to other people in a face-saving manner, in political affairs (4a) or in relation to business (4b).

<!-- #region editable=true slideshow={"slide_type": ""} -->
- (4a)   _“My lorde conjoured me to make an ende of this mater and yf y so didde y shoulde be cronycled. Y seyde, ‘My lorde, y have don my part **as y truste to God** ye shall knawe and wolle reporte as fer as y can may and thar do after youre commaundement.’”_ (SHILLING_004.1251; John Shillingford to an unidentified addressee; 1447)
- (4b)   _“**I tryste in God** ye schall be at the packyng of the sayd woll in Cottyswolde”._ (CELY_047.259; Richard Cely Senior to George Cely; 1479)
- (4c)   _“I beleeve you will fall to drawing, and besides faces, it may be Pleasent to the inhabitents as well as yr self, if you draw any thing elce in the Island. Tom wishes himself with you for some days. **God I trust** will support and Bless you;”_ (BROWNE_048.291;Thomas Browne Senior to Elizabeth Lyttelton (née Browne); 1681)

<!-- #endregion -->

Interestingly, these interpersonal uses of the construction grow less frequent over time, making room for a more literal reading instead (4c). From a historical linguistic point of view, the shift from an interpersonal meaning to a literal one is highly odd: it is much more common for words and phrases to develop in exactly the opposite way, through a combination of processes called grammaticalisation, subjectification and intersubjectification (see, e.g. <cite data-cite="9104992/35CQ9WFH"></cite> and <cite data-cite="9104992/UNTBF5P5"></cite>).


The construction’s violation of these general mechanisms of language change draws attention to what motivated the shift. In particular, it increases the likelihood that this emergence of literal uses is a consequence of a genuine shift in the letter writers’ perceived relation to God. Indeed, while fifteenth-century writers saw no objections in a more gratuitous use of divine confidence phrases for social purposes, the later attestations appear to be a reflex of a more personal, solemn and genuine faith in the power of divine entities. While it cannot be excluded that the more solemn use of the phrase is a discursive strategy or a genre convention of letter writing too, it remains the case that there is a qualitative difference with the earlier (conventional) uses of the pattern and that the direction of the change is so marked in linguistic terms that the motivating factor is likely to be social or religious in nature.


### Prayers


Prayers, by a large margin the most frequent category of divine appeals, are here taken to cover all phrases where the letter writer implores a divine entity for assistance or a desired outcome in general. While some formulaic prayers exist (e.g. the wish for God to protect or preserve the wellbeing of the addressee), they display a broad range of formal variation. 


To get more grip on their shapes and functions, we additionally annotated all prayers for two extra variables: their beneficiary (the person that is prayed for) and their agent (the person who would be in control of the event in a secular worldview). The latter parameter in particular turned out to be important for the overall function of the prayer. When God was in control, the letter writers tended to pray either for the addressee or for other people (5a). When other people were in control, the letter writers prayed mostly for themselves and occasionally for others (5b). When the addressee was in charge, letter writers prayed for the addressee and used the prayer as a rhetorical, face-saving device to exert control over the addressee (5c). When the writers themselves were in charge, they prayed for divine assistance in whatever they wished to achieve (5d).


- (5a)   _“Also, the Kyng hathe ben in Glowceterschere and pwnyssede hijs rebellious agen te lawe, and so he entendithe to doo in Norfolk, and after tat in odere contreez. **God geue grasse and good spede in hijs jornay**.”_ (PASTON_055.216; Clement Paston I to John Paston I; 1464)
- (5b)   _“**I hope the Lord wil disapoint all the plots** of thos that haue evill will ath the prosperity of Gods church.”_ (HARLEY_032.276; Brilliana Harley (née Conway) to Edward Harley; 1640)
- (5c) _“**God send you wisedome & providence** to make a prudent use of the moneys you have from mee beside what you gett, and otherwise.”_ (BROWNE_012.45;Thomas Browne Senior to Edward Browne; 1678)
- (5d) _“yet **God keep me from those unnecessary sadnesses of mind and disquiets of hart** which make me for my part unfitt for al dewtyes to God, mand and my selfe.”_ (BARRING_156.2282; Jane Hook (née Whalley) to Joan Barrington; 1631)


The respective frequencies of these four different types of prayers varies with time. The more formulaic prayers for someone’s wellbeing (5a) dominated the earliest periods but gradually waned in favour of the prayers where God was asked to exert power over others (5b), the addressees (5c) or the writers themselves (5d). Unlike with confidence phrases, this shift from more literal to more interpersonal meanings is in line with general patters of linguistic change. In addition, this shift away from the more formulaic prayers opened up the range of domains of life that was prayed for: the generic wishes for someone’s health and safe arrival made room for specific wishes in specific situations. This pattern is not just attested in the three correspondences the highest numbers of prayers (Hoskyns, Knyvett and Harley, all from the first half of the seventeenth century), but elsewhere too.



### Resignation phrases


Resignation phrases, finally, include those divine appeals where the letter writer does not ask a divine entity to take care of the matters to their advantage, but fully surrenders to whatever that divine entity has in store for them, good or bad. As a result, they are commonly attested when the letter writers are faced with situations they have very little control over, like epidemics (6a), political trouble (6b), matters of religion or salvation (6c) and disease (6d). As is apparent from the examples, their lack of shared linguistic features makes resignation phrases the least formulaic type of all divine appeals.


- (6a) _“The sekenese raynyd sore at London, **God sesyd wan ys wyll is.**”_ (CELY_045.445; Richard Cely Senior to George Cely; 1479)
- (6b) _“I was muche comforted and refreshed with hope that, by your good meanes and your sonne’s, my brother should have had present delyverye from his long and tedious imprisonment: **but I perceyve yt is God’s will yet to trye me further how I can beare his hand**”_ (FERRAR_001.144; Nicholas Ferrar to Nicholas and Mary Ferrar; 1613)
- (6c) _“**Keep close unto the lord, let him be the alpha and omega the begining and endeing of every day unto you, behould him ever behoulding you, make his word your rule and his spirit your guide**”_ (BARRING_023.379; James Harrison to Joan Barrington; 1629)
- (6d) _“I find myself very faint and weak, but yet as little strength as I seem to have, I still indure those violent paines \[...\], and that more frequently than ever. I cannot dissemble so much as not to professe myself very weary of this condition. **I pray God enable me with patience to bear whatsoever my sad fate hath designed for me and give me that entire resignation to his will which I endeavour after and do stand in so much need of.**”_ (CONWAY_057.174; Anne Conway (née Finch) to Henry More; 1664)


Curiously, these phrases are the only types of divine appeals that grow more frequent as time proceeds. This ties in with the ubiquitous observation that more formulaic divine appeals tend to diminish over time, while less formulaic phrases (which perhaps reflect a more solemn or personal faith) go up.


```python tags=["hermeneutics"]
# Compute normalised frequency of agency per correspondence
# -----------------------------------------------

# divide into god and non-god
df_god = df_annotations[df_annotations["query"] == "god"]
df_nongod = df_annotations[df_annotations["query"] != "god"]

# get all text ("wc" is "word count)
tfull_index = df_social.pivot_table(index="correspondence",values="wc").index

# compute stats for non-god
tnongod = df_nongod.pivot_table(index="CORRESPONDENCE",columns=["AGENCY"],values="hit",aggfunc="count",fill_value=0,dropna=False)
tnongod["wc"] = df_social.pivot_table(index="correspondence",values="wc",aggfunc="sum",fill_value=0)["wc"]
tnongod["year_of_writing"] = df_social.pivot_table(index="correspondence",values="year_of_writing_N",aggfunc="mean",fill_value=0)["year_of_writing_N"]
tnongod

# Working out extrapolation rate for non-annotated god hits per correspondence
tgod = df_god.pivot_table(index="CORRESPONDENCE",columns=["AGENCY"],values="hit",aggfunc="count",fill_value=0,dropna=False)
tgod["TOTAL_HITS"] = df_god.pivot_table(index="CORRESPONDENCE",columns=["query"],values="hit",aggfunc="count",fill_value=0,dropna=False)
tgod["OOS_RATE"]  = tgod["OUT_OF_SAMPLE"]/(tgod["TOTAL_HITS"])
agency_labels = df_body.pivot_table(index="CORRESPONDENCE",columns=["AGENCY"],values="hit",aggfunc="count",fill_value=0,dropna=False).columns
agency_labels = agency_labels.drop(["OUT_OF_SAMPLE","X"])
print(agency_labels)

for col in agency_labels:
    tgod[col] += tgod[col]/(tgod["TOTAL_HITS"]-tgod["OUT_OF_SAMPLE"])*tgod["OUT_OF_SAMPLE"]

# define function to convert pivot tables into searchable mappings
def import_pivot(pivot):
    mapping = {}  
    for text_id,row in pivot.iterrows():
        mapping[text_id] = {}
        for col in pivot.columns:
            mapping[text_id][col] = row[col]
    return mapping

# create mappings for god and nongod
god_mapping = import_pivot(tgod)
nongod_mapping = import_pivot(tnongod)

# create final dataframe based on individual texts
tall = pd.DataFrame(index=tfull_index)
tall["wc"] = df_social.pivot_table(index="correspondence",values="wc",aggfunc="sum",fill_value=0)["wc"]
tall["year_of_writing"] = df_social.pivot_table(index="correspondence",values="year_of_writing_N",aggfunc="mean",fill_value=0)["year_of_writing_N"]
tall["OOS_RATE"] = tgod["OOS_RATE"]

all_columns = set(tgod.columns).union(set(tnongod.columns))
all_columns.remove("year_of_writing")
all_columns.remove("wc")
all_columns.remove("OOS_RATE")
for column in all_columns:
    tall[column] = np.zeros(len(tall))

# create function to import data in an empty dataframe based on mapping
def import_row(key,mapping,dfvar):
    if key in mapping:
        rowmapping = mapping[key]
        for col in all_columns:
            if col in rowmapping:
                dfvar.at[key,col] += rowmapping[col]
    return dfvar
    
# fill the dataframe with the data from the mappings
for text_id,row in tall.iterrows():
    tall = import_row(text_id,god_mapping,tall)
    tall = import_row(text_id,nongod_mapping,tall)


# normalize
tallnorm = pd.DataFrame(index=tfull_index)
tallnorm["wc"] = tall["wc"]
tallnorm["year_of_writing"] = tall["year_of_writing"]
tallnorm["OOS_RATE"] = tall["OOS_RATE"]
for column in all_columns:
    tallnorm["%s_NORM"%column] = 10000*tall[column]/tall["wc"]

tallnorm



```

```python tags=["hermeneutics"]
from matplotlib import pyplot as plt
import matplotlib as mpl
fig_rows = 1
fig_cols = 4

# create frame to plot in
i = 0
matrix = []
for r in range(fig_rows):
    row = []
    for c in range(fig_cols):
        row.append(i)
        i += 1
    matrix.append(row)
matrix = np.asarray(matrix)

fig, axs = plt.subplots(fig_rows,fig_cols,
                      figsize=(25,10),
                      sharey=True)

# set visual properties
sns.set(font_scale=2)
palette = sns.color_palette("husl",9)

# only plot divine appeals oriented towards the future
future_agency_cols=["DIVINE APPROVAL_NORM","CONFIDENCE_NORM","PRAYER_NORM","RESIGNATION_NORM"]

# only plot correspondences with over 10K words
tallnorm = tallnorm[tallnorm["wc"]>10000]

# create plot
for i,col in enumerate(future_agency_cols):
    sns.regplot(data=tallnorm, x="year_of_writing",y=col,lowess=True,ax=axs[(np.where(matrix==i)[1][0])],color=palette[i],y_jitter=0)

# style plot
plt.ylim(-2,30)
fig.suptitle("Diachronic evolution of agency\n",fontsize=36)
fig.text(0.5, 0.895, "one dot represents one correspondence (word count > 10k)", horizontalalignment="center")
fig.tight_layout()
fig.savefig("media/agency.png",dpi=400)
```

## Discussion


What does this systematic survey of divine appeals tell us about the self-perceived agency of letter writers throughout the early modern period?



First of all, our analysis indicates that it is very likely that an early modern person’s self-perceived agency has changed throughout the early modern period. In most writing communities, we see a decrease in the relative number of divine appeals as time progresses. Moreover, the divine appeals to wither first were typically the most formulaic ones: those in the opening and closing parts of the letters gradually disappeared throughout the period. A similar pattern is attested in all types of future-oriented divine appeals except for resignation.



In order to assess the relevance of these findings within the broader framework of secularisation, we first need to figure out to what extent the use of such formulae in letters reflects genuine faith. Did early modern people complement the announcement of their travel plans with “God willing” because they genuinely believed that God could (or would) interfere with their travels, or did they use that phrase simply because it was the conventional way to express reservation, similar to “touch wood” or “if all goes well” in present-day language? Perhaps unsurprisingly, this question leads right back to Clark’s distinction between religious practice and religious faith, and the heuristic impossibility to reliably deduce the latter from the former (<cite data-cite="9104992/6IX9C7NU"></cite>). Like all others, this study too fails to provide definite answers to the question how early modern people experienced faith, and how this experience fluctuated between people and across time.



When we shift the emphasis from the individual believer to the community as a whole, however, this study does provide some relevant insights. Regardless of whether a sixteenth-century author opened their letter with a divine appeal out of genuine faith or out of habit, the mere observation that this convention was discontinued in the sixteenth century indicates that such practices are not set in stone. Even if divine appeals were mere writing conventions, their fluctuation through time highlights their interplay with the culture they were embedded in. If we hypothesise that there was no change whatsoever in the religious experience of letter writers in the early modern period, it is highly unlikely that we would have found the fluctuations we attested, especially the ones that are at odds with the general direction of linguistic change. In that respect, the gradual decrease in virtually all divine appeals except for resignation can be thought of as an indication that secularisation first got hold of the domains in people’s lives that were already in their control.



At the same time, we also observe the emergence of new types of divine appeals, like the more solemn subtypes of confidence phrases, interpersonal prayers and resignation statements. In no way do these testify to a decrease in religiosity: the rise in resignation statements, for instance, presuppose one’s total surrender to the divine plan. In line with Sommerville’s (1992) conclusions on secularisation in early modern England, our results too hint at a qualitative change from religious culture to religious faith. The medieval concept of religion as a set of rituals, conventions and practices had made room for a more internalised belief centred around one’s personal relationship with God. Around the turn of the sixteenth century, it had become at once less common to implore divine assistance for all minor challenges one is faced with, but more common to acquiesce in the divine plan for the least controllable domains but most fundamental domains of life, like epidemics and warfare.



A second major conclusion of our study is that the shift described above did not take place to the same extent among all social groups. Where some seventeenth-century communities – above all puritan ones – appealed to God at a higher rate than ever before, a fair number of their contemporary letter writers barely used any divine appeals. In that respect, our corpus data clearly show just how much the reformation impacted the lives of early modern English people. While the fifteenth-century correspondences all used divine appeals in a moderate, uniform and quite formulaic manner, the seventeenth-century data seems to be divided into, on the one hand, a rather small group of correspondences that show elevated rates of solemn, specific divine appeals and on the other hand a majority of letter writers whose use of divine appeals had significantly dropped. This observation may serve as quantitative evidence that the reformation - viewed here as a process rather than an event - caused the English religious landscape to scatter into communities of different denominational identities, the members of which jointly created their own devotional practices through letter writing (cf. <cite data-cite="9104992/ABCVJC7F"></cite>, 3-4), which may be seen as a communal counterpart to more contemplative and individual spiritual diaries (<cite data-cite="9104992/7FR7VCTW"></cite>).



The exceptionally high rate of divine appeals in puritan communities in the first half of the seventeenth century warrants further research. It is unclear, for instance, whether their divergent behaviour is due to their religious persuasions as such, or to the precarious political circumstances that their puritan persuasion had placed them in. Whatever the cause be, the increase in calls for divine intervention in the first half of the seventeenth century curiously coincides with previous findings that the period of the civil war and the interregnum was an exceptionally fertile ground for apocalyptic and millenarian prophesies. 



Millenarist ideologies stem from the idea that the apocalypse would be preceded by a series of spectacular events. Inspired by a literal interpretation of the (vernacular) Bible, many people in early modern England interpreted the religious troubles and civil wars of their time - in particular the unprecedented execution of the king - as a clear sign that the apocalypse was on its way.  While it is unclear why the shift from passive to active millenarism took place precisely during the Interregnum. In Thomas's words, the Interregnum was characterised by above all by "a conviction held by so many of the Civil War sects that the period in which they lived was somehow the climax of human history, the era for which all previous events had been a mere preparation (<cite data-cite="9104992/G8U2CWIU"></cite>, 169)". While it remains to be seen whether the coinciding surge in millenarist prophesies and the peak in divine appeals are related, they do emphasise just how profound the imprints were that this turbulent passage of history has left in the minds of the people that lived through them.



A third take-away of this paper is related to its embedding in the historiography of the future. Koselleck's hypothesis that the coming of the _Sattelzeit_ in the late eighteenth century was characterised by a shift in people's perception of not just the future but even time itself, from being God-given and determined to being open and constructible. While Koselleck himself doesn't explicitly discuss the arrival of the _Sattelzeit_ in relation to the process of secularisation, the narrative he puts forward presupposes a process of this kind to have taken place around the mid-eighteenth century at the latest. In this light, the findings of the present paper can be seen as early empirical evidence of this shift. Even if the future became only truly open and constructible around the turn of the eighteenth century, the change was gradual rather than cataclysmic and had been building up for at least two centuries. The religious confusion that followed the Reformation had lasting impacts on people's relation with the future. Some of them saw their own agency diminished even further and fully resigned to the divine plan. Other people, however, took the opposite stance and had started to reclaim the more controllable domains of their lives as early as the 1550s, as witnessed by the steady decline in formulaic divine appeals, especially in contexts where human agency was already fairly high. In that respect, the quantitative analysis presented here clearly shows that the increasing demarcation of the sacred and the profane did not result in a linear decrease in divine appeals across the board. While some people did appeal less to divine entities than their ancestors did, the same demarcation caused members of devotional groups to develop an increasingly personal bond with the divine entities they implored (<cite data-cite="9104992/WE6MDB8W"></cite>).


## Conclusion



This paper has aimed to chart (changes in) a variety of early modern English people’s perceptions of their own future as belonging to God. Our systematic analysis of references to divine entities in the Corpus of Early Modern English Correspondence has revealed that while the formulaic divine references attested in the opening and closing parts of letters were clearly on their way out, the ones in the letter bodies showed a more intricate pattern that seemed to correlate especially with the religious denominations of the writers. The attested surge in mentions of divine entities in the first half of the seventeenth century is largely attributable to a limited number of puritan letter writers whose lives were dramatically caught up in the civil wars throughout the 1640s. The other letter writers in the corpus, by contrast, displayed progressively lower rates of divine mentions as time went by, a finding that is in line with previous research that characterised the early modern period as one which saw an increasing secularisation of future thought.



The second part of our study has zoomed in specifically on those divine appeals that were oriented towards the future and analysed them based on how they framed the respective agency of humans and divine entities in the unfolding of the events at stake. This case study yielded two main take-aways. First, it further corroborated the findings in the first part of this paper. Here too, the more formulaic a divine appeal was, the less frequent it grew over time. Because those appeals usually covered domains of life where the human agents already had a fair amount of control (e.g. travel or trade), it appears that the secularisation of the future unfolded itself first in those aspects of our letter writers’ lives where their agency was highest to begin with.



Second, our analysis of future-oriented divine appeals has stressed that the transition towards a more secular form of future thinking was by no means unidirectional. Despite a decline in the formulaic cases, two new types of future-oriented divine appeals grew popular throughout the seventeenth century. The solemn confidence statement and the resignation phrase not only gain frequency, they also evolve orthogonal to established mechanisms of linguistic change, indicating that their motivational factors are to be located in social, political or religious changes outside of the language. Further confirmed by their solemn character, the emergence of these phrases is in line with the findings of Sommerville’s large-scale study on the secularisation of early modern England, who describes the period as one characterised above all by a qualitative shift from a collective, ritual and cultural experience of religion in the late medieval times to a more solemn and personal attitude towards faith around the turn of the seventeenth century. Still, the fact that these shifts are attested in letters indicates that the communal aspect of piety should not be overlooked. Rather than a shift from collective to individual practices, then, the results of this paper testify to a form of piety that remains rooted in a sense of community, albeit intellectually rather than physically due to geographical separation. Pre-reformation Catholicism was so widespread that virtually anyone had someone to celebrate with nearby, which boosted the popularity of communal ritual celebration. When the reformation shattered the religious landscape, the number of denominations rapidly increased, as did the variation in devotional practice and, arguably, the geographical distance between members of the same community, which in turn shifted the emphasis from more physical forms of devotion (e.g. partaking in a procession) to more intellectual variants (e.g. writing).


Third, the present case study has provided empirical evidence that the "discovery of the future" as open and constructible in the late eighteenth century was not the result of a sudden break with the past, but the outcome of a process that had been simmering below the surface since at least the middle of the sixteenth century, when people ceased to use formulaic divine appeals for aspects of their life that they already had agency in themselves. Even if they did not believe (yet) that they had the power to change their futures on the long term, they did feel comfortable enough not to call for divine help for risky aspects of their lives - like travel - that their fifteenth century predecessors had still seen as an action of joint responsibility between themselves and God.
