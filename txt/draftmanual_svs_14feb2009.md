**DRAFT USERS MANUAL**

**Proper Use of the Schwartz Value Survey**

**Prof. Shalom H. Schwartz**

**Compiled by Rome Littrell, *crossculturalcentre@yahoo.com***

**12 July 2008**

*Citation:* Schwartz, Shalom H. (2009). Draft Users Manual: Proper Use of the Schwarz Value Survey, version 14 January 2009, compiled by Romie F. Littrell. Auckland, New Zealand: Centre for Cross Cultural Comparisons, *http://www.crossculturalcentre.homestead.com*.

When carrying out research projects using the Schwartz Values Survey:

You will need to know the first language of the participants and administer the survey in that language unless you are investigating cultural accommodation of language. See the cultural accommodation of survey language research publications by David Ralston and Anne-Wil Harzing. The SVS is available in many languages.

For the SVS, the usual scoring procedures are discussed in Schwartz 1992 and 1994. First, the 45 SVS value items that demonstrated the strongest reliability across cultures are used to calculate the value types by computing the mean importance rating of the value items that represent each value type (Schwartz, 1992, 1994). Then the entire list of value items (i.e., 57 or 58) are used to calculate an individual’s mean to control for scale use when analyzing the SVS values (Schwartz, 1992). Finally, the four higher order dimensions were calculated by averaging the relevant value types.

A number of things need to be communicated or else you are liable to obtain distorted results. To assure obtaining useful, comparable data and results, please contact crossculturalcentre@yahoo.com for consultation on design and analysis of studies using the SVS. Help will be available for questions dealing with each of the following:

1. It is critical to clean data collected before doing analyses. There are standard criteria used to drop respondents who have not tried to discriminate among their values, who have skipped too many items, or who have responded in ways suggesting deliberate misrepresentation.

**Automating the Process: SPSS Code for Cleaning Data**

\*Cleaning SVS57 data

\*FIRST STEP: CALCULATING I.

COUNT C0=v1 to v57(0).

COUNT C1=v1 to v57(1).

COUNT C2=v1 to v57(2).

COUNT C3=v1 to v57(3).

COUNT C4=v1 to v57(4).

COUNT C5=v1 to v57(5).

COUNT C6=v1 to v57(6).

COUNT C7=v1 to v57(7).

COUNT C8=v1 to v57(SYSMIS).

COUNT C9=v1 to v57(-1).

do IF (C0 ge 35 OR C1 GE 35 OR C2 GE 35 OR C3 GE 35 OR C4 GE 35

OR C5 GE 35 OR C6 GE 35 OR C7 GE 21 OR C8 GE 15 or c9 ge 35).

compute i=1 .

else .

compute i=2.

end if.

exe.

freq var=i.

\*SECOND STEP: DELETING.

select if (i=2).

exe.

freq var=i.

2. Individual differences in use of the response scale must be controlled when doing analyses. This is ordinarily done by using the individual’s mean rating of all value items as a covariate. There are specific instructions for doing this.

3. In order to assess the extent to which items have their expected meanings, it is desirable to do a structural analysis within each sample. This also reveals the structure of relations among the ten values and clarifies whether there are problems in using the standard a priori indexes for group comparisons. Help in conducting these analyses and/or instructions on how to obtain the statistical package to do it will also be available.

4. When the analysis planned is group level rather than individual level, researchers need to correct for scale use differences among groups. There are standard procedures for doing this.

5. It is often not clear whether the appropriate analysis for a researcher’s purposes is to use the ten individual level values or the seven culture level value orientations. The SVS can be used for both purposes, but the analyses differ. If there is a glimmer of doubt, consultation with Prof. Schwartz is desirable which can be accomplished through forwarding of the initial contact and questions via *crossculturalcentre@yahoo.com* .

**Structural Analysis: Smallest Space Analysis**

The package that is needed to replicate the original structural analysis is called HUDAP. It is available for about US$300 from the Hebrew University Computer Center. It can be purchased, together with its manual and available help from Dr. Reuven Amar. His e-mail is: *reuben@mscc.huji.ac.il*

This package offers a large number of different non-parametric statistics of which SSA, the one used for structural analyses, is one. For help in interpreting results of such analyses, it is best to consult my article: Schwartz, S.H., & Sagiv, L. (1995). Identifying culture specifics in the content and structure of values. *Journal of Cross-Cultural Psychology*, *26*, 92-116.

The same analysis can be done using the SYSTAT subprogram in some versions of SPSS available as an added component of SPSS at extra cost. In SYSTAT, there is an MDS program which offers a Guttman-Lingoes option that is equivalent to SSA.

> **Keying of SVS-57 Ten Individual Level Value Scales and **
>
> **Seven Cultural Level Value Orientations**

**Discussion of items that are and are not included in the SVS indexes is found in several of Prof. Schwartz’ publications.** Only items that demonstrated near equivalence of meaning in at least 75% of cultures are included. The other items (some 11 or 12 of them) are usable within cultures after doing a structural analysis that indicates what they mean.

