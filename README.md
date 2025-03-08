# usePDR
* 

# use PDR  Install
```powershell
# git clone 
git clone https://github.com/slackmodel/usePDR.git
cd use
# install python
winget install python.python.3.13

# install poetry 
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
#PS \:usePDR> poetry -V       
#Poetry (version 2.1.1)

# install package 
> poetry install

# start server
> poetry run shiny run app.py

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
# broser open http://127.0.0.1:8000

````

# Refer 
* https://github.com/WooilJeong/PublicDataReader