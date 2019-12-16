# 2nd Annual National Health Equity Hackathon

**TL;DR** - 211 is a very valuable social services hotline available to all major cities. We helped develop an operational dashboard for their call log data for better assessment of their 211 operations.

[**Link to Presentation**](https://drive.google.com/file/d/1Yh4KMVHRuqhXnfBzyChCstQ5fz7OovwI/view?usp=sharing)

## Context
Using 211 data, provided by United Way, this weekend hackathon will gather multiple tech disciplines around a common goal of eliminating health disparities. Attendees will self-select to a team with diverse perspectives. Local and nationally-acclaimed mentors and database experts will be accessible throughout the event.

Examples of people that do not have equal access or quality of care include:

- low-income families and communities
- communities affected by racism, sexism, homophobia & transphobia
- people living with chronic illness
- people experiencing homelessness
- people affected by addiction, including opioid addiction disorder
- senior adults
- infants and children

Addtional information on this event can be found at [**Hacking Healthcare**](https://www.hacking.healthcare/).


## Our Problem Statement / Focus
During the event, we were given various problem statements [(*Link to problem statements.*)](https://www.hacking.healthcare/wp-content/uploads/2019/11/EH-HE-Hackathon-2019-Problem-Statements-Statements.pdf) and we had to decide to one to focus our efforts on for the weekend. We found the case on mental health to be interesting and try to pursue that topic. 

After driving into the data we found that for the 211 calls regarding mental health had a high success rate. 211 defined success if the caller was able to referred to a social service within their area. Thus, we thought of approaching all 211 calls holistically and try to find the most unserviced call topics and then we hope to replicate the success 211 had with mental health calls to these unmet calls.

## Development of the Operational 211 Dashboard
[**Link to Presentation**](https://drive.google.com/file/d/1Yh4KMVHRuqhXnfBzyChCstQ5fz7OovwI/view?usp=sharing)
We envision the dashboard have the following attributes:
1) **Simplicity** - an interface that is very user friendly and address the key metrics directly
2) **Locality** - to be strategic with our social services we wanted to focus on making sure that when we address / refer social services that they are allocated from the approriate locations.
3) **Adaptable** - as with any operations, we wanted this dashboard to evolve and grow with upcoming changes and issues. 

The dashboard was primarily constructed in Tableau but some manipulation of the 211 dataset was accomplished in Python utilzing Pandas.

To incorporate this elements into our dashboard, we did the following:
1) **Simplicity**  
    a) Simple gauges to measure their success rate: Total Calls, Met Volume, and Not Met Volume
    b) Then a simple line plot against time to track their success rate throughout the year
2) **Locality**  
    a) Created a zipcode mapping of the city of Houston and the coloring of the area determines the success rate of the area ; ability to quickly identify areas not met.
3) **Adaptable** - since this event lasted only one day we did not get to fully address this aspect.  

## Summary of Findings
1) Overall most services were met 95% of the time.  
2) Mental Health and Substance Abuse Services had the highest sucess.  
3) Disaster Services, and Individual / Family Life Services need to be improved  
    a) disasters are erratic and usually have a severe spike in demand that usually cannot be quickly address  
    b) individual / family life issues happen heavily during the holiday season (December)  
4) 211 is a very valuable resource that is being underutilized by the community as a whole (I personally did not even heard of it until this event) and we hope an integrated dashboard could improve the 211 call metrics.   
5) Houston is full of wonderful people that are working on many projects to improve all social determinants of health.  

Thank you!

## Authors 
- **Eddie Yuen**:   
a) [LinkedIn Profile](https://www.linkedin.com/in/edward-yuen-995145a8/)  
- **Patrick Ly**:   
a) [LinkedIn Profile](https://www.linkedin.com/in/patrick-m-ly/)  
