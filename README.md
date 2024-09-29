<html></html>
 <head>
  <title>
   Profil Pribadi
  </title>
  <style>
   body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 24px;
            font-weight: bold;
        }
        h2 {
            font-size: 20px;
            font-weight: bold;
        }
        .container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .profile-pic, .video {
            margin: 0 10px;
        }
        .profile-pic img {
            width: 200px;
            height: 200px;
            background-color: #ccc;
            display: block;
            margin: 0 auto;
        }
        .profile-pic p {
            margin-top: 10px;
        }
        .video iframe {
            width: 300px;
            height: 200px;
        }
        .section {
            margin-top: 30px;
        }
        .skills-table {
            margin: 0 auto;
            margin-top: 10px;
            border-collapse: collapse;
        }
        .skills-table th, .skills-table td {
            border: 1px solid #000;
            padding: 5px 10px;
        }
        .contact-form {
            margin-top: 20px;
        }
        .contact-form input, .contact-form textarea {
            display: block;
            margin: 10px auto;
            padding: 5px;
            width: 200px;
        }
        .contact-form button {
            padding: 5px 10px;
        }
        .social-links {
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #0000EE;
        }
        .footer {
            margin-top: 30px;
            font-size: 14px;
        }
  </style>
 </head>
 <body>
  <h1>
   Profil Pribadi
  </h1>
  <div class="container">
   <div class="profile-pic">
    <img alt="Foto Profil" height="200" src="hita.JPG" width="200"/>
    <p>
     Foto Profil
    </p>
   </div>
   <div class="video">
    <iframe allowfullscreen="" frameborder="0" src="pop.mp4">
    </iframe>
    <p>
     Video Perkenalan
    </p>
   </div>
  </div>
  <div class="section">
   <h2>
    Tentang Saya
   </h2>
   <p>
    Halo! Saya adalah seorang pengembang web antusias dengan passion di bidang teknologi dan desain kreatif.
   </p>
  </div>
  <div class="section">
   <h2>
    Keterampilan
   </h2>
   <table class="skills-table">
    <tr>
     <th>
      Keterampilan
     </th>
     <th>
      Tingkat
     </th>
    </tr>
    <tr>
     <td>
      HTML/CSS
     </td>
     <td>
      Mahir
     </td>
    </tr>
    <tr>
     <td>
      JavaScript
     </td>
     <td>
      Menengah
     </td>
    </tr>
    <tr>
     <td>
      Python
     </td>
     <td>
      Pemula
     </td>
    </tr>
   </table>
  </div>
  <div class="section">
   <h2>
    Hubungi Saya
   </h2>
   <form class="contact-form">
    <input name="name" placeholder="Nama" type="text"/>
    <input name="email" placeholder="Email" type="email"/>
    <textarea name="message" placeholder="Pesan"></textarea>
    <button type="submit">
     Kirim Pesan
    </button>
   </form>
  </div>
  <div class="section">
   <h2>
    Media Sosial:
   </h2>
   <div class="social-links">
    <a href="#">
     LinkedIn
    </a>
    |
    <a href="#">
     GitHub
    </a>
    |
    <a href="#">
     Twitter
    </a>
   </div>
  </div>
  <div class="footer">
   <p>
    Semoga Selalu diberi kemudahan^^
   </p>
  </div>
 </body>
</html>
