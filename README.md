[Gartner Reviews Scraper](https://apify.com/bucil/gartner-reviews-scraper?fpr=data)

## Gartner  Reviews Scraper

Gartner  Reviews Scraper is a web scraping tool designed to help you gather product reviews from Gartner using product URLs.

To use it, simply insert the URL of an Gartner product into the product URLs input field, initiate the scraper, and then retrieve the data from the output tab. You have the option to specify the maximum number of reviews you wish to extract, which can help shorten the scraping process. If you prefer to scrape all available reviews, just leave the 'Max Reviews' field empty.

## What will be the expense for scraping Gartner  Reviews?

When dealing with scraping tasks, gauging the necessary resources for data extraction can pose difficulties since use cases can diverge significantly. Therefore, the optimal approach is to conduct a trial scrape using a small portion of input data and restricting the output. This way, you can determine your cost per scrape, which you can subsequently multiply by the number of scrapes you plan to execute.

View [this video](https://www.youtube.com/watch?v=-wyz2iscZ30) for some valuable tips, and remember that opting for a higher-tier plan will lead to long-term cost savings.

## Input

To utilize the Gartner  Reviews Scraper, you should provide the URLs of the Gartner product from which you wish to extract reviews. Please be aware that not all public pages feature reviews. For a comprehensive description of the input format in JSON, click on the input tab.

```
{
  "proxy": {
    "useApifyProxy": true,
    "apifyProxyGroups": [
      "RESIDENTIAL"
    ]
  },
  "maxReviews": 15,
  "startUrls": [
    {
      "url": "https://www.gartner.com/reviews/market/a-b-testing-tools/vendor/wingify/product/vwo"
    }
  ],
}
```

> NOTE: Please keep in mind that using private proxies is advisable for enhanced stability in your results.

## Output sample

The outcomes will be encapsulated within a dataset, conveniently accessible in the Storage tab. Below is a snippet from the dataset you will obtain when applying the provided input parameters:

```
[{
  "sourceUrl": "https://www.gartner.com/reviews/market/a-b-testing-tools/vendor/wingify/product/vwo",
  "marketSeoName": "a-b-testing-tools",
  "reviewId": 6165474,
  "formattedReviewDate": "Apr 30, 2025",
  "reviewSourceCode": 3,
  "reviewIncentiveCode": 2,
  "productNames": "VWO",
  "reviewRating": 5,
  "industryCd": 268,
  "industryName": "Manufacturing",
  "companySizeCd": 9901,
  "companySize": "3B - 10B USD",
  "jobTitle": "Senior Product Marketing Manager",
  "reviewSummary": "Easy to run tests on multiple campaigns and quickly view the analysis of the tests which helps us a lot to correct campaign anomalies.",
  "reviewHeadline": "Quick setup of A/B tests for instant correction of elements on our content",
  "upVotes": 0,
  "functionCd": 243,
  "function": "Product Marketing",
  "partnerReview": false,
  "productSeoNames": [
    "vwo"
  ],
  "vendorSeoName": "wingify",
  "sortValue": {
    "long": true,
    "double": false,
    "boolean": false,
    "any": false,
    "string": false,
    "null": false
  },
  "url": "https://www.gartner.com/reviews/market/a-b-testing-tools/vendor/wingify/product/vwo/review/view/6165474"
}]
```

## Is it within legal boundaries to extract Gartner  reviews through web scraping?

Our Gartner Reviews Scraper operates ethically and refrains from collecting private user information, such as email addresses or locations. It exclusively gathers publicly shared data chosen by the user. Nevertheless, it's essential to exercise caution, as your results may inadvertently include personal information. Only engage in scraping personal data if you possess a valid and lawful justification.

If you're uncertain about the legitimacy of your purpose, it's advisable to seek guidance from legal professionals.

## Your feedback

We’re always working on improving the performance of our Actors. So if you’ve got any technical feedback for Gartner  Reviews Scraper or simply found a bug, please create an issue on the Actor’s Issues tab in Apify Console.