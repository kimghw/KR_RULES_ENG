# Guidance for Computer-based System Conformity Assessment

> OTHER RULES AND GUIDANCE / GC-30-E / 2025 / EN / Guidance

## CHAPTER 1 GENERAL

### Section 1 General

#### 101. Application

- **1.** This Guidance is applied to control, observation and safety software installed on ships and/or offshore plants, operating support software for ships and/or offshore plants, product design and technical/engineering software for marine equipment.
- **2.** Items not included in this Guidance may comply with ISO, IEC or equivalent recognized standards by the appropriate consideration of the Society.
- **3.** In application to 203. test result may be accepted in cases where test has been carried out or approved as follow.
  - **(1)** At a laboratory accredited for all the required tests by an accreditation body being member of KOLAS in accordance with KS Q ISO/IEC 17025
  - **(2)** At a laboratory accredited for all the required tests by an accreditation body being member of ILAC in accordance with ISO/IEC 17025
  - **(3)** The assessment of Certificates issued by other Classification Society recognized by the Society

#### 102. Definitions

The Definitions of terms are to follow the **Rules for Classification of Steel Ships**, unless otherwise specified in this Guidance.

- **1.** **“Anomaly”** means a any condition that deviates from expectations based on requirement definition, product specifications, this Guidance, etc. or from someone‘s perceptions or experiences.
- **2.** **“Application Software”** means a software that users use directly on computers where the operating system is installed.
- **3.** **“Code Coverage”** means the percentage of codes tested in the entire software source code as a criterion for determining the level of dynamic testing, it is classified with 'Statement', 'Branch', 'MC/DC' according to testing level.
- **4.** **“Coding Rule”** means a set of Guidance for a specific.
- **5.** **“Conformity Assessment”** means a systematic examination of the extent to which a product, process or service fulfills specified requirements.
- **6.** **“Dynamic Testing”** means a testing that requires the execution of the test item.
- **7.** **“Embedded Software”** means a software developed to perform a predetermined specific function on a microprocessor installed in electronic products, information devices. etc.
- **8.** **“False Alarm”** means a case that static analysis tool reports a fault when one does not exist.
- **9.** **“Fault“** means incorrect step, process, or data definition in a computer program.
- **10.** **“Function”** means a implementation of an algorithm in the software with which the end user or the software can perform part or all of a work task.
- **11.** **“Product description”** means a document stating properties of software, with the main purpose of helping potential acquirers in the evaluation of the suitability for themselves of the software before purchasing it.
- **12.** **"Source Code Metric"** means index that measures the quality of the source code.
- **13.** **“Statement Coverage”** means a percentage of the set of all executable statements of a test item that are covered by a test set.
- **14.** **“Computer-based System(Software)”** means a system of one or more computers(including programmable electronic device), associated software, peripherals and interfaces, and the computer network with its protocol.
- **15.** **“Static Testing”** means a testing in which a test item is examined against a set of quality or other criteria without code being executed.
- **16.** **“Test Case”** means a set of inputs, execution conditions, and expected results developed for a particular objective, such as exercise a particular program path or to verify compliance with a specific requirement.
- **17.** **“Test Plan”** means detailed description of test objectives to be achieved and the means and schedule for achieving them, organised to coordinate testing activities for some test item or set of test items
- **18.** **“Weakness"** means as flaws, bugs, faults, or other errors, that create vulnerabilities that can be exploited by both internal and external forces.

#### 103. Exclusion from the Guidance

The Society can not assume responsibility for use of unauthorized commercial products and other technical characteristics not specified in this Guidance.


### Section 2 Assessment Process

#### 201. Application

