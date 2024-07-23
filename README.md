# Company Funding Activities

Interested in using this scraper? Get it here: [Company Funding Activities](https://apify.com/pratikdani/company-funding-activities). Scrape Funding Activities of a company and extract funding information in bulk.

## Features

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. You can select the fields you want, allowing for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

**Ability to Resume Last Failed Runs:** In case of unexpected errors, you can simply go to the actor's last run page and click on the 'Resurrect' button to resume the last scraping progress.

## Integrations

You can use [Make](https://www.make.com/en/register) to integrate the Company Funding Activities with any other SaaS platform by designing your own automation flows.

## Sample Output

Here is a sample output of this actor:

```json
{
  "domain": "openai.com",
  "funding_activities": [
    {
      "currency": "USD",
      "date": "2023-01-23",
      "investment_type": "corporate_round",
      "investment_value": 10000000000,
      "investment_value_usd": 10000000000,
      "lead_investors": []
    },
    {
      "currency": "USD",
      "date": "2023-04-28",
      "investment_type": "series_unknown",
      "investment_value": 300000000,
      "investment_value_usd": 300000000,
      "lead_investors": []
    },
    {
      "currency": null,
      "date": "2021-01-01",
      "investment_type": "secondary_market",
      "investment_value": 0,
      "investment_value_usd": 0,
      "lead_investors": []
    },
    {
      "currency": "USD",
      "date": "2019-07-23",
      "investment_type": "corporate_round",
      "investment_value": 1000000000,
      "investment_value_usd": 1000000000,
      "lead_investors": []
    },
    {
      "currency": "USD",
      "date": "2016-08-22",
      "investment_type": "pre_seed",
      "investment_value": 120000,
      "investment_value_usd": 120000,
      "lead_investors": []
    },
    {
      "currency": null,
      "date": "2019-03-11",
      "investment_type": "seed",
      "investment_value": 0,
      "investment_value_usd": 0,
      "lead_investors": []
    }
  ],
  "linkedin_url": "https://www.linkedin.com/company/openai"
}
```

## Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **domain** (string): The domain of the company.
- **funding_activities** (list): A list of funding activities of the company.
- **linkedin_url** (string): The LinkedIn URL of the company.
