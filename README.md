# CDE4301 EIM-434 Team Lifeline: Interventional Oncology
<img width="1300" height="722" alt="Screenshot 2026-11-02 175753" src="https://github.com/user-attachments/assets/f95f16c7-4b78-421e-bbd2-6001944e751c" />

## Introduction
This project is undertaken as part of the Duke-NUS Health Innovator Program (DHIP), which brings together individuals from different academic disciplines to identify unmet clinical needs and develop innovative healthcare solutions. Our multidisciplinary team comprises five fellows with complementary backgrounds: Abhay Menon and Phua Kai Jie (Clinical Fellows), Sharleen Hu and Kirby Lee (Engineering Fellows), and Michelle Tan (Business Fellow). By integrating clinical, engineering, and business perspectives, the team aims to develop solutions that are clinically relevant, technically feasible, and commercially viable.

The project is guided by our clinical mentors, Dr Too and Dr Heng, from the Department of Vascular and Interventional Radiology at Singapore General Hospital (SGH), alongside our industry mentor, Matt Durack, Director of Strategic Innovation at BD.

The project was initiated with the following problem statement provided by our clinical mentors: **A safe and reliable way to deliver long-term systemic chemotherapy for oncology patients while reducing vascular access-related complications, treatment interruptions, and patient burden. This initial problem statement serves as the foundation for our team's exploration of existing vascular access methods used in chemotherapy delivery.** Through clinical observations, stakeholder interviews, and research into current practices, our team seeks to identify key challenges and opportunities for innovation that could improve the safety, reliability, and overall patient experience of long-term chemotherapy administration.

> **Initial Problem Statement**
>
> A safe and reliable way to deliver long-term systemic chemotherapy for oncology patients while reducing vascular access-related complications, treatment interruptions, and patient burden.

## Clinical Discovery

### Why Cancer?
Cancer remains a major public health concern in Singapore, with the number of newly diagnosed cases increasing over the years. According to the Singapore Cancer Registry Annual Report 2023, a total of 91,574 new cancer cases were reported in Singapore between 2019 and 2023, equivalent to an average of approximately 50 new cancer diagnoses per day (National Registry of Diseases Office, 2026).

This growing cancer burden highlights the importance of improving cancer treatment and care delivery. Chemotherapy remains an important treatment modality for many cancer patients, often requiring multiple treatment cycles administered over an extended period. For the purpose of this project, long-term chemotherapy is defined by our clinical mentors as chemotherapy treatment lasting three months or longer. During this period, patients may undergo repeated chemotherapy cycles, each requiring reliable vascular access for drug administration.

As such, safe and reliable long-term venous access is essential to facilitate repeated chemotherapy administration while minimising vascular access-related complications, treatment interruptions, and patient discomfort. Improving existing vascular access solutions could therefore contribute to a safer and more comfortable treatment experience, ultimately enhancing the quality of life of patients undergoing long-term chemotherapy.

### Types of vascular access
There are three main types of vascular access devices commonly used for chemotherapy administration: peripheral intravenous catheters (PIVCs), peripherally inserted central catheters (PICCs), and totally implantable venous access ports (Port-a-Caths). Each method offers distinct advantages and limitations in terms of ease of insertion, infection risk, patient comfort, and suitability for long-term chemotherapy administration.

#### Peripheral intravenous catheter
A PIVC is a short, flexible cannula inserted into a peripheral vein, typically in the hand or forearm, to provide temporary vascular access for the administration of medications and fluids. One of its main advantages is that it can be placed by a trained healthcare professional without requiring a surgical procedure. They also generally carry a lower risk of infection. 

However, PIVC insertion can be challenging in patients with difficult-to-access veins, sometimes requiring multiple attempts to locate and cannulate a suitable vein. Repeated needle punctures can cause pain and discomfort, while frequent cannulation and exposure to certain chemotherapy drugs may lead to phlebitis (inflammation of the vein) and potential venous damage. Over time, repeated vascular injury may compromise vein integrity, making subsequent venous access increasingly difficult.

#### Peripherally inserted central catheter
A PICC is a long, flexible catheter inserted through a peripheral vein, typically in the upper arm, and advanced until its tip reaches a central vein near the junction of the superior vena cava and right atrium. PICC insertion requires a specialised procedure, typically performed under ultrasound guidance and X-ray verification by an interventional radiologist. One of the main advantages of a PICC is its versatility, as it can be used to administer various medications, including chemotherapy, antibiotics, and intravenous nutrition. Some PICCs also contain multiple lumens, allowing different compatible treatments to be administered through separate channels. Furthermore, the external catheter is equipped with a standard Luer-lock connection, enabling trained nursing staff to connect compatible infusion equipment directly without repeated needle punctures.

However, as a PICC has an external segment that protrudes from the skin, this creates a potential route for microorganisms to enter, increasing the risk of catheter-related infections. Another potential complication is catheter occlusion caused by fibrin sheath formation. A fibrin sheath is a thin layer of protein-rich material that develops around the catheter following its insertion into the bloodstream. In some cases, this sheath may extend over the catheter tip and act as a one-way valve, allowing fluid to be infused into the bloodstream while preventing blood from being aspirated back through the catheter. This can interfere with catheter functionality and may require additional intervention to restore normal operation.

