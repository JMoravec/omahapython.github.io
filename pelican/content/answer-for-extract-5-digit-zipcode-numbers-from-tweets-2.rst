Answer for extract 5 digit zipcode numbers from tweets
######################################################
:date: 2017-02-10 22:10
:slug: answer-for-extract-5-digit-zipcode-numbers-from-tweets-2
:status: published

| Thank you so much for your reply
| the data is like:
| City of Sun Valley 91352...City of Sun Valley 91352.....8911
  Driftstone Dr, Spring, TX 77379....Battery at 10601-10698.......
| these are the tweets.  i wanna extract only the 5 digit ZIPCodes in
  one column. tried the following:
|    zipcode=csv.reader(csvfile,delimiter=' ', quotechar='\|')    
|     for row in zipcode:
|         re.findall(r'(\\d{5})', str(row))
| it gives me result like:
| column 1:           ['91352'] ['91352']  ['77379']"['10601'
| column 2:           '10698']" ['91352'] ['91352']
|  
| plz look at the 2nd column where the zipcode 10601-10698 divided into
  2 column. i want each of the zipcodes in the same column but in the
  same row under zipcode name.

Just posted a photo @ City of Sun Valley 91352 https://t.co/F1br8SFo8j

Just posted a photo @ City of Sun Valley 91352 https://t.co/tXR3ynr9K1

8911 Driftstone Dr, Spring, TX 77379, $174,750 4 beds, 2 baths
https://t.co/w6Kjnur90V

Just posted a photo @ City of Sun Valley 91352 https://t.co/hakE3Zfy9t
