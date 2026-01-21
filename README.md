📊 Customer Service Analytics for Improving Customer Retention at Flipkart (Excel Project)

📌 Project Overview

This project analyzes customer service call-level data to understand what drives Customer Satisfaction (CSAT) and how service performance impacts customer retention.
The goal is to identify key patterns across call centers, channels, issue types, SLA response time, and sentiment, and provide actionable recommendations to improve customer experience and reduce churn.

Tool Used: Microsoft Excel

Focus Areas: CSAT • Customer Service • Retention

🎯 Objectives :

Analyze customer service call data

Identify key drivers of CSAT

Recommend improvements to enhance customer retention

🧾 Dataset Description :

The dataset is a customer call-level dataset containing key variables such as:

CSAT Score

Customer Sentiment

Call Duration

Response Time / SLA Category

Issue Type

Support Channel (Call Center, Chatbot, Email, Web)

Call Center / Region

Date & Day Patterns

🌳 Metric Tree (Business Logic)

The project uses a simple metric tree to connect operational metrics with business outcomes:

Customer Retention

→ Repeat Customers

→ (1 - Churn Rate)

→ Customer Satisfaction (CSAT)

→ Driven by:

Sentiment Score

Issue Type

SLA Response Time

Channel

Call Center / Region

Call Duration

🧠 Key Hypotheses Tested :

This project tested multiple hypotheses around:

Time-based patterns (CSAT variation across dates)

Call center performance differences

Channel performance impact

Issue-type impact

Sentiment vs CSAT relationship

Efficiency metrics impact (call duration)

📌 Key Insights (Findings) :

✅ 1. CSAT varies by date (October 2020)

CSAT shows moderate variation across dates, with mid-month CSAT being consistently higher, suggesting workload stability improves service quality.

✅ 2. Call center performance differs significantly

Chennai had the highest CSAT

Kolkata had the lowest CSAT

✅ 3. SLA alone does not explain low CSAT

Even when Kolkata calls were within SLA, CSAT remained low — meaning quality + communication matters beyond speed.

✅ 4. Channel impacts CSAT strongly

Call Center + Web = highest CSAT

Chatbot = lowest CSAT
Customers prefer human interaction, especially for complex issues.

✅ 5. Issue types affect satisfaction

Billing issues are the most reported

Service Outage cases show consistently lower CSAT, indicating high frustration levels

✅ 6. Sentiment is the strongest driver of CSAT

Customer sentiment has a very strong positive correlation with CSAT (r ≈ 0.895).

❌ 7. Call duration has no meaningful impact

Call duration shows no correlation with CSAT and no correlation with sentiment, meaning longer/shorter calls don’t necessarily improve satisfaction.

💡 Actionable Recommendations :

Improve proactive communication and transparency during Service Outage cases

Deploy language-skilled / region-aligned agents, especially for centers handling high out-of-state calls

Reduce reliance on chatbots for complex issues, route them to human agents

Replicate best practices from Chennai call center

Improve staffing + monitoring during start and end of month, when CSAT drops

📈 Expected Business Impact :

Higher customer sentiment → improved CSAT

Improved post-purchase support → higher retention

Reduced churn risk during high-frustration scenarios (e.g., outages)

More consistent service quality across regions and call centers

Stronger long-term customer loyalty and brand trust

🛠 Tools & Skills Used:

Microsoft Excel

     > Pivot Tables

     > Charts & Dashboards

     > Correlation analysis

     > SLA category comparisons

     > Time-based trend analysis

     > Call center performance benchmarking

📂 Project Files :

Flipkart_Anlaysis.pdf → Final presentation/report 

Flipkart_Anlaysis

Flipkart_df_Working.xlsx → Excel working file (data + analysis)

🚀 How to Use :

Download the Excel file

Open in Microsoft Excel

Explore:

Pivot summaries (CSAT by channel, issue type, region)

Correlation insights (Sentiment vs CSAT)

Time trend patterns

📌 Conclusion :

The analysis shows that customer satisfaction at Flipkart is primarily driven by emotional experience and issue resolution quality, rather than operational metrics like call duration.
Targeted improvements in sentiment handling, outage resolution, region alignment, and channel strategy can significantly improve CSAT and retention.

👤 Author

Ashutosh Chandra
