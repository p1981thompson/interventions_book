


# How to select an outcome measure

Suppose you want to evaluate the effectiveness of a parent-based intervention for improving communication in three-year-olds with poor language skills. You plan to assess their skills before the intervention, immediately after the intervention, and again six months later. The initial measurement period is known as the baseline – because it acts against as a reference point against which improvement can be measured.

There are many measures you could choose: the child's mean length of utterance (MLU), scores on a direct assessment such as preschool CELF, the parent's response on a language inventory such as xxx. You may wonder whether you should include as many measures as possible to ensure you cover all bases. However, as we shall see in chapter x, if you measure too many things, you run the risk of getting spurious results, so it is important to specify a primary outcome measure – the one you would put your money on as most likely to show the effect of interest, if you were a betting person. 

The key questions you have to ask yourself are:

1.	Is the measure reliable?
2.	Is it sensitive?
3.	Is it valid? i.e., does it measure what I want to measure?
4.	Is it practical?

## Reliability

You may be surprised to see reliability at the top of the list. Surely validity is more important? Well, yes and no. As shown in Figure x, there's not much point in having a measure that is reliable unless it is also valid. But a measure that is valid but not reliable is worse than useless in an intervention study, so I put reliability at the top of the list.
(targets figure here)

So what is reliability? This has to do with the issue of random error or 'noise', which can be estimated by seeing how far scores on one testing occasion line up with scores on another occasion close in time (i.e. before we expect any change due to maturation or intervention). Quite simply you want a measure that reflects the child's underlying skill, where there is minimal influence from random, unwanted sources of variation. So if we have two occasions of measurement, they should be closely similar. The similarity can be quantified by a correlation coefficient, demonstrated in Figure x.

