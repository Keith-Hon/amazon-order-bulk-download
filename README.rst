Step:

1. virtualenv env
2. .\env\Scripts\activate
3. pip install git+https://github.com/tobiasmcnulty/amzscraper.git
4. pip install webdriver_manager
5. mkdir orders
6. download wkhtmltopdf and add its executable to system's PATH
7. python .\amzscraper.py -u "USERNAME" -p "PASSWORD" -y 2020 2021