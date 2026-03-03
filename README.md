# Praktikum-Web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prak3</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1 class="title">Form Kehadiran Praktikan</h1>
    </header>
<div class="contaner">
    <div class="bg">
    <form id="form-kehadiran" method="post" target="_blank">
        <label for="Nama">Nama:</label>
        <br>
        <input type="text" placeholder="Masukan nama" id="inpt">
        <br><br>
        <label for="NPM">NPM:</label>
        <br>
        <input type="number" placeholder="Masukan NPM" id="inpt">
        <br><br>
        <label for="Kelas">Kelas:</label>
        <br>
        <select id="klswkt">
            <option selected disabled >pilih kelas</option>
            <option>Ilkom</option>
            <option>Sisfor</option>
        </select>
        <br><br>
        <label for="tanggal">Tanggal:</label>
        <br>
        <input type="date" id="tgl">
        <br><br>
        <label for="waktu">Waktu:</label>
        <br>
        <input type="time" id="klswkt">
        <br><br>
        <button type="submit" id="but-submit">Submit</button>

    </form>
    </div>
s</div>
</body>
</html>


body{
    font-family: Arial, sans-serif;
    font-weight: bold;
    background-color: azure;

}

#main-header{
    background-color: lightblue;
    padding: 5px;
    margin: 15px;
    border-radius: 20px;
}

.title{
    color:indigo;
    font-size: 24px;
    text-align: center;
}

#inpt{
    background-color: aliceblue;
    padding: 8px 50px;
}

#klswkt{
    background-color: aliceblue;
    padding: 8px 95px;
}

#tgl{
    background-color: aliceblue;
    padding: 8px 78px;
}

#but-submit{
    background-color: plum;
    color: white;
    margin: 60px;
    padding: 10px 50px;
    font-weight: bold;
    border-radius: 30px;
    cursor: pointer;
}

.bg{
    background: white;
    padding: 30px 50px;
    border-radius: 30px 40px;
    width: 400px;
    margin: 30px auto; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.container{
    display: flex;
    justify-content: center;
    width: 100%;
}

#form-kehadiran{
    padding: 20px 0;
}
