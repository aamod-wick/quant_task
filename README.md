# quant_task
<html> 
  <body>
<p>This repo contains two jupyter notebooks of importance.</p>
    <P>1.Aamod(1).ipynb which is the repo where the main code is stored . For cross checking the code kindly follow the data upload instructions i have included in the text section of the notebook . </P>
    <p>2.Stock_data.ipynb which is the preprocessig thati did and me playing around with the data to understand size , type  no of stocks and no if days in data .Through this i concluded that using normal day to day libraries in python such as Numpy and Pandas would be more than sufficient to calculate crossover . There were 2 other approaches i looked into one was using Dask :- a distributed processing library in python but after looking at the data size i concluded that this would not be necessary and may not decrese the time complexity of the program , another alternative approach i though was using pure python code with as little dependencies as possible and calculating the average based on a sliding window approach , however this wouldnt decrease time complexity since Pandas is already optimised by vector usage .</p>

  <p>The results of crossovers are as follows :-<br> Results for 19th April:
{'ABC': None}
<br>
Results for 22nd April:
{'ABC': Timestamp('2024-04-22 09:41:44')}
<br>
    </p><p>
    Note that these are FIRST crossovers of the day as requested in the mail .There could be multiple crossovers in a day but only the first is appended to the list . The stock name is ABC and there is no crossover on 19th april and atleast one on 22nd april.
</p>
  </body>



</html>