- **1.** The applicant is, in principle, to be the manufacturer of the materials and equipment. however, the applicant, where deemed appropriate by the Society, need not always be the manufacturer of the materials and equipment.
- **2.** The manufacturer wishing to obtain a conformity assessment is to submit a copy of the application of type approval of the Society, together with three copies of the required data for approval and two copies of the required data for reference, data previously submitted to the Society, according to the Technical Rules, may be exempted from submission.
- **3.** Additional material not include this Guidance may be additionally required by the Society when deemed necessary by the Society.
- **4.** ‘Test Plan’, ‘Test Result‘, ‘Anomaly Report‘ may be written separately in accordance with static and dynamic test, Each document can be submitted as an integrated or separate document.
- **5.** Application document
  - **(1)** Test plan
    - **(A)** Product purpose
    - **(B)** Product boundaries and configuration
    - **(C)** Product summaries
      - **(a)** System name
      - **(b)** Unique identifier(reference, version number, date of issue)
      - **(c)** The history of changes or any other element that describes the process of revision of the document.
      - **(d)** the identifier of the document referenced in the body of the document.
      - **(e)** Information of writer
    - **(D)** Test purpose and boundaries, method
    - **(E)** Test environment
    - **(F)** Hardware specification
    - **(G)** Test tool;
    - **(H)** Test item(static, dynamic, non-function) and acceptance criteria
  - **(2)** Static testing report
    - **(A)** The identification of the static testing report
    - **(B)** The date of the test execution
    - **(C)** The name and the function of the person having carried out the test
    - **(D)** The development constraints(compiler, OS, etc.), language
    - **(E)** The list of acceptance criteria
    - **(F)** The test tool
    - **(G)** The execution result
    - **(H)** The list of the found anomalies by coding rule
    - **(I)** The anomaly description by coding rule
  - **(3)** Dynamic testing report
    - **(A)** The identifier of the dynamic testing report
    - **(B)** The date of the test execution
    - **(C)** The name and the function of the person having carried out the test
    - **(D)** The summary of conformity assessment results and, if any, test results
    - **(E)** The test tool
    - **(F)** The list of the found anomalies
    - **(G)** for each anomaly, the reference to the corresponding anomaly report
  - **(4)** Anomaly reports
    - **(A)** The identifier of the anomaly
    - **(B)** The point in the test case the anomaly occurred
    - **(C)** The severity(serious, interrupted, simple) and reproducibility of the anomaly
    - **(D)** The anomaly description
  - **(5)** Function list
    - **(A)** A table of hierarchical classification of the functions that make up the software.
  - **(6)** Mapping table between the product description or requirement definition and test case
    - **(A)** All functions mentioned in the function list shall be classified according to the test case(1:1, 1:N, N:N)
- **6.** Data for reference
  - **(1)** Outline of company
    - **(A)** Data on history, outline and layout of manufacturing plants
    - **(B)** The organization and management structure, including subsidiaries to be included in the approval/certification
  - **(2)** When plant audit is required in accordance with the requirements in 204., the following reference data may be submitted
    - **(A)** Data on major manufacturing facilities
    - **(B)** Data on manufacturing process
    - **(C)** Data of in-house standards or codes
    - **(D)** Data of quality control system
    - **(E)** Data on major inspection and test facilities
    - **(F)** Service records
  - **(3)** Document related to the recognition of test organization
  - **(4)** Document related to the recognition of test tools
- **7.** Notwithstanding the requirements in the preceding Sec 2, where the applicant is already approved by the Society and the attachments are entirely equal in content to the documents previously submitted the submission of documents may be partly or wholly exempted except for the approval test program.

#### 202. Document review

- **1.** The Society examines the software conformity assessment test plan, drawings and data and where deemed appropriate, those are to be approved and returned to the manufacturers.
- **2.** The document review is to evaluate the appropriateness of a document based on software conformity assessment requirement.

#### 203. Conformity assessment test

- **1.** After completion of the document reviews specified in 202., the type tests are to be carried out for the test products in the presence of the surveyor in accordance with the conformity assessment test program and test method as deemed appropriate by the Society.
- **2.** Software which have been failed to pass the conformity assessment tests specified in 1. should not be retested without revision of drawings and/or specifications. If, following analysis of the experimental data from tests, it is found that the failure of type tests have been caused by the poor test conditions, etc., retest without revision may be permitted subject to the Society‘s approval.
- **3.** Upon completion of the type test, the manufacturer is to submit to the Society the complete test report including test conditions, test results and required information.

#### 204. Plant audit

This is to comply with the requirements in **Ch 3, 105.** of **Guidance for Approval of Manufacturing Process and Type Approval**, **etc**. where type approval of equipment is carried out simultaneously or already done, plant audit may be omitted.

#### 205. Notification and announcement of approval

This is to comply with the requirements in **Ch 3, 106**. of **Guidance for Approval of manufacturing process and Type Approval, Etc.**

#### 206. Changes in the approved contents

This is to comply with the requirements in **Ch 3, 107.** of **Guidance for Approval of Manufacturing process and Type Approval, Etc.**

#### 207. Validity and renewal of approval certificate

- **1.** The approval certificate will be valid within three years from the date of issue. In case where the approval certificate is renewed in accordance with the requirements specified in the preceding 206., the expiration date will not be changed.
- **2.** This is to comply with the requirements in **Ch 3, 108.** of **Guidance for Approval of Manufacturing Process and Type Approval, Etc.** However, the renewed approval certificate will be valid within three years from the expiry date of old approval certificate.

#### 208. Confirmation test and/or occasional plant audit

This is to comply with the requirements in **Ch 3, 109.** of **Guidance for Approval of Manufacturing Process and Type Approval, Etc.**

#### 209. Suspension or withdrawal of approval

This is to comply with the requirements in **Ch 3, 110.** of **Guidance for Approval of Manufacturing Process and Type Approval, Etc.** ![](images/image3.png)
