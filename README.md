# ML dataset description
I utilized requests function in python to get the stock data from TWSE, and I retrieved several kinds of stock data, including “成交股數”, “成交金額”, “開盤價”, “最高價”, “最低價”, “收盤價”, “漲跌價差”, “成交筆數”, and parsed these json data into dataframe. And I also added the lagged feature (close-1, close-2, close-3, close-4, close-5 day closing price).
close-t closing price means the closing price at the t days before.
Additionally, I set the stock history data from 2024/10/1 to 2024/12/31. 
