# Ex-07-CSS:
```
Name: P.KEERTHANA
Ref.no: 23011895
```

# Ex-7(i):

# AIM:

Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)

# STEPS:

Step1:
Meet the requirements for the default mode or light mode

Step2:
Choose a device which is smaller in size of mobilephone of 600px and meet the prefered requirements

Step3:
Meet the requirements for the prefered darker mode

# CODE :

css.html:
 ```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="1.css">
</head>
<body>
 Saveetha Engineering College
 <br>
 <a href="https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS.git">GITHUB</a> 
 <br>
 <a href="http://www.myntra.com/mailers/skin-care/foxtale/foxtale-the-diva-overnight-glow-face-mask-with-aha-&-pha---30-ml/21887068/buy"> MYNTRA LINK</a>  
</body>
</html>
```

1.css :
```
html {
    font-size: 50px;
    color: #333;
    background-color: #f4f4f4;
}

a {
    color: #007bff;
}
@media (max-width: 600px) {
            html {
                background-color: #333;
                color: #f4f4f4;
                a {
                    color: #28a745;
            }
            }
        
        }

@media (prefers-color-scheme: dark) {
    html {
        font-size: 50px;
        background: #333;
        color: white;
    }
 a {
        color: #17a2b8; 
 }
}

footer {
    font-size: x-large;
}
```

# Output(i):

light mode:

![1 css](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/05013c4f-2481-49e4-8ea4-0923a83d7fc1)

Dark mode:

![1 csss](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/cbd6e019-0205-407c-8b41-5b47743f6cfa)

Smaller screen:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/c0c759b6-947c-41ec-bc73-8765219a8b18)

# Ex-7(ii):

# AIM:
To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.

# STEPS :

Step 1:
Start a html project

Step 2:
Create a css file in the same folder in which html file is created

Step 3:
inside html code give href link of the css code

Step 4:
meet the requirements given in the question

Step 5:
run the program with prefered screen width


# CODE :
2.css :

```
html {
    font-size: 50px;
    color: #333;
    background-color: red;
}

a {
    color: #007bff;
}
@media (max-width: 600px) {
            html {
                background-color: blue;
                color: #f4f4f4;
                a {
                    color: #28a745;
            }
            }
        
        }
```
# OUTPUT :

default:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/2ae1182a-9a02-4b07-892e-5adac6ee6c59)

max screen width of 600px:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/e2a31a44-3ceb-4b32-90c5-5ecf74b79148)

# Ex-7(iii):

# AIM:

Explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

#  STEPS :

Step1:
start a html project

Step 2:
create a css file in the same folder in which file is created,give the href link in the html code

Step3:
Define a CSS media query for each orientation. The syntax for a media query is @media (orientation: value), where value can be either portrait or landscape.

Step 4:
You can change background color of it

Step4:
Run the html program


# CODE :
3.css :

```
@media (orientation: potrait) {
    html {
        background-color: pink;
        color: white;
        
    }
    a {
        color: red;
}

}
@media (orientation: landscape) {
    html {
        color: #28a745;
        background-color: pink;

        a {
        color: green;
   }
    }

}
```
# OUTPUT :

landscape:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/98fb107d-ef38-405f-9461-d8c1bbf8e59e)

potrait:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/fc20a645-6a74-4824-b24f-80f3c129113d)

# Ex-7(iv):
# AIM:
To describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.

# STEPS :
Step1:
start a html project

Step 2:
create a css file in the same folder in which file is created,give the href link in html code

Step 3:
give different font sizes for different screen sizes accordingly

Step4:
adjusting different colors for different screen width

Step5:
Run the html program

# CODE :
4.css :

```
html {
    font-size: 20px;
    color: yellow;
    background-color: orange;
}

a {
    color: yellow;
}
.non-essential {
    display: none;
    }
@media (min-width: 600px) {
            html {
                font-size: 50px;
                background-color: blueviolet;
                color: #f4f4f4;
                a {
                    color: #28a745;
                    
                        
            }
            }
           
        
        }
@media (min-width: 800px) {
            html {
                font-size: 80px;
                background-color: pink;
                color: #f4f4f4;
                a {
                    color: #28a745;
                    
                        
            }
            }
           
        
        }
```

# OUTPUT :

min-width=800px:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/e1ba7bd2-201e-4f4c-8c23-8e68aa622263)

max-width=600px:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/6d1e7113-4f28-4162-9c26-dd84718e9821)

default:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/05960ec8-af47-4e1a-806f-88d21f30442c)

# Ex-7(v):
# AIM:
Media queries can be used to provide print-friendly styles for web pages. How would you use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements Provide a CSS example.

# STEPS :
Step1:
start a html project

Step 2:
create a css file in the same folder in which file is created,give href link in html program

Step3:
after creating a css file give Inside each media query block, adjust the styles for the identified elements. You can change the background to white and hide non-essential elements.

Step4:
test the html file

Step5:
run the html program

# CODE :
5.css :

```
html {
    font-size: 50px;
    color: #333;
    background-color: #f4f4f4;
}

a {
    color: #007bff;
}
@media print {
            html {
                font-size: 20px;
                background-color: #333;
                color: #f4f4f4;
                a {
                    color: #28a745;
                    .non-essential {
                        display: none;
                    }
            }
            }
        
        }
```
# OUTPUT :

default:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/44486df1-0937-4fc6-87ab-7e622bf4d737)

non essential:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/91ec0004-3d94-4ad6-9608-c79183cf76cc)

# Ex-7(vi):

# AIM:

With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.

# STEPS :

Step1:
start a html project

Step 2:
create a css file in the same folder in which file is created,give href link in html program

Step 3:
using media queries set the preference to dark mode and night mode

Step 4:
change the background color and font color to different

Step 5:
run the html program

# CODE :
6.css :

```
html {
    font-size: 50px;
    color: #333;
    background-color: #f4f4f4;
}

a {
    color: #007bff;
}


@media (prefers-color-scheme: dark) {
    html {
        font-size: 50px;
        background: #333;
        color: orange;
    }
 a {
        color: #17a2b8;
 }
}
```

# OUTPUT :

lightmode:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/026a1cdc-da7f-406b-8b5b-890a0806e205)

darkmode:

![image](https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS/assets/145743072/a062ba68-143e-4cef-b6de-51c30ccc7ac9)














