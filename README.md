# Ex.06 Book Front Cover Page Design
## Date: 13:12:2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
# Html Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <link rel="stylesheet" href="./bookcover.css">
</head>
<body>
    <div class="book-cover">
        <div class="expert-tag">Expert Insight</div>
        
        <div class="title-container">
            <h1 class="main-title">
                Responsive Web Design with HTML5 and CSS
            </h1>
            <p class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS techniques
            </p>
        </div>

        <div class="decorative-pattern"></div>

        <div class="bottom-container">
            <div class="edition">Third Edition</div>
            
            
                
                <div class="author-container">
                    <div class="author-name">BALASUBRAMANIAM </div>
                    <div class="author-image">
                        <img src="images/profile-min .jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```
# CSS code:
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #f0f0f0;
    padding: 20px;
}

.book-cover {
    width: 100%;
    max-width: 700px;
    min-height: 900px;
    margin: 2rem auto;
    background-color: #1a1a1a;
    padding: 3rem;
    position: relative;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

.expert-tag {
    color: #ffffff;
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 2.5rem;
    border-bottom: 2px solid #ff5722;
    display: inline-block;
    padding-bottom: 0.5rem;
    font-weight: 500;
}

.title-container {
    margin-bottom: 2rem;
    position: relative;
    z-index: 2;
}

.main-title {
    color: #ffffff;
    font-size: 3.8rem;
    font-weight: 700;
    line-height: 1.1;
    margin-bottom: 1.5rem;
    font-family: 'Segoe UI', Arial, sans-serif;
    letter-spacing: -0.5px;
}

.subtitle {
    color: #ffffff;
    font-size: 1.2rem;
    line-height: 1.5;
    margin-bottom: 2rem;
    max-width: 70%;
    opacity: 0.9;
    font-weight: 300;
}

.decorative-pattern {
    position: absolute;
    bottom: -100px;
    right: -50px;
    width: 70%;
    height: 500px;
    /* Placeholder for wave pattern */
    background: linear-gradient(45deg, 
        rgba(0,255,255,0.1) 0%,
        rgba(144,238,144,0.1) 100%);
    transform: rotate(-5deg);
    z-index: 1;
}

.bottom-container {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 2rem 3rem;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    z-index: 2;
}

.edition {
    color: #ff5722;
    font-size: 1.8rem;
    font-weight: 600;
    font-family: 'Segoe UI', Arial, sans-serif;
}

.right-content {
    display: flex;
    align-items: flex-end;
    gap: 2rem;
}

.publisher-logo {
    width: 120px;
    height: 40px;
    background-color: #ffffff;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 0.5rem;
}

.author-container {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.author-name {
    color: #ffffff;
    font-size: 1.5rem;
    font-weight: 500;
    text-align: right;
}

.author-image {
    width: 114px;
    height: 100px;
    border-radius: 50%;
    background-color: #444;
    overflow: hidden;
}

@media (max-width: 768px) {
    .book-cover {
        padding: 2rem;
        min-height: 800px;
    }

    .main-title {
        font-size: 2.8rem;
    }

    .subtitle {
        max-width: 100%;
    }

    .bottom-container {
        flex-direction: column;
        gap: 2rem;
        align-items: flex-start;
    }

    .right-content {
        flex-direction: column;
        align-items: flex-start;
        gap: 1rem;
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e155df53-7705-4ff2-9cfd-99d286492677)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
