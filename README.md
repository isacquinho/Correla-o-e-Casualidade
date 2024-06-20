![Capa](![image](https://github.com/isacquinho/Correla-o-e-Casualidade/assets/168225345/0f025003-1a5d-4a1f-bad1-997dee1d7e3e)
)
# CASUALIDADE E CORRELAÇÃO: ​QUAL A DIFERENÇA?

## O que é Casualidade?
Casualidade é quando uma coisa faz outra coisa acontecer. É como quando você joga uma pedra na água e ela faz ondas. A pedra causou as ondas.
Um exemplo de casualidade muito útil para o seu entendimento é, por exemplo, Se você estuda muito para uma prova e tira uma boa nota, o estudo causou a boa nota. Ou melhor, se você come muito doce e fica com dor de barriga, o doce causou a dor de barriga.

## O que é Correlação?
Correlação é quando duas coisas acontecem juntas, mas uma não causa a outra. É como se todas as vezes que você vê um arco-íris, você também vê uma borboleta, mas o arco-íris não causa a borboleta.
Então, por exemplo, imagine que sempre que você come sorvete, você vai ao parque. Comer sorvete e ir ao parque acontecem juntos, mas comer sorvete não faz você ir ao parque, nem o parque faz você comer sorvete.

## Como usar Casualidade e Correlação em linguagem de programação, como Python?
### Exemplo de causalidade: A entrada de dois números causa a soma deles
def soma(a, b):
    return a + b

resultado = soma(5, 3)
print(f"A soma de 5 e 3 é {resultado}")

### Exemplo de Correlação:
import pandas as pd

# Criando um DataFrame com duas variáveis
data = {
    'Horas_de_Estudo': [2, 3, 4, 5, 6],
    'Notas': [70, 80, 85, 90, 95]
}

df = pd.DataFrame(data)

### Calculando a correlação
correlacao = df['Horas_de_Estudo'].corr(df['Notas'])
print(f"A correlação entre horas de estudo e notas é {correlacao}")

#EstatísticaDivertida #CuriosidadesCientíficas #Programação
