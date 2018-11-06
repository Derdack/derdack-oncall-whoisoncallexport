# SQL Query to Get All On-Call Plan Duties from The Enterprise Alert Database

The purpose of this SQL script is to export who-is-on-call information for further processing, e.g. to embed that information into third-party systems or views.

You can modify the @PeriodStartDate and the @PeriodEndDate dates in order to retrieve information within that timeframe.

You can include a where clause, e.g. "TeamDisplayName = 'Support'" in order to filter for a specific team.
