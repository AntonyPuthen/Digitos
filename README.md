# Digitos

Brief steps in the process:
      Weather forecasting 
      Load forecasting 
      Demand forecasting 
      Load scheduling
      App Demonstration

    #1:Weather forecasting: Weather forecasting ipynb file named 'weather new.ipynb'.
                        Processing notebook calls for data which is 'Book1.csv'
                        
    #2:Load forecasting:Load forecasting is done using 'demand forecasting new.ipynb'
                        Load forecasting data is provided in hte same file named 'load forecasting.csv'

    #3: Load scheduling:Scheduling related files remain inside Folder named SIH Final and Sub-folder named Scheduling.
                        Scheduling folder contains Export.xlsx,Import.xlsx,optimalsoln.mlx,out.xlsx,weather.xlsx respectively.
                        Scheduling related coding done on maltab is in the file named optimalsoln.mlx, Import.xlsx contains hourly price on 24hour duration.
                        out.xlsx contains the total load demand and weather.xlsx provides renewable energy demand.
                        Export.xlsx provides required energy demand to be scheduled with generator ie (out.xlsx-weather.xlsx)

                          
    #4: App Demonstration:App related files remain inside Folder named SIH Final and Sub-folder named App
                          App folder contains ForecastingApp.mlapp flie and its respective database in the same folder.
                          database folder contains relevant data outputs which have to be set as path on MATLAB to get plots on app developed.
