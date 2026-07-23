# AI's Carbon Footprint

### A Research Report on an Academic Review of the Environmental Impact of Artificial Intelligence

*Prepared as a plain-language review of the AI's Carbon Footprint report*
*based on the published page and documentation contained in this repository*

---

## Foreword

Every question typed into a chatbot is answered somewhere. Not in the phone or
the laptop, but in a warehouse of computers, usually hundreds or thousands of
miles away, drawing electricity from a regional power grid and shedding heat
into the air or into water drawn from a local supply. The person asking the
question sees none of this. The electricity bill goes to a company, the
emissions go to the atmosphere, and the water goes to a cooling tower in a
county the user has never heard of.

This distance between where a technology is used and where its costs land is a
familiar problem in environmental policy. It is the reason we have life-cycle
accounting, emissions disclosure rules, and impact assessments. Artificial
intelligence has grown very quickly, and the accounting has not kept pace.

The repository reviewed here contains a student research report titled AI's
Carbon Footprint, produced under the Ethical Tech CoLab at the NYU School of
Professional Studies Center for Global Affairs in collaboration with Microsoft.
It gathers what is publicly known about the energy, carbon, water, and hardware
costs of artificial intelligence, and about the policies that might contain
them. This paper explains, in non-technical language, what that report says,
how it was assembled, what its numbers mean, where those numbers come from, and
where a careful reader should apply caution. It is written for a policy,
humanitarian, and legal audience rather than a technical one.

---

## 1. Executive Summary

1.1 The repository does not contain a software tool. It contains a piece of
writing. The whole artefact is a single web page, a file named `index.html`,
which holds the complete text of an academic report along with the styling that
controls how it looks on screen. There is no program that calculates anything,
no database, and no live data connection. Every figure in the report was
gathered by the authors from published sources and typed into the page by hand.
This is an important distinction for how the paper should be read and assessed.

1.2 The report's argument is stated plainly at the top of the page and repeated
in its introduction: the environmental costs of artificial intelligence,
arising from energy-intensive model training and everyday model use, from data
centres, and from hardware manufacturing, require urgent action; and a
combination of sustainable practices, policy intervention, and technological
innovation could reduce that footprint without arresting the development of the
technology itself.

1.3 The report is organised into seven chapters covering an introduction,
energy consumption, data centres and hardware, mitigation strategies,
regulatory frameworks, ethical and policy considerations, and a conclusion. It
closes with 55 numbered references, most of which are hyperlinked to their
sources.

1.4 The report's substantive contribution is synthesis rather than new
measurement. It brings together in one accessible document a set of findings
that are otherwise scattered across academic papers, corporate sustainability
disclosures, trade press, and intergovernmental reports. For a reader who needs
an orientation to the subject, this is genuinely useful.

1.5 The report's headline numbers are drawn from the published literature and
are, for the most part, traceable to real studies. A small number of figures
have been misattributed, mislabelled, or given in the wrong unit during the
process of summarising, and one technical definition is stated incorrectly.
Section 9 of this paper sets these out specifically, because a policy reader
citing the report onward needs to know which numbers to check.

1.6 The field moves quickly and its central estimates are contested. Several
figures in the report reflect the state of published knowledge at the time of
writing and have since been superseded by newer official estimates. This is not
a fault of the authors so much as a structural feature of the subject, but it
does mean the report should be read as a snapshot rather than a current
reference.

---

## 2. Background and Rationale

2.1 The problem. Artificial intelligence systems, particularly the large
language and image models that became widely available from 2022 onward,
consume electricity on an industrial scale. That electricity comes from
regional grids whose carbon content varies enormously. The computers running
these systems generate heat, and removing that heat consumes further
electricity and, in many designs, large volumes of water. The chips themselves
are manufactured from mined minerals through processes with their own
environmental and human costs.

