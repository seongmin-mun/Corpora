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

# Examples for the functions of each postposition

## <i>-ey</i>

Location (LOC) is a function that represents the spatial place where an event occurs. In the following sentence (i.e. this sentence is extracted from the file <i>V-phamwuthita</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>in</i> in English.

<pre>
     (1) <i>-ey</i> as LOC (location)
         그는    온종일     서재에            파묻혀       지낸다.
         ku-nun oncongil secay-ey        phamwuthye  cinay-n-ta.
         He-TOP all day  study room-LOC  bury in     be-PRS-DECL
         'He is buried in his study room all day.'  
</pre>

Goal (GOL) is a function that indicates the preceding word is where the object reaches. In the following sentence (i.e., this sentence is extracted from the file <i>V-naylyekkochita</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>to</i> in English.

<pre>
     (2) <i>-ey</i> as GOL (goal)
         철수가         던진      칼이        땅바닥에         내리꽂혔다.
         Chelswu-ka   tenci-n  khal-i     ttangpatak-ey  naylyekkochy-ess-ta.
         Chelswu-TOP  throw    knife-NOM  ground-GOL     stick-PST-DECL
         'The knife thrown by Chelswu stuck to the ground.'  
</pre>

Effector (EFF) is a function that indicates that the preceding word influences the theme to act or change when an event occurs. In the following sentence (i.e., this sentence is extracted from the file <i>V-kentultayta</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>by</i> in English.

<pre>
     (3) <i>-ey</i> as EFF (effector)
         문들이         거센     바람에     모두     건들댄다.
         mwuntul-i    keseyn  palam-ey  motwu  kentultay-n-ta.
         door-PL-NOM  strong  wind-EFF  all    sway-PRS-DECL
         'The doors all sway by the strong wind.'
</pre>

Criterion (CRT) is a function that indicates that the preceding word is the standard for quantitative classification of the specific property of the theme. In the following sentence (i.e., this sentence is extracted from the file <i>V-nakchalhata</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>for</i> in English.

<pre>
     (4) <i>-ey</i> as CRT (criterion)
         영호는          20만원에           모니터를         낙찰했다.
         Yenghuy-nun   20manwen-ey       monithe-lul   nakchalhay-ss-ta.
         Yenghuy-TOP   200,000 won-CRT   moniter-ACC   sell-PST-DECL
         'Yenghuy sold the monitor to a bidder for 200,000 won.'
</pre>

Theme (THM) is a function that makes the preceding word as an entity that directly receives the action of the verb. In the following sentence (i.e., this sentence is extracted from the file <i>V-hekicita</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>for</i> in English.

<pre>
     (5) <i>-ey</i> as THM (theme)
         현대인들은                 모두    참된       지식에           허기져있다.
         hyentayintul-un         motwu  chamtoyn  cisik-ey       hekicye-iss-ta.
         modern people-PL-TOP    all    true      knowledge-THM  hungry-DECL
         'All modern people are hungry for true knowledge.'
</pre>

Instrument (INS) is a function that indicates the preceding word engages in an action or a process as a tool. In the following sentence (i.e., this sentence is extracted from the file <i>V-nokita</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>in</i> in English.

<pre>
     (6) <i>-ey</i> as INS (instrument)
         그     어린    소년은       화롯불에           손을        녹이고     있었다.
         ku    elin   sonye-nun   hwalospwul-ey   son-ul     noki-ko   iss-ess-ta.
         That  young  boy-TOP     fire-INS        hand-ACC   melt-and  be-PST-DECL
         'The young boy was using the fire to warm his hands.'
</pre>

Agent (AGT) a function that makes the preceding word as an entity that intentionally carries out the action of the verb. In the following sentence (i.e., this sentence is extracted from the file <i>V-cecitoyta</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>by</i> in English.

<pre>
     (7) <i>-ey</i> as AGT (agent)
         가두      진출이          경찰에           저지되었다.
         katwu    cinchwul-i    kyengchal-ey   cecitoy-ess-ta.
         street   go out-NOM    police-AGT     stop-PST-DECL
         'Going out to the street was stopped by the police.'
</pre>

Final state (FNS) is a function that allows the preceding word to present the current state. In the following sentence (i.e., this sentence is extracted from the file <i>V-chwuchenhata</i> in the Sejong Electronic Dictionary), <i>-ey</i> is playing the same role as <i>as</i> in English.

<pre>
     (8) <i>-ey</i> as FNS (final state)
         김교수는              조교에           박군을         추천했다.
         kimkyoswu-nun       cokyo-ey       pakkwun-ul   chwuchenhay-ess-ta.
         professor Kim-TOP   assistant-FNS  Pakk-ACC     recommend-PST-DECL
         'Professor Kim recommended Pakk as an assistant.'
</pre>

## <i>-eyse</i>

Source (SRC) is a function that indicates the origin of an action, the point at which the action is initiated. In the following sentence (i.e., this sentence is extracted from the file <i>V-ppopaollita</i> in the Sejong Electronic Dictionary), <i>-eyse</i> is playing the same role as <i>from</i> in English.

<pre>
     (9) <i>-eyse</i> as SRC (source)
         광부들이          바다에서      석유를       뽑아올린다.
         kwangpwutul-i   pata-eyse  sekyu-lul   ppopaolli-n-ta.
         miner-PL-NOM    sea-SRC    oil-ACC     pull-DECL
         'Miners pull oil from the sea.'
</pre>

The definition of the location (LOC) is the same as described for <i>-ey</i> (location). In the following sentence (i.e., this sentence is extracted from the file <i>V-thayenata</i> in the Sejong Electronic Dictionary), <i>-eyse</i> is playing the same role as <i>in</i> in English.

<pre>
     (10) <i>-eyse</i> as LOC (location)
          철수는          서울에서      태어났다.
          Chelswu-nun   sewul-eyse  thayen-ass-ta.
          Chelswu-TOP   seoul-LOC   born-PST-DECL
          'Chelswu was born in Seoul.'
</pre>

## <i>-(u)lo</i>

The definition of the final state (FNS) is the same as described above (see (8)). In the following sentence (i.e., this sentence is extracted from the file <i>V-chopingtoyta</i> in the Sejong Electronic Dictionary), <i>-(u)lo</i> is playing the same role as <i>as</i> in English.

<pre>
     (11) <i>-(u)lo</i> as FNS (final state)
          그는      대표              강사로            초빙되었다.
          ku-nun   tayphyo          kangsa-lo       chopingtoy-ess-ta.
          He-TOP   representative   lecturer-FNS    invite-PST-DECL
          'He was invited as a representative lecturer.'
</pre>

The definition of instrument (INS) is the same as described above (see (6)). In the following sentence (i.e., this sentence is extracted from the file <i>V-kamkita</i> in the Sejong Electronic Dictionary), <i>-(u)lo</i> is playing the same role as <i>with</i> in English.

<pre>
     (12) <i>-(u)lo</i> as INS (instrument)
          전선이       연줄로                 감겼다.
          censen-i   yencwul-lo            kamky-ess-ta.
          wire-NOM   connection wire-INS   wind-PST-DECL
          'The wire wound around with the connection wire.'
</pre>

Direction (DIR) is a function to indicate the direction of the point at which the preceding word is directed. In the following sentence (i.e., this sentence is extracted from the file <i>V-talanata</i> in the Sejong Electronic Dictionary), <i>-(u)lo</i> is playing the same role as <i>into</i> in English.

<pre>
     (13) <i>-(u)lo</i> as DIR (direction)
          범인은           어두운     골목으로        달아났다.
          pemi-nun       etwuwun   kolmok-ulo   talan-ass-ta.
          criminal-NOM   dark      alley-DIR    flee-PST-DECL
          'The criminal fled into a dark alley.'
</pre>

The definition of effector (EFF) is the same as described above (3). In the following sentence (i.e., this sentence is extracted from the file <i>V-koylowehata</i> in the Sejong Electronic Dictionary), <i>-(u)lo</i> is playing the same role as <i>due to</i> in English.

<pre>
     (14) <i>-(u)lo</i> as EFF (effector)
          환자가           위암으로                매우     괴로워하고        있습니다.
          hwanca-ka      wiam-ulo              maywu   koyloweha-ko   isssupni-ta.
          patient-NOM    stomach cancer-EFF    very    suffer-and     be-DECL
          'The patient is suffering greatly due to stomach cancer.'
</pre>

The definition of criterion (CRT) is the same as described above (see (4)). In the following sentence (i.e., this sentence is extracted from the file <i>V-paychatoyta</i> in the Sejong Electronic Dictionary), <i>-(u)lo</i> is playing the same role as <i>at</i> in English.


<pre>
     (15) <i>-(u)lo</i> as CRT (criterion)
          적당한         시간     간격으로        배차되었다.
          cektangha-n  sikan   kankyek-ulo   paycha.toy-ess-ta.
          appropriate  time    interval-CRT  arrange-PST-DECL
          'It was arranged at appropriate time intervals.'
</pre>

The definition of LOC is the same as described above (see (1)). In the following sentence (i.e., this sentence is extracted from the file  <i>V-apsonghata</i> in the Sejong Electronic Dictionary),  <i>-(u)lo</i> is playing the same role as  <i>to</i> in English.

<pre>
     (16) <i>-(u)lo</i> as LOC (location)
          검찰이           피해자를        검찰로              압송하다.
          kyengchal-i    phiuyca-lul   kemchal-lo        apsongha-ta.
          police-NOM     suspect-ACC   prosecution-LOC   transport do-DECL
          'The police transport the suspect to the prosecution.'
</pre>
