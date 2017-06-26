### Installation Steps for Firefox testing
1. Clone Repo
2. Use Python 2.X
3. Download Gecko Driver
  - https://github.com/mozilla/geckodriver/releases
  - tar -xvzf geckodriver*
  - chmod +x geckodriver
  - sudo mv geckodriver /usr/local/bin/ (suggested)
  - export PATH=$PATH:/path-to-extracted-file/geckodriver 
    (export PATH=$PATH:/usr/local/bin/geckodriver)
4. Download and install Firefox if necessary   
5. cd to the project
6. Run from command line python searchProducts.py

### Installation Steps for ChromeDriver testing
1. Clone Repo
2. Use Python 2.X
3. Download chromedriver
  - http://chromedriver.storage.googleapis.com/index.html
  - tar -xvzf chromedriver*
  - chmod +x chromedriver
  - sudo mv chromedriver /usr/local/bin/ (suggested)
  - export PATH=$PATH:/path-to-extracted-file/chromedriver 
    (export PATH=$PATH:/usr/local/bin/chromedriver)
4. Download and install Chrome browser if necessary   
5. cd to the project
6. Run from command line python searchProducts.py