2.2 The gap. Public attention to artificial intelligence has concentrated
overwhelmingly on questions of accuracy, bias, safety, employment, and
misinformation. Environmental cost has been a secondary concern, and it is
poorly served by disclosure. Companies are not generally required to publish
the energy or water consumption of specific models, and the figures that do
circulate are frequently estimates produced by outside researchers working from
public information about hardware and training duration. As a result, the
numbers in circulation vary by an order of magnitude or more depending on who
produced them and when.

2.3 The response. The report gathers the available evidence and presents it as
a structured argument for a general educated reader. It does not attempt an
original measurement, and it does not claim to. Its purpose is to make the
subject legible to people who will make or influence policy about it, and to
show that the environmental question deserves a place alongside the safety and
fairness questions in artificial intelligence governance.

2.4 The report's positioning is worth noting. It was produced under a research
initiative that is itself a collaboration between a university and Microsoft, a
company that both operates large data centres and has made public commitments
on emissions. The repository carries an explicit disclaimer that the views
expressed are those of the researchers and do not represent the official
positions of NYU, Microsoft, or any partner institution. Readers may weigh that
context as they see fit; the report's treatment of Microsoft is descriptive
rather than promotional, and it is notably blunt about OpenAI's silence on the
subject.

---

## 3. Objectives

The report sets out to:

3.1 Describe how artificial intelligence consumes energy, separating the two
distinct phases in which it does so, namely the initial building of a model and
its subsequent everyday use.

3.2 Explain the physical infrastructure behind that consumption, meaning the
data centres that house the computers, the systems that cool them, and the
specialised chips that do the computing.

3.3 Trace the environmental costs that sit further back in the supply chain,
particularly the mining and refining of the minerals from which those chips are
made.

3.4 Survey what companies and universities are actually doing to reduce these
costs, naming specific organisations and specific measures rather than speaking
generally about sustainability.

3.5 Map the regulatory landscape, identifying where environmental obligations
on artificial intelligence exist, where they were proposed and then dropped,
and where they remain absent.

3.6 Argue that the technology can be made substantially less environmentally
costly without slowing its development, and that this requires action from
industry, government, and researchers together.

---

## 4. How the Artefact Is Built

4.1 A single page, no software. The report exists as one file of about 55
kilobytes. That file contains the report's text, its list of references, and a
block of styling instructions that tell a web browser how to display it: the
typefaces, the near-black purple background, the lime-green accent colour, and
the layout. Opening that file in any ordinary web browser displays the finished
report. Nothing is installed, nothing is compiled, and no server-side processing
takes place.

4.2 Publication. The page is published through GitHub Pages, a free service
that takes files stored in a code repository and serves them as an ordinary
public website. The repository also contains an empty marker file named
`.nojekyll`, which is a technical instruction telling that service to publish
the file exactly as written rather than passing it through a document-processing
step first. The practical effect is that what the authors wrote is precisely
what a reader sees.

4.3 What is absent, and why it matters. There is no calculating code anywhere
in the repository. No script totals emissions, converts units, or updates a
figure when a source changes. Every number in the report is a fixed piece of
text. This means the report cannot silently drift, which is a virtue, but it
also means that no figure recalculates when the underlying evidence moves, and
that any arithmetic performed by the authors was performed off the page and
cannot be inspected. Where this paper identifies a numerical problem in Section
9, the problem is one of transcription or interpretation rather than of a
faulty program.

4.4 Design as argument. The visual presentation is not incidental. The page
opens with a band of four large figures, set in the accent colour at several
times the size of the body text, before the reader reaches a single sentence of
argument. This is a deliberate rhetorical choice: it establishes scale before it
establishes reasoning. Section 5 examines those four figures directly, because
they are the part of the report most likely to be quoted onward and least likely
to be read with their caveats attached.

4.5 The page adapts to whether a reader's device is set to a light or a dark
display mode, and it reflows for small screens. These are accessibility
considerations rather than substantive ones, but they indicate that the artefact
was built to be read on a phone as readily as on a desktop computer.

---

## 5. Reading the Headline Figures

