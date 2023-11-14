# horiseon_website_refactor
This is the first challenge of the boot camp. The main goal is to make the website meet the standards of accessibility.
    
## Challenge Introduction:

This week my challenge is an on-the-job ticket, which means I have been provided with the starter code that I need to modify which consist of index.html and style.css files. This week's challenge involves the modification of a marketing agency's website named Horiseon. 
The main goal of this challenge is to take existing code and refactor it. Refactor code means to improve the code and meet a certain set of standards without changing what the code does. 
This is the user story and acceptance criteria:

## User Story:

```
AS A marketing agency
They WANT a codebase that follows accessibility standards
SO THAT their own site is optimized for search engines
```

## Acceptance Criteria

Their website must meet accessibility standards. For that purpose I have to make these changes to achieve the task:

* Semantic HTML elements can be found throughout the source code:
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

###  Creation of New Repository:

I have made these changes to achieve the Acceptance Criteria.

* To complete this challenge and to put it on Github, I created a new repository with the name of Horiseon_website_refactor.
* I added the README.md file in this repository. 
* After creation of this repo I copied the SSH key of this repo and I pulled it to my local machine with the help of gitbash. 
* I used git clone command with SSH key to clone this repo on my laptop.
* I opened this repo folder in vscode with the help of code . command in gitbash.
* After opening the folder in vscode I copied and pasted the code files and assets folder in my repo folder. I have been provided this index.html and style.css files to make changes in the website code for refactor.
* After copying the files I added the changes with the command git add . and then commited the changes with the git commit -m "" command. After comminting the changes I pushed the changes to Github with the help of this command git push origin main
* After doing this commit I started modification of the code to achieve the Acceptance Criteria.

### Acceptance Criteria Modification:

#### Semantic HTML elements:

* I changed all non-semantic elements to semantic elements. To change make website SEO friendly I changed div tag to header, main, footer, nav, section and article. I also put comments before each changes in order to describe the changes. After converting div to semantic elements I saved the changes with git add . command in gitbach and commited the changes with git commit -m "" . After commiting the changes I pushed the code to my repo on Github with the comments for each commit.

#### Title elements contain a concise, descriptive title:

I changed the title of website which is shown in browser. So changed the title by going into index.html and found the title in head tag. It was website which is not descriptive so I changed it to the name of the brand Horiseon. I put comment before this change telling what have I done.

#### HTML elements follow a logical structure independent of styling and positioning:

I looked into the logical structure of the html elements and made sure that all elements are placed logically well. Like everthing goes inside the html tag instead of <!DOCTYPE html> tag. In html there comes two parts head and body. head consists of links and meta tags with title of the website. And everything which is shown on website comes inside the body tag. 
I made sure that body tag is divided into 3 parts. 1 Header 2 Main 3 Footer.
Navbar comes inside the header tag. Hero section and other content comes inside the main tag. main tag then devided with the help of section, article and aside tags. At the end of the page I put footer tag and put everything which comes at the end of the website like contact and address etc in the footer tag. This is how tried to follow a logical structure of html elements.

#### Image and icon elements contain accessible `alt` attributes:

I have added alt attribute to every image in the website and added the descriptive text to it so, that if images don't show becuse of any reason then text will be shown. I have saved the changes with the use of git add. command and pushed it to github after commiting it. 

#### Heading attributes fall in sequential order:

I have made sure that there should be only one h1 in whole page and headings should fall in sequential order. So, I have changed one h2 which was inside footer to h3 because it was written after h3. there is no h2 coming after h3 now. Each h3 is coming after h2.

#### CSS code modification:

I have combined the elements which were sharing the same styles. like there are classes and elements which had same styles but they were written separatly. So, I combined them with coma in between them. I also put the comments before this change in style.css file.

#### Scout Rule:

An important rule to follow when working with someone else's code is the Scout Rule, which recommends that you always leave the code a little cleaner than when you found it. So I made sure that all links are functioning correctly and I have devided the code into 3 parts with highlighted text. First part is Header second is Main and last part of code is Footer. I also tried to put comments after each change so anyone who looks at the code he can understand the code easily.

#### Website working same:

So, After making all these changes the website working same as it was working before modification.












 

