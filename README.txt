Description:
===================

Signals API (v1)

SignalsApi is a REST API that process a csv file and save data into MySQL database. signals_Api contains mainly two get methods . 

getSignals:
 which retreives all signals from MySql database.

getSignal:
 retreives a singel signal given its node_id

to run the signalsApi use the following command line:
        python -m uvicorn signalsApi:app --reload

To interact  with the above api please use the following Url:
                http://127.0.0.1:8000/docs
              