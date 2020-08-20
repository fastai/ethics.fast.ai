## Syllabus

As the over 250 [tech ethics syllabi on this crowd-sourced spreadsheet](https://docs.google.com/spreadsheets/d/1jWIrA8jHz5fYAW4h9CkUD8gKS5V98PDJDymRf8d9vKI/edit#gid=0) (spearheaded by Casey Fiesler) illustrate, there is a huge amount of variation in what can be covered in a tech ethics course.  This class is not intended to be exhaustive. Read an [overview of the course](/) here.

There is a ton of great research and writing on the topics below, and it was very tough for me to cut this down to a "reasonable" length. There are many more fantastic articles, papers, essays, and bookson these topics that are not included here.

## Lesson 1: Disinformation

From deepfakes being used to harass women, widespread misinformation about coronavirus (labeled an "infodemic" by the WHO), fears about the role disinformation could play in the 2020 election, and news of extensive foreign influence operations, disinformation is in the news frequently and is an urgent issue. It is also indicative of the complexity and interdisciplinary nature of so many data ethics issues: disinformation involves tech design choices, bad actors, human psychology, misaligned financial incentives, and more.

### [Lesson 1 video](http://ethics.fast.ai/videos/?lesson=1)

### Required Reading:

- Will Oremus (covering the work of Mike Caulfield), [The Simplest Way to Spot Coronavirus Misinformation on Social Media](https://onezero.medium.com/the-simplest-way-to-spot-coronavirus-misinformation-on-social-media-4b7995448071)
- Guillaume Chaslot, [How Algorithms Can Learn to Discredit the Media](https://medium.com/@guillaumechaslot/how-algorithms-can-learn-to-discredit-the-media-d1360157c4fa)
- Rachelle Hampton, [The Black Feminists Who Saw the Alt-Right Threat Coming](https://slate.com/technology/2019/04/black-feminists-alt-right-twitter-gamergate.html)
- Renee DiResta, [Mediating Consent](https://www.ribbonfarm.com/2019/12/17/mediating-consent/)
- Manuel Velasquez et al, [“What is ethics?”](https://www.scu.edu/ethics/ethics-resources/ethical-decision-making/what-is-ethics/)

### Optional Reading:
- Gordon Pennycook et al, [Understanding and reducing the spread of misinformation online](https://psyarxiv.com/3n9u8/)

### Optional Lab for Coders:
- Intro to Language Modeling & Text Generation: [video lecture](https://www.youtube.com/watch?v=PNNHaQUQqW8&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=12&t=0s) and [jupyter notebook](https://github.com/fastai/course-nlp/blob/master/5-nn-imdb.ipynb) (from fast.ai NLP course)

## Lesson 2: Bias & Fairness

Unjust bias is an increasingly discussed issue in machine learning and has even spawned its own field as the primary focus of Fairness, Accountability, and Transparency (FAccT).  We will go beyond a surface-level discussion and cover questions of how fairness is defined, different types of bias, steps towards mitigating it, and complicating factors.

### [Lesson 2 video](http://ethics.fast.ai/videos/?lesson=2)

### Required Reading/Watching:

- Arvind Narayan, [21 Definitions of Fairness](https://www.youtube.com/watch?v=jIXIuYdnyyk)
- Timnit Gebru et al, [Datasheets for Datasets](https://arxiv.org/abs/1803.09010)
- Harini Suresh and John Guttag, [A Framework for Understanding Unintended Consequences of Machine Learning](https://arxiv.org/abs/1901.10002)
- Samir Passi and Solon Barocas, [Problem Formulation and Fairness](https://arxiv.org/abs/1901.02547)

### Optional Reading:
- Ulrich Aivodji et al, [Fairwashing: the risk of rationalization](https://arxiv.org/abs/1901.09749)
- Alice Xiang and Deborah Raji, [On the Legal Compatibility of Fairness Definitions](https://arxiv.org/abs/1912.00761)

### Optional Lab
Involves code, but was geared to audience that included beginners:
- [Word Embeddings, Bias in ML, Why You Don't Like Math, & Why AI Needs You](https://www.youtube.com/watch?v=25nC0n9ERq4) and the [jupyter notebooks](https://github.com/fastai/word-embeddings-workshop)

## Lesson 3: Ethical Foundations & Practical Tools

Now that we’ve seen a number of concrete, real world examples of ethical issues that arise with data, we will step back and learn about some ethical philosophies and lenses to evaluate ethics through, as well as considering how ethical questions are chosen.  We will also cover the Markkula Center’s Tech Ethics Toolkit, a set of concrete practices to be implemented in the workplace.

### [Lesson 3 video](http://ethics.fast.ai/videos/?lesson=3)

### Required Reading
- Shannon Vallor et al, [Conceptual Frameworks in Technology and Engineering Practice: Ethical Lenses to Look Through](https://www.scu.edu/ethics-in-technology-practice/ethical-lenses/)
- Ian Bogost, [Enough With the Trolley Problem](https://www.theatlantic.com/technology/archive/2018/03/got-99-problems-but-a-trolley-aint-one/556805/)
- Zeynep Tufekci, [Sociological Storytelling vs. Psychological Storytelling](https://blogs.scientificamerican.com/observations/the-real-reason-fans-hate-the-last-season-of-game-of-thrones/)
- Langdon Winner, [Do Artifacts Have Politics?](https://www.cc.gatech.edu/~beki/cs4001/Winner.pdf)
- Shannon Vallor, [An Ethical Toolkit for Engineering/Design Practice](https://www.scu.edu/ethics-in-technology-practice/ethical-toolkit/)

### Optional Reading
- Meg Young et al, [Toward inclusive tech policy design: a method for underrepresented](https://www.scu.edu/ethics-in-technology-practice/ethical-toolkit/)
voices to strengthen tech policy documents
- Margaret Mitchell et al, [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993)
- Eric P. S. Baumer and M. Six Silberman, [When the Implication Is Not to Design (Technology)](https://www.ics.uci.edu/~djp3/classes/2011_01_INF134/papers/impl9-rev.pdf)
Mark White, [Superhuman Ethics Class With The Avengers Prime](https://media.wiley.com/product_data/excerpt/72/11180745/1118074572-234.pdf)

## Lesson 4: Privacy and surveillance

Huge amounts of data are being collected about us: apps on our phones track our location, dating sites sell intimate details, facial recognition in schools records students, and police use large, unregulated databases of faces.  Here, we discuss real-world examples of how our data is collected, sold, and used.  There are also concerning patterns of how surveillance is used to suppress dissent and to further harm those who are already marginalized.

### [Lesson 4 video](http://ethics.fast.ai/videos/?lesson=4)

### Required Reading
- Jennifer Valentino-DeVries et al (NYT), [Your Apps Know Where You Were Last Night, and They’re Not Keeping It Secret](https://www.nytimes.com/interactive/2018/12/10/business/location-data-privacy-apps.html)
- Phillip Rogaway, [The Moral Character of Cryptographic Work](https://web.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf)
- Alvaro Bedoya, [Privacy as a Civil Right](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3599201)
- Chris Gilliard, [Caught in the Spotlight](https://urbanomnibus.net/2020/01/caught-in-the-spotlight/)

### Optional Reading
- Maciej Ceglowski, [The New Wilderness](https://idlewords.com/2019/06/the_new_wilderness.htm)
- Lindsey Barrett, [Our collective privacy problem is not your fault](https://www.fastcompany.com/90447583/our-collective-privacy-problem-is-not-your-fault)
- Ciara Byrne, [Trading privacy for survival is another tax on the poor](https://www.fastcompany.com/90317495/another-tax-on-the-poor-surrendering-privacy-for-survival)
- Tim Wu, [How Capitalism Betrayed Privacy](https://www.nytimes.com/2019/04/10/opinion/sunday/privacy-capitalism.html)
- Reyhan Harmanci, [Forget about “privacy”: Julia Angwin and Trevor Paglen on our data crisis](https://www.fastcompany.com/90337954/who-cares-about-liberty-julia-angwin-and-trevor-paglen-on-privacy-surveillance-and-the-mess-were-in)

## Lesson 5: How did we get here? Our Ecosystem
News stories understandably often focus on one instance of a particular ethics issue at a particular company.  Here, I want us to step back and consider some of the broader trends and factors that have resulted in the types of issues we are seeing.  These include our over-emphasis on metrics, the inherent design of many of the platforms, venture capital’s focus on hypergrowth, and more.

### [Lesson 5 video](http://ethics.fast.ai/videos/?lesson=6)

### Required Reading:
- Zeynep Tufekci, [How social media took us from Tahrir Square to Donald Trump](https://www.technologyreview.com/s/611806/how-social-media-took-us-from-tahrir-square-to-donald-trump/)
- James Grimmelman, [The Platform is the Message](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3132758)
- Rachel Thomas, [The Problem with Metrics](https://www.fast.ai/2019/09/24/metrics/)
- Tim O’Reilly, [The fundamental problem with Silicon Valley’s favorite growth strategy](https://qz.com/1540608/the-problem-with-silicon-valleys-obsession-with-blitzscaling-growth/)
- Ali Alkhatib, [Anthropological/Artificial Intelligence & the Institute for Human-centered AI](https://ali-alkhatib.com/blog/anthropological-intelligence)
- Tom Slee, [The incompatible incentives of private sector AI](https://tomslee.github.io/publication/oup_private_sector_ai/)

## Lesson 6: Algorithmic Colonialism, and Next Steps
When corporations from one country develop and deploy technology in many other countries, extracting data and profits, often with little awareness of local cultural issues, a number of ethical issues can arise. Here we will explore algorithmic colonialism.  We will also consider next steps for how students can continue to engage around data ethics and take what they’ve learned back to their workplaces.

### [Lesson 6 video](http://ethics.fast.ai/videos/?lesson=9)

### Required Reading:
- Abeba Birhane, [The Algorithmic Colonization of Africa](https://reallifemag.com/the-algorithmic-colonization-of-africa/)
- Amy Maxmen, [Can tracking people through phone-call data improve lives?](https://www.nature.com/articles/d41586-019-01679-5)
- Adrienne Lafrance, [Facebook and the New Colonialism](https://www.theatlantic.com/technology/archive/2016/02/facebook-and-the-new-colonialism/462393/)

### Optional Reading:
- Joe Parkinson et al, [Huawei Technicians Helped African Governments Spy on Political Opponents](https://www.wsj.com/articles/huawei-technicians-helped-african-governments-spy-on-political-opponents-11565793017)
- Davey Alba, [How Duterte Used Facebook To Fuel The Philippine Drug War](https://www.buzzfeednews.com/article/daveyalba/facebook-philippines-dutertes-drug-war)
- Rumman Chowdhury, [Algorithmic Colonialism](https://docs.google.com/document/d/1wyes_kCE_WlctUtEQw5yuuJplddkSQtuGHBMxsjycGA/edit#heading=h.7bwzqcvjorcc)
- Jess Whittlestone et al, [The role and limits of principles in AI ethics: towards a focus on tensions](https://www.aies-conference.com/2019/wp-content/papers/main/AIES-19_paper_188.pdf)

