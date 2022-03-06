# Udacity Data Product Manager

In this project, I will apply the skills acquired in this course to create the MVP launch strategy for the first flying car taxi service, Flyber, in one of the most congested cities in America-- New York City. I'm responsible for bringing the first flying car taxi service to market by analyzing data and building a product proposal.

Because Flyber is the first flying car, my team acquired taxi data for a comparable initial analysis. The dataset contains real taxi drop-offs and pick-ups in New York City.

Flyber’s budget is limited, and thus it’s important to unveil our service when profits will be maximized. 
I will be using the workspace provided in the classroom as well as Tableau and I will be filling out and submitting a slide deck (using Powerpoint template) with my answers in the appropriate places for review.

I will complete the tasks below, as per the project rubric:

1. Product Management - Identify your customer and their pain points
    * What are taxis used for?
    * What are the characteristics of the people that use them?
    * What are existing pain points with taxis?
    * What are the existing pain points with digital ride-sharing services?
    * What user & market improvements do you hypothesize a flying taxi service would have over the existing state of taxis today?

Upload the data to Tableau Public. Ensure the fields are parsed correctly. Let’s start exploration!
You may notice that values in the Distance column appear as null in Tableau. If this is the case, you will need to convert that column to decimals. To do so, click on the # above the Distance column and select Number (decimal) from the drop-down menu. This should populate the column with the correct distance values.

2. Get a high-level understanding of the granularity and scope of the dataset.
    * How many records are in the dataset
    * What does each record represent?
    * What is the primary key?
    * What date range is your dataset bound to?
    * What are the geographical bounds of this dataset?

Enrich the dataset with relevant fields
You notice that ride price is not included, but figure it could be derived. Based on information about New York taxi prices gleaned from the internet, create a calculated field called price using fixed variables, duration, distance, and passenger count.

You hypothesize your target users will be those who take a relatively longer time getting to a destination that is relatively close by, due to heavy traffic conditions and/or limitations to physical road infrastructure. To be able to analyze where this is happening, you will need to create a calculated field called distance-to-duration ratio.

3. Analyze the distribution of the dataset
Calculate the average, median, and the first & second standard deviation of the mean for the following measures:
* duration
* distance
* passenger counts
* duration-to-distance ratio
* price

Flying cars may have to have a lower weight for efficiency / take-off. Create a histogram of passenger counts to analyze the potential market volume of low passenger pickups.
1. Extract spatial trends from the dataset
    * Which neighborhoods/zip codes tends to experience a relatively higher density of pickups?
    * Which neighborhoods/zip codes tends to experience a relatively higher density of dropoffs?
    * Which neighborhoods/zip codes tends to have the highest duration-to-distance ratios, based on pickup?
    * Which neighborhoods/zip codes tends to have the highest duration-to-distance ratios, based on dropoff?

2. Extract temporal trends from the dataset
For the MVP (or even for production launch) it may not make operational sense to have the service running 24/7.
    * What times throughout the day experience relatively higher volumes of ride pickups?
    * What days throughout the week experience relatively higher volumes of ride pickups?
    * Analyze the user research survey data to determine sentiment and user segments that would likely use a flying car service
3. User research survey questions (these questions are also in the slide deck template):
    * What is your email?
    * What gender do you identify as?
    * What is your age?
    * What is your annual income? (income bands)
    * What neighborhood do you reside in?
    * Do you currently use taxis? (Y/N)
    * Do you currently use ridesharing services? (Y/N)
    * Would you use a flying taxi service, if such a concept existed? (Y/N)
    * If yes to Q8, how much would you be willing to pay per mile for such a service? (USD)
    * If no to Q8, what is the reason?



## Results

### Bringing the First Flying Car Taxi Service to Market
In this project, I will apply the skills acquired in this course to strategize how to unveil the first flying car taxi service, Flyber, in one of the most congested cities in America-- New York City. I'm responsible for bringing the first flying car taxi service to market by analyzing data in Part 1 (Midterm) and building a product proposal in Part 2 (Final).

My data scientist has passed me a plethora of visualizations, model outputs and aggregated statistics from a dataset containing real taxi drop-offs and pick-ups in New York City. Because Flyber is the first flying car, my team has acquired taxi data for a comparable initial analysis.

I will be using the provided slide powerpoint version to complete my **Business Proposal** and answer the provided question, and will also be provided a SQL workspace to be able to work with the data.

### Flying Taxi Business Case 

### Flyber Data Strategy

### Iterative Design & The Future of Flyber: A Path Forward