The four numbers displayed across the top of the page are the report in
miniature. Each is examined here for what it represents, where it comes from,
and how far it can be carried.

5.1 The first figure: 1,287 megawatt-hours to train GPT-3, described as the
annual energy use of roughly 130 United States households. A megawatt-hour is
one thousand kilowatt-hours, and a kilowatt-hour is the unit that appears on a
domestic electricity bill. The figure originates in a 2021 study by Patterson
and colleagues at Google and Berkeley, which estimated the energy and emissions
of several large models from published information about the hardware used and
the duration of training. The household comparison is arithmetically sound: an
average American home uses something in the region of 10,000 kilowatt-hours a
year, so 1,287,000 kilowatt-hours corresponds to roughly 120 to 130 homes. The
figure is an estimate, not a measurement disclosed by the model's developer, and
it describes one training run of one model completed in 2020.

5.2 The second figure: 552 tonnes of carbon dioxide falling to 24 tonnes,
labelled on the page as the difference between training on a coal grid and
training on a renewable grid. The 552 tonne figure comes from the same 2021
study, but in that study it is not a coal-grid figure. It is the estimate for
the United States average electricity mix, calculated using a carbon intensity
of 0.429 kilograms of carbon dioxide equivalent per kilowatt-hour. The
arithmetic confirms this: 1,287 megawatt-hours multiplied by 429 kilograms per
megawatt-hour gives 552 tonnes exactly. A genuinely coal-dominated grid carries
roughly twice that carbon intensity and would produce a considerably higher
number. The underlying point the report is making, that the same computation
produces very different emissions depending on where it is run, is correct and
important. The label attached to the number is not.

5.3 The third figure: 240 to 340 terawatt-hours of electricity drawn annually
by the world's data centres. A terawatt-hour is one million megawatt-hours. This
range corresponds to International Energy Agency estimates published for 2022,
excluding cryptocurrency mining. The Agency's subsequent Energy and AI analysis
estimated data centre consumption at approximately 415 terawatt-hours in 2024,
around 1.5 per cent of global electricity, and projected roughly 945
terawatt-hours by 2030. The report's own text elsewhere gives data centres 1 to
2 per cent of global electricity, which remains consistent with the newer
estimate even though the terawatt-hour range does not. A reader citing this
figure onward should use the current Agency estimate rather than the one on the
page.

5.4 The fourth figure: a query processed in coal-heavy Wyoming producing
roughly ten times the emissions of the same query in hydroelectric Quebec. This
is the report's clearest illustration of a genuinely important idea, namely that
the emissions of a computation are set by the grid that powers it rather than by
the computation itself. The magnitude is directionally right and arguably
conservative, since the carbon intensity gap between a coal-dominated grid and a
hydroelectric one is wide. The figure describes emissions, not energy: the same
query uses the same electricity in both places.

5.5 A general caution applies to all four. None of these numbers was measured by
the report's authors. Each is a secondary rendering of an outside estimate, and
each is presented on the page without the assumptions that produced it. That is
the ordinary compression that headline statistics undergo, but it means the
figures should be treated as illustrative of scale rather than as precise
quantities.

---

## 6. The Measures Explained

The report uses a small vocabulary of technical measures. A policy reader who
understands these six will be able to read almost any document in this field.
Each is set out here with what it represents, why it is used, and how it feeds
into the conclusions the report draws.

6.1 The kilowatt-hour, and its larger relatives. A kilowatt-hour is a quantity
of electrical energy: one kilowatt of power drawn for one hour. It is the unit
on a household electricity bill. A megawatt-hour is a thousand of them; a
terawatt-hour is a billion of them. The report moves between all three, which is
where several of its arithmetical difficulties arise. This measure is the
foundation of everything else in the subject, because energy is what is actually
consumed. Carbon and water are consequences of how that energy is produced and
how the resulting heat is removed.

