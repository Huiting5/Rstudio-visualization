# Rstudio-visualization
Variable Description of datasets
US percentage population of age groups over time dataset:
congress: The number of the Congress that this member’s row refers to.

start_date: First day of a Congress.

chamber: The chamber a member of Congress sat in: Senate or House.

state_abbrev: The two-letter postal abbreviation for the state a member represented.

party_code: A code that indicates a member’s party, based on the system used by the Inter-university Consortium for Political and Social Research. The most common values will be 100 for Democrats, 200 for Republicans.

bioname: Full name of member of Congress.

bioguide_id: Code used by the Biographical Directory of the United States Congress to uniquely identify each member.

birthday: Date of birth for a member.

cmltv_cong: The cumulative number of Congresses a member has or had served in (inclusive of listed congress), regardless of whether the member was in the Senate or House.

cmltv_chamber: The cumulative number of Congresses a member has or had served in a chamber (inclusive of listed congress).

age_days: Age in days, calculated as start_date minus birthday.

age_years: Age in years, calculated by dividing age_days by 365.25.

generation: Generation the member belonged to, based on the year of birth.

New variables I added:

age_group: Convert the Generations in the data to the defined year range

party: Convert the party code to the name of the party which the code represent.

Aging congress dataset:
Age group as a percentage of total population:

ages 0-17

ages 18-64

ages 65 and older

Age group as a percentage of the dependent population:

ages 0-17
State Label
State

Abbreviation
