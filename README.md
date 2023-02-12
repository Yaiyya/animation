# animation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animaciones y transiciones en css</title>
    <link rel="stylesheet" href="../css/ejercicioanimaciones.css">
</head>
<body>
    <button class="btn-modern">Button
    </button>
</body>
</html>
body {
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height:100vh ;
}
.btn-modern {
    position: relative;
    padding: 5px 20px;
    border-radius: 5rem;
    color: black;  
background-color:pink;
cursor: pointer;
}

.btn-modern:hover {
    background-color: burlywood;
    color: white;
    box-shadow: inset 20%;
    
    
}

.tooltip::before {
    content: '';
    border: solid 10px transparent;
    border-top-color: #f5f5;
    
}

.btn-modern:hover {
    animation-duration: 5s;
    translate: -5px;
    transform: translateY(50%);
        background-color: blueviolet; 
}
