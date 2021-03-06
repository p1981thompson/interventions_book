# Controlling for selection bias: randomised assignment to intervention

In chapter 6, we saw how observational studies could be misleading because they are likely to contain unknown differences between intervention and control groups. Recognition of this limitation led to the development of the randomised controlled trial as a gold standard approach to the evaluation of interventions. The core idea is that once a target population has been identified for study, the experimenter allocates participants to intervention and control groups in a way that avoids any bias.

There is a quite substantial literature on methods of allocation to intervention. The main principle behind modern intervention studies is that allocation should be completely random, i.e. not predictable from any characteristics of participants. There are many approaches to treatment allocation that are designed to avoid bias but which are not random. For the time being we are ignoring the question of who does the randomisation: this will be discussed in Chapter 8. We also defer until later the question of recruitment and what to do about people who do not wish to take part in a trial. We assume we have a population of potential participants and have to decide who will be in the intervention group and who will be in the control group. Consider the following methods of allocation and note your judgement as to whether they are (a) reasonable ways of avoiding bias and (b) random.

A.	Allocate people to the intervention group until the desired sample size is reached; then allocate all subsequent cases to the control group
B.	Allocate the more severe cases to the intervention group and the less severe to the control group
C.	Alternate between intervention and control: thus the first person on the list is an intervention case and the last one is a control
D.	For each potential participant, toss a coin and allocate those with 'heads' to the intervention group and those with 'tails' to the control group
E.	Create pairs of people matched on a key variable such as age, and then toss a coin to decide which will be in the intervention group and which in the control group
F.	Create pairs of people matched on the baseline score on the outcome measure, and then toss a coin to decide which will be in the intervention group and which in the control group

If you have read this far, it is hoped that you will identify that B is clearly a flawed approach. Not only does it fail to equate the intervention and control groups at the outset, it also is likely to result in regression to the mean, so that greater gains will be seen for the intervention vs. the control group, for purely spurious statistical reasons. Despite its obvious flaws, this approach is sometimes seen in published literature – often taken to the extreme where an intervention group with a disorder is compared to a 'control' group with no disorder. This makes no sense at all – you are not controlling for anything unless the groups are equivalent at the outset, and so cannot evaluate the intervention this way.

Approach A is an improvement, but it is still prone to bias, because there may be systematic differences between people who are identified early in the recruitment phase of a study and later on. For instance, those who sign up immediately may be the most enthusiastic. Approach A also creates problems for blinding, which is discussed further in Chapter 9.

Most people think that Approach C as a reasonable way to achieve equal group sizes and avoid the kinds of 'time of recruitment' issues that arise with Approach A. But this is not a random approach and would therefore be regarded as problematic by modern standards of trials design. One reason, which I will discuss at more length in Chapter 8, is that this method could allow the researcher to influence who gets into the study. Suppose the experimenter allocates aphasic patients to a study to improve word-finding according to some systematic method such as their serial order on a list, but notices that the next person destined for the intervention group has particularly profound difficulties with comprehension. It may be sorely tempting to ensure that he had an 'odd' number rather than an 'even' number and so ended up in the control group. Similar objections arise to methods such as using a person's case number or date of birth as the basis for intervention assignment: although this may be a fixed characteristic of the person and so appear to avoid bias, it raises the possibility that the experimenter could simply decide not to include someone in the study if they were destined for the intervention group and looked unpromising. 

Approach D is clearly random, but it runs the risk that the two groups may be of unequal size and they may also be poorly matched on the pre-intervention measures, especially if sample sizes are small.

Approach E would seem like the logical solution: it avoids unequal sample sizes, ensures groups are comparable at the outset, yet includes randomisation. This method does, however, have some disadvantages: it can be difficult to apply if one does not have information about the full sample in advance, and can be problematic if participants drop out of the trial, so the matching is disrupted.

## Units of analysis: Individuals vs clusters 

In the examples given above, allocation of intervention is done at the level of the individual. There are contexts, however, where it makes sense to use larger units containing groups of people such as classrooms, schools or clinics. Research in schools, in particular, may not readily lend itself to individualised methods, because that could involve different children in the same class receiving different interventions. This can make children more aware of which group they are in, and it can also lead to 'spill-over' effects, whereby the intervention received by the first group affects other children who interact with them. It may make sense for children in classroom A to have one intervention and those in classroom B to have a control intervention. This is what happens in a clustered trial.

