



# Data Ethics

Now that we have covered the basics of data management, we will take a moment to consider and reflect on the implications of our use and sharing of data.

<img src="resources/images/05-Data_Ethics_files/figure-html//1SRokLaGAc2hiwJSN26FHE0ZEEhPr3KQdyMICic8kAcs_g11ef3a2f2bf_0_4.png" title="Learning Objectives: 1.Describe the general considerations for data ethics, 2. Recognize where these considerations come from in the history of research, 3. Understand what the current ethical dilemmas are in the current climate of biomedical research 4. Be aware of methods for mitigating current ethical issues to protect both the participants in your research and others. " alt="Learning Objectives: 1.Describe the general considerations for data ethics, 2. Recognize where these considerations come from in the history of research, 3. Understand what the current ethical dilemmas are in the current climate of biomedical research 4. Be aware of methods for mitigating current ethical issues to protect both the participants in your research and others. " width="100%" style="display: block; margin: auto;" />

## What is data ethics?

Data ethics involves the consideration of data collection, maintenance, security, privacy, and sharing, and mindfulness about how our research can ultimately impact (or not impact as the case may be for research that lacks inclusivity and equity) research participants and other individuals. Importantly, we do not yet have established societal norms or protocols for every aspect of medical research, and many topics are still under debate especially when it comes to cutting edge research.  However, general principles of ethics can be helpful and involve practices for research integrity, consideration for social justice, data security, and transparency. 

### Before and after research

Data ethics requires thoughtfulness *both* throughout the planning and research process to produce research that benefits society and does as little harm as possible, as well as mindfulness for what happens after the research is complete and published. Researchers need to consider both how their work will resolve unanswered questions and who the research might help, as well as consider how others might use or misuse their data, code, and results in the future [@lipworth_ethics_2017; @teoli_informatics_2021]. 

### Considerations before

