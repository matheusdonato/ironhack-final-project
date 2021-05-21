# ironhack-final-project

# Análise Exploratória de Dados sobre Energia Solar
![image](https://user-images.githubusercontent.com/78570724/119060980-abed4f80-b9a9-11eb-9206-a4da3318f7d1.png)


# Motivação

Aquecimento global e energias renováveis são assuntos que a minha geração ouve falar desde sempre.

Inclusive, uma das minhas primeiras lembranças está associada ao buraco na camada de ozônio, assunto recorrente nos meios de comunicação bem como nas escolas durante meus primeiros anos de vida.

Por isso e por ser uma pessoa de certa forma idealista, gosto de refletir sobre esses temas e de como as mudanças farão a vida melhor no futuro.

O que me leva a 2021, quando já durante o bootcamp de Data Analytics, li notícias sobre os esforços e comprometimentos de países europeus em desenvolver ainda mais suas  fontes de energia renovável.

![image](https://user-images.githubusercontent.com/78570724/119062368-ff14d180-b9ac-11eb-8ee0-3c170cacee29.png)

![image](https://user-images.githubusercontent.com/78570724/119062401-1eabfa00-b9ad-11eb-96b1-b74616cac810.png)

Interessante, porém algo recorrente.

Contudo, no mesmo período li algo diferente, a notícia dizia que o Marrocos estava construindo uma fazenda de captação de energia solar que seria a maior do mundo. O país planejava produzir uma grande quantidade de energia, tendo como foco, a exportação para o continente europeu.

![image](https://user-images.githubusercontent.com/78570724/119062618-a3971380-b9ad-11eb-83ab-8e46f556ed16.png)

Neste momemnto eu passei a ver essa questão de uma forma diferente. 

Seria realmente possível a países como o Marrocos ou o Brasil, que possuem alta incidência de radiação solar, produzir energia limpa suficiente para atendimento de suas necessidades e ainda possuir excedentes para exportação?



# Dados

Para encontrar uma resposta a esses questionamentos utilizei dados das Nações Unidas disponíveis em: http://data.un.org/

Os dados foram limpos e pré-processados utilizando Python, em especial a biblioteca Pandas.

Os gráficos foram gerados no Tableau.



# Situação atual

## Mundo e Países Europeus

- Gases do efeito estufa (1992-2018)

A partir da Cúpula do Clima de 1992, países passaram a formular compromissos mais concretos de redução das emissões de gases do efeito estufa. 

Dentre os maiores poluidores se encontravam os países europeus, o Japão e os Estados Unidos.

Como me parecia ser o caso, os europeus tiveram os melhores resultados, com uma diminuição de 18% da emissão de gases poluentes entre 1992 e 2018.

![image](https://user-images.githubusercontent.com/78570724/118998378-c7cc0380-b95f-11eb-9398-965f73576670.png)



- Produção de energia - mundo (matrizes energéticas)

Apesar dos esforços, infelizemnte grande parte da energia produzida no mundo ainda é de origem não renovável.

![image](https://user-images.githubusercontent.com/78570724/119001331-41fd8780-b962-11eb-8fe8-635dd904af0b.png)

'Others' que é ainda é a maior fonte de energia inclui em sua maioria combustíveis fósseis como petróleo e derivados, carvão e gás natural.

Essas fontes são responsáveis por 64.5% da matriz energética global.

![image](https://user-images.githubusercontent.com/78570724/119025234-4fbf0700-b97a-11eb-8612-60a46f43108a.png)!



- Produção de energia - União Europeia e Reino Unido (matrizes energéticas)

![image](https://user-images.githubusercontent.com/78570724/119002137-fbf4f380-b962-11eb-8cc9-4592d2d9d56a.png)

Apesar dos esforços, os europeus ainda recorrem a petróleo e derivados, carvão e gás natural para 45% de sua energia elétrica.

Energia nuclear, 26.5%.

Apesar de já relevante, a energia solar ainda representa apenas 4.1% deste total.

![image](https://user-images.githubusercontent.com/78570724/119029893-9b27e400-b97f-11eb-817a-f39b4b352fee.png)



- Produção de energia - Alemanha (matrizes energéticas)

Dentre os europeus, a Alemanha se destaca na geração de energia solar, com praticamente um terço da produção europeia.

![image](https://user-images.githubusercontent.com/78570724/119008906-fac6c500-b968-11eb-8176-5918cea2eb7f.png)

O país produz 7.5% de sua eletricidade desta forma, marca que impressiona, em especial, se levarmos em consideração seu tamanho e volume de energia que essa fração representa.

![image](https://user-images.githubusercontent.com/78570724/119031442-7cc2e800-b981-11eb-8601-2450efa7a3b0.png)



## Morrocos & Norte da África, Brasil

Diferente da maior parte dos países europeus, e certamente da Alemanha, os países do norte da África e o Brasil estão entre as regiões com maior incidência de radiação solar no planeta.

Apesar disso, suas matrizes energéticas ainda não reproduzem esse 'talento natural.'



- Produção de energia - Marrocos (matrizes energéticas)

![image](https://user-images.githubusercontent.com/78570724/119015224-19c85580-b96f-11eb-8c99-17e6d2f842fa.png)

Fontes não renováveis representam um valor excessivamente alto matriz energética do país. (81%)

Energia solar cresceu nos últimos anos mas ainda representa uma fração muito pequena do todo produzido. (2.65%)

![image](https://user-images.githubusercontent.com/78570724/119032163-40dc5280-b982-11eb-8cf3-13e5ac7b9b66.png)



- Produção de energia - Norte da África (matrizes energéticas)

![image](https://user-images.githubusercontent.com/78570724/119017803-c1468780-b971-11eb-9bc4-db6e0d591bee.png)

No conjunto dos países da região, a disparidade entre o uso de energias não-renováveis e renováveis é a ainda mais alta.

![image](https://user-images.githubusercontent.com/78570724/119033360-7f264180-b983-11eb-9df2-7e784a29926f.png)




- Produção de energia - Brasil (matrizes energéticas)

No Brasil, vemos uma situação um pouco diferente. Dada a nossa abundância de recursos naturais, produzimos majoritariamente energia hidrelétrica, que apesar de ser tema complexo, é em geral considerada uma fonte de energia renovável.

![image](https://user-images.githubusercontent.com/78570724/119018412-6e210480-b972-11eb-82e5-cabbfc0e315c.png)

Contudo, o potencial enrgético solar não parece fazer jus aos meros 0.5% que ela representa na matriz energética nacional.

![image](https://user-images.githubusercontent.com/78570724/119034491-c234e480-b984-11eb-9931-fd1b902c5f37.png)

Locais como o Nordeste e Centro-Oeste são propícios à produção de energia fotovoltáica mas ainda não são devidamente aproveitados.



# Cenário projetado

As situações apresentadas anteriormente me fizeram pensar na seguinte hipótese.

E se a produtividade na geração da energia solar da Alemanha pudesse ser reproduzida ao Norte da África e mesmo ao Brasil?

O quanto seriam capazes de produzir a mais e o quanto a energia solar passaria a representar na composição da matriz energética dessas regiões?


## Produtividade da geração de energia solar por área

Para atestar a produtividade na geração de cada país, dividi a sua produção energética de fonte solar pela área do país ou região em questão.

![image](https://user-images.githubusercontent.com/78570724/119050567-6d9b6480-b998-11eb-9191-a422fd8a674b.png)

Com 128,108 kilowatts-hora produzidos por km², a produção relativa da Alemanha equivale a 96 vezes a do Marrocos e 315 vezes a do Brasil. 


## Produtividade da geração de energia solar por área da Alemanha aplicada a outras regiões

Finalmente, ao projetarmos a capacidade produtiva relativa da Alemanha a países e regiões muito maiores temos resultados surpreendentes.

Não só estas regiões produziriam o equivalente a toda sua produção atual (considerando todas as fontes energéticas) como gerariam excedentes gigantescos, que com o devido investimento, poderiam ser exportados a países como a própria Alemanha, contribuindo de forma muito considerável para a redução (e eventual abolição) do uso de outras fontes energéticas nocivas ao meio ambiente.

![image](https://user-images.githubusercontent.com/78570724/119056298-d686da80-b9a0-11eb-8089-a48dc679cfee.png)

Como mostrei no início, apenas a União Europeia e o Reino Unido consomem 1,405,875 milhões de kilowatts-hora energia gerada através da queima de carvão, petróleo e gás natural.

![image](https://user-images.githubusercontent.com/78570724/119002137-fbf4f380-b962-11eb-8cc9-4592d2d9d56a.png)

Se o excedente do que seria produzido apenas pelos países do Norte da África e pelo Brasil pudesse ser redirecionado à Europa, poderíamos reduzir a necessidade de fontes 'sujas' em 920,055 milhões de kilowatts-hora. (65.5% do total)

![image](https://user-images.githubusercontent.com/78570724/119057549-0c2cc300-b9a3-11eb-9050-07194625ed53.png)




# Conclusão

O objetivo deste trabalho foi fornecer uma breve perspectiva de como estamos e o que podemos esperar para o futuro no quesito energias renováveis, em especial, energia solar.

Como visto, ainda estamos longe de um futuro completamente sustentável, as políticas de muitos países ainda não é condizente com a urgência do tema, o que desestimula os mais entusiastas, ainda mais quando consideramos os recentes acontecimentos no Brasil.

Contudo, como também demonstrado, grandes possibilidades não estão tão distantes de nosso alcance.

Por questões de priorização, este trabalho considerou produtividade e área dos países enquanto desconsiderou fatores muito relevantes por igual, como relevo, clima e o mais importante, horas de sol.

Se levassemos esses fatores em conta, é provável que os resultados das projeções consideradas fossem ainda mais surpreendentes.

Ainda, não foram levados em consideração questões econômicas como a transferência de renda de países mais ricos para países mais pobres através da exportação de energia. Isto poderia ser um fator importante para reduzirmos problemas como o das disparidade de renda entre os mais ricos e os mais pobres no mundo.

Em resumo, diversas questões mais poderiam ser consideradas, no entanto, como mensagem final fica a percepção de que caminhamos para um futuro melhor, com energia mais barata e renovável, acessível a mais pessoas e com mais cooperação entre países, o que sem dúvida nos levará a um ciclo de desenvolvimento econômico mais sustentável. 