This method, however, raises new problems, because we now have a confound between classroom and intervention. Suppose the teacher in classroom A is a better teacher, or it just so happens that classroom B contains a higher proportion of disruptive pupils. In effect, we can no longer treat the individual as the unit of analysis. In addition, we may expect the children within a classroom to be more similar to one another than those in different classrooms, and this has an impact on the way in which the study needs to be analysed. Clustered studies typically need bigger sample sizes than non-clustered ones. We will discuss this issue further in Chapter 17.

## Class exercise

Use a literature search for an intervention/disorder of interest with the term 'randomised controlled trial' or RCT, and download the article.
Is the randomisation process clearly described? Is it adequate?

## Randomization methods

### Simple randomization

In our earlier examples from the start of this chapter, we saw various examples of simple randomization (A-D). This takes the idea of the "coin toss" but adds in some degree of control of other variables which might affect the result. Typically, a coin is not used as the random nature of the coin toss means that balanced numbers in each group will not be guaranteed. A randomization list is created by an individual who is unrelated to the trial. This list contains an equal number of allocations for a fixed number of participants which will have been pre-specified according to a sample size calculation. Our first issue is that the allocation list does not allow for individuals dropping out before assignment of intervention. This means that we potentially can have unbalanced groups despite following the list. 

Furthermore we saw earlier, simple randomization does not suffciently control unknown variables which may exhert an effect on the outcome, i.e. overrepresentation of a particular feature in one group that influences the outcome. For example, we randomize children with a language difficultly into two groups, but we find that there are more boys than girls in one group. The intervention sees an effect as predicted, but on further inspection we find that the group difference is confounded by gender.

Simple randomization is rarely (if at all) used in practice, so other approaches have been developed to counter the drawbacks encoutered.  

### Random permuted blocks

The permutated blocks approach tries to overcome the unbalanced problem by allocating individuals into blocks. The idea is that patients are allocated to intervention or control in blocks, so that at certain equally spaced points across the trial, equal numbers are ensured. Let's see how this works using an example: 

Say we have chosen out block size to be 4. So, in each block we have 2 assigned to intervention and 2 to control group. The order of assignment of each block is random, for example, ABAB, AABB, ABBA, BBAA, BAAB, and so on. This means at any point in the trial, the randomization is only ever two individuals unbalanced if the trial stops short or fails to recruit sufficient numbers of inidividuals, so the imbalance is minimal and statistical power is maintained.

However, permuted blocks has an unfortunate downside as it is relatively straighforward for the researcher to see a pattern emerge in the allocation, so the randomization can become predictable. This is problematic, if the next allocation is known to the researcher as control and the next child for allocation is a particularly severe case who could benefit from the intervention. This would rely on the researcher making a difficult moral judgement to continue with correct allocation and not deviate.

### Unequal randomization

The approach of unequal randomization differs from the convention of 1:1 allocation ratio. A fixed ratio is decided on before allocation of individuals begins, for example, 2:1 intervention vs control allocation. Use of this method should be considered carefully as there are both pros and cons. On the positive side, we may obtain a more accurate estimate of the effects of intervention, but we are prone to a reduction in power. 

> "Unequal allocation also has consequences for statistical power. For example, a 2:1 allocation ratio requires 12% more patients than a trial using 1:1 to detect the same size effect with equivalent power; a 3:1 randomization scheme requires 33% more patients."

Hey, S. P., & Kimmelman, J. (2014). The questionable use of unequal allocation in confirmatory trials. Neurology, 82(1), 77-9.


### Stratification

The previously discussed randomizations have dealt with the unbalanced groups but we are still in need of a way to counter the effect of known or unknown variables on the outcome. Stratification is the first method to permit some control of these variables by splitting the allocation according to those variables. For example, suppose we have an intervention for school aged children and we have a exclusion criteria that they must be between the ages of 5 and 11. We also provide the intervention at three different schools, one inner city school in a low SES area, one public school requiring fees, and a small remote village school. We would anticipate that there might be significant performance differences in age and potentially differences between schools, so we must allow for this when we randomize children to intervention and control groups. The scheme would follow the table below,