6.2 Carbon dioxide equivalent. Different gases warm the atmosphere by different
amounts and persist for different lengths of time. Carbon dioxide equivalent, or
CO2e, converts them all into the quantity of carbon dioxide that would produce
the same warming effect, so that a single number can express a total climate
impact. It is a policy convention rather than a physical fact, and it depends on
the time horizon chosen for the conversion. In practice, for electricity
consumption, carbon dioxide dominates the total.

6.3 Carbon intensity of the grid. This is the hinge on which the report's whole
energy argument turns, and it deserves the most attention. It expresses how much
carbon dioxide is emitted to generate one kilowatt-hour of electricity in a
given place, usually in kilograms. The Patterson study used 0.429 kilograms per
kilowatt-hour for the United States average. A grid running largely on coal sits
far above that; a grid running on hydroelectric or nuclear generation sits far
below it. The consequence, which the report states correctly, is that the
emissions of a computation are not a property of the computation at all. They
are a property of the electricity system it happens to be plugged into. This is
what makes location a policy lever: moving work to a cleaner grid, or timing it
for hours when cleaner generation is abundant, reduces emissions without
changing the work itself. The report cites carbon-aware scheduling of this kind
as capable of cutting emissions by around 30 per cent.

6.4 Parameters. When the report says a model has 175 billion parameters, it is
describing the number of adjustable internal values the model contains, the
settings that are tuned during training so the model produces useful outputs.
Parameter count is used throughout the field as a rough proxy for a model's size
and therefore for its cost to build and to run. The report makes the useful
observation that the relationship is not proportional: it reports that doubling
the parameter count can increase energy consumption by three to five times,
because the parts of the system that move data between processors become a
constraint alongside the computation itself. Readers should note that parameter
count has become a less reliable proxy in recent years, as architectural choices
allow large models to activate only part of themselves for any given task.

6.5 Power usage effectiveness, or PUE. This measures how much electricity a data
centre uses in total compared with how much reaches the computers themselves.
The formula is total facility energy divided by the energy used by the computing
equipment. If a facility draws 150 units of electricity to deliver 100 units to
its servers, with the remaining 50 going to cooling, lighting, power conversion,
and backup systems, its PUE is 1.5. The measure was developed by The Green Grid,
an industry consortium concerned with data centre efficiency, and it is the
standard by which facilities are compared.

The report's description of this measure contains an error that should be
corrected before the number is used. The report states that the scale runs from
0 to 1.0 with 1.0 being ideal. In fact PUE can never be below 1.0, because a
facility cannot deliver more energy to its computers than it draws in total. The
scale runs upward from 1.0, and 1.0 is the unattainable ideal representing a
facility with no overhead whatsoever. Lower is better, which the report states
correctly; but a value of 1.5 is a real figure and a value of 0.7 is impossible.
For context, the Uptime Institute's annual industry surveys have reported an
average of around 1.56 for several consecutive years, easing to approximately
1.54 in its 2025 survey, against averages above 2.5 in 2007. The practical
implication, which the report captures well, is that efficiency gains in this
area have largely plateaued, so growth in computing demand now translates
almost directly into growth in electricity demand.

6.6 Water usage effectiveness, or WUE. The companion measure for water,
expressing how much water a facility consumes for each unit of computing energy
delivered. Lower is better. The report explains the central tension clearly:
evaporative cooling, which uses the cooling effect of water turning to vapour,
reduces electricity consumption but consumes water, so a facility can improve
its PUE and worsen its WUE at the same time. In a water-stressed region this is
a poor trade. The report does not, however, give any quantities of water
anywhere in its text, which leaves the water discussion qualitative. Readers
seeking figures should consult the published work of Li and colleagues, whose
2023 study estimated that training GPT-3 in Microsoft's United States data
centres could consume in the region of 5.4 million litres of water in total,
including approximately 700,000 litres consumed directly on site.

