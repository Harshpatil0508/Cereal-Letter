# Cereal Letter
<a href="https://freeimage.host/i/HoICctS"><img src="https://iili.io/HoICctS.md.jpg" alt="HoICctS.md.jpg" border="0" width="300"></a>
<br>
A daily letter composed of jokes, news, a deep quote and some good song suggestions.
<br>
<br>
### Motivation

Motivation behind this project was to understand how the ETL pipelines work and learn how frameworks such as airflow and argo are used
<br>
<br>
### Stack

airflow, mongodb, postgres, docker
<br>
<br>
### Working
<br>
<a href="https://freeimage.host/i/HoIC0o7"><img src="https://iili.io/HoIC0o7.md.jpg" alt="HoIC0o7.md.jpg" border="0"></a>
<br>
Our airflow DAG looks something like this

first we fetch the information from various open apis

we later combine this info together, and save the json data inside mongodb for safekeeping

and we generate the pdf using that same data, and send it to the user at the scheduled time

<a href="https://freeimage.host/i/HoIC1V9"><img src="https://iili.io/HoIC1V9.md.jpg" alt="HoIC1V9.md.jpg" border="0"></a>
<br>
<br>
### Pdfs

pdfs get stored in the /temp folder
<br>
<br>
### Env

to enable emails, you will need to configure your [sendgrid.com](http://sendgrid.com) account.

after setting it up, add the email and the api key in the .env file

then the email operator should succeed
<br>
<br>
### Future scope

Multiple users should be able to subscribe to the letter, and all receive letters customised with their own preferences
#   C e r e a l - L e t t e r 
 
 
