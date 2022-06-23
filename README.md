# Kizito.github.io https://github.com/KizzyAdrain/Kizito.github.io
### **Support for Clinical Decision**
Clinical decision support systems have undergone a quick change in the current healthcare sector. They are now frequently monitored or administered through computerized clinical processes and electronic medical records, which has been made possible by the expanding global usage of sophisticated electronic medical records.
 **![Design-Level-BRB-CDSS-Architecture](https://user-images.githubusercontent.com/102212173/175336235-f4fab4d2-c698-4080-85b8-ada98b1b9665.png)
**

Software called a clinical decision support system (CDSS) analyzes patient data to help doctors make judgments. Along with doctors and nurses, CDS (Clinical Decision Support) is for staff members, patients, and other caregivers. Therapeutic decision support systems (cdss) are computer-based programs that analyze data from electronic health records (EHRs) and provide cues and reminders to help healthcare professionals follow clinical recommendations that are supported by evidence at the point of care. Any system, practice, or method involving health information technology (HIT) that attempts to:

	With the appropriate information, to the appropriate individuals (the patient and the entire care team) (evidence-based recommendations, reaction to clinical need).

	At the proper points in the workflow (for decision making or action).

	Following the correct procedures (e.g., EHR, mobile device, patient portal) 

	When applied to the proper intervention formats (e.g., order sets, flow-sheets, dashboards, patient lists).

These success factors are being quickly incorporated into the care operations of healthcare organizations.
Misdiagnoses make about 10 to 30 percent of clinical errors, according to the Agency for Healthcare Research and Quality. Numerous things, from supplier bias to unique and rare disorders, can result in a misdiagnosis. Sometimes it's as straightforward as the provider committing a logical or moral blunder.
Since the ailment cannot be effectively treated until it is correctly diagnosed, misdiagnosis is a significant issue. Clinical decision support systems can significantly reduce these kinds of errors, improving patient outcomes.

***•	A reduction in prescription:***
      Prescription ends up being extensively more problematic while overseeing complex populaces, for instance, kids. Dosing can be jumbled to register. The grouping of equations expected to make accurate calculations make having this information available at top of the psyche particularly problematic. Clinical Decision Support gives specialists speedy admittance to dosing adding machines, drug monographs, loads, infections, and so forth This makes it fundamentally almost certain that the appropriate medication at the right piece will be given the initial time.
      
***•	Impact in the emergency room:***
       Despite the fact that diagnostic mistakes can happen in any clinical setting, CDS may have the greatest impact in the emergency room (ED). As a result of the ED's hectic environment and the frequent presentation of patients with diseases that seem to be the same, doctors have a tendency to skip over more straightforward treatment options. A CDS can ensure that significant conditions are not disregarded.
As doctors prepare the patient for a lung scan, for instance, the CDS system can determine the patient's risk of pulmonary embolism (PE) based on presentation details and recent lab results, as well as taking into account information regarding other potential diagnoses. For instance, an ED patient may complain of chest pain, shortness of breath, and other symptoms suggesting an apparent pulmonary embolism (PE). The CDS may advise ordering a non-invasive blood test to rule out PE while further examining the likelihood of a heart attack if the results show a very low PE risk but a high risk of myocardial infarction (MI).

***•	Improved Used Of Imaging:***
       In the PE example, CDS can stop an unneeded lung scan in addition to refocusing the diagnosis and guiding doctors to arrange the right tests. Consider a patient who complains of dizziness, a sign that could point to a stroke or a variety of other medical conditions. As a common procedure, procedures may instruct doctors to order a CT scan to rule out stroke because an MRI is significantly more expensive than a CT scan. However, if the patient is genuinely experiencing a stroke, the CT scan may miss it, therefore it would be better to move right along to an MRI. According to several studies, an MRI may be preferable to a CT scan for diagnosing strokes.
But there's a catch for doctors. Every patient shouldn't have an MRI performed instead of a CT scan to rule out stroke because doing so would increase the number of MRIs that turned out to be medically pointless. However, there is also demand on professionals to provide prompt, precise diagnosis.

In order to avoid what would result in an unnecessary CT scan, CDS can help doctors with resource realignment in both areas by recommending MRIs for the lower proportion of patients whose overall clinical picture indicates a higher risk of stroke. The MRIs recommended by CDS can significantly save expenditures that could arise from a delayed response to a stroke by improving the likelihood of correctly diagnosing stroke more immediately.

***•	Avoiding Catastrophic Misdiagnoses:***
       Diagnoses of life-threatening developments that are difficult to see can be helped by CDS systems. This is especially true when sepsis develops after a patient has been admitted to the hospital. The CDS system can continuously monitor the patient as long as professionals continue to treat patients in accordance with an initial, accurate diagnosis, such as acute appendicitis.

CDS can notify doctors of the possibility of sepsis development and the requirement for prompt treatment if the patient displays minute indicators of deterioration, such as white blood cell counts that gradually rise in lab tests, a minor tendency toward hypotension, and fever. When time is of the essence, CDS can also help with early oncology diagnoses.

***•	Bringing Useful Intelligence To The EMR Function:***
    The current organizational structure of electronic medical records, particularly in the ED, tends to concentrate doctors on a certain pathway starting with basic symptom profiles. A more thorough clinical view of the patient is used by CDS to strike a balance. It can also correct prejudices that might encourage a particular way of thinking.
Clinicians frequently rely on "heuristics" to make provisional diagnoses, particularly when assessing common sets of symptoms, but cognitive psychology has demonstrated that this practice carries a risk of bias traps like an excessive reliance on prior knowledge, gut feelings, or collateral information While both patients approach with identical symptoms and either could be having a heart attack, emergency room doctors might be less likely to diagnosis MI in a thin, 40-year-old girl than in an overweight, 65-year-old diabetic man. When a heroin user complains of stomach pain, it may be assumed that they are going through opiate withdrawal when, in fact, they have a bowel perforation.
The CDS can issue an appropriate alert to consider important factors that might otherwise be overlooked by taking into account the complete clinical picture of the patient, including information that isn't always readily available within the ED and without anchoring bias regarding observed conditions. The physician, who makes the determination using a combination of art and science as well as other evidence to support a medically sound diagnosis, retains the authority over the diagnosis.

***Purpose of CDSS***
          By enabling the analysis of patient data and the use of that data to assist in the development of a diagnosis, CDS's main objective is to improve healthcare. In order to help doctors and other primary care professionals offer their patients with better care, a CDSS gives information to them. Reminders, warnings, and care suggestions are sent out by a CDDS tool. CDDS can boost productivity while also enabling cost-effective healthcare.
Modern approaches, however, enable physicians to connect with CDSS and use both their expertise and CDSS to evaluate patient data more effectively than either humans or CDSS could do on their own. Typically, the clinician will extract pertinent information from the data offered and disapprove of incorrect CDSS proposals after reviewing the suggestions made by the CDSS. Knowledge basis and non-knowledge base CDSS are the two primary categories. 

***Knowledge-based CDSS*** 
The knowledge base, an inference engine, and a communication mechanism make up the majority of CDSSs. The knowledge base comprises the rules and associations of compiled data, which are most frequently expressed as IFTHEN rules, according to Peyman et al. If this were a system for identifying drug interactions, a rule may read, "Alert user IF drug X AND drug Y are taken." An experienced user could update the knowledge base with new medications by using a different interface. The knowledge base's rules are combined with the patient's data by the inference engine. The system can receive input from the user and display results thanks to the communication mechanism. 
For representing knowledge artifacts in a computable manner, an expression language is required, such as GELLO or CQL (Clinical Quality Language). For instance, retesting is advised if more than six months have gone since the patient's last hemoglobin A1c test result was less than 7 percent, but re-examination is advised if it was 7 percent or more. -Check if it has been longer than three months. Building on the Clinical Quality Language is the HL7 CDS WG's current priority (CQL). The eCQM specification will now employ CQL, according to CMS https://ecqi.healthit.gov/cql).

***Non-knowledge base CDSS***
Machine learning is a type of artificial intelligence that is used by CDSS, which does not use a knowledge base. This enables computers to draw lessons from the past and identify patterns in health data. This eliminates the requirement for regulations and expert judgment. The majority of clinicians do not employ machine learning-based systems directly for diagnosis because to reliability and accountability concerns because they cannot explain why a decision was reached. Even so, it might be used as a post-diagnosis system to flag patterns for doctors to look into further.

***Additional areas where CDS can help:***
•	Analyze filtered information or educational materials 
•	Pick up drug equation guidelines 
•	Analyze reportable preconditions based on EHR inputs, use time-triggered reminders for medication delivery and dosage adjustments 
•	Determine drug dosing calculations 
•	create alert templates or order sets for particular diseases 
•	Use severity indexes to treat specific 
•	Analyzing filtered information or education material

***Conclusion***

In order to support sophisticated analytics, CDS systems are increasingly incorporating artificial intelligence and machine learning. Large amounts of data may be ingested by machine learning algorithms, which can then spot trends and give consumers in-depth results. A clinical decision support system's main goal is to assist medical professionals in making decisions, much like an enterprise support system does for business experts. Alternative perspectives on clinical decision support technologies include improved patient outcomes and patient satisfaction. 

***References:***
Martin Pusic, M Ansermino
British Columbia Medical Journal 46 (5), 236-239, 2004
Webmedy.com
(https://www.google.com/amp/s/webmedy.com/blog/what-do-you-understand-by-clinical-decision-support-system).
Berner, Eta S., ed. Clinical Decision Support Systems. New York, NY: Springer, 2007.
"Decision support systems ." 26 July 2005. 17 Feb. 2009 .
Peyman., Dehghani Soufi, Mahsa. Samad-Soltani, Taha. Shams Vahdati, Samad. Rezaei-Hachesu. Decision support system for triage management: A hybrid approach using rule-based reasoning and fuzzy logic. OCLC 1051933713
“HL7 CDS Standards". HL7 CDS Working Group. Retrieved 25 June 2019

Nancy Zimmerman RN, BSN, Chief Nursing Officer for medCPU:  Reducing Diagnostic Errors Through Clinical Decision Support. 
(https://www.healthitoutcomes.com/doc/reducing-diagnostic-errors-through-clinical-decision-support-0001)

Spie (March 2015). "Tanveer Syeda-Mahmood plenary talk: The Role of Machine Learning in Clinical Decision Support". SPIE Newsroom. doi:10.1117/2.3201503.29.
https://en.m.wikipedia.org/wiki/Clinical_decision_support_system








**Blog writter by Kizito**

**Matric no: 22108629**

**2022**