See:

For the individual values:

Schwartz, S. H. (1992). Universals in the content and structure of values: Theory and empirical tests in 20 countries.  In M. Zanna (Ed.), *Advances in experimental social psychology (Vol. 25)* (pp. 1-65). New York: Academic Press.

Schwartz, S.H. (1994b). Are there universal aspects in the content and structure of values? *Journal of Social Issues*, Vol. *50*, No. 4, pp. 19-45.

Schwartz, S.H., & Sagiv, L. (1995). Identifying culture specifics in the content and structure of values. *Journal of Cross-Cultural Psychology*, *26*, 92-116.

For the culture level, see:

Schwartz, S.H. (1999). Cultural value differences: Some implications for work. *Applied Psychology: An International Review*, *48,* 23-47.

Schwartz, S. H. (2004). Mapping and interpreting cultural differences around the world. In H. Vinken, J. Soeters, & P Ester (Eds.), *Comparing cultures, Dimensions of culture in a comparative perspective* (pp.43-73). Leiden, The Netherlands: Brill.

**Item 58**

|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **SVS-58 Chinese version expands SVS-57 item 46, using items 46 and 58: **                                                                                                                   
                                                                                                                                                                                               
 46 \_\_\_\_\_\_\_ 保持自我公众形象(在大众面前保持自己美好的一面) “PRESERVING MY PUBLIC IMAGE (protecting my "face")                                                                           
                                                                                                                                                                                               
 58 \_\_\_\_\_\_\_ 遵守社会规范 (维护面子) “OBSERVING SOCIAL NORMS (to maintain face)”                                                                                                         
                                                                                                                                                                                               
 Some researchers are adding item 58 to other language versions. If the smallest space analysis indicates item 58 is a Power item, it would be also included where item 46 is included below:  |

**Keying of SVS Ten Individual Level Value Scales **

<span id="table01" class="anchor"></span>**SVS items**

|---------------------|-------------------------------------|
| **Conformity**      | ***11, 20, 40, 47***                |
| ***Tradition ***    | ***18, 32, 36, 44, 51***            |
| **Benevolence **    | ***33, 45, 49,52, 54***             |
| ***Universalism *** | ***1, 17, 24, 26, 29, 30, 35, 38*** |
| **Self-Direction**  | ***5, 16, 31, 41, 53***             |
| ***Stimulation ***  | ***9, 25, 37***                     |
| **Hedonism **       | ***4, 50, 57***                     |
| ***Achievement ***  | ***34, 39, 43, 55***                |
| **Power **          | ***3, 12, 27, 46, 58***             |
| ***Security ***     | ***8, 13, 15, 22, 56***             |

The score for each value is the mean of the ratings given to the items listed above for that value. Note, however, that for most purposes it is necessary to make a correction for individual differences in use of the response scale. Instructions for making the corrections follow. **Failure to make the necessary scale use correction typically leads to mistaken conclusions!**

 **Scale Use Correction for the 56 or 57 item SVS**

(Note: the SVS56 and SVS57 not only have different numbers of items, a few of the first 56 items in the SVS57 are different from the SVS56, see below.)

Individuals and cultural groups differ in their use of the response scale.<sup>1</sup> When treating value priorities either as independent or as dependent variables, it is necessary to correct for scale use. In such analyses, scale use differences often distort findings and lead to incorrect conclusions.<sup>2</sup> Follow the appropriate instructions below to correct for scale use.

> A. Compute each individual’s total score on all value items and divide by the total number of items (56 or 57). I call this the MRAT (Mean RATing for the particular individual).
>
> B1. Center scores of each of the items for an individual around that    individual’s MRAT. Then compute scores for the 10 values by taking the means of the centered items. Use these centered value scores in correlations.
>
> B2. Alternatively, use the raw scores for the 10 values, but use partial correlation to correlate them with other variables, partialing out their relations to MRAT (i.e., use MRAT as a covariate).

      *The two alternative methods yield virtually identical results. *

> A. Compute MRAT as in 1A above
>
> B1. Center scores for each item and compute 10 value scores as in 1B1. Then use these centered scores in the analyses.
>
> B2. Alternatively, use raw scores and include MRAT as a covariate (i.e., a control at the individual level) in all analyses.

   *The two alternative methods yield virtually identical results. *

> C1) If all 10 values are included, the regression weights for the values will be **inaccurate and uninterpretable.**
>
> C2) Choose the values to **exclude as predictors** *a priori* on theoretical grounds because they are irrelevant to the topic.

F. If the value is your dependent variable, use the centered value score.

G. In publications, I strongly advise providing a table with the correlations between the values and the dependent variables in addition to any regression. Use correlations following 1B1 or 1B2, above. These correlations will aid in understanding results and reduce confusion due either to multicolinearity or to intercorrelations among the values.

