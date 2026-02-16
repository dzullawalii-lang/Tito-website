# Tito-website
Ada Deh
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Satria Banten</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;

    /* Background gambar */
    background: url("background.png") no-repeat center center fixed;
    background-size: cover;

    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Kotak tengah */
.container {
    background: rgba(0,0,0,0.6);
    padding: 40px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 0 25px rgba(255,0,0,0.7);
}

/* Tombol */
button {
    padding: 15px 35px;
    font-size: 18px;
    border: none;
    border-radius: 10px;
    background: red;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: gold;
    color: black;
    transform: scale(1.1);
}

/* Tulisan muncul */
#pesan {
    margin-top: 25px;
    font-size: 26px;
    color: yellow;
    opacity: 0;
    transition: 0.5s;
}

.show {
    opacity: 1 !important;
}
</style>
</head>

<body>

<div class="container">
    <button onclick="muncul()">PENCET SINI</button>
    <div id="pesan">tito gendut nih bos 😂</div>
</div>

<script>
function muncul() {
    document.getElementById("pesan").classList.add("show");
}
</script>

</body>
</html>
