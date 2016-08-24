This page contains few coding exercise that we want our future engineers to solve. Feel free to solve these problems (as a project in your github) and share the project url to us using the <u>comment</u> option on <u>LinkedIn post</u> so that we can review **your creativity!!**

#### Before completing the test below, keep these points in mind:

1. There is no one correct solution to this problem, there are many
2. The whole point of this exercise is to complete a deliverable – so fill in any missing info as you see fit
3. Relax and show your style and creativity
4. **See #3**

#### Basic Requirements:

- All code should be accessible from github.com. If you are using private repository, please provide access to id 'codensolve'. In case of any doubt please check https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/
- All code should be executable and delivered with test cases.
- Any frameworks or build tools can be used as long as complete projects are included with all instructions to execute it.
- Detailed error/exception handling is not required, but encouraged
- Additional functionality/creativity/user interface is allowed and encouraged, but not required

### Problem 1: Encourage Donation

Sarah owns a Cookie shop. Sarah has a limited number of types of cookies but she has an unlimited supply of each type. In her shop every cookie is associated with a donation amount - which means every time someone buys a cookie she keeps the donation amount associated to that and give to charity. Sarah want to encourage people to buy those cookies which will make her donate more money. 

###### Rules:

- No limit on maximum amount that a person can use.
- Each cookie has a name, price and donation amount. 
- Name should be less than 20 characters
- Price and Donation amount should be > 0
- Result should display maximum donation amount Sarah can hold with thecombination of cookies.

##### Sample Input:

Total Money: $20

| Name | Price | Table |
| ---- | ----- | ----- |
| A    | 5     | 2     |
| B    | 3     | 1     |
| C    | 7     | 4     |
| D    | 9     | 3     |
| E    | 1     | 0     |

##### Sample Output:

10 (7,7,5,1)

### Probelm 2: Cash Back Application

John and his friends are planning to design a product to help people to do a price match on products based on purchase price at different sellers. The idea is not match price to all purchases but for only one product in a day, depends on the price and popularity of product. 

###### Rules:

- Users have to submit name, product name and price to application and at end of each day there will be one top product  with lowest price will be selected.
- All the words are strings of size from 1 to 20 characters
- Name of people may coincide.
- At the end of given time 
  - Display top product (only one) with name and price.
  - Display name of other people bought same device along with eligible cash back amount (different between their purchase and lowest price).
  - Do not display if the difference is 0.

|Sample Input|Sample Output|
|------------|-------------|
|John <br/> iPhone6 <br/> 625 <br/> Tim <br/> GalaxyS7 <br/> 685 <br/> Norman <br/> iPhone6 <br/> 618 <br/> Alex <br/> GalaxyS7 <br/> 700 <br/> Sam <br/> iPhone6 <br/> 610 <br/>||

##### Sample Input

John

iPhone6

625

Tim

GalaxyS7

685

Norman

iPhone6

618

Alex

GalaxyS7

700

Sam

iPhone6

610

##### Sample Output

iPhone6 610

John – 15

Norman – 8 

### Problem 3: Help with Time Table

Smith needs some help in preparing a timetable for the school. Apart from the school he is also a part-time employee of a nearby art gallery. So having a proper time table is very critical for him.  Smith has received number of courses, day of the week and number of lesson from school. He want to create a table with these details.

###### Rules:

- The application need to accept 3 different data. 
  - An integer represents total number of courses that Smith going to attend.
  - Course name - The name of the course may consist of up to five words, which are divided by exactly one space (there are no spaces before the first word and after the last one). The words consist of capital and lowercase Latin letters. The length of every word is within the range from 1 to10.
  - Course description - Description contains the day of week and the number of a lesson, when it takes place. The day of week may take one of the three values: “Monday”, “Wednesday”or “Saturday”. The number of a lesson is an integer from 1 to 5. 
- The resultant table should be size 4×3
  - Columns of the table should correspond to the three academic days
  - Rows should correspond to the four classes. 
  - Width of each column should be equal to 10 characters. 
  - Height of the row of the table equals to the height of the highest of its cells. 
  - If all the cells in the row are empty then the height of the row should be equal 1 character. I
  - f some word doesn’t find room in the current line, it should be placed in the next line. 
  - The text in the cell should be aligned to top and left borders. Make the table itself using characters “-” 

##### Sample Input

 9

Physics

Wednesday 3

Maths

Monday 1

Chemistry

Wednesday 1

Physical education

Saturday 2

Astronomy

Saturday 4

Urban geography

Monday 4

History

Saturday 1

Modeling

Wednesday 2

Biology

Wednesday 4

##### Sample Output

![Answer](https://raw.githubusercontent.com/codensolve/solve-this/master/answer.png)
