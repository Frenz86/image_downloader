# image_downloader

# 2. Key features

+ Supported Search Engine: Google, Bing, Baidu
+ Keywords input from keyboard, or input from line seperated keywords list file for batch process.
+ Download image using customizable number of threads.
+ Fully supported conditional search (eg. filetype:, site:).
+ Switch for Google safe mode.
+ Proxy configuration (socks, http).
+ CMD and GUI ways of using are provided.

## 3. Install python 3.8

### 3.2 Download and setup chromedriver [recommend]
+ Require Google Chrome Browser or Chromium Browser installed.
+ Download the corresponding version of chromedriver from [here](https://chromedriver.chromium.org/downloads)
+ Copy `chromedriver` binary to ${project_directory}/bin/ folder

### 3.3 Install python packages

```bash
pip3 install -r requirements.txt
```

## 4. Usage
python run run.py