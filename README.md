# web_scraping
data source:
https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

based on tutorial:
https://www.youtube.com/watch?v=8dTpNajxaH0

changes to the tutorial:

'Rank' - to int

'Revenue (USD millions)' - deleted "," / to int

'Revenue growth', - deleted "%" / searching by span in html to find is increase or decrease / to float

'Employees' - to int

'Headquarters' - splited 'Headquarters city' 'Headquarters state'