Ethical research should involve consideration of how data should be collected, so that certain individuals are not left out of reaping the benefits of important research. For example, women, non-binary individuals, disabled individuals, and people of certain ethnic backgrounds, and intersections of various demographic factors have been historically left out of clinical trials or when included, their data was inadequately recorded [@clark_increasing_2019]. For example, clinical trials often have questions about sex or gender with limited binary options (overlooking [people without a binary sex](https://en.wikipedia.org/wiki/Intersex) and [non-binary gendered](https://en.wikipedia.org/wiki/Non-binary_gender) individuals) resulting in a lack of collection of important information that could impact clinical outcomes, research results, and communication about results [@chen_approach_2019].

Beyond this, even basic studies have historically often neglected to evaluate female animal models which can provide a greater understanding of how the research may successfully translate to more individuals. Yet another example is the historical lack of diversity in genomic reference datasets. To learn more about how social injustice, sexism and other societal aspects have influence bioethical and therefore data ethics practices, see @Farmer_2004. 


## After Considerations

While data sharing can result in wonderful opportunities for secondary analysis, we need to also consider some of the harm that could be caused by sharing our data and make sure that we do it mindfully. With more advanced forms of genomic and imaging technology, and increased use of data from our phones we have much more information (including real-time data) about the subjects we are using, and thus the risk to our subject from the consequences of others **identifying** the subjects in our studies is much higher than it used to be [@byrd_responsible_2020]. 


Overall there is a continuum of risk across the various types of data that we as researchers collect. Wile some forms of data, such as that derived from model organisms pose essentially no risk, intermediate forms of data such as summarized counts across a set of human samples pose more risk, while raw data and in particular data from individuals such as whole genome sequencing data, pose great risk for identification [@byrd_responsible_2020]. 


Why does it mater that research subjects might be identifiable to others?

In some cases open awareness about patients with certain types of cancers or diseases can be useful to allow other researchers and patients to find these individuals to encourage additional research and patient support group participation (especially for rare diseases or conditions). 

However, such information can put these individuals at risk for difficulty with insurance and employment, as well as at risk for other forms of discrimination. Furthermore, research data often also contains basic information about individuals, such as their address, which can be potentially deleterious for the safety of those individuals. New forms of research data from apps on our phone such as social media data collection, can pose more complicated risks based on data collection about the behaviors of research participants [@seh_breaches_2020].  

Beyond the risk that data breaches pose to research participants, such breaches also cause harm to the research institutes where the breach occurred. Reputations and funding opportunities can be greatly compromised.


Why else does data protection matter at the individual level?

If data gets manipulated or corrupted, this can result in false research findings, altered treatment plans by physicians, and more @seh_breaches_2020. 


We will discuss what can be done to reduce the risks of research participants and others from your research.



## Data ethics history

To have an understanding of current theories about how to best deal with our research ethic conundrums it is helpful to be aware of the history of biomedical research in general.

Most regulations of biomedical research stems from historical ill treatment of research participants. This has taken many forms from outright ill intent, to much more well-intended but **neglectful** research practices often due to a lack of awareness of the potential consequences. This has been especially difficult more recently as our potential to create and share data has dramatically expanded.

### Historical incidences:

Here are a couple of famous historical examples of medical research that was performed in a harmful manner. These incidences have shaped policy about ethical research, in terms of advocacy for informed consent (more on that in the next section), as well as recognition for the role of social injustice in research. 

1. [Tuskegee syphilis trial](https://www.mcgill.ca/oss/article/history/40-years-human-experimentation-america-tuskegee-study):
A study in Tuskegee, Alabama about the outcomes of untreated syphilis in Black males (1932-1972) in which the patients were told they were being treated but were in fact not being treated [@mcvean_40_2019].

2. [Henrietta Lacks and HeLa Cells](https://www.nature.com/articles/d41586-020-02494-z):
In 1951, a patient named Henrietta Lacks was treated for cervical cancer at Johns Hopkins. Her cancerous cells turned out to be uniquely capable of surviving and reproducing and have been used widely in research for decades for many discoveries. Her family did not receive money from the companies that profited from her cells, and for decades her family was often not asked for consent as doctors and scientists revealed her name and medical records publicly (@noauthor_henrietta_2020).


See [here](https://jhudatascience.org/Informatics_Research_Leadership/promoting-diversity-equity-and-inclusion.html#historical-injustice) for additional examples.



### Recent incidences:

With advances in technology allowing for cheaper and easier production of medical datasets more than ever before, we saw the creation of databanks and other shared data resources. This resulted in new ethical issues. 

Here are some examples that exemplify more current data ethics issues:

1) Data Misuse for Marketing

Commercial use of data is yet another possible use of research data. There is one example in which such a situation may have occurred, although there sources about the incident are conflicting [@kramer_surescripts_2019]. ReMy Health is a data analytics company that processes raw patient prescription and insurance data and provides this data to other companies. It was using data from [Surescripts](https://surescripts.com/), a prescription and health record data company and providing it in a processed form for Amazon's PillPack (https://www.pillpack.com/), a prescription delivery service. ReMy Health or one of its customers was accused of providing unauthorized access of prescription and patient health insurance information, which was believed to be for pharmaceutical companies for marketing decisions about what medications to market [@chiruvella_ethical_2021]. Surescripts then decided to  revoke access for ReMy health to their data, thus hindering access to PillPack. However, Surescripts who made the allegations against ReMy Health has also had complaints of being threatening toward other companies, so it is a bit unclear exactly what happened [@kramer_surescripts_2019]. However, ultimately this resulted in a difficult situation for patients to receive their prescriptions and illustrates how data breaches or misuse by a single party when the data is utilized by multiple parties can get complicated [@kramer_surescripts_2019]. 


2) Data Breaches

[MyHeritage](https://en.wikipedia.org/wiki/MyHeritage) is a genetic testing company based in Israel that provides ancestry information to customers. In 2018, a security incident occurred in which an unauthorized user somehow acquired access to email address and password hash key for over 92 million users. Although this was a very large data breach in terms of the number of users impacted, they believe that none of the genetic data actually got leaked to this unauthorized user [@myheritage_2018]. This incident however highlights the concern that could happen if the cybercriminal had been more successful. 


3) Data mistakes and neglect

[Keith Baggerly](https://www.utmb.edu/research/research-at-utmb/utmb-research-day/keith-baggerly) is a well-known expert in what he calls "Forensic Bioinformatics". He evaluates other studies to see if he can reproduce their work. He has in a few cases found some very important mistakes. Often the mistakes have to do with sample mixups or a shift in a table resulting mislabeled rows or columns. Although such simple mistakes seem minor, Keith has shown that this can result in major consequences. 

One rather well-known example is his evaluation (along with Kevin Coombes and Jing Wang) of several now retracted articles (see [here](https://pubmed.ncbi.nlm.nih.gov/17057710/) and  [here](https://www.thelancet.com/journals/lanonc/article/PIIS1470-2045(07)70345-5/fulltext)) by Anil Potti regarding chemosensitivity of cancer cell lines based on gene expression signatures [@baggerly_deriving_2009]. First the forensic team discovered simple yet very consequential errors (sample case control labels were swapped) in Potti's work.  This lead to further investigations revealing further mistakes, as well as data falsification in several of Potti's articles. Ultimately, the clinical trials that were initiated based on Potti's work were terminated, several of Potti's articles were [retracted](https://retractionwatch.com/2011/01/29/lancet-oncology-retracts-previously-questioned-anil-potti-paper/),  and he was asked to resign from his position. See @national_academies_of_sciences_detailed_2017 for more [information](https://www.ncbi.nlm.nih.gov/books/NBK475955/) about Potti's case as well as 4 other similar cases.

Keith Baggerly [points out](https://www.nature.com/articles/d41586-018-06903-2) that simple errors do not need to lead to dramatic consequences and encourages investigators to be transparent in reporting their mistakes as early as possible. A good example of an investigator owning up to a mistake is that of Bob Carpenter, see [here](https://lingpipe-blog.com/2009/09/15/retraction-only-1-precision-at-99-9-recall-for-biocreative-gene-chunks/) due to some "buggy evaluation code" as he states [here](https://statmodeling.stat.columbia.edu/2010/10/21/forensic_bioinf/). While pressures often make us feel a need to be perfect. To err is to be human, and taking responsibility for our research mistakes should become acceptable, common practice, and revered by the research field at large.

Keith points out however, that it is currently difficult for researchers to find the time to deeply investigate the work of others and suggests that perhaps scientists at funding agencies could perform such forensic work to ensure the integrity of our scientific findings [@baggerly_what_2018].

https://academic.oup.com/g3journal/article/5/10/2177/6028939
https://projecteuclid.org/journals/annals-of-applied-statistics/volume-3/issue-4/Deriving-chemosensitivity-from-cell-lines--Forensic-bioinformatics-and-reproducible/10.1214/09-AOAS291.full



4) Data falsification

Although the previous example ultimately led to some discoveries of falsification, the majority of the discovery started with findings of simple mistakes. However, there are many other reported cases of researchers falsifying or modifying their data to improve their results. See [here](https://ori.hhs.gov/education/products/RIandImages/misconduct_cases/findings_of_misconduct.pdf) for examples of misconduct cases identified by the [Office of Research Integrity at the US department of Health and Human Services](https://ori.hhs.gov/).  


https://www.thphys.uni-heidelberg.de/~stamatescu/DIDEPG/SEMPE/SEE/see13_35046090.pdf




https://en.wikipedia.org/wiki/Scientific_misconduct

Goodstein, D. 2002. “Scientific Misconduct.” Academe Online; 88(1): 

https://www.thphys.uni-heidelberg.de/~stamatescu/DIDEPG/SEMPE/SEE/see13_35046090.pdf

https://www.tandfonline.com/doi/full/10.1080/08989621003641132

https://journals.sagepub.com/doi/pdf/10.1177/1745691612460687



4) Improper Data Reuse for Research

This section is largely based on an [article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5310710/) by @garrison_genomic_2013.

A research group at Arizona State University (ASU) initially collected DNA data from individuals of the Havasupai Tribe to study risk for type 2 diabetes in 1989. These samples were then later used for other genetic studies, including studies about "schizophrenia risk, ethnic migration, and population inbreeding" [@garrison_genomic_2013]. The Tribe did not want research to be done on these topics, as they could be stigmatizing for certain groups. The research participants did not feel that they consented to other research outside the scope of diabetes and this ultimately led the Tribe to file a lawsuit in 2004 against the researchers and the ASU board of regents. No ruling was made as there was a procedural error leading to the case being dismissed, however a settlement was reached, giving monetary compensation and then return of the genetic samples back to the Tribe. The Tribe also banned all ASU researchers from their reservation. 

This case pointed out the challenges of informed consent especially when documents are written in languages other than the native language of the participants. In this case the participants signed informed consent documents written in English that said samples would be used for "behavioral/medical problems", yet in spoken word, the consent documents may have been described as indicating that the samples were to be used for diabetes specifically.

When the researchers decided to study schizophrenia, they obtained Internal Review Board (IRB) approval based on the consent documents, and no additional conversations happened with the Tribe to ensure that the participants understood and consented to the samples being used for other types of studies.

Another important component of native or tribal populations, is that some tribes consider all Biological materials to be sacred and therefore greater transparency about the details of how materials are to be used and greater opportunity to determine how unused materials should be disposed would be very valuable.

This was a very informative case in terms of pointing out many overlooked concerns in data ownership, particularly of vulnerable populations.  These concerns include a lack of consideration about the balance of benefit to researchers and others relative to the potential harm or lack of benefit to the research participants and a lack of clarity about how to properly consent populations. 

Due to this case [@after_2010] and other historical disrespectful, neglectful, or harmful research engagements [@garrison_genomic_2019], subsequently many tribes became reluctant to participate in research. As many of these concerns continue, many remain justifiably reluctant. Over time this has more recently resulted in discussions about how research can be more respectful, transparent, and culturally responsive with equity and justice as the priority, with Indigenous, Tribal or Native scholars leading the way [@garrison_genomic_2019]. However more work is desperately needed to improve both health disparities and justice. 

Possible guidelines could include (based on @garrison_genomic_2019, @garrison_genomic_2013, and the author's thoughts):

1) To better understand the needs and concerns of the populations to be studied, members of those populations and communities should be directly involved in the governance of biological data. This concept is called data sovereignty [@garrison_genomic_2019].  Population members should help determine how researchers work with and consent individuals. More direct participation of these members in the research or IRB processes itself is also  beneficial. 

2) Where possible biological samples should be physically "owned" by the populations that the come from or at least considered as such, even when samples are taken to a lab for processing. Details about how the samples should be stored or disposed of, should be discussed with the study population. 

3) Researchers and IRBs should consider not only the health impacts and security of research participants, but also the potential social and community consequences. To better understand these possible consequences, members of the populations studied should again be directly involved in these discussions.
  
3) Researchers and IRBS should consider more about the balance of the possible benefit to researchers and society versus the potential lack of benefit or harm that the research may cause the participants are the communities they come from - research should aim to be more beneficial to those participating. To better understand the needs and possible harmful consequences of research, members of the communities or populations should be involved in discussions.

4) Ambiguity about consent should be reduced as much as possible to ensure that information is provided that is as transparent, culturally responsive, and clear to those who are consented.

5) Participants may need to be contacted again to ensure that consent remains responsive and transparent.

6) More targeted specific data uses may be more comfortable for some populations, and may therefore be worth potential later restriction.

Many research groups have decided to use **Broad Consent** in which only a set of potential future activities are consented to reduce later concerns. However this can still result in discomfort and thus a lack of participation by populations that are concerned about the use of their biological materials. This can ultimately result in even deeper health disparities. 

Overall, it is very important that researchers and research institutions continue to discuss and work with members of the populations they wish to study to create more equitable, just, and culturally responsive consent processes.

One [article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7895446/)  by @begay_weaving_2020 about the history of genetic studies of the Diné (or Navajo nation), another population that has faced genetic data misuse, state that the authors: 

> encourage researchers to consider cultural perspectives and traditional knowledge that has the potential to create stronger conclusions and better-informed, ethical, and respectful science.

## General Ethics Code

maybe go into this: https://educationprojects.co.uk/medical-ethics-ethical-dilemmas-in-healthcare/

and this amazing timeline:
https://www.usuhs.edu/sites/default/files/2021-06/TimelineofLandmarkEventsinBioethics.pdf

- informed consent etc. [@commissioner_guide_2020]

Code of Medical Ethics (1957) - Legal Binding of Patient-Physician Confidentiality 

1996 Health Insurance Portability and Accountability Act (HIPAA)
 - protected health information and identifiable health information must not be shared with anyone outside of certain covered entities without consent. Covered entities include: clinicians, insurance companies, and health care government agencies. 
 
 Genetic Information Nondiscrimination Act of 2008 (GINA)

2009 Health Information Technology for Economic and Clinical  Health (HITECH) Act

https://www.govinfo.gov/app/details/FR-2013-01-25/2013-01073

Code of Federal Regulations (CFR)- protocol for life cycle for patient records

Higher Education Act of 1965


https://www.nih.gov/health-information/nih-clinical-research-trials-you/guiding-principles-ethical-research

https://www.compliance.iastate.edu/sites/default/files/imported/irb/guide/docs/Recruitment%20of%20Research%20Participants.pdf

https://www.hipaajournal.com/largest-healthcare-data-breaches-of-2021/

## Current Ethical Issues

There are several issues that researchers and research participants, and really all individuals engaging in health care face. We will discuss some of these briefly.


### Consent for Data Reuse

One major current ethical issue that we face now, is the consequences of the reuse of shared data. As we have described, there are major benefits of sharing data. It can allow researchers to really maximize their efforts. However, there are also negative potential consequences as well. Furthermore, it is still unclear what is exactly possible with our data, for both good and bad uses, as technology continues to advance.


Previous management strategies for informed consent originate from research that predates the large scale data sharing that we now use today. In those cases, informed consent was a bit more straight forward to achieve. Now that data is often reused more often, it is often less obvious how data will be used for research purposes in the future, thus it is less obvious how to inform potential research participants what participation really means. Ideally we want to protect participants and family, while also maximizing the research potential of useful data. So how do we do this?

Although ethical guidelines about this type of consent are evolving as research and technology evolve, here are some current methods for consent as described in @mckeown_consent_2021.

1) blanket consent - Subjects agree that their data can be used for any purpose that the data holder agrees is reasonable.
2) broad consent - Subjects agree that their data can be used for a set of specified purposes. This is more protective but also restricts some uses of data.
3) dynamic consent - Subjects are asked case-by-case for others to use their data. This requires more burden on both the data managers and also the subjects, as they need to continually decide about providing consent or not.
4) meta consent - Subjects get to choose what type of consent they prefer of the other 3 options. 


