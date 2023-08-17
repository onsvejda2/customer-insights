---
title: FAQ for Data prep report (preview)
description: This FAQ provides information about the AI technology used in Dynamics 365 Customer Insights data prep report (preview). It provides key considerations and details about how AI is used, how it was tested and evaluated, and any specific limitations.
ms.date: 07/20/2023
ms.custom: 
  - responsible-ai-faqs
ms.topic: article
author: radsay01
ms.author: rsayyaparaju
ms.reviewer: m-hartmann
---

# FAQ for the data prep report (preview)

These frequently asked questions (FAQ) describe the AI impact of Dynamics 365 Customer Insights data prep report (preview) feature.

## What is the data prep report?

The data prep report gives you information to help you understand the overall quality of your data, which insights are suited to your data, and what you need to do to improve your data. It includes an AI-generated summary to help you get a concise overview of your data quality and a comprehensive report to help you act to improve your data quality to get more and better insights about your customers.

## What are the feature’s capabilities?

The data prep report provides the following components or capabilities:

- An AI-generated summary of your data quality.

- An overall data quality grade.

- A determination of insight readiness for each type of insight offered before you attempt to generate it.

- Detailed information on data quality issues, categorized by data quality pillar, severity of impact, and impacted insights.

- Actionable suggestions on how you can improve your data quality to use all the insights  offered in Customer Insights.

## What is the feature’s intended use?

The data prep report is strictly intended to be used to understand and act on your data quality.

## How was the data prep report evaluated? What metrics are used to measure performance?

The performance of the data prep report is determined by the successful generation of the AI-generated summary, the comprehensive report, and the improved data quality to generate insights. The feedback provided through the thumbs up or thumbs down is tracked to understand customers satisfaction with the feature.

## What are the limitations of the data prep report? How can users minimize the impact of the  data prep report limitations when using the system?

Customer Insights recommends that customers adhere to the intended use for the data prep report for the Dynamics 365 Customer Insights product only. Other products and services have different requirements for data quality that the report can't adequately address. We recommend that customers review the comprehensive data report and not rely solely on the data quality summary before taking action to improve their data quality.

## What operational factors and settings allow for effective and responsible use of the feature?

The data prep report monitors reliability and performance. It doesn't allow for any user input and relies solely on aggregated data quality content created by evaluating customers’ data. There's no ability to use or generate content that could lead to harm. Opt in consent to the data prep report is provided in the **Settings** page and managed by the Admin role for Customer Insights. Consent can be revoked at any time to turn off the feature.

## See also

- [Data prep report](data-prep-overview.md)

[!INCLUDE[footer-include](includes/footer-banner.md)]