6.7 Two further measures appear briefly. GPU hours and TPU hours count how long
specialised processors were occupied, multiplied by how many of them were used;
this is a measure of computational effort rather than of energy, and converting
between the two requires knowing how much power each processor draws. The report
gives a useful anchor, noting that one class of high-end processor draws
somewhere between 120 and 200 watts depending on the workload. Separately, the
report distinguishes between energy consumed in training a model and energy
consumed in inference, which is the term for using a finished model to answer a
question. This distinction is treated at length in the next section.

---

## 7. The Argument, Chapter by Chapter

7.1 Energy consumption. The report's strongest chapter. It separates the two
phases of a model's life. Training is the process of building the model by
exposing it to very large quantities of text or images so that its internal
settings adjust toward useful behaviour; this runs continuously for weeks or
months on thousands of processors and is enormously energy-intensive as a single
event. Inference is the process of using the finished model to answer an
individual question; this costs very little per question but happens billions of
times.

The chapter's central and correct claim is that the second of these has overtaken
the first in operational significance. It reports that inference accounts for 60
to 80 per cent of energy use in many real deployments, and that leading
technology companies now spend more of their artificial-intelligence energy
budget on serving models than on building them. This is an important corrective
to a public conversation that has focused heavily on the dramatic one-off cost of
training.

The chapter also identifies several specific drivers that a policy reader would
otherwise miss. Hyperparameter tuning, meaning the practice of training a model
repeatedly with different configurations to find the best one, is reported to
add 20 to 40 per cent to training energy, because the published cost of a model
reflects only the successful run and not the discarded attempts. The preparation
of training data carries its own energy cost that is rarely counted. Real-time
applications such as autonomous vehicles prevent processors from ever entering
low-power idle states. And image generation is reported to be dramatically more
energy-intensive per operation than text processing.

7.2 Data centres and hardware. This chapter covers the physical infrastructure
and is the most descriptive of the seven. Its most substantive contribution is a
clear comparison of five cooling approaches: air cooling, which is familiar and
cheap but struggles as computing density rises; liquid cooling, which is more
efficient and extends hardware life but costs more to install; free cooling,
which draws in cool outside air and is highly effective in the right climate;
evaporative cooling, which saves electricity at the cost of water; and hybrid
arrangements combining these, which the report identifies as the direction of
travel. For a reader trying to understand why data centre siting decisions
matter, this section does real work, because it shows that the environmental
profile of a facility is substantially determined by the climate it sits in.

The chapter also traces the supply chain backward to the mining of minerals used
in specialised chips, naming cobalt extraction in the Democratic Republic of the
Congo and rare earth processing in China, and identifying habitat destruction,
toxic refining byproducts, and transport emissions as the associated costs. This
is a genuine strength, since the embodied cost of hardware is routinely omitted
from discussions that count only electricity.

7.3 Mitigation and sustainable practice. A survey of what named organisations
are doing, covering Google's carbon-free energy commitment and its
machine-learning-driven cooling optimisation, Microsoft's carbon-negative
pledge and its work on more efficient model architectures, Amazon Web Services
on renewable supply and workload distribution, and Meta on emissions disclosure
for its published models. It notes that OpenAI has released no sustainability
strategy, carbon disclosure, or emissions commitment, which is a pointed and fair
observation given the scale of that company's operations. The chapter closes
with university research, including work on training optimisation, on model
designs that avoid repeated retraining, and on emerging carbon reporting
standards for machine learning.

7.4 Regulatory frameworks. The most policy-relevant chapter. Its central finding
is one of absence: environmental sustainability is largely missing from
artificial intelligence regulation, and largely missing from environmental
regulation as it applies to artificial intelligence. The report traces this
through the European Union's 2024 Artificial Intelligence Act, noting that
earlier drafts contained sustainability provisions including energy logging
requirements which were weakened during negotiation, leaving disclosure
obligations on providers of general-purpose systems and little else. It contrasts
this with the European Energy Efficiency Directive's reporting threshold for
data centres above 500 kilowatts, and with Germany's stricter national
requirement for renewable sourcing at facilities above 300 kilowatts. It covers
proposed United States legislation, and it records the formation, at the
February 2025 Artificial Intelligence Action Summit, of a coalition for
environmentally sustainable artificial intelligence convened by France, the
United Nations Environment Programme, and the International Telecommunication
Union.

