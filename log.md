# 100 Days Of Code - Log

### Day 6: April 26, 2020

**Today's Progress**: Fixed FLASK APP YAY!!! Worked on Javascript exercises.

**Thoughts:** Found the bugs, big thanks to Stack Overflow and Flask Documentation !!!(***applause***). I currently have a working Flask App with Mongo DB Database and HTML/CSSS user interface. They bugs were so tiny and insignificant and yet they screwed up the whole project.  The first bug was a space between a bracket and modulus in one of the conditionals of the Flask app on the html template file.  The second was the absence of a period before the namespace in the template file. Today I also worked on Javascript Exercises, including more arrow functions, destructuring, object deconstruction, and spread function. 

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp), [Javascript Exercises](https://github.com/HajaSChilds/javascript_playground)

**Caught Bugs Below**

**Two Errors Preventing Jinja2 Engine From Pulling Data into the templates**

#1:
url_for('.index') – Missing the dot before the name             (Flask Documentation)


#2:
Typo, in the second for-loop – extra space before the %         (Stack Overflow) 
{   % for post in posts %}

The Reason: Since there is space after { before % Jinja will not recognize it as an endfor tag. thus giving you the error.



### Day 5: April 25, 2020

**Today's Progress**: Worked on Javascript Exercises and debugging Flask App

**Thoughts:** Worked on Javascript Exercises, including arrow functions, destructuring and object deconstruction. Printed out error logs for Flask app, there were 17 errors listed, one that included Jinja2. Started going through each one - googling and checking code.  Hopefully this process works!

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp), [Javascript Exercises](https://github.com/HajaSChilds/javascript_playground)


### Day 4: April 24, 2020

**Today's Progress**: Worked on Flask App, HTML, Mongo DB and Javascript Practice 

**Thoughts:** Haven't figured it out yet, why the data is not being pulled into the HTML templates. Now going through the code with a fine tooth comb.  I should have known that trying to figure out issues at this point would be a nightmare. I needed to test it sooner instead of building so much and trying to figure it out later.  That was never going to work, of course. I will give a few more days then scrap it and start from scratch and debug properly.

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp)


### Day 3: April 23, 2020

**Today's Progress**: Worked on Flask App, HTML, Mongo DB and more Javascript review

**Thoughts:** Worked on the HTML part of the Flask app.  For some reason the Jinja2 engine is not pulling data into the HTML templates although the Flask app is running. I have to troubleshoot that. On another note, I realize how rare it is for me to use table in my html documents.  I read somewhere that prior to modern css - flexbox and grid - developers would use TABLE to layout and position elements. Yikes!  As much as I have been tortured by flexbox and css-grid I would not have made it typing out all those tr's and td's!!

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp)


### Day 2: April 22, 2020

**Today's Progress**: Worked on Flask App, HTML, a small Javascript review, and some Python exercises

**Thoughts:** The HTML part of the Flask app continues to go well. I'm excited to see it all coming together.  I reviewed Python exercises and briefly saw some of the differences between Python 2 and Python 3.  I definitely like Python 3 better so far. Just working on Javascript after spending a few weeks on Python I was forgetting all of the semicolons and yet things were still running...

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp), [Python Playground Exercises](https://github.com/HajaSChilds/python_playground), [Javascript Playground Exercises](https://github.com/HajaSChilds/javascript_playground) 


### Day 1: April 21, 2020

**Today's Progress**: Worked on Flask App, HTML and also a small Javascript challenge

**Thoughts:** The HTML part of the flask app went really well. I practiced using the Emmet abbreviations in VS Code, made everything super snappy.  The Javascript challenge was also fun.  I was able to see that it took me six lines of code to solve a simple challenge and the solution only needed one line of code plus a one line error built in.  Well at least I came up with a solution that worked. Student - 0 Instructor - 1  I realize I need to spend time understanding arrow functions in Javascript

**Link(s) to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp) and [Javascript Trim Array Challenge](https://github.com/HajaSChilds/javascript_playground/blob/master/trim.js)

### Day 0: April 20, 2020

**Today's Progress**: Worked on Flask App with MongoDB, HTML and CSS

**Thoughts:** It was super fun. Opening the python virtual environment, installing all the python modules, creating the Flask app with the routes for Mongo DB, which I just binge learned the week before (watching every video tutorial imaginable). Plus I spent 4 days pulling my hair out, and my computer literally threatened to report me, while trying to get MongoDB to actually run on the non-admin account on my computer.

**Link to work:** [Flask With MongoDB Task App](https://github.com/HajaSChilds/FlaskWithMongoTaskApp)




