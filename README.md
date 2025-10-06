# Ex.06 Book Front Cover Page Design
# Date:06/10/2007
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover</title>
<style>
    body {
        margin: 0;
        font-family: 'Courier New', monospace;
        background: linear-gradient(135deg, #faf8f8, #ebeeeb, #ececed);
        color: white;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .cover {
        width: 420px;
        height: 600px;
        background: linear-gradient(135deg, #fd0505, #4206f5);
        box-shadow: 0 0 15px rgba(0,0,0,0.3);
        padding: 30px;
        box-sizing: border-box;
        position: relative;
    }

    .top {
        font-size: 14px;
        font-weight: bold;
        border-bottom: 2px solid rgba(255,255,255,0.5);
        padding-bottom: 5px;
        margin-bottom: 40px;
    }

    .title {
        font-size: 28px;
        font-weight: bold;
        line-height: 1.4em;
        text-align: center;
        margin-bottom: 10px;
    }

    .subtitle {
        font-size: 16px;
        text-align: center;
        font-family: Arial, sans-serif;
        color: #f0f0f0;
        margin-bottom: 60px;
    }

    .bottom-section {
        position: absolute;
        bottom: 30px;
        left: 30px;
        right: 30px;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
    }

    .author {
        font-size: 16px;
        font-weight: bold;
    }

    .edition {
        position: absolute;
        bottom: 130px;
        left: 30px;
        font-size: 16px;
        font-weight: bold;
        color: black;
        background-color: rgba(255,255,255,0.8);
        padding: 3px 10px;
        border-radius: 3px;
    }

    .photo {
        width: 100px;
        height: 120px;
        border: 2px solid #fff;
        object-fit: cover;
    }

</style>
</head>
<body>

<div class="cover">
    <div class="top">SEC INSIGHT</div>
    <div class="title">
        Web Development:<br>
        The Complete Reference
    </div>
    <div class="subtitle">with Django and Bootstrap Insights</div>
    
    <div class="edition">Extended Edition</div>
    
    <div class="bottom-section">
        <div class="author">Dr. v . balaji</div>
        <img src="img.jpg" alt="Author Photo" class="photo">
    </div>
</div>

</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-10-06 223200.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
