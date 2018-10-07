---
title: Research
layout: page
---

<style>
.abstract {
  display: none;
  padding: 15px 25px;
  margin: 0 5px 10px 5px;
  background-color: #EEE;
}

div .p {
    padding: 5px 0 10px 0;

}
.cl{
    font-weight: bolder;
}

.place_holder {
    height: 10px;
}

</style>
### Publications

#### Peer-reviewed Journal Publications

&ldquo;quanteda: An R package for the quantitative analysis of textual data&rdquo; Forthcoming, _Journal of Open Source Software,_ 3(30), 774, with Kenneth Benoit, KoheiWatanabe, HaiyanWang, Paul Nulty, Adam Obeng, and Stefan Müller.
[[DOI]](https://doi.org/10.21105/joss.00774)


&ldquo;Multi-dimensional Policy Preferences in the 2015 British General Election: A Conjoint Analysis&rdquo; 2018, _Electoral Studies,_ 55, 89-98, with Seonghui Lee.
`[Abstract]`{:.cl}
[[DOI]](https://doi.org/10.1016/j.electstud.2018.07.005)


{:.abstract}
This research explores voter preferences in the multi-dimensional policy space of the 2015 UK general election, as well as the influence of those preferences on vote choice. In our original pre-election survey, we apply a conjoint experimental design where we use actual party manifestos to examine voters’ policy preferences across five main policy domains. This design allows us to both identify voters’ sincere preferences, as estimated by their responses to hypothetical policy packages, and to reveal the influence of these preferences on voter support in the actual election. Our analysis reveals a considerable level of congruence between voters’ underlying policy preferences and their vote choice in the 2015 election. Our results also speak to the previous literature on policy preferences and vote choice by demonstrating that voters not only weigh the importance of particular policy domains differently, but also have clear preferences regarding specific policy positions in a given domain, which eventually influence their support for a party in the election.


&ldquo;Decomposing Political Knowledge: What Is Confidence in Knowledge and Why It Matters&rdquo; 2018, _Electoral Studies,_ 51(1):  1-13, with Seonghui Lee.
`[Abstract]`{:.cl} [[DOI]](https://doi.org/10.1016/j.electstud.2017.11.005)

{:.abstract}
While political knowledge has been conceptually defined with two constructs – accuracy and confidence in factual information – conventional measurement of political knowledge has relied heavily on retrieval accuracy. Without measuring confidence-in-knowledge, it is not possible to rigorously identify different types of political informedness, such as misinformedness and uninformedness. This article theoretically explores the two constructs of knowledge and argues that each construct has unique antecedents and behavioral consequences. We suggest a survey instrument for confidence-in-knowledge and introduce a method to estimate latent traits of retrieval accuracy and confidence separately. Using our original survey that includes the measure of confidence-in-knowledge, we find that misinformed citizens are as engaged in politics as the well-informed, but their active involvement does not guarantee informed political choices. Our findings warrant further theoretical and empirical exploration of confidence in political knowledge.

&ldquo;Predicting the Brexit Vote by Tracking and Classifying Public Opinion Using Twitter Data.&rdquo; 2017, _Statistics, Politics and Policy,_ 8(1), 85-104, with Julio Amador, Sofia Collignon-Delmar, and Kenneth Benoit.
`[Abstract]`{:.cl}
[[DOI]](https://doi.org/10.1515/spp-2017-0006)

{:.abstract}
We use 23M Tweets related to the EU referendum in the UK to predict the Brexit vote. In particular, we use user-generated labels known as hashtags to build training sets related to the Leave/Remain campaign. Next, we train SVMs in order to classify Tweets. Finally, we compare our results to Internet and telephone polls. This approach not only allows to reduce the time of hand-coding data to create a training set, but also achieves high level of correlations with Internet polls. Our results suggest that Twitter data may be a suitable substitute for Internet polls and may be a useful complement for telephone polls. We also discuss the reach and limitations of this method.



&ldquo;The Effects of Election Proximity on Participatory Shirking: The Staggered-Term Chamber as a Laboratory.&rdquo; 2015,
_Legislative Studies Quarterly,_ 40(4),  599-625, with Kentaro Fukumoto. `[Abstract]`{:.cl}
[[DOI]](https://doi.org/10.1111/lsq.12090)

{:.abstract}
This study discusses a downside of electoral pressure. As elections approach, legislators reduce their effort in legislative activities, albeit while increasing their efficiency. To show this, we propose a new, natural experimental design exploiting staggered legislative election calendars to identify the effect of approaching elections. Two-way natural blocking improves the balance of pretreatments and an instrumental variable approach addresses noncompliance by retirees. Our analysis of the Japanese House of Councillors demonstrates that legislators up for election show up in the chamber less often than those not facing election; however, when they do show up and speak, they tend to speak longer.


&ldquo;Kokkai Giin Ha Naze Iinkai De Hatugen Suru No Ka? Seitou, Rieki, Senkyo Seido [Why Do Diet Members Speak in Committees? Political Parties, Legislators, and Electoral Systems].&rdquo; 2010, _Japanese Journal of Electoral Studies_, 26(2),  84-103, with Shunta Matsumoto [in Japanese].
`[Abstract in English]`{:.cl}

{:.abstract}
This article explains what determine the amount of speeches delivered by Japanese Lower House members at standing committees.  The literature has considered committees as merely obstacles to pass legislations or as an &ldquo;arena&rdquo; for debates only for partisan purposes.  This article argues that individual members' motivations are also important: members use speeches as opportunities for improving electoral fortunes, getting promotion in their party, and influencing policy by exerting their expertise.  To support this argument, the authors parse conference minutes in the 1980s and 2000s using Perl scripts and compile an original dataset on the amount of committee speeches given by individual House members.  The analyses show that there are three important determinants of speech amounts, which are members' electoral interests, policy expertise of each member, and partisan politics.  In addition, comparison between two decades suggests the changing pattern of members' speeches after the electoral reform in 1994.

#### Peer-reviewed conference proceedings

&ldquo;Findings from the Hackathon on Understanding Euroscepticism Through the Lens of Textual Data.&rdquo; 2018, ParlaCLARIN at the 11th edition of the Language Resources and Evaluation Conference (LREC2018), with Federico Nanni, Gran Glavas, Simone Paolo Ponzetto, [and 19 others].


### Work in Progress

&ldquo;Altruistic Motivations for Election Participation.&rdquo;

&ldquo;Brexit Debate through Social Media&rdquo; (with Kenneth Benoit)


### Software

R packages:

  - [spacyr](https://github.com/quanteda/spacyr) (with Kenneth Benoit, [CRAN](https://cran.r-project.org/web/packages/spacyr/index.html))
  - [kaigiroku](https://github.com/amatsuo/kaigiroku)
  - [wordshoal](https://github.com/kbenoit/wordshoal) (with Kenneth Benoit and Benjamin Lauderdale)

Interactive Online Experiment: [altruisticVoting](https://github.com/amatsuo/altruisticVoting), taxCompliance (both are implemented on [nodeGame](https://nodegame.org/))

<script src="https://code.jquery.com/jquery-latest.min.js"
        type="text/javascript"></script>

<script>
$(document).ready(function(){
  $(document).on('click touchstart', '.cl', function() {
    $(this).parent().next(".abstract").fadeToggle();
  });
});
</script>
