# ORIE 4741 Project Proposal: Financial Aid Assistance
Members: Cean Park (ckp42), Tiffany Shih (ts568)

September 22, 2017

## Background
The problem of rising tuition costs at post-secondary educational institutions has been a problem facing the U.S. for over a century. Questions surrounding the importance of post-secondary education, the role of higher institutions in subsidizing these costs, and the issuance of loans and debt have been debated for years, and are issues that most college students face today. As such, many forms of financial assistance are readily available: scholarships, grants, and awards exist to recognize the academic and personal achievements of college students and help offset tuition costs.

The New York State Tuition Assistance Program (TAP) is a program provides eligible New York residents pay tuition at a set of approved colleges and universities in New York State. Selected applicants are awarded annual grants of up to $5,165 based on a set of factors including: family income, attending school, academic performance, and dependency status.

The increasing complexity of applying for programs such as the New York State TAP has created the need for an improved process. We believe that we can employ data analysis and machine learning techniques in order to improve the process.

## Dataset and Analysis
The dataset we wish to analyze comes from the NYS government website (https://data.ny.gov/Education/Tuition-Assistance-Program-TAP-Recipients-Dollars-/2t78-bs45). This dataset, named "Tuition Assistance Program (TAP) Recipients & Dollars by Income, Age Group and Program Information," includes data on over 190,000 application types submitted to the TAP starting from the year 2000. Each of 190,000 rows contains 16 features, such as academic year, age group, income, and total recipient dollars.

This dataset will require some cleaning, as examples are indexed by application type and number of applications with the same information. We will likely have to create another feature column to track average recipient cost for a certain application type.

## Goals and Significance
The goals for our data anlysis are:
* Achieve an understanding of the different attributes that contribute to the grant award amount, and correlations that may exist between variables
* Build a model that can accurately predict, given a set of application data, the TAP grant award amount
* Observe trends or patterns in the application data that may inform of us any underlying changes in applications from the year 2000

With the above objectives, we believe that our data analysis can improve financial assistance programs in NYS and equip students with a tool they can utilize when applying for grant aid. Additionally, this analysis may uncover patterns in application data that suggest structural inefficiencies or inconsistencies in the grant award process that the TAP can use to make the process fairer.
