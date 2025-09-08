# TUGAS-3-PWEB-A-BRILIAN
Tugas 3 : Membuat Form, Table, dan Frames dengan HTML

### Identitas  
- **Nama** : Brilian Kurniawan Prasisto  
- **NRP**  : 5025241213  
- **Mata Kuliah** : Pemrograman Web

---
## Tujuan  
Tugas ini bertujuan untuk membuat table, form, dan frames dengan menggunakan HTML.  
---
## Hasil Implementasi
1.**Tabel**
 - Menampilkan Tabel Daftar Nilai Mahasiswa yang berisi Nomor, NPM, Nama, serta Nilai UTS & UAS.
  ![Tampilan Tabel](Identitas.png)

  Kode : 
  ```html
   <body>
  <table border="1"bgcolor="white"align="center">
    <caption align="top">
        <b>Tabel Daftar Nilai Mahasiswa</b></caption>
    <tr bgcolor="gray"><th rowspan="2">No</th>
    <th rowspan="2">NPM</th><th rowspan="2">Nama</th><th colspan="2">Nilai</th>    
    </tr>
    <tr bgcolor=""gray><th>UTS</th><th>UAS</th>
    <tr><td align="center"width="20">1.</td>  
    <td align="left" valign="middle"width="80"height="40">06.100.001</td>
    <td align="left" valign="middle"width="180"height="40">Amin A.Angkasa</td>
    <td align="center"valign="middle">70</td><td align="center"valign="middle">80</td>
    </tr>
    <tr><td width="20">2.</td>
    <td align="left"valign="middle"width="80"height="40">06.100.002</td>
    <td align="left" valign="middle"width="180"height="40">Beni B.Bernardi</td>
    <td align="center"valign="middle">70</td><td align="center" valign="middle">80</td>
    </tr>
</table>
```

2.**Form**
 - Menampilkan Form yang berisi First Name, Last Name, Email, Password, Re-Type Password, Contact, dan juga Gender. Selain itu, juga tertera tombol input type berupa "Submit".
  ![Tampilan Tabel](Identitas.png)

  Kode :
  ```html
<h2 align="center">Registration Form</h2>
<form align="center" action="">
    <label for="first">First Name:</label><br>
    <input type="text" id="first" name="first"required /><br>

    <label for="last">Last Name:</label><br>
    <input type="text" id="last" name="last" required /><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required /><br>

    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required /><br>

    <label for="repassword">Re-Type Password:</label><br>
    <input type="password" id="repassword" name="repassword" required /><br>

    <label for="mobile">Contact:</label><br>
    <input type="text" id="mobile" name="mobile" maxlength="10" required/><br>

    <label for="gender">Gender:</label><br>
    <select id="gender" name="gender" required>
        <option value="male">
            Male
        </option>
        <option value="female">
            Female
        </option>
        <option value="other">
            Other
        </option>
    </select><br><br>

    <button type="submit">
        Submit
    </button><br>
</form>
```

3. **Frames**
 - Menampilkan Frames yang menggabungkan antara HTML dan CSS.
  ![Tampilan Tabel](Identitas.png)

  Kode : 
  ```html
<!DOCTYPE html>
<html>
<head>
    <title>Layout Website</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div class="wrap">
        <div class="header">
            <h1 align="center">Header</h1>
        </div>

        <div class="menu">
            <h2 align="center">Menu Navigasi</h2>
        </div>

        <div class="badan">
            <div class="sidebar">
                <h1 align="center">Sidebar</h1>
            </div>

            <div class="content">
                <h1 align="center">Content</h1>
            </div>
        </div>

        <div class="footer">
            <h1 align="center">footer</h1>
        </div>
    </div>
</body>
</html>
```

  ```css
.wrap {
    background: white; 
    width: 900px;
    margin: 10px auto;
}

.wrap .header {
    background: #42a5f5;
    padding: 15px;
    text-align: center;
    font-size: 24px;
    font-weight: bold;
}

.wrap .menu {
    background: #42a5f5;
    text-align: center;
    padding: 10px;
    margin-top: 5px;
}

.badan {
    display: flex;
    height: 450px;
    margin-top: 5px;
}

.wrap .badan .sidebar {
    background: #42a5f5;
    width: 25%;
    padding: 20px;
    box-sizing: border-box;
}

.wrap .badan .content {
    background: #42a5f5;
    width: 75%;
    padding: 20px;
    margin-left: 5px;
    box-sizing: border-box;
}

.wrap .footer {
    background: #42a5f5;
    text-align: center;
    padding: 10px;
    margin-top: 5px;
}
```
   
