# Ho Sung Yi
# A01198596
# midterm for 1620 October 2020
# BCIT

## Q1
Git is a popular version control system which allows to record and keep track of changes </br>
GitHub is the web server that host git and make it to be used more efficiently with also making it possible to work with others in a projects from anywhere. </br>
Git is the actual software that is utilized for the version control system and GitHub is a git hosting service that provides efficient usage of Git.

## Q2
Git branch is used to test features before uploading to the main. The branch does not effect the main branch. </br>
I will mainly use this when I want to add a new feature in my code and test the feature if it works properly before actually adding it in by using the branch.

## Q3
when a resource is not found you will get a 404 status code. 404 belongs to the client error category(400 codes) which contains errors that has been caused by the client side. It is not permanent.

## Q4
The id already contains the color value pink but by adding style red it will present the text in color red. Inline style comes first so color given in the style tag on top with the id will not work.

## Q5
example: https://www.markdownguide.org/cheat-sheet/text.html </br>
https tells what protocol the browser use </br>
// are for correct syntax only </br>
www.markdownguide.org is the domain name, it is possible to use the ip address for the website </br>
www is the sub domain. It stands for the folder where the web content is located in the webserver. </br>
org is the top level domain, it resolves the location of the site </br>
/cheat-sheet tells server to find the cheat-sheet directory </br>
/text.html tells to find the text.html file </br>

## Q6
http reader is a human readable name value pair separated by a colon added to the http request or response. http header send the information of the state along the request or response.
- Authentication header: prove to server if you have the authorization by sending authentication header with authentication information such as username and password using Base64 encoding
- cookie header: used to pass a small piece a data containing the information of where it has been and what state it has been in 
- cache header: tell browsers what files to save, how long it should be saved, and tells if it should be updated

## Q7
CSS box model is a set of rule that defines how elements are sized, spaced, positioned, and relations which each other </br>

From inside to outside
- Content, padding, border, margin

## Q8
Descendant combinator : style without adding additional attributes such as classes, id </br>
p strong { </br>
    color : green; </br>
    } </br>
will make all `<strong>` in `<p>` green </br>
</br>
Child combinator: style direct child </br>
p > strong { </br>
    color: green; </br>
    } </br>
will make any strong tag that are children of paragraph green </br>
</br>
Adjacent sibling combinator: style siblings directly next to each other </br>
h1 + p { </br>
    color: green; </br>
    } </br>
will only make p that comes right after h1 green </br>
</br>
General sibling combinator: style sibling that share parent but not right next to each other </br>
h1 ~ p { </br>
    color: green; </br>
    } </br>
will make any paragraph that are siblings to h1 green </br>

## Q9
It will appear on two separate lines because adding another `<p>`tag means it will start a new paragraph </br>

## Q10
on img does not include a required attribute which is alt </br>
adding attributes on the closing tag is wrong
