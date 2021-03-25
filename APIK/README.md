# Adverbial Postpositions In Korean (APIK)

## Abstract
To conduct the research on Korean adverbial postpositions, I need a corpus with the intended functions of postpositions tagged in each sentence. However, the [Sejong corpus](https://www.korean.go.kr), mother corpus of my study does not code the functions of postpositions directly. Therefore, I annotate the corpus manually with the help of three native speakers of Korean. Among the three, one was an instructor who teaches Korean to children and the other two were Ph.D. candidates in linguistics. They managed all the details of the corpus annotation, from the development of the annotation manual to the manual annotation of the intended function of postposition in each sentence. <br> <br>
Regarding the process of creating a hand-coded corpus, I extract sentences having only one postposition and predicate. Although this manipulation omitted many sentences already extracted from the original corpus, it was beneficial for controlling any additional confounding factors which could have interfered with the performance of my model. If a sentence contains more than one postposition, including the three postpositions that I focused on, they become less independent of each other. This means the model performance of each postposition will be affected by each other. This reduction process resulted in a total of 27,720 sentences, with 14,096 sentences for <i>-ey</i>, 5,078 sentences for <i>-eyse</i>, and 8,546 sentences for <i>-(u)lo</i>. I then extract 5,000 sentences randomly for each postposition to keep an equal number of sentences for each one.<br> <br>
The final corpus data are then hand-coded by the three native speakers of Korean, following the functions of the individual postpositions. The inter-rater reliability of the data was measured with the Fleiss's Kappa ([Landis and Koch, 1977](https://www.jstor.org/stable/2529310?seq=1)). The results were a score of 0.948 for <i>-ey</i>, 0.928 for <i>-eyse</i>, and 0.947 for <i>-(u)lo</i>, which are considered <i>almost perfect</i> according to the Kappa scale. I decide to exclude sentences that caused disagreement among the human annotators (i.e., 285 sentences for <i>-ey</i>, 147 sentences for <i>-eyse</i>, and 292 sentences for <i>-(u)lo</i>). After which, I obtain the final corpus
data for each postposition. This yielded 4,715 sentences for <i>-ey</i>, 4,853 sentences for <i>-eyse</i>, and 4,708 sentences for <i>-(u)lo</i>. The table below presents the detailed by-function frequency list of the three postposition types.

## By-function frequency list of <i>-ey</i>, <i>-eyse</i>, and <i>-(u)lo</i> in cross-validated corpus.

<div class="table*">

| ***-ey*** |           | ***-eyse*** |           | ***-(u)lo*** |           |
|:----------|:---------:|:------------|:---------:|:-------------|:---------:|
| Function  | Frequency | Function    | Frequency | Function     | Frequency |
| LOC       |   1,780   | LOC         |   4,206   | FNS          |   1,681   |
| CRT       |   1,516   | SRC         |    647    | DIR          |   1,449   |
| THM       |    448    |             |           | INS          |    739    |
| GOL       |    441    |             |           | CRT          |    593    |
| FNS       |    216    |             |           | LOC          |    158    |
| EFF       |    198    |             |           | EFF          |    88     |
| INS       |    69     |             |           |              |           |
| AGT       |    47     |             |           |              |           |
| Total     |   4,715   | Total       |   4,853   | Total        |   4,708   |

*Note*. Abbreviation: AGT = agent; CRT = criterion; DIR = direction; EFF
= effector; FNS = final state; GOL = goal; INS = instrument; LOC =
location; SRC = source; THM = theme

</div>

### <i>-ey</i>
<img src="./Glosses/1.png" width="60%">