#### Totally implantable venous access ports
A Port-a-Cath is a small, fully implanted device that provides long-term central venous access for the administration of chemotherapy and other medications. The device consists of a subcutaneous reservoir connected to a catheter, with its tip positioned in a central vein. To administer medication, a trained healthcare professional uses a specialised Huber needle to puncture the skin and access the port reservoir. The medication then flows through the connected catheter and is delivered directly into the central circulation. One of the main advantages of a Port-a-Cath is its lower risk of catheter-related infection compared to a PICC, as the device is fully implanted beneath the skin without an external catheter segment. Furthermore, once the port is implanted, patients generally experience less discomfort during repeated access compared to PIVC, making it particularly suitable for long-term chemotherapy administration.

However, Port-a-Cath placement requires a more invasive insertion procedure, involving the creation of a subcutaneous pocket to accommodate the port reservoir and the placement of a catheter into the central venous system. Additionally, unlike a PICC, which can be accessed through a standard Luer-lock connection, a Port-a-Cath requires specially trained healthcare professionals to access the implanted reservoir using a Huber needle for chemotherapy administration.

### Clinical Findings
Through clinical observations and stakeholder interviews, our team sought to better understand the challenges associated with existing vascular access methods for chemotherapy administration. A total of 31 stakeholder interviews were conducted, comprising 8 interventional radiology (IR) clinicians and staff, 4 medical oncology clinicians and staff, 3 BD industry personnel, and 16 patients.

Overall, the findings indicated that the Port-a-Cath, the current gold standard, remains a well-established and effective solution for long-term chemotherapy administration, with generally positive feedback from both healthcare professionals and patients. Most stakeholders expressed satisfaction with its reliability, functionality, and suitability for repeated chemotherapy administration.

However, one significant finding emerged from our interviews with medical oncology clinicians: approximately 50% of patients who were eligible for a Port-a-Cath reportedly declined implantation, despite its clinical benefits. Common reasons cited included an aversion to undergoing an additional invasive procedure, reluctance to have a foreign object permanently implanted in the body, and concerns that the port might interfere with their daily activities.

For patients who decline port implantation, chemotherapy may instead be administered through PIVC. However, repeated peripheral administration of chemotherapy can cause venous irritation and inflammation, potentially resulting in phlebitis in approximately 30% of patients (Sudhakar et al., 2023). As peripheral veins become increasingly inflamed, scarred, or unsuitable for cannulation, establishing reliable venous access may become progressively more challenging. This can lead to repeated cannulation attempts, increased pain and discomfort, and potential delays in chemotherapy administration. Inevitably, some patients may eventually require a PICC or Port-a-Cath to continue treatment safely and reliably, despite their initial reluctance to undergo central venous access placement.

#### Refinement of the Clinical Need Statement
Based on these clinical findings, our team recognised that the primary challenge was not necessarily to improve the existing Port-a-Cath, but rather to address the unmet needs of patients who are unwilling to undergo port implantation. While Port-a-Caths remain an effective solution for long-term chemotherapy administration, a significant proportion of eligible patients may decline them due to concerns about procedural invasiveness, the presence of an implanted foreign body, and potential interference with daily activities.

This insight prompted our team to shift our focus from redesigning existing central venous access devices towards exploring ways to make peripheral intravenous access safer and more sustainable for patients undergoing repeated chemotherapy cycles. In particular, we identified chemotherapy-induced phlebitis and progressive peripheral venous damage as key challenges that could compromise vascular access over the course of treatment.

As such, our team revised the initial problem statement to address this unmet clinical need: **There is a need for a way to protect peripheral veins from chemotherapy-induced damage in port-eligible patients who decline a port, reducing chemotherapy-related phlebitis from 30% to below 15%, so that peripheral access stays usable for the full course of treatment.**

## Commercial Discovery

### Market Sizing
To evaluate the commercial potential of our proposed solution, our team conducted a preliminary market sizing analysis to estimate the number of patients who could benefit from improved peripheral venous access during chemotherapy.

<img width="646" height="394" alt="Screenshot 2026-11-13 095028" src="https://github.com/user-attachments/assets/5bdb0f91-96cc-4f7e-ba72-0b9b6626413b" />

According to the Singapore Cancer Registry, approximately 18,000 new cancer cases are diagnosed annually in Singapore (National Registry of Diseases Office, 2026). Based on estimates provided by our industry partner, BD, approximately 30% of these patients are clinically eligible for a Port-a-Cath, representing around 5,400 patients annually. However, our clinical findings suggest that approximately 50% of port-eligible patients decline port implantation, leaving an estimated 2,700 patients per year, or 15% of newly diagnosed cancer patients, who could potentially benefit from improved peripheral venous access solutions.


## References
National Registry of Diseases Office. (2026). Singapore Cancer Registry Annual Report 2023. Health Promotion Board. https://www.nrdo.gov.sg/publications/singapore-cancer-registry-annual-report-2023/

Sudhakar et al. (2023). J Oncol Pharm Pract. doi.org/10.1177/10781552231161517