7.5 Ethical and policy considerations. The shortest and most general chapter,
covering national strategies, the Paris Agreement, the OECD Artificial
Intelligence Principles, and the Sustainable Development Goals. It is the section
with the least specific sourcing and should be read as scene-setting.

7.6 Conclusion. Restates the argument and turns toward the constructive case
that artificial intelligence can contribute to environmental goals through
applications in energy optimisation, climate modelling, and conservation. The
report is careful not to present this as an offset for its own costs.

---

## 8. Where the Figures Come From

8.1 The report rests on 55 numbered references. These fall into several distinct
categories, and the distinction matters for how much weight each carries.

8.2 Peer-reviewed and technical research. A minority of the sources, but the
origin of the report's most-quoted numbers. The energy and emissions estimates
for large models trace to academic work of this kind.

8.3 Corporate sources. Google, Microsoft, Amazon, Meta, Intel, and specialist
vendors are cited directly for their own sustainability claims. These are the
best available account of what each company says it is doing, and they are not
independent verification that it is being done. The report generally reports
these claims in the companies' own terms.

8.4 Intergovernmental and official sources. The United Nations Environment
Programme, the United Nations Framework Convention on Climate Change, the
European Union's own publication of the Artificial Intelligence Act text, the
United States Department of Energy, the National Institute of Standards and
Technology, and United States Congressional bill texts. These are the strongest
sources in the collection for policy claims.

8.5 Trade press, consultancies, and explanatory websites. A substantial share of
the total, and the source of most of the technical explanation in the data
centre chapter. These are reasonable for definitions and industry practice, and
weaker as evidence for quantities.

8.6 The report uses author-date citations in its running text but does not
attach reference numbers to individual claims. Several statistics in the energy
chapter carry no visible attribution at all in the sentence where they appear.
For a reader wishing to trace a specific number to its origin, this is the
report's principal structural weakness, and it is what makes an independent
check of the kind performed in Section 9 necessary rather than optional.

---

## 9. Figures Requiring Correction or Care

This section exists because the report is a research document that others may
cite. Each item below was checked against the primary source. None of these
undermines the report's argument, which is well founded; all of them matter to
anyone quoting a specific number onward.

A note on status, added after peer review. Four of the items below have since
been corrected in the report itself, and the descriptions are retained here in
their original form because the corrected figures circulated for a period and a
reader may hold either version. Items 9.2, 9.3, 9.4 and 9.6 are corrected: the
626,000 pound figure is now attributed to the neural architecture search it
belongs to, both inference-energy scenarios are recomputed in consistent units
and labelled as illustrative upper bounds, and the power usage effectiveness
scale is stated correctly. A mineralogy error not catalogued below, which
described lithium, cobalt and nickel as rare earth elements, is also corrected;
they are critical minerals, and the rare earths are the lanthanides plus
scandium and yttrium. Items 9.1, 9.5, 9.7 and 9.8 stand as written and are
matters for a future revision. Section 4 of the report, which relayed corporate sustainability
claims at face value, has also been revised to distinguish a pledge from an
achievement, market-based from location-based energy accounting, and an offset
tonne from an unemitted one, and to cite the peer-reviewed primary studies
directly rather than through the outlets that summarise them.

9.1 The 552 tonne figure is not a coal-grid figure. As set out at 5.2, it is the
estimate for the United States average electricity mix. Presenting it as the
coal case understates how bad a genuinely coal-powered training run would be,
while overstating the emissions of an average one.

