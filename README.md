# cw_praca_z_kodem


# Jak poprawnie zainstalować zależności i uruchomić aplikację



##  Wpisz komendy w bash

    git clone https://github.com/wrx75752/cw_praca_z_kodem.git
	

    cd cw_praca_z_kodem
	

    make
	
	
*Jak korzystamy z interpretrea python pod Windowsem to musimy dodadkowo zainstalować paczkę make poprzez powershell jako administrator 

    1.  Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('[https://community.chocolatey.org/install.ps1')](https://community.chocolatey.org/install.ps1') "https://community.chocolatey.org/install.ps1')"))
    2. choco install make

## Dlaczego ważne jest README w projekcie ?

Plik README jest dokumentem wprowadzającym, który zawiera podstawowe informacje o projekcie, takie jak jego cel, sposób użycia, instalacji, a także zasady współpracy, co czyni go niezbędnym przewodnikiem dla nowych użytkowników i współtwórców.



##  Rezulatat wykonania komendy  "make"


pip3 install -r requirements.txt
Requirement already satisfied: Flask==2.3.2 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from -r requirements.txt (line 1)) (2.3.2)
Requirement already satisfied: Werkzeug>=2.3.3 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Flask==2.3.2->-r requirements.txt (line 1)) (2.3.4)
Requirement already satisfied: Jinja2>=3.1.2 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Flask==2.3.2->-r requirements.txt (line 1)) (3.1.2)
Requirement already satisfied: itsdangerous>=2.1.2 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Flask==2.3.2->-r requirements.txt (line 1)) (2.1.2)
Requirement already satisfied: click>=8.1.3 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Flask==2.3.2->-r requirements.txt (line 1)) (8.1.3)
Requirement already satisfied: blinker>=1.6.2 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Flask==2.3.2->-r requirements.txt (line 1)) (1.6.2)
Requirement already satisfied: colorama in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from click>=8.1.3->Flask==2.3.2->-r requirements.txt (line 1)) (0.4.6)
Requirement already satisfied: MarkupSafe>=2.0 in d:\lab_2\lista_2\cw_praca_z_kodem\.venv\lib\site-packages (from Jinja2>=3.1.2->Flask==2.3.2->-r requirements.txt (line 1)) (2.1.3)
pylint app.py
************* Module app
app.py:1:0: C0114: Missing module docstring (missing-module-docstring)
app.py:7:0: C0116: Missing function or method docstring (missing-function-docstring)
app.py:13:0: C0116: Missing function or method docstring (missing-function-docstring)
app.py:2:0: W0611: Unused escape imported from markupsafe (unused-import)

------------------------------------------------------------------
Your code has been rated at 4.29/10 (previous run: 4.29/10, +0.00)

