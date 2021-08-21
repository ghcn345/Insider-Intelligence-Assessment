<p>
<img src="images/Insider-Intelligence.png" width="900" height="504">
</p>

# Insider Intelligence Standard Assessment for Data Intern

**Applicant**: Ning Chen


This assessment is designed to focus on the core competencies of a successful data analyst at Insider Intelligence; conversion analysis, producing and sharing insights to leadership, and offering recommendations. The assessment has two components, with the first focusing on the ability to convey technical insight to company leadership and the second part doing a standard funnel conversion analysis.

- Part 1:
Explain to company leadership what model lift is and why they should care. We expect the technical issues like ROC and AUC to be addressed but conveyed to leadership in simple and actionable terms.

- Part 2:
Please review the scenario outlined below and use all the data files included in the zip drive. Analyzing the funnel and performing optimizations along the path is what a typical Data Analyst/Data Scientist would do on a commercial site. You are to provide insights to the product/marketing teams on user behavior to help them design a better customer experience and maximize conversion rate.

Scenario:

You are presented with user activity data from a commerce website. The site has 4 pages:

- Home Page - Where users land first (all users start here).
- Search Page - From the Home Page, they can do a search for products and arrive on the Search Page.
- Payment Page - Once on the Search Page, the user might click on a product that would take her to the Payment Page. Here she will be asked to provide credit card information to buy that product.
- Confirmation Page - If she does decide to buy, the last step of the journey is on the Confirmation Page.

The Chief Executive Officer isn’t satisfied with the company's sales results, especially sales coming from new users, and asks you to investigate. You are supposed to create a narrative on how to improve the conversion rate, and, more importantly, to identify if something is wrong at some point in the conversion funnel.

Tasks:
- 1. Create a full picture of funnel conversion rate (for both desktop and mobile)

![graph](/images/funnel1.png)
![graph](/images/funnel2.png)

- 2. Generate specific insights on what the product team can do in order to improve conversion rate.

![graph](/images/rate.jpg)
![graph](/images/desktop.jpg)
![graph](/images/mobile.jpg)

- 3. Anything else you have discovered that might improve conversion rate.

![graph](/images/sex.jpg)


## For More Information

Please review question analysis in [Jupyter Notebook](https://github.com/ghcn345/Insider-Intelligence-Assessment/blob/master/Assessment.ipynb) or [Presentation](https://github.com/ghcn345/Insider-Intelligence-Assessment/blob/master/Presentation.pdf). \
For any additional questions, please contact **Ning Chen—chen.ning345@gmail.com**.

## Repository Structure

Description of the structure of the repository and its contents:
```
├── README.md                           <- The top-level README for reviewers of this project
├── Assessment                          <- Data Internship Assessment in Jupyter notebook
├── Presentation                        <- PDF version of project presentation
├── TakeHomeAssessment                  <- Document of Data Internship Assessment
├── data                                <- Insider Intelligence Standard Assessment Data Set
└── images                              <- logo
```