@mckeown_consent_2021 suggests that we also need to be mindful of the following:

1) Participants should be educated about the uncertainty of the possible future uses of the data.
2) Participants should be able to withdraw their consent for reasons that have been identified as being reasonable. (This creates many more ethical considerations.)
3) Those managing the data and those using the data behave in a trustworthy manner based on defined data management and use regulations (including protection of of data).
4) Participants should be informed about how ethical decisions about their data are weighed based on the benefit to society vs. the risk to individuals and that this involves uncertainty as well.

We would like to suggest that updated information should possibly be provided to participants about changes in awareness of potential data uses and changes in awareness of the potential benefit or lack of benefit of the data to society.

New consent issues:https://www.frontiersin.org/articles/10.3389/fgene.2019.01107/full

hmm or how it is described here:https://www.nature.com/articles/s41576-020-0257-5.pdf

great clinical resource: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4943495/

### Data sovereignty

Let's take a slightly deeper dive into what data sovereignty really is. 

We have already described it as a concept of ownership of data, that the people who the data comes from determine or at least are highly involved in what happens with that data. This is important in the study of people who have been marginalized and historically mistreated in research or otherwise. However, the term data sovereignty can also be defined more broadly, such as the authority of governments to survey or use data from domestic or foreign sources, a concept that is also of important recent interest [@hummel_data_2021].