<table class="table table-striped table-bordered" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:strattable)Randomized allocation by stratas: Age, School</caption>
 <thead>
  <tr>
   <th style="text-align:left;">   </th>
   <th style="text-align:center;"> Intervention </th>
   <th style="text-align:center;"> Control </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school1, ages 5-7 </td>
   <td style="text-align:center;"> 23 </td>
   <td style="text-align:center;"> 24 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school2, ages 8-9 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 31 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school3, ages 10-11 </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> 27 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school1, ages 8-9 </td>
   <td style="text-align:center;"> 19 </td>
   <td style="text-align:center;"> 20 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school2, ages 10-11 </td>
   <td style="text-align:center;"> 25 </td>
   <td style="text-align:center;"> 24 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school3, ages 5-7 </td>
   <td style="text-align:center;"> 35 </td>
   <td style="text-align:center;"> 35 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school1, ages 10-11 </td>
   <td style="text-align:center;"> 22 </td>
   <td style="text-align:center;"> 27 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school2, ages 5-7 </td>
   <td style="text-align:center;"> 24 </td>
   <td style="text-align:center;"> 23 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;"> school3, ages 8-9 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 31 </td>
  </tr>
</tbody>
</table>

### Minimization

An alternative to stratification called minimization is also very popular in clinical RCTs. Its popularity has grown in recent years as stratifcation becomes weaker when the number of strata increases and is particularly susceptable when used in smaller trials. Minimization was first proposed by Pocock and Simon (ref) and is referred to as a dynamic or adaptive randomization. Each participant's allocation is dependant on the characteristics and allocation of participants already allocated to groups. The idea is to minimise the imbalance by considering a range of factors for each allocation. This prevents the allocation of particular sub groups into one allocation which may happen in any of the aforementioned methods. To demostrate this method, we restate the example from Scott et al. (2002), using table \@ref(tab:minitable):


<table class="table table-striped table-bordered" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:minitable)Randomized allocation by minimization</caption>
 <thead>
  <tr>
   <th style="text-align:center;"> Prognostic factor </th>
   <th style="text-align:center;"> Intervention </th>
   <th style="text-align:center;"> Control </th>
  </tr>
 </thead>
<tbody>
  <tr grouplength="2"><td colspan="3" style="border-bottom: 1px solid;"><strong>Sex</strong></td></tr>
<tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> Male </td>
   <td style="text-align:center;"> 3 </td>
   <td style="text-align:center;"> 5 </td>
  </tr>
  <tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> Female </td>
   <td style="text-align:center;"> 5 </td>
   <td style="text-align:center;"> 3 </td>
  </tr>
  <tr grouplength="3"><td colspan="3" style="border-bottom: 1px solid;"><strong>Age band</strong></td></tr>
<tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> 21-30 </td>
   <td style="text-align:center;"> 4 </td>
   <td style="text-align:center;"> 4 </td>
  </tr>
  <tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> 31-40 </td>
   <td style="text-align:center;"> 2 </td>
   <td style="text-align:center;"> 3 </td>
  </tr>
  <tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> 41-50 </td>
   <td style="text-align:center;"> 2 </td>
   <td style="text-align:center;"> 1 </td>
  </tr>
  <tr grouplength="2"><td colspan="3" style="border-bottom: 1px solid;"><strong>Risk factor</strong></td></tr>
<tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> High </td>
   <td style="text-align:center;"> 4 </td>
   <td style="text-align:center;"> 5 </td>
  </tr>
  <tr>
   <td style="text-align:center;font-weight: bold; padding-left: 2em;" indentlevel="1"> Low </td>
   <td style="text-align:center;"> 4 </td>
   <td style="text-align:center;"> 3 </td>
  </tr>
</tbody>
</table>
>If we now consider allocation of the 17th participant who has factors: Male, 31-40, and High.
>**Using the Pocock and Simon's method**

>If allocated to intervention group, total imbalance is $$|(3+1)-5|+|(2+1)-3|+|(4+1)-5|=1$$.
>If allocated to control group, total imbalance is $$|3-(5+1)|+|2-(3+1)|+|4-(5+1)|=7$$. 
>Patient allocated to the group that would lead to less overall imbalance.
>Therefore 17th participant allocated to intervention group because $$1<7$$.

### Adaptive randomisation 