4. *For multidimensional scaling, canonical, discriminant, or confirmatory factor analyses*:

   Use raw value scores for the items or 10 value means.

5. *Exploratory factor analysis* is not recommended to search for factors underlying the value items. EFA is not suitable for discovering a set of relations among variables that form a circumplex, as the values data do. The first unrotated factor represents scale use or acquiescence. It is not a substantive common factor. You can obtain a crude representation of the circular structure of values using EFA by plotting the locations of the value items on factors 2 x 3 of the unrotated solution.

**NOTES:**

1. Schwartz, et al., (1997) examines meanings of such scale use as an individual difference variable. Smith (2004) discusses correlates of scale use differences at the level of cultures.

2. Individual differences in the mean of the values are largely a scale use bias. This assertion is grounded both in theory and empirically.

      A first theoretical ground is the assumption that, across the full range of value contents, everyone views values as approximately equally important. Some attribute more importance to one value, others to another. But, on average, values as a whole are of equal importance. This assumption is dependent on the further assumption that the value instrument covers all of the major types of values to which people attribute importance. Empirical evidence to support this assumption appears in Schwartz 1992, 2004. To the extent that individuals' attribute the same average importance to the full set of values, their mean score (MRAT) should be the same. Differences in individual MRATs therefore reflect scale use and not value substance. Of course, differences in MRAT may reflect some substance, but the empirical analyses suggest that substance is a much smaller component of MRAT than scale use bias is (Schwartz, et al., 1997).

      A second theoretical ground is that values are of interest because they form a system of priorities that guide, influence, and are influenced by thought, feeling and action. Values do not function in isolation from one another but as systems. For example, a decision to vote for one or another party is influenced by the perceived consequences of that vote for the attainment or frustration of **multiple** values--promoting equality or freedom of expression versus social power or tradition. It is the trade-off among the relevant values that affects the vote. Consequently, what is really of interest are the **priorities** among the values that form an individual's value system. Correcting for scale use with MRAT converts absolute value scores into scores that indicate the relative importance of each value in the value system, i.e., the individual’s value priorities.

      The empirical basis for viewing differences in MRAT as bias is the findings of many analyses (50 or so, at least) that related value priorities to other variables--attitudes, behavior, background. The associations obtained (mean differences, correlations) when using scores corrected for MRAT are consistently more supportive of hypotheses based on theorizing about how values should relate to these other variables than the associations with raw scores. Indeed, with raw scores associations sometimes reverse. In no case have raw score associations made better sense than those corrected for MRAT.

3. A more refined way to measure MRAT is possible. Separate MRATs may be calculated for each of the ten values. For this purpose, the average response on all items *other than those that index a value* is computed as the MRAT for each value. Scores on the items that index each of the 10 values are then centered around their own MRAT. Alternatively, the particular MRAT for each value is used as the covariate when correlating that value with other variables. Studies indicate that using this more refined method with the SVS makes virtually no difference.

References to be Read

Schwartz, S. H. (1992). Universals in the content and structure of values: Theory and empirical tests in 20 countries. In M. Zanna (Ed.), *Advances in experimental social psychology (Vol. 25)* (pp. 1-65). New York: Academic Press.

Schwartz, S. H. (1994a). Beyond individualism/collectivism: New cultural dimensions of values. In U. Kim, H.C. Triandis, C. Kagitcibasi, S-C. Choi, & G. Yoon (Eds.), *Individualism and collectivism: Theory, method and applications,* pp. 85-119. Newbury Park, CA: Sage.

Schwartz, S.H. (1994b). Are there universal aspects in the content and structure of values?. *Journal of Social Issues*, 50(4), 19-45.

Schwartz, S.H. & Sagiv, L. (1995). Identifying Culture-Specifics in the Content and Structure of Values. *Journal of cross-cultural psychology,* 26(1), 92-116.

Schwartz, S.H. (1996). Value priorities and behavior: Applying a theory of integrated value systems. In C. Seligman, J.M. Olson, & M.P. Zanna (Eds.), *The Psychology of Values: The Ontario Symposium, Vol. 8* (pp.1-24). Hillsdale, NJ: Erlbaum.

Schwartz, S.H., Verkasalo, M., Antonovsky, A., & Sagiv, L. (1997). Value priorities and social desirability: Much substance, some style. *British Journal of Social Psychology, 36,* 3-18.

Schwartz, S. H. (2004). Basic human values: Their content and structure across countries. In A. Tamayo & J Porto (Eds.), *Valores e trabalho* [Values and work]. Brasilia: Editora Universidade de Brasilia.

Smith, P. B. (2004). Acquiescent response bias as an aspect of cultural communications style. *Journal of Cross-Cultural Psychology, 35,* 50-61.

> **Keying of SVS for Seven Cultural Level Value Orientations**

