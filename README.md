**Cyber Challenge: Apache Log Analysis Adventure**

**Background:**
You've been tasked with investigating suspicious login attempts and potentially malicious activities in Apache logs. Your goal is to sift through the logs, identify anomalies, follow the trails of suspicious users, and analyze login patterns to uncover any potential security threats using ESQL in [Kibana.](https://demo.elastic.co/app/r?l=DISCOVER_APP_LOCATOR&v=8.12.0&lz=N4IgjgrgpgTgniAXKKBnMAbJIBmMD2AtgAQ4CWGUARlAIYAuAtAFQA0G%2BA5qi8QD7EMZQmXrEAjAAYQAX1YhU%2BGPSQBtVSAAC9YWnq1CABxDyAJmgDGIALrX5F%2FBgiEAdqjV2QZF%2BYAe2UwAmAFYcYOCLU0YAdgAWaIBmRlicAE4ADkZU2nFMhKpYwPFo9JwoSRwqEy8XelgAN1osRBBaCHp8avIMOph3RFVPAAsycwBhIdplJHoYaDMGWgA1MigAdwBlQygrZC9TAJCwiKi4xOS0zOzcxnzC4tLyyuqdekpsbuo6JjYObhYXroAGKrDC)


**Getting Started:**
Access the Apache logs using the provided ESQL queries. These queries will help you filter and analyze login attempts, track user activities, and identify any unusual behavior.

**Objectives:**

**Part 1: Exploring Login Attempts**
- Use the ESQL query "[ES|QL] - Apache logs - Exploring login attempts" to access Apache logs.
- Analyze the data to identify login attempts.
- Focus on the URLs containing "/login".
- Limit your analysis to the top 10 entries.

**Part 2: Filtering Suspicious User**
- Utilize the ESQL query "[ES|QL] - Apache logs - Filtering suspicious user".
- Narrow down your search to suspicious login attempts by a specific user.
- Investigate activities related to the user "haag8418" within a specific timeframe.
- Keep track of timestamps, user names, countries, and URLs accessed.

**Part 3: Following the Evidence**
- Employ the ESQL query "[ES|QL] - Apache logs - Following the evidence".
- Track user activities regardless of whether they've logged in successfully.
- Analyze time buckets to identify patterns in user behavior.
- Focus on the top 10 entries with the highest data transfer (bytes).

**Part 4: Grouping Logins Using a Time Histogram**
- Execute the ESQL query "[ES|QL] - Apache logs - Grouping logins using a time histogram".
- Group login attempts based on time intervals.
- Analyze login attempts within each time bucket.
- Pay attention to the frequency of login attempts by different users.

**Challenge Questions:**
1. What is the IP address of the suspicious user "haag8418" based on the Apache logs?
2. How many login attempts were made within the specified timeframe by the user "haag8418"?
3. Which country is associated with the highest data transfer (bytes) in the suspicious login attempts?
4. What are the top three URLs accessed during the suspicious login attempts?
5. What is the most common time interval (in minutes) for login attempts based on the grouping performed in the "Grouping logins using a time histogram" ESQL query?

**Note:** Ensure to document your findings and observations throughout the investigation process. Utilize the provided ESQL queries effectively to extract meaningful insights from the Apache logs.
