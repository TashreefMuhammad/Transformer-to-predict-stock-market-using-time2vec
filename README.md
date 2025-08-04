# Transformer-Based Deep Learning Model for Stock Price Prediction  
### A Case Study on Bangladesh Stock Market

This repository contains the official implementation of the paper:  
**"Transformer-Based Deep Learning Model for Stock Price Prediction: A Case Study on Bangladesh Stock Market"**  
Published in: *[International Journal of Computational Intelligence and Applications | VOL. 22, NO. 03](https://www.worldscientific.com/worldscinet/ijcia)*  
DOI: **[https://doi.org/10.1142/S146902682350013X](https://doi.org/10.1142/S146902682350013X)*
 
---

## 📄 Abstract

In the modern capital market, the price of a stock is often considered to be highly volatile and unpredictable because of various social, financial, political and other dynamic factors. With calculated and thoughtful investment, stock market can ensure a handsome profit with minimal capital investment, while incorrect prediction can easily bring catastrophic financial loss to the investors. This paper introduces the application of a recently introduced machine learning model — the transformer model, to predict the future price of stocks of Dhaka Stock Exchange (DSE), the leading stock exchange in Bangladesh. The transformer model has been widely leveraged for natural language processing and computer vision tasks, but, to the best of our knowledge, has never been used for stock price prediction task task using DSE data. Recently, the introduction of time2vec encoding to represent the time series features has made it possible to employ the transformer model for the stock price prediction. This paper aims to leverage these two effective techniques to discover forecasting ability on the volatile stock market of DSE. We deal with the historical daily and weekly data of eight specific stocks listed in DSE. Our experiments demonstrate promising results and acceptable root-mean-squared error on most of the stocks. We also compare the performance of our model with that of a well-known benchmark stock forecasting model called ARIMA and report satisfactory results.

---

## 🧠 Key Contributions

- Application of Transformer architecture for univariate/multivariate stock time series forecasting.
- Case study focused on stocks from the **Dhaka Stock Exchange (DSE)**.
- Analysis of trends, volatility, and predictive capabilities with MAE, RMSE, and directional accuracy.

---

## 📊 Dataset
The stock price data used in this study is publicly available from:

[🔗 Mendeley Data – Stock Market Dataset of Bangladesh](https://data.mendeley.com/datasets/23553sm4tn/3)
This dataset includes historical stock prices from multiple companies listed on the Dhaka Stock Exchange (DSE), including fields such as:

* Company Ticker Information
* Date
* Opening Price
* Highest Price
* Lowest Price
* Close Price
* Volume

Please download the dataset and place the CSV files in the /data directory before running the code.

## 🙋‍♂️ Contact
For questions, suggestions, or collaboration opportunities, feel free to reach out:

📧 Email: tashreef.muhammad@gmail.com

🌐 Website: https://tashreefmuhammad.github.io/

🐙 GitHub: https://github.com/TashreefMuhammad

💼 LinkedIn: https://linkedin.com/in/tashreefmuhammad


# The paper can be cited as:

```bibtex
@article{muhammad2023transformer,
  title={Transformer-based deep learning model for stock price prediction: A case study on Bangladesh stock market},
  author={Muhammad, Tashreef and Aftab, Anika Bintee and Ibrahim, Muhammad and Ahsan, Md Mainul and Muhu, Maishameem Meherin and Khan, Shahidul Islam and Alam, Mohammad Shafiul},
  journal={International Journal of Computational Intelligence and Applications},
  volume={22},
  number={03},
  pages={2350013},
  year={2023},
  publisher={World Scientific}
}
```

The dataset was introduced in this paper. But the dataset can be cited as:

```bibtex
Muhammad, Tashreef; Islam, Rakibul; Alam, Mohammad Shafiul (2024), “Dhaka Stock Exchange Historical Data”, Mendeley Data, V3, doi: 10.17632/23553sm4tn.3
```