|-------------------------|--------------------------------------------|
| *Cultural level*        |                                            |
| Embeddedness            | 8,11,13,15,18,20,26,32, 40, 46,47,51,54,56 |
| Hierarchy               | ***3,12,27,36,39***                        |
| Mastery                 | 23,31, 34,37,39, 41,43,55,                 |
| Affective Autonomy      | ***4,9,25,50,57***                         |
| Intellectual Autonomy   | 5,16,35,53                                 |
| Egalitarianism          | ***1,30,33,45,49,52***                     |
| Harmony                 | 17,24,29,38                                |

> ***Scale Use Correction***: Because individuals and cultural groups use the value scale differently, it is necessary to correct for scale use in all analyses.

***Culture Level:*** Compute mean sample score on all values. Subtract sample mean from 4.00. Add the result to the score for each value dimension. (e.g., Mean = 4.5; Dimensions = 4.0; Adj. = 3.5)

For example: Say you want to calculate a score for mastery in Chile.

1. You calculate the mean for all respondents from Chile on all 57 items in the survey. Say it is 4.375.

2. Comparing the overall mean in Chile to the international mean of 4.00, I find that Chileans tend to use the upper part of the scale. They have a mean that is .375 higher than the average (4.375-4.00).

3. Therefore, I will subtract .375 from whatever score I get for a cultural dimension in Chile.

4. If the observed score on mastery in Chile, before adjusting for scale use, is 5.375 (the mean of all mastery items across all respondents in the sample), then the adjusted score for mastery will be 5.00 (5.375-.375). That is the score to use for the mastery dimension in cross-national comparisons.

5. Let's say the Chilean average for harmony was 2.875. Then the score on this dimension would be corrected to 2.500 (2.875-.375) for cross-national comparisons.

***FAILURE TO CORRECT FOR SCALE USE YIELDS INCORRECT RESULTS!!!***

**Database of SVS Study Results:**

The following website has all the data from teachers and students that Prof. Schwartz gathered through 2005 in the HUJI Social Science Data Archives site, Data Set Name: Schwartz Value Survey (SVS), data set number 0789:

 

*http://isdc.huji.ac.il/ehold10.shtml\#* *E2*

**Businesspeople Samples**

Romie Littrell, *crossculturalcentre@yahoo.com* is running a project collecting SVS sample data for businesspeople across cultures. If you wish to collaborate or obtain data for comparisons please contact.

> **Addenda: Some templates that are useful with SPSS, Speadsheets, HUDAP**

|-----|-------|----------------|
| 5   | AA25  |                |
| 4   | AA4   |                |
| 50  | AA50  |                |
| 7   | AA57  |                |
| 9   | AA9   |                |
| 1   | EG1   | Egalitarianism |
| 30  | EG30  |                |
| 3   | EG33  |                |
| 5   | EG45  |                |
| 9   | EG49  |                |
| 2   | EG52  |                |
| 1   | EM11  |                |
| 3   | EM13  |                |
| 5   | EM15  |                |
| 8   | EM18  |                |
| 20  | EM20  |                |
| 6   | EM26  |                |
| 2   | EM32  |                |
| 40  | EM40  |                |
| 6   | EM46  |                |
| 7   | EM47  |                |
| 1   | EM51  |                |
| 4   | EM54  |                |
| 6   | EM56  |                |
| 8   | EM8   |                |
| 7   | HAR17 |                |
| 4   | HAR24 |                |
| 9   | HAR29 |                |
| 8   | HAR38 |                |
| 2   | HI12  |                |
| 7   | HI27  |                |
| 3   | HI3   | Hierarchy      |
| 6   | HI36  |                |
| 9   | HI39  |                |
| 6   | IA16  |                |
| 5   | IA35  |                |
| 5   | IA5   |                |
| 3   | MA23  |                |
| 1   | MA31  |                |
| 4   | MA34  |                |
| 7   | MA37  |                |
| 1   | MA41  |                |
| 3   | MA43  |                |
| 5   | MA55  |                |
| 3   | SD53  |                |
| 10  | X10   |                |
| 4   | X14   |                |
| 9   | X19   |                |
| 2   | X2    |                |
| 1   | X21   |                |
| 2   | X22   |                |
| 8   | X28   |                |
| 2   | X42   |                |
| 4   | X44   |                |
| 8   | X48   |                |
| 58  | X58   |                |
| 6   | X6    |                |
| 7   | X7    |                |

