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




# CODE :

css.html:

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="6.css">
</head>
<body>
 Saveetha Engineering College
 <br>
 <a href="https://github.com/keerthanapillaram/ODD2023-WT-Ex-07-CSS.git">GITHUB</a> 
 <br>
 <a href="http://www.myntra.com/mailers/skin-care/foxtale/foxtale-the-diva-overnight-glow-face-mask-with-aha-&-pha---30-ml/21887068/buy"> MYNTRA LINK</a>  
</body>
</html>

1.css :

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



# CODE :


