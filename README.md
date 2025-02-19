# Atualizando o arquivo index.html com imagens e melhor design
html_with_images = """<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CO2CrediCarbono - Créditos de Carbono</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 0; padding: 0; background-color: #f5f5f5; color: #333; }
        .header { background-image: url('https://source.unsplash.com/1600x900/?forest,carbon'); background-size: cover; padding: 50px 20px; color: white; }
        h1 { margin: 0; font-size: 2.5em; }
        .container { max-width: 900px; margin: auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); margin-top: -30px; position: relative; }
        .button { display: inline-block; padding: 10px 20px; margin: 20px; color: white; background-color: green; text-decoration: none; border-radius: 5px; }
        .section { text-align: left; margin-top: 20px; padding: 20px; display: flex; align-items: center; }
        .section img { width: 80px; margin-right: 20px; }
        .section h2 { color: green; margin: 0; }
        .footer { background: #333; color: white; padding: 20px; margin-top: 30px; }
    </style>
</head>
<body>
    <div class="header">
        <h1>CO2CrediCarbono</h1>
        <p>Transforme suas emissões em impacto positivo!</p>
        <a href="#" class="button">Saiba Mais</a>
    </div>

    <div class="container">
        <div class="section">
            <img src="https://cdn-icons-png.flaticon.com/512/2330/2330521.png" alt="Missão">
            <div>
                <h2>🌱 Nossa Missão</h2>
                <p>Facilitar a compensação de carbono utilizando tecnologia blockchain, garantindo transparência e acessibilidade para indivíduos e empresas.</p>
            </div>
        </div>

        <div class="section">
            <img src="https://cdn-icons-png.flaticon.com/512/2906/2906274.png" alt="Token CARBO">
            <div>
                <h2>🔹 O que é o Token CARBO?</h2>
                <p>O Token <b>CARBO</b> representa créditos de carbono certificados, permitindo que empresas e indivíduos compensem suas emissões de CO₂.</p>
            </div>
        </div>

        <div class="section">
            <img src="https://cdn-icons-png.flaticon.com/512/1086/1086477.png" alt="Como Comprar">
            <div>
                <h2>💰 Como Comprar?</h2>
                <p>1️⃣ Criar uma carteira MetaMask ou Trust Wallet</p>
                <p>2️⃣ Adquirir USDT ou BNB</p>
                <p>3️⃣ Trocar por <b>CARBO</b> na nossa plataforma</p>
            </div>
        </div>

        <div class="section">
            <img src="https://cdn-icons-png.flaticon.com/512/1828/1828640.png" alt="Certificação">
            <div>
                <h2>🔍 Transparência e Certificação</h2>
                <p>Nosso sistema garante que todos os créditos de carbono sejam verificados por instituições como <b>VERRA</b> e <b>Gold Standard</b>, e registrados na blockchain.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>📩 Contato: contato@co2credicarbono.com.br</p>
        <p>🌍 Redes sociais: LinkedIn | Instagram | Twitter</p>
    </div>
</body>
</html>
"""

# Criar o arquivo atualizado index.html com imagens
file_with_images_path = "/mnt/data/index.html"

with open(file_with_images_path, "w", encoding="utf-8") as file:
    file.write(html_with_images)

file_with_images_path