|------|-----------|-------------------------|------------------------------------------------------------------------|
| 4    | AA04      | Affective Autonomy      | 4 PLEASURE (gratification of desires)                                  |
| 9    | AA09      | Affective Autonomy      | 9 AN EXCITING LIFE (stimulating experiences)                           |
| 25   | AA25      | Affective Autonomy      | 25 A VARIED LIFE (filled with challenge, novelty and change)           |
| 50   | AA50      | Affective Autonomy      | 50 ENJOYING LIFE (enjoying food, sex, leisure, etc.)                   |
| 57   | AA57      | Affective Autonomy      | 57 SELF-INDULGENT (doing pleasant things)                              |
| 1    | EG01      | Egalitarianism          | 1 EQUALITY (equal opportunity for all)                                 |
| 30   | EG30      | Egalitarianism          | 30 SOCIAL JUSTICE (correcting injustice, care for the weak)            |
| 33   | EG33      | Egalitarianism          | 33 LOYAL (faithful to my friends, group)                               |
| 45   | EG45      | Egalitarianism          | 45 HONEST (genuine, sincere)                                           |
| 49   | EG49      | Egalitarianism          | 49 HELPFUL (working for the welfare of others)                         |
| 52   | EG52      | Egalitarianism          | 52 RESPONSIBLE (dependable, reliable)                                  |
| 8    | EM08      | Embeddedness            | 8 SOCIAL ORDER (stability of society)                                  |
| 11   | EM11      | Embeddedness            | 11POLITENESS (courtesy, good manners)                                  |
| 13   | EM13      | Embeddedness            | 13 NATIONAL SECURITY (protection of my nation from enemies)            |
| 15   | EM15      | Embeddedness            | 15 RECIPROCATION OF FAVOURS (avoidance of indebtedness)                |
| 18   | EM18      | Embeddedness            | 18 RESPECT FOR TRADITION (preservation of timehonoured customs)        |
| 20   | EM20      | Embeddedness            | 20 SELFDISCIPLINE (selfrestraint, resistance to temptation)            |
| 26   | EM26      | Embeddedness            | 26 WISDOM (a mature understanding of life)                             |
| 32   | EM32      | Embeddedness            | 32 MODERATE (avoiding extremes of feeling & action)                    |
| 40   | EM40      | Embeddedness            | 40 HONOURING OF PARENTS AND ELDERS (showing respect)                   |
| 46   | EM46      | Embeddedness            | 46 PRESERVING MY PUBLIC IMAGE (protecting my "face")                   |
| 47   | EM47      | Embeddedness            | 47 OBEDIENT (dutiful, meeting obligations)                             |
| 51   | EM51      | Embeddedness            | 51 DEVOUT (holding to religious faith & belief)                        |
| 54   | EM54      | Embeddedness            | 54 FORGIVING (willing to pardon others)                                |
| 56   | EM56      | Embeddedness            | 56 CLEAN (neat, tidy)                                                  |
| 17   | HA17      | Harmony                 | 17 A WORLD AT PEACE (free of war and conflict)                         |
| 24   | HA24      | Harmony                 | 24 UNITY WITH NATURE (fitting into nature)                             |
| 29   | HA29      | Harmony                 | 29 A WORLD OF BEAUTY (beauty of nature and the arts)                   |
| 38   | HA38      | Harmony                 | 38 PROTECTING THE ENVIRONMENT (preserving nature)                      |
| 3    | HI03      | Hierarchy               | 3 SOCIAL POWER (control over others, dominance)                        |
| 12   | HI12      | Hierarchy               | 12 WEALTH (material possessions, money)                                |
| 27   | HI27      | Hierarchy               | 27 AUTHORITY (the right to lead or command)                            |
| 36   | HI36      | Hierarchy               | 36 HUMBLE (modest, selfeffacing)                                       |
| 39   | HIM39\*   | Hierarchy/Mastery       | 39 INFLUENTIAL (having an impact on people and events)                 |
| 5    | IA05      | Intellectual Autonomy   | 5 FREEDOM (freedom of action and thought)                              |
| 16   | IA16      | Intellectual Autonomy   | 16 CREATIVITY (uniqueness, imagination)                                |
| 35   | IA35      | Intellectual Autonomy   | 35 BROADMINDED (tolerant of different ideas and beliefs)               |
| 53   | IA53      | Intellectual Autonomy   | 53 CURIOUS (interested in everything, exploring)                       |
| 23   | MA23      | Mastery                 | 23 SOCIAL RECOGNITION (respect, approval by others)                    |
| 31   | MA31      | Mastery                 | 31 INDEPENDENT (selfreliant, selfsufficient)                           |
| 34   | MA34      | Mastery                 | 34 AMBITIOUS (hardworking, aspiring)                                   |
| 37   | MA37      | Mastery                 | 37 DARING (seeking adventure, risk)                                    |
| 41   | MA41      | Mastery                 | 41 CHOOSING OWN GOALS (selecting own purposes)                         |
| 43   | MA43      | Mastery                 | 43 CAPABLE (competent, effective, efficient)                           |
| 55   | MA55      | Mastery                 | 55 SUCCESSFUL (achieving goals)                                        |
| 2    | X02       |                         | 2 INNER HARMONY (at peace with myself)                                 |
| 6    | X06       |                         | 6 A SPIRITUAL LIFE (emphasis on spiritual not material matters)        |
| 7    | X07       |                         | 7 SENSE OF BELONGING (feeling that others care about me)               |
| 10   | X10       |                         | 10 MEANING IN LIFE (a purpose in life)                                 |
| 14   | X14       |                         | 14 SELF RESPECT (belief in one's own worth)                            |
| 19   | X19       |                         | 19 MATURE LOVE (deep emotional & spiritual intimacy)                   |
| 21   | X21       |                         | 21 PRIVACY (the right to have a private sphere)                        |
| 22   | X22       |                         | 22 FAMILY SECURITY (safety for loved ones)                             |
| 28   | X28       |                         | 28 TRUE FRIENDSHIP (close, supportive friends)                         |
| 42   | X42       |                         | 42 HEALTHY (not being sick physically or mentally)                     |
| 44   | X44       |                         | 44 ACCEPTING MY PORTION IN LIFE (submitting to life's circumstances)   |
| 48   | X48       |                         | 48 INTELLIGENT (logical, thinking)                                     |
| 58   | X58       |                         | 58 OBSERVING SOCIAL NORMS (to maintain face)                           |

|--------------------------------------|----------------------------------------------|
| 1 EQUALITY                           | equal opportunity for all                    |
| 2 INNER HARMONY                      | at peace with myself                         |
| 3 SOCIAL POWER                       | control over others, dominance               |
| 4 PLEASURE                           | gratification of desires                     |
| 5 FREEDOM                            | freedom of action and thought                |
| 6 A SPIRITUAL LIFE                   | emphasis on spiritual not material matters   |
| 7 SENSE OF BELONGING                 | feeling that others care about me            |
| 8 SOCIAL ORDER                       | stability of society                         |
| 9 AN EXCITING LIFE                   | stimulating experiences                      |
| 10 MEANING IN LIFE                   | a purpose in life                            |
| 11POLITENESS                         | courtesy, good manners                       |
| 12 WEALTH                            | material possessions, money                  |
| 13 NATIONAL SECURITY                 | protection of my nation from enemies         |
| 14 SELF RESPECT                      | belief in one's own worth                    |
| 15 RECIPROCATION OF FAVOURS          | avoidance of indebtedness                    |
| 16 CREATIVITY                        | uniqueness, imagination                      |
| 17 A WORLD AT PEACE                  | free of war and conflict                     |
| 18 RESPECT FOR TRADITION             | preservation of timehonoured customs         |
| 19 MATURE LOVE                       | deep emotional & spiritual intimacy          |
| 20 SELFDISCIPLINE                    | selfrestraint, resistance to temptation      |
| 21 PRIVACY                           | the right to have a private sphere           |
| 22 FAMILY SECURITY                   | safety for loved ones                        |
| 23 SOCIAL RECOGNITION                | respect, approval by others                  |
| 24 UNITY WITH NATURE                 | fitting into nature                          |
| 25 A VARIED LIFE                     | filled with challenge, novelty and change    |
| 26 WISDOM                            | a mature understanding of life               |
| 27 AUTHORITY                         | the right to lead or command                 |
| 28 TRUE FRIENDSHIP                   | close, supportive friends                    |
| 29 A WORLD OF BEAUTY                 | beauty of nature and the arts                |
| 30 SOCIAL JUSTICE                    | correcting injustice, care for the weak      |
| 31 INDEPENDENT                       | selfreliant, selfsufficient                  |
| 32 MODERATE                          | avoiding extremes of feeling & action        |
| 33 LOYAL                             | faithful to my friends, group                |
| 34 AMBITIOUS                         | hardworking, aspiring                        |
| 35 BROADMINDED                       | tolerant of different ideas and beliefs      |
| 36 HUMBLE                            | modest, selfeffacing                         |
| 37 DARING                            | seeking adventure, risk                      |
| 38 PROTECTING THE ENVIRONMENT        | preserving nature                            |
| 39 INFLUENTIAL                       | having an impact on people and events        |
| 40 HONOURING OF PARENTS AND ELDERS   | showing respect                              |
| 41 CHOOSING OWN GOALS                | selecting own purposes                       |
| 42 HEALTHY                           | not being sick physically or mentally        |
| 43 CAPABLE                           | competent, effective, efficient              |
| 44 ACCEPTING MY PORTION IN LIFE      | submitting to life's circumstances           |
| 45 HONEST                            | genuine, sincere                             |
| 46 PRESERVING MY PUBLIC IMAGE        | protecting my "face"                         |
| 47 OBEDIENT                          | dutiful, meeting obligations                 |
| 48 INTELLIGENT                       | logical, thinking                            |
| 49 HELPFUL                           | working for the welfare of others            |
| 50 ENJOYING LIFE                     | enjoying food, sex, leisure, etc.            |
| 51 DEVOUT                            | holding to religious faith & belief          |
| 52 RESPONSIBLE                       | dependable, reliable                         |
| 53 CURIOUS                           | interested in everything, exploring          |
| 54 FORGIVING                         | willing to pardon others                     |
| 55 SUCCESSFUL                        | achieving goals                              |
| 56 CLEAN                             | neat, tidy                                   |
| 57 SELF-INDULGENT                    | doing pleasant things                        |
| 58 OBSERVING SOCIAL NORMS            | to maintain face                             |

Helpful in creating tables, charts, SPSS variable lists, and SSA variable lists:

**Item – Motivational Type – Code Key**

|----------|----------|--------------------------------------|-----------------------------------------------------------------------|
| **Item** | **Code** | **Short Content**                    | **Item Content in Survey**                                            |
| **34**   | **A34**  | **Ambitious **                       | **AMBITIOUS (hardworking, aspiring)**                                 |
| **39**   | **A39**  | **Influential **                     | **INFLUENTIAL (having an impact on people and events)**               |
| **43**   | **A43**  | **Capable **                         | **CAPABLE (competent, effective, efficient)**                         |
| **55**   | **A55**  | **Successful **                      | **SUCCESSFUL (achieving goals)**                                      |
| 33       | B33      | Loyal                                | LOYAL (faithful to my friends, group)                                 |
| 45       | B45      | Honest                               | HONEST (genuine, sincere)                                             |
| 49       | B49      | Helpful                              | HELPFUL (working for the welfare of others)                           |
| 52       | B52      | Responsible                          | RESPONSIBLE (dependable, reliable)                                    |
| 54       | B54      | Forgiving                            | FORGIVING (willing to pardon others)                                  |
| **11**   | **C11**  | **Politeness **                      | **POLITENESS (courtesy, good manners)**                               |
| **20**   | **C20**  | **Selfdiscipline **                  | **SELFDISCIPLINE (selfrestraint, resistance to temptation)**          |
| **40**   | **C40**  | **Honouring of parents and elders ** | **HONOURING OF PARENTS AND ELDERS (showing respect)**                 |
| **47**   | **C47**  | **Obedient **                        | **OBEDIENT (dutiful, meeting obligations)**                           |
| 4        | H4       | Pleasure                             | PLEASURE (gratification of desires)                                   |
| 50       | H50      | Enjoying life                        | ENJOYING LIFE (enjoying food, sex, leisure, etc.)                     |
| 57       | H57      | Self-indulgent                       | SELF-INDULGENT (doing pleasant things)                                |
| **12**   | **P12**  | **Wealth **                          | **WEALTH (material possessions, money)**                              |
| **27**   | **P27**  | **Authority **                       | **AUTHORITY (the right to lead or command)**                          |
| **3**    | **P3**   | **Social power **                    | **SOCIAL POWER (control over others, dominance)**                     |
| **46**   | **P46**  | **Preserving my public image **      | **PRESERVING MY PUBLIC IMAGE (protecting my "face")**                 |
| **58**   | **P58**  | **Observing social norms **          | **OBSERVING SOCIAL NORMS (to maintain face)**                         |
| 16       | SD16     | Creativity                           | CREATIVITY (uniqueness, imagination)                                  |
| 31       | SD31     | Independent                          | INDEPENDENT (selfreliant, selfsufficient)                             |
| 41       | SD41     | Choosing own goals                   | CHOOSING OWN GOALS (selecting own purposes)                           |
| 5        | SD5      | Freedom                              | FREEDOM (freedom of action and thought)                               |
| 53       | SD53     | Curious                              | CURIOUS (interested in everything, exploring)                         |
| **13**   | **SE13** | **National security **               | **NATIONAL SECURITY (protection of my nation from enemies)**          |
| **15**   | **SE15** | **Reciprocation of favours **        | **RECIPROCATION OF FAVOURS (avoidance of indebtedness)**              |
| **22**   | **SE22** | **Family security **                 | **FAMILY SECURITY (safety for loved ones)**                           |
| **56**   | **SE56** | **Clean **                           | **CLEAN (neat, tidy)**                                                |
| **8**    | **SE8**  | **Social order **                    | **SOCIAL ORDER (stability of society)**                               |
| 25       | ST25     | A varied life                        | A VARIED LIFE (filled with challenge, novelty and change)             |
| 37       | ST37     | Daring                               | DARING (seeking adventure, risk)                                      |
| 9        | ST9      | An exciting life                     | AN EXCITING LIFE (stimulating experiences)                            |
| **18**   | **T18**  | **Respect for tradition **           | **RESPECT FOR TRADITION (preservation of timehonoured customs)**      |
| **32**   | **T32**  | **Moderate **                        | **MODERATE (avoiding extremes of feeling & action)**                  |
| **36**   | **T36**  | **Humble **                          | **HUMBLE (modest, selfeffacing)**                                     |
| **44**   | **T44**  | **Accepting my portion in life **    | **ACCEPTING MY PORTION IN LIFE (submitting to life's circumstances)** |
| **51**   | **T51**  | **Devout **                          | **DEVOUT (holding to religious faith & belief)**                      |
| 1        | U1       | Equality                             | EQUALITY (equal opportunity for all)                                  |
| 17       | U17      | A world at peace                     | A WORLD AT PEACE (free of war and conflict)                           |
| 24       | U24      | Unity with nature                    | UNITY WITH NATURE (fitting into nature)                               |
| 26       | U26      | Wisdom                               | WISDOM (a mature understanding of life)                               |
| 29       | U29      | A world of beauty                    | A WORLD OF BEAUTY (beauty of nature and the arts)                     |
| 30       | U30      | Social justice                       | SOCIAL JUSTICE (correcting injustice, care for the weak)              |
| 35       | U35      | Broadminded                          | BROADMINDED (tolerant of different ideas and beliefs)                 |
| 38       | U38      | Protecting the environment           | PROTECTING THE ENVIRONMENT (preserving nature)                        |
| **10**   | **X10**  | **Meaning in life **                 | **MEANING IN LIFE (a purpose in life)**                               |
| **14**   | **X14**  | **Self respect **                    | **SELF RESPECT (belief in one's own worth)**                          |
| **19**   | **X19**  | **Mature love **                     | **MATURE LOVE (deep emotional & spiritual intimacy)**                 |
| **2**    | **X2**   | **Inner harmony **                   | **INNER HARMONY (at peace with myself)**                              |
| **21**   | **X21**  | **Privacy **                         | **PRIVACY ( the right to have a private sphere)**                     |
| **23**   | **X23**  | **Social recognition **              | **SOCIAL RECOGNITION (respect, approval by others)**                  |
| **28**   | **X28**  | **True friendship **                 | **TRUE FRIENDSHIP (close, supportive friends)**                       |
| **42**   | **X42**  | **Healthy **                         | **HEALTHY (not being sick physically or mentally)**                   |
| **48**   | **X48**  | **Intelligent **                     | **INTELLIGENT (logical, thinking)**                                   |
| **6**    | **X6**   | **A spiritual life **                | **A SPIRITUAL LIFE (emphasis on spiritual not material matters)**     |
| **7**    | **X7**   | **Sense of belonging **              | **SENSE OF BELONGING (feeling that others care about me)**            |

> **DIFFERENCES IN THE SVS56 AND SVS57**

The SVS56 and SVS57 are different, with one item changed and one item added in the SVS57, so when comparing results you should note this. This manual is for the SVS57.
Changed items:

SVS56, item v21d, Detachment

SVS57, item v21p, Privacy (the right to have a private sphere)

Added:

SVS57, item v57, Self-Indulgent (doing pleasant things)

You need to thoroughly read the articles required in the draft users' manual. Schwartz & Sagiv (1995) is the first article using the SVS57. Here are the dimension-item relationships for the SVS56, which are different from the SVS57, from Schwartz (1994: 33) “Table 3. Empirical Locations of Each Value in Regions of Each Motivational Type (Percents): Based on SSA Two-Dimensional Projections for 97 Samples”. Numbers in parentheses are the percent of locations in adjacent regions rather than the theoretical region.

**Power**

 

Social power                     100

Authority                         97

Wealth                            95

Preserving my public image        64         (32)

Social recognition                62         (36)

 

**Achievement**

 

Successful                        96

Capable                           87

Ambitious                         85

Influential                       76         (21)

Intelligent                       66

Self-respect                      36          (4)

 

**Hedonism**

 

Pleasure                          98

Enjoying life                     97

 

**Stimulation**

 

Daring                            96          (3)

A varied life                     96          (3)

An exciting life                  90          (5)

 

**Self-direction**

 

Creativity                        95          (3)

Curious                           92          (3)

Freedom                           84          (5)

Choosing own goals                81          (4)

Independent                       78          (9)

 

**Universalism**

 

Protecting the environment        93          (3)

A world of beauty                 93          (4)

Unity with nature                 90

Broad-minded                      86         (10)

Social justice                    77         (11)

Wisdom                            77         (13)

Equality                          76         (10)

A world at peace                  75          (7)

Inner harmony                     48         (28)

** **

**Benevolence**

 

Helpful                           98

Honest                            94          (6)

Forgiving                         88          (8)

Loyal                             82         (12)

Responsible                       79         (18)

True friendship                   65         (14)

A spiritual life                  57         (35)

Mature love                       53         (22)

Meaning in life                   42         (33)

** **

**Tradition**

 

Devout                            96

Accepting portion in life         90          (4)

Humble                            81         (16)

Moderate                          76         (22)

Respect for tradition             76         (22)

Detachment                        48         (15)

 

**Conformity**

 

Politeness                        95          (5)

Honoring parents and elders       93          (6)

Obedient                          91          (9)

Self-discipline                   85         (14)

 

**Security**

 

Clean                             87          (8)

National security                 85          (3)

Social order                      81

Family security                   80          (3)

Reciprocation of favors           75          (9)

Healthy                           57

Sense of belonging                56         (10)

