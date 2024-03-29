# Accenture Social Buzz Project for Data Analytics and Visualisation
## Project Description

Mae Mulligan, my Managing Director at Accenture and the client lead for Social Buzz, has reviewed their brief and formed a diverse expert team for the project. She has scheduled a project kick-off call with this team for tomorrow morning and shared the brief for review:

### Team
![image](https://github.com/kalilalincen/Accenture-Data-Analytics-and-Visualisation/assets/155357106/1dd43cad-9a64-4a4b-a1f9-f8fd54c0ad2d)

Client name: Social Buzz

Client industry: Social media & content creation

Year established: 2010

Location of HQ: San Francisco

Number of employees: 250

Client background:

Social Buzz was founded by two former engineers from a large social media conglomerate, one
from London and the other from San Francisco. They left in 2008 and both met in San
Francisco to start their business. They started Social Buzz because they saw an opportunity to
build on the foundation that their previous company started by creating a new platform where
content took center stage. Social Buzz emphasizes content by keeping all users anonymous,
only tracking user reactions on every piece of content. There are over 100 ways that users can
react to content, spanning beyond the traditional reactions of likes, dislikes, and comments.
This ensures that trending content, as opposed to individual users, is at the forefront of user
feeds.

Over the past 5 years, Social Buzz has reached over 500 million active users each month.
They have scaled quicker than anticipated and need the help of an advisory firm to oversee
their scaling process effectively.

Due to their rapid growth and digital nature of their core product, the amount of data that they
create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging
from text, images, videos and GIFs are posted. All of this data is highly unstructured and
requires extremely sophisticated and expensive technology to manage and maintain. Out of the
250 people working at Social Buzz, 200 of them are technical staff working on maintaining this
highly complex technology.

Up until this point, they have not relied on any third party firms to help them get to where
they are. However there are 3 main reasons why they are now looking at bringing in external
expertise:

1) They are looking to complete an IPO by the end of next year and need guidance to
ensure that this goes smoothly.

3) They are still a small company and do not have the resources to manage the scale that
they are currently at. They could hire more people, but they want an experienced
practice to help instead.

5) They want to learn data best practices from a large corporation. Due to the nature of
their business, they have a massive amount of data so they are keen on
understanding how the world's biggest companies manage the challenges of big
data.

To start our engagement with Social Buzz, we are running a 3 month initial project in order
to prove to them that we are the best firm to work with. They are expecting the following:

- An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the
largest aggregate popularity

Tasks to be delegated:
- Creation of an up-to-date big data best practices presentation
- Extraction of sample data sets using SQL
- On-site audit of their data-center
- Merging of sample data set tables
- Virtual session with Social Buzz team to present previous client success stories relevant
to them
- Preparation of best practice document for IPO
- Loading of sample data sets into Accenture sandbox database
- Technology architecture workshop with Social Buzz Data Team to understand their
technology landscape
- Stress testing of their technology to identify weak spots
- Communication with previous IPO companies within our client base for reference stories -
Analysis of sample data sets with visualizations
- Full documentation of the process that we can guide them through for IPO

## Brief Analysis
### Client & Business Problems
- 500 million active users each month, leading to a need for advisory support to improve the scaling process.
- Data management challenges with a vast amount of unstructured data daily, including text, images, videos, and GIFs, and 200 out of 250 technical staff members who struggle to manage and maintain complex technology.
- Insufficient resources to manage the current scale, needing experienced practice to assist before expanding through the hiring process.
- Lack of guidance to ensure a smooth transition to an IPO at the end of the year.
- A need to learn data best practices to manage the challenges of big data.

### Client Expectation
- A audit of big data practice
- Recommendation for IPO
- An analysis for popular content

## Data
### Datasets
A total of 7 datasets, each data set contains different columns and values.
![image](https://github.com/kalilalincen/Accenture-Data-Analytics-and-Visualisation/assets/155357106/56e78638-620e-4a19-8519-02bc07c79fcb)

### Data model
This shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
![image](https://github.com/kalilalincen/Accenture-Data-Analytics-and-Visualisation/assets/155357106/92d3cbec-8dff-4fa1-8dff-39bcab30d12b)
Definitions of different data types:

String - Sequence of characters, digits, or symbols—always treated as text

UUID - Universally Unique Identifiers

Array - List with a number of elements in a specific order—typically of the same type

Integer - Numeric data type for numbers without fractions

Timestamp - Number of seconds that have elapsed since midnight (00:00:00 UTC), 1st January 1970 (Unix time)

### Selected Datasets for this work

Based on the client's requirements, an analysis of their content categories is needed, highlighting the top 5 categories with the highest popularity. According to the document, popularity is quantified by the 'Score' assigned to each reaction type. Therefore, you should begin by the Content dataset to the Reaction dataset, which in turn links to the Reaction Types dataset containing the 'Score'.

content ID, category, content type, reaction type, and reaction score.
