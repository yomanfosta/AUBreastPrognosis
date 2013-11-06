Joshua Foster
Dr. Owrang
American University
Breast Cancer Prognosis tool plan:
----------------------------------
Frontend: HTML/CSS/JS webpage
Backend: Django/Python
Debug-DB: sqlite3

1) collect/mine Data:
	will use various databases of breast cancer paitent information to scrap together and implement a large dataset
2) Using the data collected in step 1, the software will use the information to calculate proportional hazard risks.
3) Webpage setup:
	The frontend webpage will consist of a simple form for a patient/doctor to fill out including major medical information, as well as age and race. Once completed the form is sent to the server where the inputed information is run through a Cox model algorithm to estimate survival rate of the individual.
4) the inputed information will be used for farther analysis (would require follow up form to indicate whether patient survived)

TIMELINE:
	November 04-10: 	Converting current javafiles to an html/js format
	November 11-17: 	Mining Data and creating backend database.
	November 18-24: 	Calaculation of Proportions and implementation of Cox model backend.
	November 25-Dec 01:	Frontend Webpage creation.
	December 02- end:	testing and tweaking.			

GITHUB REPO: 	https://github.com/yomanfosta/AUBreastPrognosis
	dev branch: https://github.com/yomanfosta/AUBreastPrognosis/tree/dev

current end production site: http://fosterjosh.com/aubreast/