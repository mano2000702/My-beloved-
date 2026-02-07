# My-beloved-

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Love ❤️</title>
<style>
    body {
        background: linear-gradient(to right, #ffdde1, #ee9ca7);
        font-family: Arial, sans-serif;
        text-align: center;
        padding: 30px;
        color: #333;
    }
    .card {
        background: white;
        padding: 25px;
        border-radius: 15px;
        box-shadow: 0 0 20px rgba(0,0,0,0.2);
        max-width: 700px;
        margin: auto;
    }
    h1 { color: #e91e63; }

    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 10px;
        margin: 20px 0;
    }
    .gallery img {
        width: 100%;
        border-radius: 12px;
        box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    button {
        padding: 12px 25px;
        font-size: 18px;
        background-color: #e91e63;
        color: white;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        margin-top: 15px;
    }
</style>
<script>
function showMessage() {
    document.getElementById("hidden").style.display = "block";
}
</script>
</head>
<body>

<div class="card">
    <h1>Hello My Beautiful ❤️</h1>

    <p>Every picture here holds a memory I never want to forget.</p>

    <div class="gallery">
        <img src="photo1.jpg" alt="Our Memory 1">
        <img src="photo2.jpg" alt="Our Memory 2">
        <img src="photo3.jpg" alt="Our Memory 3">
    </div>

    <p>You are my smile, my peace, my best friend, and my forever person.</p>

    <button onclick="showMessage()">Click here</button>

    <div id="hidden" style="display:none; margin-top:20px;">
        <h2>Will you be mine forever? 💍</h2>
        <p>I want to spend my whole life with you.</p>
        <h2>Will you marry me?</h2>
    </div>
</div>

</body>
</html>
