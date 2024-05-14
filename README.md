# Ex.07 Software Product Company Website
## Date: 06.05.2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
### index.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AMSS | Home Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
<link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="assets/css/images/AM.png" style="width: 100%;">
        </div>
        <div class="col-5" style="margin-top: 65px;">
            <a href="index.html">Home</a>
            <a href="people.html">People</a>
            <a href="product.html">Products</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="col-3" style="margin-top: 65px;">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-twitter"></i>
            <i class="bi bi-instagram"></i>
        </div>
    </div>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-10">
          
          <img src="assets/css/images/OIG2.jpeg" alt="" width="100%">
        </div>
        <div class="col-1"></div>
    </div>
    
</body>
</html>

### Product.html:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="assets/css/images/AM.png" style="width: 100%;">
        </div>
        <div class="col-5" style="margin-top: 65px;">
            <a href="index.html">Home</a>
            <a href="people.html">People</a>
            <a href="product.html">Products</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="col-3" style="margin-top: 65px;">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-twitter"></i>
            <i class="bi bi-instagram"></i>
        </div>
    </div>
    <div class="row2" style="margin-top: 20px;">
        <div class="col-1"></div>
        <div class="col-3" id="main">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/download (3).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Customized wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/download (4).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Kids wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (1).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Denim wears</p>
                </div>
            </div>
        </div>
        <div class="col-1"></div>
    </div>
    <div class="row3">
        <div class="col-1"></div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (2).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Casual wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (3).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Daily wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (4).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Unisex wears</p>
                </div>
            </div>
        </div>
        <div class="col-1"></div>
    </div>
</body>

</html>

### people.html:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="assets/css/images/AM.png" style="width: 100%;">
        </div>
        <div class="col-5" style="margin-top: 65px;">
            <a href="index.html">Home</a>
            <a href="people.html">People</a>
            <a href="product.html">Products</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="col-3" style="margin-top: 65px;">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-twitter"></i>
            <i class="bi bi-instagram"></i>
        </div>
    </div>
    <div class="people">
        <div class="name">
            <div>
                <img src="assets/css/images/MD.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Mr. Manivannan T G</h3>
                <h4>Managing Director</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
        <div class="name">
            <div>
                <img src="assets/css/images/ad.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Mrs.Manjula</h3>
                <h4>Associate Dean</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
        </div>
        <div class="people">
        <div class="name">
            <div>
                <img src="assets/css/images/designer.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Ms. Shas</h3>
                <h4>Fashion Designer</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
        <div class="name">
            <div>
                <img src="assets/css/images/sales.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Ms. Caterine</h3>
                <h4>Sales Person</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
    </div>
    <div class="people">
        <div class="name">
            <div>
                <img src="assets/css/images/exe.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Mr. Raj</h3>
                <h4>Executive Officer</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
        <div class="name">
            <div>
                <img src="assets/css/images/sales 1.jpeg" alt="">
            </div>
            <div style="margin-left: 50px;">
                <h3>Mr. Hem</h3>
                <h4>Sales Person</h4>
                <h5>Fashion Studio</h5>
            </div>           
        </div>
    </div>
</body>

### contact.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AMSS | Home Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
<link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="assets/css/images/AM.png" style="width: 100%;">
        </div>
        <div class="col-5" style="margin-top: 65px;">
            <a href="index.html">Home</a>
            <a href="people.html">People</a>
            <a href="product.html">Products</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="col-3" style="margin-top: 65px;">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-twitter"></i>
            <i class="bi bi-instagram"></i>
        </div>
    </div>
    <div class="contact">
        <div>
            <p><i class="bi bi-telephone-fill"></i>9874563210</p>
            <p><i class="bi bi-envelope-at-fill"></i>amfashionstudio@gmail.com</p>
            <p><i class="bi bi-buildings-fill"></i>No.225 ,Fashion Studio ,3rd Avenue Street ,Anna Nagar West ,Chennai</p>
            <p><i class="bi bi-alarm-fill"></i>10am to 10pm</p>
            <p><i class="bi bi-calendar-date-fill"></i>All working days</p>
        </div>
    </div>
</body>



## OUTPUT:
### index.html:
![image](https://github.com/Aishwarya-TM/Web-Ex-7/assets/127846109/6c2cb904-79ea-46fa-98bd-732116d688be)

### product.html:
![image](https://github.com/Aishwarya-TM/Web-Ex-7/assets/127846109/9a64dfd0-d8de-47d7-8c6a-d017cc41b643)

### people.html:
![image](https://github.com/Aishwarya-TM/Web-Ex-7/assets/127846109/71ed79af-1d6f-400b-8e84-99577c9e96e1)

### contact.html:
![image](https://github.com/Aishwarya-TM/Web-Ex-7/assets/127846109/91b21740-f794-451f-848b-666781e27e28)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully
