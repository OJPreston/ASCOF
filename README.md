# ASCOF
## Adult Social Care Outcomes Framework Data

The Department of Health and Social Care (UK) have released their 2018-19 data returns for Adult Social Care this week:

https://digital.nhs.uk/data-and-information/publications/statistical/adult-social-care-outcomes-framework-ascof/upcoming/measures-from-the-adult-social-care-outcomes-framework-england-2018-19

These annual returns include area level data on a range of indicators in social care for adults across England. Up to date definitions of how these data are collected is here (PDF file):

https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/687208/Final_ASCOF_handbook_of_definitions_2018-19_2.pdf 

Alongside this, the NHS digital service also produce some basic summary documents each year. But these could be further expanded on (PDF again):

https://files.digital.nhs.uk/A8/645273/meas-from-asc-of-eng-1819-ASCOF_2018-19_Report.pdf

The data is described as follows:

The fields are interpreted as follows:

**Geographical Code** – this is the geographical level code represented by the row.  This will be either:
  Council with Adult Social Services Responsibilities (CASSR) code,
  Region code
  Council type code
  England
  
**Geographical Description** – this is the geographical level description represented by the row and is defined as for Geographical Code.

**Geographical Level** – this is provided to aid analysis. As data are made available to various levels (i.e. England, council type, regional and council totals) within the same datasets, this field is designed to enable users to access a single subset of the data which represents the overall total and the required level of detail. The levels are either:
  - Council
  - Region
  - Council Type
  - England
  
**ONS Area Code** – this is the geographical level represented by the row as defined by ONS Administrative Categories.  These codes are designed to facilitate the integration of datasets from disparate sources.  Further details of the ONS Administrative Geographies are available at https://geoportal.statistics.gov.uk.  Details of all regional and national codes used in the data file are outlined in Annex A.

**ASCOF Measure Code** – this is a concatenation of the high-level measure code and any age group or gender disaggregations that are present.
  - Age ranges are represented numerically, with for example ‘1864’ representing ’18 to 64’.
  Furthermore, ‘OV’ and ‘U’ are used for example in ‘65OV’ to represent ‘65 and over’ or ‘64U’ as ’64 and under’.
  Gender is represented as ‘M’ for ‘Male’ and ‘F’ for ‘Female’.

**Disaggregation Level** – as with the measure code above, this field contains a description of the disaggregation level represented by the data.

**Measure Type** – this field represents the type of measure provided by each row
  - Base is the number of survey respondents (which are only relevant and included for survey-based measures)
  - Denominator is the total available population who could have indicated agreement with a given measure
  - Numerator is the total population who indicated agreement with a given measure
  - Outcome is calculated as the numerator divided by the denominator

**Measure Value** – this is the value represented by the unique combination of ASCOF Measure Code, Geographical Level, Disaggregation Level and Measure Type for a given measure

**Measure Group** – this is the high-level code of the measure represented by each row

**Measure Group Description** – this is a description of the high-level measure
- Using the line of data highlighted, this shows that the outcome measure for females in England for measure 1F (Proportion of adults in contact with secondary mental health services in paid employment) is 8.0.


## Other things to be aware of when using these data
A list of the data sources and the corresponding ASCOF measures is provided below:
  - Adult Social Care Survey – Measures 1A, 1B, 1I(1), 3A, 3D(1), 4A and 4B
  - Short and Long Term Activity – Measures 1C, 1E, 1G, 2A and 2D
  - Short and Long Term Activity and Hospital Episode Statistics – Measure 2B
  - Survey of Adult Carers – Measures 1D, 1I(2), 3B, 3C and 3D(2)
  - Mental Health and Learning Disabilities Dataset – Measures 1F and 1H
  - Delayed Transfers of Care and ONS mid-year population estimates – Measure 2C

On the survey based measures outlined above, the base (i.e. the number of responses on which the outcome is based) should be taken into account when assessing the reliability of the outcome values. Outcomes based on a small base should be treated with caution.

Numerator and denominator values used to calculate the indictors are provided unrounded and not suppressed. Exceptions to this are:
  Measure 2C(1) and 2C(2) where the numerators are rounded to the nearest one.
  The measure values for Adult Social Care survey based measures (1A, 1B, 1I(1), 3A, 3D(1), 4A and 4B) are suppressed if the base is less than three.
  The Hospital Episode Statistics data used in the denominator for Measure 2B are suppressed if values are between one and five.

Additionally, some of the cells within the data file are blank. These will be as a result of ether:
  the measure type not being relevant for a given measure. For example, the short and long term activity based measures do not have a base as the numerator and denominator represent the whole reported population.
  small numbers having been suppressed,
  data not having been submitted by a council.

