## Movie Log

https://a3-cameronnorris-1.onrender.com/

Include a very brief summary of your project here. Images are encouraged, along with concise, high-level text. Be sure to include:

- The goal of this application was to create a functional movie logger that stores the movies a user logs between visits. Whenever the user logs in again after not using it, their movies should still be saved in the database.
- Coming in, I had no experience with any databases and learning MongoDB was a little difficult. Using express and communicating with Mongo took a while to get down.
- I went with a simple log in with a username and password because it seemed simple. I store the username and password in the database and authenticate in my backend server.
- I used System.CSS framework to create a cool, retro feel to this. A lot of the films I watch and would log are ‘retro’, and I thought that it would be fitting. 
	- I made little modifications, namely the button placement (in the center of the screen) in order to make the user’s experience flow better.
- I used custom functions for the post, patch and delete functions as well as a login function in the backend to update and override information in the database

## Technical Achievements
- **Tech Achievement 1**: I used multiple forms of input including a star rating system in which the user can rate a movie visually with stars
- **Tech Achievement 2**: I scored 90% or higher in each of the categories in each of my pages using Google Lighthouse

<img width="1557" height="732" alt="Screenshot 2025-09-23 120630" src="https://github.com/user-attachments/assets/f4bfb922-1ccc-424b-b177-c6e781c63825" />
<img width="1548" height="750" alt="Screenshot 2025-09-23 120639" src="https://github.com/user-attachments/assets/104c6094-b9bc-4adc-a241-cfebb6a11934" />
<img width="1526" height="732" alt="Screenshot 2025-09-23 120645" src="https://github.com/user-attachments/assets/f02314f5-3bae-4266-962b-231dffc2dad1" />


- **Tech Achievement 3**: I display all the movies logged by a particular user, not all of the data in the database.


### Design/Evaluation Achievements
- **Design Achievement 1**: I followed 12 tips from W3C's resources and hints:

Developing for Web Accessibility:

1. Associate a label with every form control: I added labels for text boxes whenever it seemed necessary. In the past, I have either placed text before the text box, or placeholder text, but I learned about the “for” element for things like log-in boxes, entering movie spaces, etc.
2. Help users avoid and correct mistakes: A big piece of criticism that I received on my last project was that the form in which the user enters information was not clear. This time, I spaced the input into different forms, (with specified types such as passwords and dates), making it easier for the user to utilize.
3. Reflect the reading order in the code order: I took careful note to space and order the code in a readable manner. I frequently have a different time reading large chunks of HTML code, so I made sure to space and indent everything so that it reflects how the website looks. Specifically, the windows (with use of system.css framework) are spaced in the code so that they reflect how it appears on screen.
4. Help users avoid and correct mistakes: Throughout, I have implemented catches to help the users use my site correctly. These catch when an input is incorrect or when there is an error. If something behind the scenes goes wrong (due to an unknown error made by the user), and the site doesn’t notify them that something went wrong, the user will continue to make that mistake and the site will not work properly for them.

Designing for Web Accessibility:
 
5. Provide sufficient contrast between foreground and background: As much as it helped, System.css also limited me in my design choices. The framework was meant to emulate early Apple UI, which I thought would be a great fit for my site. Although, the framework does not allow color, meaning that I had to work with what I had. The headings and subheadings are bolded by default in the framework. I used this to make contrast between the background and foreground, allowing the titles and subheaders to stand out, and the body text to do it less so (while still being very readable).
6. Ensure that interactive elements are easy to identify: I already had the working star hover animation at the time of discovering this article, but since then, I have added (with help from system.css) buttons that change color when clicked, and text boxes that appear black when the user is entering text into them. Since the page has a lack of color, highlighting aspects with black or gray really helps them stand out.’
7. Ensure that form elements include clearly associated labels: Like mentioned earlier, I used textbox labels to clearly convey what each box does. Since most of the web page relies on entering information, an abundance of text boxes could be confusing. So, I structured the forms’ labels in close proximity. Further, I ordered and reordered the forms in such a way that the order of information would make the most sense.
8. Use headings and spacing to group related content: With help from System.css, I used the “window” class to my advantage in order to maximize whitespace where information isn’t. The necessary information on any given page takes place in the center of the screen, and everything is spaced appropriately. It is outlined in a box and the rest of the space is white.

Writing for Web Accessibility:

9. Provide informative, unique page titles: For each page on this site, I labeled it clearly at the top with information about it in the subheaders. As well as this, I placed buttons around each page to navigate to and from the different pages. Each button is labeled clearly on where it will take the user.
10. Use headings to convey meaning and structure: I used subheadings and even smaller text to separate each page and make them easier to navigate for the user. For example, on the Logged Movies page, I have a title, a subheader explaining that you can change the rating on a film, as well as some plain text underneath telling the user exactly how to enter a film.
11. Provide clear instructions: Especially during the login page of this site, I made sure to properly show the process of logging in to the user. If they enter their password wrong, it will tell them and prompt them to re-enter. If the username is not recognized, it tells them to re-enter with their password and that it will create an account. If the user gets all the information correct, it will tell them that they successfully logged in. 
12. Keep content clear and concise: The concept of the site is pretty well known (or easy to understand), so I wanted to leave the user’s choices up in the air, and keep the information concise. Each page is clearly labeled with a title and only necessary text underneath when needed, describing what each function does. 
**Design Achievement 2**: I used the CRAP principles in the Non-Designer’s Design Book readings: 

Contrast
	Contrast is important, even for minimalistic websites like mine. The information on the screen might be difficult to pull, so I used contrast to make the entire experience easier for the user. I used contrast especially to make the ‘windows’ and their headers stand out from the background. The System.css framework I used works in black and white, meaning that I had to use contrast primarily as a substitution for colors. The framework provided great methods of allowing the title text to pop (as seen on the black lines interrupted by the bolded title texts atop each of the pages). For the table, I was allowed to color the background so I chose a light gray to make the text pop especially from the white background. The stars were not a part of the framework, and I made them the only colorful aspect of the site (bright yellow) to emphasize the stars’ meaning (the more colorful stars a movie has, the more you enjoyed it).

Repetition
	Repetition is also important for similar reasons to contrast. If each page is different, it can prolong the user’s ability to actually make decisions as they would need to re-find everything on the screen, ending in confusion. I utilized System.css’s window feature (again) to make each screen look similar to each other. I implemented the bars across the top with a large header so that if in need of a reminder, the user can simply look at where the title is to know what page they’re on (and this works for every page, too). The form and star rating aspects are carried over from the Movie Log page to the Logged Films page so that when altering a movie rating, the user can have a familiar and similar experience to one they just had on the previous page. The star rating system was carried over as well so that the user could have an easier time visualizing how much they enjoyed a film (because visual, repetitive stars are clearer than numbers). 

Alignment
	With help from System.css (and simple css syntax), I aligned the aspects on screen and sized them in proportion to each other. For example, on each of the pages, the text boxes are roughly exactly the size they need to be for user input. I tried entering a few of my favorite movie titles and gave brief opinions of them to see how much of the text boxes the user would generally need. There were some film titles that were much longer than others, meaning that I needed to find a common ground, and I sized them how I did. For the username and password, the text boxes are much smaller. I used alignment to organize information as well in that I spaced all of the input boxes together and in the center of the screen (in the order in which I thought was appropriate and made the most sense thinking-wise). I spaced the title and descriptions farther from the text boxes for clarity. On the logged films page, I separated the input boxes and the display table with a line so that the user could tell which part of the page was for what.

Proximity
	Lastly, I used proximity to organize the visual information on the page by comparing my site to other sites that I enjoy using. I viewed minimalistic sites with similar functions to see how they grouped visual aspects. I then made adjustments and tried to use the page from the perspective of a user who has never used the site before. I took quick glances at the information and saw which aspects needed grouping. On the movie logging page, the text boxes are spaced together in the order that one would think of the answers in, and placed the submit button near the stars so that the user would be able to submit their answers quickly after entering them. I placed the “Logged films” and “Back” buttons at the top of the page, and the “Submit” buttons towards the bottom, as that is both what made the most sense to me, and what other websites frequently do. The “Logged films” and “Back” buttons navigate to different pages, and just like internet browsers do with their back and tab buttons, I chose to place them higher. The submit buttons are like conclusions to the information entering, so I chose to put them towards the bottom of the page.


AI (and outside sources) Use:
I used AI in this assignment (along with outside sources) to fully understand how Mongo works, and how express communicates with it. I was briefly having a bug where my site on render would not process some of the CSS, and before going to office hours, I used AI to help diagnose why it was doing that. The problem went away by itself thankfully. Some of the more helpful sources that I used:

https://www.geeksforgeeks.org/mongodb/how-to-connect-node-js-to-a-mongodb-database/
https://studio3t.com/knowledge-base/articles/connect-to-mongodb/
https://www.simplilearn.com/tutorials/css-tutorial/css-framework
