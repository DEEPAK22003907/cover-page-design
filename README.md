# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new project and a app for your project.Create templates for your web application to display image.
### Step 2:

Now write the appropiate html code and css code.
### Step 3:

Provide proper margins and padding to display it in proper way.
### Step 4:

Then create appropiate views for your templates and provide the urls for them in urls.py.Now run the server to use your web application and see the result.

## Code:
```
<!DOCTYPEhtml>
<html lang="en">
    <head>
        <meta name="viewport"
         content="width=device-width,initial-scale=1.0">
         <style>
         .bookpage{
             width:400px;
             height:600px;
             color:red;
             margin-left:auto;
             margin-right:auto;
             padding:20px;
             font-family:'Family Gothic Medium','Arial Narrow',Arial,sans-serif;
             background-image:url(/static/images/black.jpg);
             background-size:cover;
         }
         .insight{
             color:brown;
         }
         .hrstyle{
             width:100px;
         }
         .author{
             color:white;
             display:inline;
             position:relative;
             color:red;
             top:190px;
             font-family:Georgia;
             font-size:medium;
         }
         .booktitle{
             font-family:'Courier New',Courier,monospace;
             font-size:larger;
             text-align:center;
             position:relative;
             top:30px;
         }
         .id{
              width:400px;
              position:relative;
              top:180px;
         }
         .pub{
             font-size:medium;
             position:relative;
             top:155px;
             left:330px;
         }
         .ed{
             color:blue;
             font-size:medium;
             font-family:verdana;
             position:relative;
             top:85px;
         }
         .subtitle{
             font-family:Tahoma;
             font-size:large;
             position:relative;
             top:40px;
         }
         .mypic{
             position:relative;
             top:135px;
             left:260px;
             width:100px;
             height:100px;
             background-size:cover;
         }
         </style>  
         <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:red;">
            </div>
            <div class="title">\
                <h1>Fundamentals of Web Application Development</h1></div>
                <div class="subtitle">
                    HTML and CSS Combined with Django Architecture
                </div>
                <div class="mypic">
                    <img scr="/static/images/my.jpg"width="130"height="145"alt="">
                </div>
                <div class="id">
                    <hr style="color:orange;">
                    </div>
                    <div class="author">
                        <p><b>deepak</b></p>
                    </div>
                    <div class="pub">
                        SEC
                    </div>
                    <div class="ed">
                        <b>Seventh Edition</b>
                    </div>
        </div>
    </body>
</html>
```

## Output:
![output](./dee.png)

## Result:
Thus,a book cover has been successfully created using HTML and CSS.