A [review](https://journals.sagepub.com/doi/10.1177/2053951720982012) of recent literature by @hummel_data_2021 indicates that data sovereignty is often defined in **many ways** including the ability, rights, or laws surrounding the control, flow, privacy, security, or use of data. The review also suggests that there are therefore several major ways in which data sovereignty can be realized:

1. Self-determination - Promoting, honoring, and respecting the interests, values and culture of those that the data comes from (particularly when it comes to indigenous populations) by allowing for their participation in determining what happens with the data and how it is collected.Strategies should be used to ensure that the data is beneficial and responsive to the needs of those that the data comes from, as well as mindful of the potential consequences of their use and collection.

2. Technical Consideration - IT architecture to ensure that the data is safe and used as intended.

3.Transparency - People should know when data is being collected about them and what it is being used for. 

4. Legal  Considerations - Some countries or nations have regulations about what can be done with data particularly when it comes to transmission to other nations.

The authors of the review [@hummel_data_2021] caution that the inconsistency with which data sovereignty is defined could lead to negative consequences if efforts are not made to define the term when it is used. For example, if someone's concept of data sovereignty is strictly of a technical definition, then important aspects related to transparency or self-determination may be overlooked. They note that Indigenous data sovereignty or data sovereignty as it pertains to indigenous populations, is more more clearly defined, and could be used as a model for other uses of the term in other contexts.

The meaning of the terminology is likely to evolve over time, however, this indicates the complexity of data handling ethics that we are currently encountering and will continue to encounter.

### Finding Artifacts

In some cases researchers will determine aspects about the potential health or genetic risk of an individual as an artifact of performing other research. This leads to the question of if those individuals should be informed about these findings.

Depending on the nature of the research, the potential for finding incidental findings will vary. The [Secretary’s Advisory Committee on Human Research Protections (SACHRP)](https://www.hhs.gov/ohrp/sachrp-committee/recommendations/attachment-f-august-2-2017/index.html) at the US Department of Health and Human Services [@protections_ohrp_attachment_2017] offers guidelines about this topic. Furthermore, if the research requires FDA regulations, than there is more defined guidance and requirements about incidental findings. Yet, for other forms of research, the determination will occur mostly with the institutional IRB. 

Often the first suggested step is to determine how likely the research is to yield any actionable incidental findings. Actionable findings are those where the research subject could actually do something to about the finding to improve their health or reduce the risk of health concerns. However, it can be difficult to determine if such a finding will become actionable in the future, particularly when it comes to collecting genomic data. 

To be more mindful of future consequences, researchers could also ask their research participants if they would want to know about incidental findings if they were to become actionable in the future. 


### Protection of Vulnerable Populations

#### Minors
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0237875
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8178732/?report=classic
### Equity of Health Care


### Data Security and Privacy in the Age of AI

avocado... possibly introduce: differential privacy https://mccourt.georgetown.edu/research/the-massive-data-institute/resources/dp-resources/




patient experience: https://journals.sagepub.com/doi/full/10.1177/160940691401300121

HIPAA: https://www.hipaaexams.com/blog/everything-you-need-to-know-about-a-hipaa-violation/#:~:text=Criminal%20Penalties,-These%20penalties%20are&text=They%20can%20be%20as%20follows,for%20up%20to%20five%20years

https://inspiredelearning.com/blog/hipaa-violation-examples/

https://www.hhs.gov/hipaa/filing-a-complaint/index.html

bad examples:

https://www.hipaajournal.com/ocr-3-6-million-settlement-feinstein-institute-for-medical-research-3361/

Places that report data breaches - based on @@seh_breaches_2020:
1) PRC Database (Consumer data  established in 1992)
2) HIPAA Journal (Examples of violations of HIPAA compliance and guides to avoid violation, established in 2009)
3) Office for Civil Rights Department of Health and Human Services of the USA (OCR) reports (yearly reports on health care data since 2009)
4) Ponemon Institute Reports (Data privacy and security issues and policies, established in 2002)
5) Verizon-DBIR (yearly investigations by Verizon Enterprises, established in 2008)

