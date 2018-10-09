# secu
Secu (pronounced Seck You, from the word Secular https://plato.stanford.edu/entries/religion-politics/ ) is a hybrid mobile/web app that for the MVP allows for non-profits and PoliSci folks to make score cards for legislators based on their voting history using the roll call votes published on the house and senate websites. An example score card is here http://www.cfequality.org/issues/congressionalscorecard/house-115/ 

ProPublica has an open API to call U.S. Congress in JSON format but the data actually published on the .gov form is XML. https://projects.propublica.org/api-docs/congress-api/ and https://www.senate.gov/legislative/votes.htm and https://xml.house.gov/

Currently the project uses Phonegap https://phonegap.com/ based on Cordova https://cordova.apache.org/ for the hybrid app development. Framework7 is used for the user interface and Split View Template http://framework7.io/templates/ and https://framework7io.github.io/framework7-template-split-view/ . Languages used are Javascript, CSS, HTML5. Secu is released under the GPLv3 https://www.gnu.org/licenses/quick-guide-gplv3.html and https://www.gnu.org/licenses/gpl.html 

The long term goal is a mobile app that regular people can use on voting day to quickly compare the candidates based on their actual voting history in their careers as legislators. Each state and locale have different publishing requirements and standards so grabbing from every legislature will be a project in and of itself. The goal is to get the full voting history of legislators from their starting in local/county/state as they climb the ladder. Organizations can make their own score cards and users can see them in the app so you can put in the app what you are pro or con like prof life or pro choice and rank your interests based on how important they are and then either have a custom score card generated or have the organizations scorecards displayed in order of compatibility with your views. You can publish your own score cards in the app if you want, or share on social media. Push notifications for when legislators vote either for or against your interests as soon as the vote is published on the .gov. Features to contact your legislators on social media or email/phone/snail mail/social media when they vote for or against your interests.

The project is in its very early stages so most of the files are from the component repositories and haven't yet been customized, like the template. * denotes the current step. Things to do:

1. *
	1. JS to pull in JSON format from ProPublica
	1. HTML5 to build table and search using JSON data
1. 
	Make the table interactive 
	Add score carding

3. 
	Remove excess content from template 
	Publish for use by non-profits and PoliSci folks

4. Begin making the app more user friendly with features like
	List of interests to be pro or con ranked in order of importance
	Search for score cards made by organizations
	Push notifications based on interests
	Favoriting/Saving specific bills and push notifications as they go through the pipeline
	Share to social media: bills, scorecards, etc
	Contact your legislators using phone/email/snail mail/social media
	Official Launch

5. 
	Research all 50 states legislatures and their current data formats

6. 
	Add all 50 states to the app in order of least to greatest difficulty and time needed

7. 
	Research all counties and major cities for their current data formats

8. 
	Add all counties and major cities in descending order of population, difficulty and time needed

7. 
	Research all cities, towns, villages, etc for their current data formats

8. 
	Add all cities, towns, villages, etc in descending order of population, difficulty and time needed

...

Profit!