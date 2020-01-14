# Exercise_1_Hakansson

# checking for pandas
!pip show pandas

import pandas


# columns of the data frame (as lists):
names=["Mikael", "Erin", "Aisulu", "Shannon"]
age=[60, 25, 25, 40]
sex=['M', 'F', 'F', 'F']
city=["Solvesborg", "Redwood City", "Almaty", "Lacrosse"]
country=["Sweden", "USA", "Kazakhstan", "USA"]
major=["Comp Sci", "Psychology", "DS", "Psychology"]

# now in a dict:
dataInDict={'names':names, 'ages':ages, 'sex':sex, 'city':city, 'country':country, 'major':major}

# the dataframe
dataInDict
