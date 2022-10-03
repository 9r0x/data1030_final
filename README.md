# Malicious sites classification

## Overview

Shopping, streaming, instant messaging, ... The majority of our daily activities rely on the internet, but cyber-security threats have increased at an unprecedented rate. In 2021, Australia alone reported 71,299 incidents of phishing, usually in the form of fraudulent websites designed to trick users into revealing sensitive information, and 4.3 Million AUD lost. The ability to distinguish malicious sites from benign sites protects inexperienced Internet users from the information or financial loss, enables organizations to identify viruses/attacks from external networks, and assists website owners in enhancing their site's design to improve their search engine ranking.

This project classifies websites as Malicious(type = 1) and Benign(type = 0) using the "Malicious and Benign Websites" dataset from Kaggle. 1781 data points with 20 raw characteristics and one target variable(Type) are contained in this dataset. Features fall into two categories: The Application layer and the Network layer, as defined by the Open Systems Interconnection (OSI) model: the former addresses what the user actually sees in their browser, whereas the latter handles the underlying data packets that are delivered to your computer. URL_LENGTH, CHARSET, CONTENT_LENGTH, and SERVER are examples of application features, whereas DISTREMOTETCP_PORT, APP_BYTES, and DNSQUERYTIMES are examples of network features.

The dataset was compiled from reputable sources, such as malwaredomainlist.com, and then filtered using another security application, such as VirusTotal. After initial filtering, Python scripts were utilized to confirm site availability and generate application layer and network layer data for each active site.

## Package versions

```
- python=3.10.5
- matplotlib=3.5.2
- pandas=1.4.2
- scikit-learn=1.1.1
- numpy=1.22.4
- xgboost=1.5.1
- shap=0.40.0
- jupyter_client=7.3.1
- jupyter_core=4.10.0
- jupyterlab=3.4.2
- jupyter_server=1.17.0
- jupytext=1.13.8
- rise=5.7.1
- plotly=5.8.0
- ipywidgets=7.7.0
```

## License

The MIT License (MIT)
Copyright © 2022 <SHUKAI NI>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