maybe talk about federated learning? https://www.nature.com/articles/s41591-021-01614-0

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7349636/


interesting resource!https://ctep.cancer.gov/branches/ctmb/clinicalTrials/docs/good_clinical_practices.pdf

## Causes of research misconduct

A research study @davis_causal_2007 investigated closed cases from the Office of Research Integrity (ORI), using statements from the reports to evaluate reasons why researchers sometimes do not perform research responsibly.


The following categories of factors were identified among the reports:
1) Personal and professional stressors
 This included statements about stressors encountered at work and personally such as:
 
 - pressure to produce
 - overworked
 - insufficient time
 - mental health issues
 - overcommitted
 - lack of support
 - stress

2) Organizational climate factors
This included statements of factors such as:

- insufficient mentoring/supervision
- poor communication/coordination
- substandard lab procedures
- lost stolen data

3) Job Insecurities
These cases described situations in which a researcher felt hesitant to ask for help due to a perception of job insecurity.
- Inappropriate responsibility
-  Competition for position
- Language Barrier
 
4) Rationalizations
Justifications that were often offered included:
- Lack of control over environment
- jumping to the gun to disseminate findings

5) Personal Inhibitions
Difficult job/task
Frustrations

6) Another category of Rationalizations

Fear, Apathy/Dislike, Restoring Equity, Avoiding Degradation by Others, and Slippery Slope

7) Personality traits


Impatience, Amnesia, Laziness, Character Flaw, and Personal Need for Recognition
Choosing Public Good over Science can also be viewed as a personality factor since it seems indicative of dogma that can compromise the integrity of the scientific process, thus resulting in research misconduct.


## Consequences of research misconduct


### The Researcher

According to a study of misconduct cases in the Office of Research Integrity (ORI), the investigator is always the accused and are scrutinized by their institution and federal agencies. If found guilty, the face many consequences including possible debarment [@davis_causal_2007].

