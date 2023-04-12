# m2-money-growth-2019-22

_Why I Started The Project:_

After reading an article on Switzerland's low inflation rate post-COVID-19, I decided I wanted to explore how much Switzerland's M2 money supply had changed over the COVID-19 period. I had felt most articles post-COVID-19, whether they were about Switzerland's low inflation or the United Kingdom's highest inflation levels since the days of Thatcher, lacked a consideration for the impact that M2 money growth has on a country's inflation rate.

M2 money is defined as: currency in circulation (i.e., physical notes and coins outside banking institutions), demand deposits (checking/current accounts), savings accounts, time deposits/fixed-term savings less than $100,000, and money-market deposit accounts for individuals.

_The Dataset:_

I wanted to stick to mainly developed/high-income countries, as high inflation is not uncommon in developing/low-middle income countries—Lebanon, Venezuela, and Nigeria are three examples—whereas inflation has been relatively low in developed economies since 2009. I have included China due to its sheer size as an economy, its increasing influence as a geopolitical power, and its ambigous status as to whether it's a developing or developed country.

I wanted to include a mixture of GDP sizes, partly so I could have a couple to compare to each other. For example, the US and China have similar GDP levels, as do the United Kingdom and Canada, as well as Switzerland and Poland. I wanted to include EU countries, however, the European Central Bank only seemed to record M3 money supply. When I tried to obtain the data on an individual level, M2 appeared to be measured differently, which was the case when looking into Germany. Australia was also not included because it only measures M3 supply.

The data was mostly obtained from the Central Bank websites of the countries included or other governmental agencies, such as the Office for National Statistics in the UK. I downloaded the data, cleaned it, and formatted it according to how I wanted it to be presented. I performed the first analysis in Excel and later performed the same queries in MySQL. I have included the MySQL code in the project files. The data files and a.txt file containing my source links can be found here: https://www.kaggle.com/datasets/jonathanhateley/m2-growth-2019-2022

_Data Visualisation:_

Once I'd analysed the dataset, I then uploaded it to Tableau, where I created a data visual for each country. I included more context for the data at the bottom of each chart, which was a summary of the findings of my analysis and my conclusions from it.

The visuals can be found here: 
https://public.tableau.com/app/profile/jonathan.james.hateley/viz/M2MoneySupply/
