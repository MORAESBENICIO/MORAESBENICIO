<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartão de Visita - Benicio Morais</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .card {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 400px;
            position: relative;
        }
        .profile-pic {
            position: absolute;
            top: -60px;
            left: 20px;
            border-radius: 50%;
            width: 100px;
            height: 100px;
            object-fit: cover;
            border: 3px solid #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #007BFF;
        }
        h2 {
            font-size: 18px;
            margin-bottom: 20px;
            color: #555;
        }
        p {
            margin: 10px 0;
            font-size: 16px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        .social-links a {
            margin: 0 10px;
            font-size: 20px;
            color: #333;
        }
        .social-links a:hover {
            color: #007BFF;
        }
    </style>
</head>
<body>
    <div class="card">
        <!-- Foto de Perfil -->
        <img src="images/perfil.jpg" alt="Foto de Benicio Morais" class="profile-pic">

        <h1>Benicio Matheus do Nascimento Morais</h1>
        <h2>Advogado | OAB/PA 36.480</h2>
        <p>Brasileiro, solteiro, advogado especializado em Direito Trabalhista e Cível.</p>
        <p><strong>Endereço:</strong> Travessa Treze de Maio, nº 366-B, Bairro Centro, Itaituba-PA, CEP: 68180-635</p>
        <p><strong>Telefone:</strong> (86) 98160-3985</p>
        <p><strong>Email:</strong> <a href="mailto:moraesbenicioadv@gmail.com">moraesbenicioadv@gmail.com</a></p>
        <div class="social-links">
            <a href="https://wa.me/5586981603985" target="_blank">WhatsApp</a> | 
            <a href="https://www.instagram.com/moraesbenicio.adv/" target="_blank">Instagram</a>
        </div>
    </div>
</body>
</html>

