# python-api-challenge Module 6 Challenge
**----------Content under Python-api-challenge repository ----------**
* .gitignore file and README.MD
* WeatherPy folder - contains the Completed/Solved assignment Jupyter Source File and output_data folder<br>
    ** --Inside WeatherPy Folder--**
    * WeatherPy.ipynb - Completed solution Jupyter Source File
    * VacationPy.ipynb - Completed solution Jupyter Source File
    * output_data folder - Contains all the output figures and Citiy extract(csv file) which are genrated as part of this acitivity<br>
        -- Fig1 <br>
        -- Fig2 <br>
        -- Fig3 <br>
        -- Fig4 <br>
        -- Cities.csv <br>        
**----------To Execute the Jupyter source file ----------**
* Create api_keys.py in the same level as WeatherPy folder and add the below content. You need add your own keys in this file. To get your keys visit OpenWeatherMap and geoapify website and register yourself, get the key and update below.<br>
  Comment-OpenWeatherMap API Key below<br>
   weather_api_key = "YOUR KEY GOES HERE"<br>
   <br>
   Comment-Geoapify API Key below<br>
   geoapify_key = "YOUR KEY GOES HERE"<br>
   
* Open the Jupyter Source File using Visual studio code
* Ensure correct Kernell is selected.
* Ensure api_keys.py is placed in the same level as WeatherPy folder
* Execute WeatherPy.ipynb file first as the the Cities.csv extract will be generated which is the input for VaccationPy.ipynb.
* Run All or Run individual cell code in sequence it is written. Running the code block in between might throw error as the variables used in that code block might be defined in the prior code block. Hence recommended to Run All to ensure it is run in sequence without any error
  Note: WeatherPy.ipynb file first and then VacationPy.ipynb
