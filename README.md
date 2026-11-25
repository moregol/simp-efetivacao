# Protótipo Foguete
O Repositorio contem todos os arquivos utilizados para a criação de um foguete de apogeu de 3km utilizando o enviroment da IREC 2026, juntamente com seus dados metereologicos. 

# Motor
O motor foi gerado pelo openMotor idealizado a partir de um impulso total de 9500 Ns, a partir disso foi definida uma fuselagem e sua recuperação.

# Imagem do foguete
![OpenRocket 3D](https://github.com/moregol/simp-efetivacao/blob/main/rocketIm/ff1da9fd-91b2-43cd-9bf0-4138a71422f6.jpg)

# Resultados
Pelo RocketPy obtive um erro total de 10% em relação ao apogeu do OpenRocket(3073m), ou seja, no RocketPy obti um valor de 3500 metros de apogeu, valor nao desejado.

A causa nao foi diretamente encontrada, entretanto, creio que tenha sido por conta das condições metereologicas em que utilizei o RocketPy e as informações de um balão da região da IREC de 2026.

Além disso, a curva de arrasto do RASAero foi outro fator, sendo ela bem diferente do OpenRocket, causando essa diferença total de 2500 metros.