9.2 The 626,000 pound carbon dioxide figure is not a BERT figure. The report
states that training the BERT-base model on a coal-powered grid generated
626,000 pounds of carbon dioxide. In the 2019 Strubell study from which this
number comes, the figure of 626,155 pounds is attributed to a neural
architecture search, which is an automated process of trying very large numbers
of model designs to find a good one, and not to training a single BERT model.
The report's own adjacent sentence gives the correct BERT-base figure of 1,507
kilowatt-hours, which cannot be reconciled with 626,000 pounds of emissions
under any plausible carbon intensity. Two additional cautions apply: that
estimate was subsequently disputed at length by researchers at Google, who
argued it overstated the actual search by a very large factor because it assumed
a much larger model configuration and batch size than were actually used; and
the study's authors did not run the search themselves but estimated its cost
from published descriptions. This is among the most widely circulated numbers in
the field and among the least reliable.

9.3 The trillion-query calculation appears to be out by a factor of one thousand.
The report states that one trillion queries at 0.047 kilowatt-hours each would
consume 47,000 megawatt-hours, and compares this to the annual residential
electricity use of Ireland. The multiplication gives 47 billion kilowatt-hours,
which is 47 million megawatt-hours, or 47 terawatt-hours. The figure of 47,000
megawatt-hours is one thousandth of that. The comparison to Ireland is the tell:
47,000 megawatt-hours is a very small quantity of electricity, nowhere near a
national total, whereas 47 terawatt-hours is of the right order for such a
comparison. The error is one of unit rather than of reasoning.

9.4 The 4.3 billion user calculation does not follow from its own inputs. The
report states that 4.3 billion users submitting one query per day would consume
470,000 megawatt-hours annually, described as 365 times the cost of training.
That figure is exactly 1,287 megawatt-hours multiplied by 365, which suggests it
was derived by multiplying the training cost by the number of days in a year
rather than from the stated query volume. Carrying out the stated calculation
instead, at 0.047 kilowatt-hours per query, gives roughly 74 terawatt-hours per
year. The conclusion the report draws from this passage, that cumulative
inference dwarfs training, survives the correction and is in fact strengthened by
it.

9.5 The per-query energy figure of 0.047 kilowatt-hours sits at the high end of a
genuinely contested range and should not be presented as settled. Published
estimates for the energy of a single chatbot query span more than an order of
magnitude. Analyses published in 2023, based on the model generation and
processor hardware then in service, produced figures around 3 watt-hours per
query. A 2025 analysis by Epoch AI, using newer hardware and more realistic
assumptions about typical query length, estimated approximately 0.3 watt-hours.
The report's figure of 0.047 kilowatt-hours is 47 watt-hours, which is
substantially above both. Any conclusion that depends on this number should be
stated as a range with its assumptions attached.

9.6 The power usage effectiveness scale is misstated, as set out at 6.5. PUE
cannot be less than 1.0.

9.7 The 240 to 340 terawatt-hour data centre figure has been superseded, as set
out at 5.3. The International Energy Agency's Energy and AI analysis puts 2024
consumption at approximately 415 terawatt-hours and projects roughly 945
terawatt-hours by 2030.

9.8 The report contains a small internal inconsistency, describing 1,287
megawatt-hours as the annual use of 130 households in one place and of more than
100 households in another. Both are defensible roundings of the same
calculation, but the variation illustrates how loosely such comparisons travel.

---

## 10. Limitations

10.1 It is a literature review, not a measurement study. The report produces no
original data. Its authority is entirely the authority of its sources, and where
a source is a company describing its own performance, that limitation is
substantial.

10.2 It is a snapshot of a fast-moving subject. The estimates in this field are
revised frequently and sometimes dramatically, in both directions: model
efficiency improves, while total deployment grows. A report of this kind begins
to age immediately, and several of its figures have already been overtaken.

10.3 Individual claims are not traceable. Because citations are not attached to
specific statements, a reader cannot verify a given number without independently
locating its source, as this paper has had to do.

10.4 The water discussion has no quantities. Water is identified as a serious
concern and the relevant measure is explained, but no volumes appear anywhere in
the text. This is a notable gap given that water may be the more acute local
constraint in many of the regions where data centres are being built.

