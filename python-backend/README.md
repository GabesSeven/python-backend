<h1 align="center">python-backend</h1>

<hr>

## 📋 Project description

<p align="justify">
  Basic scripts for requests and data manipulation in back-end running locally.<br>
</p>

<hr>


## 🖥️ Usability

<p align="justify">

<!--sec data-title="Prompt: OS X and Linux" data-id="OSX_Linux_prompt" data-collapse=true ces-->
  
  All files must be executed from the command: <br>
  
  $ python index.py

<!--endsec-->

</p> 

<h3>Folder "input Parameters to python API"</h3>

<p align="justify">
  <br>
  Executing the following URLs in the browser:<br>
  <br>
  <ul>
    <li>  
      <b>localhost:8882</b>, redirects to a standard html page.
    </li>
    <li>  
      <b>localhost:8882/animal</b>, redirects to the <b>"index.html"</b> page.
    </li>
    <li>  
      <b>localhost:8882/isEven?num=2</b>, redirects to an html page where it is checked if the value of the parameter passed in <b>"num"</b> is an integer or not.
    </li>
    <li>  
      <b>localhost:8882/students/name/id</b> redirects to an html page where the parameters <b>"name"</b> and <b>"id"</b> are displayed (respectively. through regular expressions [a-z]+ and [0-9]+) .
    </li>
  </ul>
</p>

<h3>Folder "dynamic POST and GET JSON HTTP APIs"</h3>

<p align="justify">
  <br>
  Executing the following URLs in the browser:<br>
  <br>
  <ul>
    <li>  
      <b>localhost:8882/list</b>, performs a GET HTTP request, displaying the strings of the text file <b>"list.txt"</b> in JSON on the web page.
    </li>
    <li>
      using POST requests with the JSON parameter {"message": "fruit_name"}, for example, with the <i>Postman</i> program (<a href='https://identity.getpostman.com/'>https ://identity.getpostman.com/</a>) you can insert a new string in the <b>"list.txt"</b> file.
    </li>
  </ul>
</p>


<hr>

## 📁 Project access

You can [access the project's source code](https://github.com/GabesSeven/python-backend/) or [download it](https://github.com/GabesSeven/python-backend/archive/refs/heads/main.zip).

<hr>

## ✔️ Techniques and technologies used

- ``Python``
- ``Postman``

<hr>

## 🧑‍💻 Developer

| [<img src="https://avatars.githubusercontent.com/u/37443722?v=4" width=115><br><sub>Gabriel Ferreira</sub>](https://github.com/GabesSeven)
| :---: 
