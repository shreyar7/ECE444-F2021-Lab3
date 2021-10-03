Name: Shreya Rajendran

This repo is a clone of https://github.com/nelaturuk/education_pathways.


Lab 3 Activity 1: Docker Installation

![Activity1](https://user-images.githubusercontent.com/90438521/135700019-6cc08d1a-1afc-4ef3-aade-599081b1b59d.PNG)



Lab 3 Activity 2: Cloning Education Pathways repo

![Activity2](https://user-images.githubusercontent.com/90438521/135700043-ccaf427a-ee51-47bb-92a9-93994533aede.PNG)



Lab 3 Activity 3: Building docker image

![Activity3-1](https://user-images.githubusercontent.com/90438521/135701720-563c0d79-ff73-477b-96c1-8e9e7d76cbc6.PNG)

![Activity3-2](https://user-images.githubusercontent.com/90438521/135701852-5015f310-f840-4ac3-a974-387c9737a6ea.PNG)

![Activity3-3](https://user-images.githubusercontent.com/90438521/135701854-af846a13-50d7-4df4-85a1-81417fb3316f.PNG)

![Activity3-4](https://user-images.githubusercontent.com/90438521/135701861-3376a0ab-788e-4a96-aaf7-d0a08aa9fdda.PNG)

![Activity3-5](https://user-images.githubusercontent.com/90438521/135701869-9be925fa-845d-4bf2-8438-1dc05e4c3186.PNG)

![Activity3-6](https://user-images.githubusercontent.com/90438521/135701872-cf511967-6cea-4931-b85c-e40b79311cfa.PNG)

![Activity3-7](https://user-images.githubusercontent.com/90438521/135701881-92a27c2d-6147-4264-91be-a33a534526cd.PNG)

![Activity3-8](https://user-images.githubusercontent.com/90438521/135701886-de2de5c0-cf8b-4f91-9c7d-98f6b9b309a7.PNG)

![Activity3-9](https://user-images.githubusercontent.com/90438521/135701889-707c63fe-d634-4188-a64b-e946ff773fbb.PNG)

![Activity3-10](https://user-images.githubusercontent.com/90438521/135701893-1b0a158d-b882-4cf3-81fb-1cc5981cad67.PNG)

![Activity3-11](https://user-images.githubusercontent.com/90438521/135701896-a8e779e1-fbef-46d6-8863-49ababf0cc08.PNG)

![Activity3-12](https://user-images.githubusercontent.com/90438521/135701901-128a73ae-b242-47c1-a983-e01bf353b180.PNG)

![Activity3-13](https://user-images.githubusercontent.com/90438521/135701906-b1694c34-94ff-43bb-8446-75c2680ea70e.PNG)

![Activity3-last](https://user-images.githubusercontent.com/90438521/135701463-ffe38be6-32c3-48a5-9460-5e34f71aa4ea.PNG)



Lab 3 Activity 4: Run docker image on localhost

![Activity4](https://user-images.githubusercontent.com/90438521/135701815-38dc81e9-4cb5-4be8-af4a-e4280c24c153.PNG)

![Activity4b](https://user-images.githubusercontent.com/90438521/135701833-ef794eb2-bbe2-492b-81fd-3f276b3c6ac4.PNG)



Lab 3 Activity 5: Feedback on Education Pathways application


Functional Requirement - Course Search

The web application shall allow the search of courses using keywords in the course description as well as the Course Title and Course Code. Then, multiple dropdown filters will be used to narrow the search.
Ex: The search term ECE444 should be accepted to provide direct matches or related matches based on related course topics, pre requisite courses, department or offering faculty, etc. Currently, the webpage only allows the narrowing of the search by one of Division or Department or Campus but it would be better to allow the user to narrow down the search results using a combination of multiple filters.

Non-functional Requirement - Usability

The web application shall provide responsive messages to prompt the users for further or modified inputs based on their selections.
Ex: If no courses were found matching the criteria selected by the user, an error message should be displayed saying "No courses were found matching the selected criteria." This will prompt the user to intuitively change the selected filters.




# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