10.5 Electronic waste is named but not developed. The introduction identifies it
as one of three headline harms, alongside carbon and water. It receives no
sustained treatment thereafter.

10.6 The geographic frame is narrow. The regulatory chapter covers the European
Union and the United States in detail, with brief mention of China. The mining
regions that bear the extraction costs appear as sites of harm rather than as
jurisdictions with policies, interests, and agency of their own.

10.7 Comparative baselines are absent. The report establishes that artificial
intelligence consumes a great deal of energy. It does not situate this against
the energy consumption of the activities it displaces or the wider digital
sector, which limits what a policy reader can conclude about net effect.

10.8 It is student research. The report was produced by masters students as
part of a research collaboration. It should be read as a well-sourced
orientation to a subject, valuable for exactly that, and not as an authoritative
reference for specific quantities.

---

## 11. Intended Audience and Use

11.1 The report is pitched at an educated general reader rather than a
specialist. It explains what a graphics processing unit is, what training means,
and why cooling matters, which places it usefully in the hands of policy staff,
students, and journalists approaching the subject for the first time.

11.2 Its most defensible uses are as an orientation to the shape of the problem,
as a guide to the regulatory landscape and its gaps, and as an annotated route
into a dispersed literature by way of its 55 references. Its least defensible use
is as a source for a specific quoted statistic, for the reasons set out in
Section 9.

11.3 The four figures displayed at the top of the page are, by design, the part
most likely to be extracted and repeated. Two of the four require the corrections
noted above. Anyone quoting them should go to the primary sources, which are
identified in this paper.

---

## 12. Conclusion

12.1 The report makes a case that deserves to be made. Environmental cost has
been a marginal concern in the governance of artificial intelligence, and the
report is right that this is a gap in both technology regulation and
environmental regulation. Its account of how the European Union's sustainability
provisions were written into an early draft and negotiated back out again is the
kind of specific, documented finding that policy readers can act on.

12.2 Two of its analytical contributions stand out. The first is the insistence
that everyday use of models has overtaken their construction as the dominant
energy cost, which redirects attention from a dramatic one-off number toward a
continuous and growing one. The second is the emphasis on carbon intensity of
the grid, which establishes that the emissions of a computation are set by where
it happens rather than by what it computes. That observation converts an
apparently technical problem into a siting and scheduling problem, which is to
say into a problem that policy can reach.

12.3 The report's weaknesses are those of a synthesis assembled at speed in a
field where the underlying numbers are unstable, disputed, and frequently
reported without their assumptions. Several figures have been mislabelled or
misattributed in transit from their sources, one unit conversion has gone astray,
and one technical definition is stated incorrectly. Section 9 of this paper
records these so that the report can be used with appropriate care rather than
either accepted whole or dismissed.

12.4 The honest position is that nobody currently knows the environmental cost of
artificial intelligence with precision, because the companies that could measure
it are not required to publish it, and the researchers who estimate it must work
from the outside. That is itself the report's most durable finding, and the
strongest argument in it for the disclosure requirements it advocates.

---

## Attribution

Written by Alexandra Du, Elizabeth Matthews, Emily Harrington, Hannah Zhao,
Jennifer Hofmann, Natasha Nagarajan, Renata Gladkikh, and Smita Samanta, advised
by Professor Yorke Rhodes III, as part of masters research at the NYU Center for
Global Affairs (2026), under the Ethical Tech CoLab. The published web page in
this repository was built and deployed by Carolina Moron.

Views expressed in the report are those of the researchers and do not represent
the official positions of NYU, Microsoft, or any partner institution.

> Note: This paper is a plain-language review of an academic student report. The
> report is a literature synthesis rather than an original measurement study,
> and the estimates it draws on are contested and change quickly. Figures should
> be verified against their primary sources before being cited, and several
> requiring correction are identified in Section 9 above.
