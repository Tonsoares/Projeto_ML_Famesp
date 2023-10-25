# Projeto_ML_Famesp

## **Problema**
A água segura e prontamente disponível é **importante para a saúde pública**, seja para **beber**, para **uso doméstico**, **produção de alimentos** ou para fins recreativos. A melhoria do abastecimento de água e do saneamento e uma melhor gestão dos recursos hídricos podem **impulsionar o crescimento económico dos países** e contribuir grandemente para a redução da pobreza.

Água contaminada e saneamento precário estão ligados à transmissão de doenças como:
1. cólera
2. diarreia
3. disenteria
4. hepatite A
5. febre tifóide
6. poliomielite.
<br>

Serviços de água e saneamento ausentes, inadequados ou inadequadamente administrados expõem os indivíduos a **riscos de saúde evitáveis**. Este é particularmente o caso em estabelecimentos de saúde onde tanto os pacientes como os funcionários são colocados em risco adicional de infecção e doença quando faltam serviços de água, saneamento e higiene.

Globalmente, **15% dos pacientes desenvolvem uma infecção durante uma internação hospitalar**, com a proporção muito maior em países de baixa
renda **negrito**.

Então, vamos utlizar esse conjunto de dados de qualidade da água para entender o que é água potável segura e aplicar aprendizado de máquina para distinguir entre água potável e não potável.

## **Descrição das Features**

**ph**: pH de 1. água (0 a 14).

**Hardness**: Capacidade da água de precipitar sabão em mg/L.

**Solids**: Total de sólidos dissolvidos em ppm.

**Chloramines**: Quantidade de Cloraminas em ppm.

**Sulfate**: Quantidade de sulfatos dissolvidos em mg/L.

**Conductivity**: Condutividade elétrica da água em μS/cm.

**Organic_carbon**: Quantidade de carbono orgânico em ppm.

**Trihalomethanes**: Quantidade de Trihalometanos em μg/L.

**Turbidity**: Medida da propriedade de emissão de luz da água em NTU.

**Potability**: Indica se a água é segura para consumo humano. Potável - 1 e Não potável - 0

## **Descrição dos Dados**

1. Valor de pH:
O pH é um parâmetro importante na avaliação do equilíbrio ácido-base da água. É também o indicador da condição ácida ou alcalina do estado da água. A OMS recomendou o limite máximo permitido de pH de 6,5 a 8,5. Os intervalos de investigação atuais foram de 6,52 a 6,83, que estão na faixa dos padrões da OMS.

2. Dureza:
A dureza é causada principalmente por sais de cálcio e magnésio. Esses sais são dissolvidos a partir de depósitos geológicos através dos quais a água viaja. O período de tempo em que a água está em contato com o material produtor de dureza ajuda a determinar quanta dureza existe na água bruta. A dureza foi originalmente definida como a capacidade da água de precipitar sabão causada por cálcio e magnésio.

3. Sólidos (total de sólidos dissolvidos - TDS):
A água tem a capacidade de dissolver uma ampla gama de minerais ou sais inorgânicos e alguns orgânicos, como potássio, cálcio, sódio, bicarbonatos, cloretos, magnésio, sulfatos, etc. Esses minerais produziram sabor indesejado e cor diluída na aparência da água. Este é o parâmetro importante para o uso da água. A água com alto valor de TDS indica que a água é altamente mineralizada. O limite desejável para TDS é de 500 mg/le o limite máximo é de 1000 mg/l prescrito para beber.

4. Cloraminas:
Cloro e cloramina são os principais desinfetantes usados ​​em sistemas públicos de água. As cloraminas são mais comumente formadas quando a amônia é adicionada ao cloro para tratar a água potável. Níveis de cloro de até 4 miligramas por litro (mg/L ou 4 partes por milhão (ppm)) são considerados seguros na água potável.

5. Sulfato:
Os sulfatos são substâncias naturais encontradas em minerais, solo e rochas. Eles estão presentes no ar ambiente, águas subterrâneas, plantas e alimentos. O principal uso comercial do sulfato é na indústria química. A concentração de sulfato na água do mar é de cerca de 2.700 miligramas por litro (mg/L). Varia de 3 a 30 mg/L na maioria dos suprimentos de água doce, embora concentrações muito mais altas (1000 mg/L) sejam encontradas em algumas localizações geográficas.

6. Condutividade:
A água pura não é um bom condutor de corrente elétrica, mas um bom isolante. O aumento da concentração de íons aumenta a condutividade elétrica da água. Geralmente, a quantidade de sólidos dissolvidos na água determina a condutividade elétrica. A condutividade elétrica (EC) realmente mede o processo iônico de uma solução que lhe permite transmitir corrente. De acordo com os padrões da OMS, o valor EC não deve exceder 400 μS/cm.

7. Carbono_orgânico:
O Carbono Orgânico Total (COT) nas águas de nascente vem de matéria orgânica natural em decomposição (NOM), bem como de fontes sintéticas. TOC é uma medida da quantidade total de carbono em compostos orgânicos em água pura. De acordo com a US EPA < 2 mg/L como TOC em água tratada/potável, e < 4 mg/Lit em água de fonte que é usada para tratamento.

8. Trialometanos:
THMs são produtos químicos que podem ser encontrados em água tratada com cloro. A concentração de THMs na água potável varia de acordo com o nível de matéria orgânica na água, a quantidade de cloro necessária para tratar a água e a temperatura da água que está sendo tratada. Níveis de THM de até 80 ppm são considerados seguros na água potável.

9. Turbidez:
A turbidez da água depende da quantidade de matéria sólida presente no estado suspenso. É uma medida das propriedades de emissão de luz da água e o teste é usado para indicar a qualidade da descarga de resíduos em relação à matéria coloidal. O valor médio de turbidez obtido para o Wondo Genet Campus (0,98 NTU) é inferior ao valor recomendado pela OMS de 5,00 NTU.

10. Potabilidade:
Indica se a água é segura para consumo humano onde 1 significa Potável e 0 significa Não potável.