<div class="figure">
<img src="02-outcomes_files/figure-html/correlation-1.png" alt="The correlation coefficient is a statistic that takes the value of zero when there is no relationship between two variables, one whether there is a perfect relationship, and minus one when there is an inverse relationship. If you draw a straight line through the points on the graph, then if all points fall exactly on the line, the correlation is 1, indicating that you can predict perfectly a person's score on Y if you know their score on X." width="864" />
<p class="caption">(\#fig:correlation)The correlation coefficient is a statistic that takes the value of zero when there is no relationship between two variables, one whether there is a perfect relationship, and minus one when there is an inverse relationship. If you draw a straight line through the points on the graph, then if all points fall exactly on the line, the correlation is 1, indicating that you can predict perfectly a person's score on Y if you know their score on X.</p>
</div>


<!-- Paul comment: I wondered whether to mention Anscombe's Quartet here as a limitation of the correlation. It should be under the assumption that the data follow the same pattern to assess reliability.-->

<div class="figure">
<img src="02-outcomes_files/figure-html/anscombequartet-1.png" alt="Anscombe's Quartet" width="576" />
<p class="caption">(\#fig:anscombequartet)Anscombe's Quartet</p>
</div>

<table class="table table-striped table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:AQTable)Different data same correlation</caption>
 <thead>
  <tr>
   <th style="text-align:center;"> plot </th>
   <th style="text-align:center;"> cor(x, y) </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> 1 </td>
   <td style="text-align:center;"> 0.8164205 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2 </td>
   <td style="text-align:center;"> 0.8162365 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 3 </td>
   <td style="text-align:center;"> 0.8162867 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 4 </td>
   <td style="text-align:center;"> 0.8165214 </td>
  </tr>
</tbody>
</table>


Let's illustrate this with mean length of utterance (MLU). Roger Brown's classic work first showed that in very young children this is a pretty good indicator of a child's language level (ref and ?plot). As children grow older, though, it become less useful, and it may be strongly influenced by the context in which language is sampled. Length of the language sample will also be important: if you just based a MLU estimate on ten child utterances, then the estimate will be less stable than if you took 50 utterances. 

We can't say that MLU is inherently good or bad on the reliability front: it will depend on numerous factors. It may work well if assessed from a reasonable length of language sample collected in closely similar contexts. Reliability may be better for a clinical sample, where language skills are less variable, than for typically-developing children. The important thing is to find out as much as you can about reliability before committing to an outcome measure – or even better, do your own test-retest study with the measures of interest before embarking on a study.

So how reliable should a measure be? Most psychometric tests report reliability estimates, and a good test is expected to have test-retest reliability of at least .8. But be careful in interpreting such estimates, as you need also to consider the age range on which the estimate is based. Figure x shows how a test that has very poor reliability within 3-year-olds looks highly reliable when considered across the full age range from 3 to 8 years. This is because the index of reliability, the correlation coefficient, is affected by the range of scores. If your study is focused just on 3-year-olds, you really want to know how reliable it is just within that age range.

The topic of reliability is covered more formally in test theory (ref). This involves a mathematical approach that treats an observed test score as the sum of a 'true' effect (i.e. what you want to measure) plus random error. The lower the reliability, the greater the random error, and the harder it is to detect the true effect of intervention against the background of noise. Figure x illustrates this.
(illustrative figure)

I have focused on test-retest reliability as this is the most relevant in intervention studies. If you plan to use the same measure at baseline and after intervention, then what you need to know is how much variation in that measure is likely to occur just by chance. There are other reliability indices that are sometimes reported with psychometric tests. In particular split-half reliability and internal consistency (Cronbach's alpha), both of which consider the extent to which a score varies depending on the specific items used to calculate it. For instance, we could assess split half reliability for MLU by computing it separately for all the odd-numbered utterances and the even-numbered utterances. Although this gives useful information, it is usually overestimates test-retest reliability, because it does not take into account fluctuations in measurement that relate to changes in the context or the child's state. 

It is much easier to compute measures of internal consistency than to do the extra testing that is needed to estimate test-retest reliability, and many published psychometric tests only provide that information. Table x shows reliability estimates from some commonly used tests.
(table 

## Sensitivity

Those who develop psychometric tests often focus on reliability and validity but neglect sensitivity. Yet sensitivity is a vital requirement for an outcome measure in an intervention study. This refers to the grain of the measurement: whether it can detect small changes in outcome. Consider Bridget Jones on a holiday to a remote place where there are no scales, just a primitive balance measure that allows her to compare herself against weights of different sizes (cartoon here). She would be unable to detect the daily fluctuations in pounds, and only be able to map her weight change in half-stone units. She could genuinely lose weight but be unaware of the fact.

Many standardized tests fall down on sensitivity, especially in relation to children scoring at the lower end of the ability range. It is customary to convert raw scores into scaled scores on these tests. This allows us to have a single number that can be interpreted in terms of how well the child is performing relative to others of the same age. But these often reduce a wide range of raw scores to a much smaller set of scaled scores, as illustrated in Table x. This means that a child could make substantial gains in raw score after intervention, but still come out with the same scaled score.
(Cathy Adams; Elspeth McCartney; EEF)

For this reason, it is often recommended that raw scores be used for evaluating intervention effects. This is fine if the study involves a narrow age range, but it is more problematic when a wider range is used, because age will be a major determinant of test score. Indeed, that is one reason why scaled scores are often preferred: they allow us to compare children of different ages on the same metric – i.e. a score that reflects how the child's performance relates – statistically – to that of a normative group of the same age.

In the case where a wide age range is used, raw scores can work well provided an appropriate statistical analysis is performed to take into account the age differences. We will cover this topic in chapter x.

Problems with sensitivity can also be an issue with measures based on rating scales. For instance, if we just categorise children on a 5-point scale as 'well below average', 'below average', 'average', 'above average' or 'well above average', we are stacking the odds against showing an intervention effect – especially if our focus is on children who are in the bottom two categories to start with. Yet we also know that human raters are fallible and may not be able to make finer-grained distinctions. Some instruments may nevertheless be useful if they combine information from a set of ratings.

Although we need sensitive measures, we should not assume that a very fine-grained measure is always better than a coarser one. For instance, we may be measuring naming latency in aphasic patients as an index of improvement in word-finding. It's unlikely that we need millisecond precision in the timing, because the changes of interest are likely to be in the order of tenths of a second at most. While there's probably no harm in recording responses to the nearest millisecond, this is not likely to provide useful information.

## Measuring the right thing: validity

A modification of a popular adage is 'If a thing is not worth doing, it's not worth doing well.' This applies to selection of outcome measures: you could have a highly reliable and sensitive measure, but if it is not measuring the right thing, then there's no point in using it.

Deciding what is the 'right thing' is an important part of designing any invention study, and it can be harder than it appears at first sight. The answer might be very different for different kinds of intervention. I'll start with an issue that is particularly relevant to the first and third vignettes from chapter 1, word-finding intervention for aphasia, and the classroom-based vocabulary intervention 

Generalisability of results: the concepts of far and near transfer
The vignettes on word-finding intervention and vocabulary training illustrate interventions that have a specific focus.  This means we can potentially tie our outcome measures very closely to the intervention: we would want to measure speed of word-finding in the first case, and vocabulary size in the second. 

There is a risk, though, that this approach would lead to trivial findings. If we did a word-finding training with an aphasic patient using ten common nouns and then showed that they his naming had speeded up on those same ten words, this might give us some confidence that the training approach worked (though we would need appropriate controls, as discussed in later chapters). However, ideally, we would want to the intervention to produce effects that generalised and improved his naming across the board. Similarly, showing that a teaching assistant can train children to learn ten new animal names is not negligible, but it doesn't tell us whether this approach has any broader benefits.

These issues can be important in situations such as phonological interventions, where there may be a focus on training the child to produce specific contrasts between speech sounds. If we show that they master those contrasts but not others, this may give us confidence that it was the training that had the effect, rather than spontaneous maturation (see Chapter x), but at the same time we might hope that training one contrast would have an impact on the child's phonological system and lead to improved production of other contrasts that were not directly trained.

These examples illustrate the importance of testing the impact of intervention not only on particular training targets, but also on other related items that were not trained. As noted above, this is something of a two-edged sword. We may hope that treatment effects will generalise, but if they do, it can be difficult to be certain that it was our intervention that brought about the change. The important thing when planning an intervention is to think about these issues and consider whether the mechanism targeted by the treatment is expected to produce generalised effects, and if so to test for those. This is discussed further in chapter 4.

The notion of generalisation assumes particular importance when the intervention does not directly target skills that are of direct relevance to everyday life. An example is CogMed training, which is a computer-based intervention that has been promoted as a way of improving children's working memory and intelligence. The child plays games that involve visual tasks that tax working memory, with difficulty increasing as performance improves. Early reports maintained that training on these tasks led to improvement on nonverbal intelligence, as assessed by Raven's Matrices. However, more recent literature has challenged this claim, arguing that what is seen is 'near transfer' – i.e. improvement in the types of memory task that are trained – without any evidence of 'far transfer' – i.e. improvement in other cognitive tasks. This is still a matter of hot debate, but it seems that many forms of 'computerised brain training' that are available commercially give disappointing results. If repeatedly doing computerised memory exercises only improves the ability to do those exercises, with no 'knock on' effects on everyday functioning, then the value of the intervention is questionable. It would seem preferable to use the time on training skills that would be useful in the classroom.

## Functional outcomes vs test scores

In the second vignette we have an intervention where issues of far and near transfer are not relevant, as the intervention does not target specific aspects of language, but rather aims to modify the parental communicative style in order to provide a general boost to the child's language learning and functional communication. This suggests we need a rather general measure, and we are likely to consider using a standardized language test because this has the advantage of providing a reasonably objective and reliable approach to measurement. But does it measure the things that clients care about? Would we regard our intervention as a failure if the child made little progress on the standardized test, but was much more communicative and responsive to others? Or even if the intervention led to a more harmonious relationship between parent and child, but did not affect the child's language skills?

We might decide that these are the most important key outcomes, but then we have to establish how to measure them. In thinking about measures, it is important to be realistic about what one is hoping to achieve. If, for instance, the therapist is working with a client who has a chronic long-term problem, then the goal may be to help them use the communication skills they have to maximum effect, rather than to learn new language. The outcome measure in this case should be tailored to assess this functional outcome, rather than a gain on a measure of a specific language skill. 

## Subjectivity as a source of bias

In chapters x and x I will discuss various sources of bias that can affect studies, but one that crops up at the measurement stage is the impact of so-called 'demand characteristics' on subjective ratings. Consider, for a moment, how you respond when a waiter comes round to ask whether everything was okay with your meal. There are probably cultural differences in this, but the classic British response is to smile and say it is fine even if it was disappointing. We tend to adopt a kind of 'grade inflation' to many aspects of life when asked to rate them, especially if we know the person whose work we are rating.  

In the context of intervention, people usually want to believe that interventions are effective and they don't want to appear critical of those administering the intervention, and so ratings of language are likely to improve from baseline to post-test, even if no real change has occurred. This phenomenon has been investigated particularly in situations where people are evaluating treatments that have cost them time and money (cognitive dissonance) but it is likely to apply even in experimental settings when interventions are being evaluated at no financial cost to those participating.

An example of this in the published literature comes from x et al who did a small-scale study to evaluate a computerised language intervention, FastForword (FFW). I will discuss larger evaluations of FFW in chapter x, but this study is noteworthy because as well as measuring children's language pre and post intervention, it included parent ratings of children's outcomes. There was a striking dissociation between the positive parent reports and the lack of improvement on language tests. 
Another example comes from a well-conducted trial of 'Sunshine therapy' for children with a range of neurodevelopmental disorders; here again we see that parents were very positive about the intervention, while objective measures showed children had made not significant progress relative to a control group.

Such results are inherently ambiguous. It could be that parents are picking up on positive aspects of intervention that are not captured by the language tests. For instance, in the Sunshine therapy study, parents reported that their children had gained in confidence – something that was not assessed by other means. However, there it is hard to know whether these evaluations are valid, as they are likely to be contaminated by demand characteristics.

Ideally we want measures that are valid indicators of things that are important for functional communication, yet are reasonably objective – and they need also to be reliable and sensitive! I don't have simple answers as to how this can be achieved, but it is important for researchers to discuss these issues when designing studies to ensure they achieve optimal measures.

## Is it practical?

Intervention research is usually costly because of the time that is needed to recruit participants, run the intervention and do the assessments. There will always be pressures, therefore, to use assessments that are efficient, and provide key information in a relatively short space of time. 

In my career I have occasionally been asked to advise people who are designing an intervention study, and I find that practicality is often very low on the list of topics that is discussed. A common experience is that the researchers want to measure everything they can think of in as much detail as possible. This is understandable: one does not want to pick the wrong measure and so miss an important impact of the intervention. But, as noted above, and discussed more in chapter x, there is a danger that too many measures will just lead to spurious findings. And each new measure will incur a time cost, which will ultimately translate to a financial cost, as well as potentially involving participants in additional assessment. There is, then, an ethical dimension to selection of measures: we need to optimise our selection of outcome measures to fulfil all the criteria of reliability, sensitivity and validity, but also to be as detailed and complex as we need, but no more. 

My interest in efficiency of measurement may be illustrated with a vignette. When I started out in research, I was not involved in an intervention study, but I was embarking on a longitudinal study of 4-year-olds with developmental language disorders (Bishop & Edmundson, 1987). I took advice on what measures to use, and a common piece of advice was that I should take a language sample, and then analyse it using LARSP (Crystal et al.,xxxx), which at the time was a popular approach to grammatical analysis. Fortunately, I also had the chance to meet Catherine Renfrew, a retired SLT who had developed some language assessments for this age range – a sentence elicitation task, the Action Picture Test – and a narrative task – the Bus Story. As a practising therapist, Renfrew saw the need for short assessments that were easy to administer and interpret, and the tests she had developed fitted the bill. 

I tried language sampling in my study but it seemed to provide little useful information in relation to the time it took to gather and transcribe the sample. Many of the children in my study rather little and did not attempt complex constructions. I found I could get more information in five minutes with the two Renfrew tests thank I could in 30 minutes of language sampling. Furthermore, I had more confidence in the test results, as all children were given the same task. When I came to do a grammatical analysis, I found that, after many hours of training in LARSP, analysing the results, and attempting to extract a quantitative measure from this process, I ended up with something that had a correlation of greater than .9 with mean length of utterance (MLU). The lesson I learned was that the measure needs to fit the purpose of what you are doing. I wanted an index of grammatical development that could be used to predict children's future progress. The Renfrew tasks provided to be among the most effective measures for doing that. A therapist working with a child might well find LARSP and language sampling useful for identifying therapy targets and getting a full picture of the child's abilities, but for my purposes this was far more detail than I needed. 

There are other cases where researchers do very complex analysis in the hope that it might give a more sensitive indicator of language, only to find that it is highly intercorrelated with a much simpler index: use of xx index in nonword repetition is one example – this score, which takes into account the specific errors made in nonword repetition, is highly correlated with a score based on number of nonwords correct. In the domain of expressive phonology, it was only after I tried to develop an index based on analysis of phonological processes that I found that this was entirely predictable from a much simpler measure of percentage consonants correct. 

A related point is that researchers are often tempted by the allure of the new, especially when this is associated with fancy technology, such as methods of brain scanning or eye-tracking. Be warned: these approaches yield masses of data that are extremely complex to analyse, and they typically are not well-validated in terms of reliability, sensitivity or validity! Even when high-tech apparatus is not involved, the newer the measure, the less likely it is to be psychometrically established – some measures of executive functioning fall in this category, as well as most measures that are derived from experimental paradigms.  Clearly, there is an important place for research that uses these new techniques to investigate the nature of language disorders, but that place is not as outcome measures in intervention studies. 

So, on the basis of my experience, I would advise that if you are tempted to use a complex, time-consuming measure, it is worthwhile first doing a study to see how far it is predictable from a more basic measure targeting the same process. It may save a lot of researcher time and we owe it to our research participants to do this due diligence to avoid subjecting them to unnecessarily protracted assessments. 

## Class exercise

Pick one of the three vignettes from Chapter 1 – or if you prefer, pick another intervention scenario – and make a list of possible outcome measures. For each one, evaluate its reliability, sensitivity, validity and practicality. At the end of this exercise, try to come up with a primary outcome measure that will be best for demonstrating an effect of intervention.

 
