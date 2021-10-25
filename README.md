# sample_bot: Bot auto trade Binance theo yeu cau: cross macd, va rsi
Đánh giá chung Bot:
1. Đã test các chức năng ok như spec, xem file logbot.txt
2. Code dễ hiểu, dễ check ko gian lận, code ẩn, public source cho khách
3. Ý tưởng lời mới bán, lỗ dca tới chết rất hay ^^, khả năng bot đơn giản, nhưng sẽ hiệu quả kiếm tiền được.
4. Nhược: Vào lệnh market bất chấp nếu có signal Buy, Đánh long term ok. Đánh ngắn hạn thì sẽ tốt hơn nếu improve
   lên để bot vào khung thời gian nhỏ hơn, tìm điểm mua limit đẹp, kết hợp margin lên nữa thì best
5. Nhược: Lúc mới mở bot, nếu thị trường đang lên bot sẽ vào lệnh ngay lập tức (vì macd tăng và rsi tăng). Thường người
   ta bắt đáy đoạn vừa cắt lên, tức là phải xem nhiều candles trước nữa thì tốt hơn.

Bảng giá các chức năng thêm:
1> Code chạy được cả linux + win: 				+30usd
2> Cấu hình 1 vps/window chạy source: 			+50usd/1pc
3> Code notification về phone mỗi khi có order, 
	>telegram: 									+50usd, 
	>line: 										+30usd
   Gửi command ngược lại bot để tắt bot, đóng lệnh,... +50usd
4> Code tự động chỉnh delay để không bị disconnect server Binance, không bị block api,
   có lỗi thì auto resume: 						+100usd
   (mục đích cho tool len vps, chạy suốt ngày đêm)
5> Code để tool kết hợp với user, user có thể đóng lệnh bằng tay, bot tự động cập nhật,
   Hoặc user order lệnh bằng tay -> bot phai cập nhật status+tham số theo.
	Price: 										+100usd

6> Code show giao diện candles chart + show đường vẽ rsi,macd,.... 
   show vị trí lệnh đã Buy/Sell (chi hỗ trợ windows)
    > Show dạng file log(jpg/html), 
	  ví dụ 5minute report 1 lần: 				+150usd
	  Sample: https://github.com/hanquockorean/sample_bot/blob/3ef836b17316e29d2c0d55be4f293661b8573f79/chart.PNG
	> Show dạng realtime, liên tục cập nhật
	  chart live theo market:					+300usd 
	  
7> Upgrade code len multi thread, để chạy nhiều coin hơn cùng lúc: +200usd
8> Add thêm các lệnh trailing take profit, stoploss,...     +50usd  
9> Hỗ trợ backtest mô phỏng trên dữ liệu cũ để xem bot có hiệu quả không, Đồng thời tối ưu hóa tham số cho bot.
   Ví dụ có thể cặp BTCUSDT nhạy với RSI 10,20 hơn là cặp RSI 12,26... Phải chạy mô phỏng hết thì mới lọc ra tham số tốt nhất
   --> Lúc đó áp dụng vào bot hiện tại thì tỷ lệ win cao.
   Price: +200usd/1 cặp
   
10> Ngoài ra: follow twitter để mua coin theo tin tức, follow usdt/coin nạp lên sàn để mua coin,
  Follow telegram channel để mua coin,.... từ simple đến complex như tensorflow AI,
  cào web bằng chrome, auto duyệt web (không liên quan finance lắm ^^), fill web form làm ico.... 
  đều làm, liên hệ thêm thảo luận giá cho từng loai:
  Hoặc thuê Basic price: support, cài tool,... = 10usd/1h | code new function = 20usd/1h
  Min: 100usd/1project
  
  Donate: BTC: 15tXa3umn5UJBGoHKwxkNDjxxneQNnPXrU |ETH: 0x097eaa2e7e5bba5e732dd86681e5d4f5871b72cc
