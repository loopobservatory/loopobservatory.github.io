# Plan of Development

# prel-reviews 

`
The fundamental idea is to structure the online resources (both paid and free) and provide a plotform for their vetting through the reviews from the community of users. 


Operational todo list

* Firebase Connectivity
* Scrapping data for content
* Adding Filters
	* free/paid
	* beginner/intermediary/advanced
* Using Discuss for reviews
* Search 
	* on home page
	* also along with filters in the topics page



* we will start with 4 verticals for structuring the content - ordered according to priority
	* Parents looking for Tuitions for kids below 10th standard - particularly programming for kids
	* Professionals looking to upgrade their skills - upgrad customers
	* College freshmen, looking for rights resources and guidance for curricullam 
	* UPSC and other government exam aspirants

### Programming for kids/ Online Tuitions for kids

todo 

- [ ] Gather data on online tutions
- [ ] Developing UI for intuitive understanding of the reviews and comparasion with other services
- [ ] Get People to use it

### Professional looking to upgrade their skills 

- [ ] Gather data on online tutions
- [ ] Developing UI for intuitive understanding of the reviews and comparasion with other services
- [ ] Get People to use it

### College freshmen

- [ ] Gather data on online tutions
- [ ] Developing UI for intuitive understanding of the reviews and comparasion with other services
- [ ] Get People to use it

### Government Exams

- [ ] Gather data on online tutions
- [ ] Developing UI for intuitive understanding of the reviews and comparasion with other services
- [ ] Get People to use it




# **prel-courses - In cold storage** 

## 1st Iteration
* [UI-Design](https://www.figma.com/file/oB2qSvWWPlBietJ1O2K5fh/app?node-id=0%3A1) 
	* Splash screen with logo, without login
	* Landing Page
		* Search Bar to search courses
		* widgets
			* Courses List
			* Ask a question
			* Syllabus
			* Resources
	* Course Module
		* Here I am explaining the design by an example of a particular course say economics
		* once the user clicks on the course, she will land on the first module of a course
		* There will be side bar which will show all the modules - like a table of content, and kind of green dot in front of the module which the user is currently viewing
		* The first module of the course will have a start button at the bottom which we take the user to second module
		* every module in the 1st iteration will be like a page of text, in the end there will be previous and next button
		* In the last module, in the end there will be a button name complete, and it will take the user to another static screen which will show a congratulatory message for 3 second and will take the user back to the home page


## Pending Design decisions
* <del>Format of the ask a question page</del>
* <del>CMS - Content Management System module interface to upload and amend content in the app</del>
	* CMS - for 1st iteration, will be json files in the backend - firebase database


## Task to be taken care of
* development of the first course	
* Upload dummy course material for app development in firebase database - json files

## Ideas for the next iteration
* Better UI design
* Content database interface for automation
* profile authentication and state management module
* chat for asking a question

