<html>
    <head>
        <style>
            body{
                margin-top: 20px;
                background-color:white;
            }
            li{
                font-size: 15px;
                color: black;
                font-family: sans-serif;
            }
            h1{
                font-size: 25px;
                color: black;
            }
            .objectImage {
    width: 1200px;
    height: 150px;
    object-fit: cover;
    object-position: center -140px;
}
        </style>
    </head>
    <body>
        <div class="imagem">
            <img class="objectImage" src="https://i.ibb.co/k1d1njH/rent-house-73089751-5bfc333346e0fb002602ddbe.jpg">
        </div>
        
        <h1>Lista 01 </h1>
        <ul>
            <li>Considere o banco <a href="https://www.dropbox.com/s/8auhk2zaogovjvn/houses_to_rent_v2.csv?dl=0">houses_to_rent_v2</a> que contém o valor (em reais) do aluguel de imóveis no Brasil. Você pode trabalhar apenas com os imóveis localizados em São Paulo, Rio de Janeiro e Belo Horizonte.</li>
        </ul>
        <ol start="1">
            <li>Divida o conjunto de dados em para treinamento e teste. Explique como decidiu qual porcentagem deixar
para cada um.</li>
            <li>Utilizando o conjunto de treinamento, ajuste uma regressão (i) via mı́nimos quadrados, (ii) via lasso (usando validação-cruzada no treinamento para escolher λ) e (iii) (Pós-graduação apenas) regressão ridge. Qual o melhor valor de λ encontrado para o lasso?</li>
            <li> Qual dos métodos acima apresentou melhores resultados? Responda essa pergunta utilizando o conjunto de teste e o melhor valor de λ encontrado. Inclua os intervalos de confiança para o risco preditivo nos seus resultados.</li>
            <li>Interprete os resultados do melhor modelo encontrado (via coeficientes). Ele faz sentido?</li>
            <li>Includa todas as interações entre as variáveis observadas e repita o ajuste do método de mı́nimos quadrados e o lasso. Como esses ajustes se comparam em relação aos anteriores? Qual foi o melhor modelo encontrado?Esses resultados são esperados?</li>
        </ol>
    </body>
</html>

