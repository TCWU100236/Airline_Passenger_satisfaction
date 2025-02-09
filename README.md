# Airline_Passenger_satisfaction
使用機器學習演算法分析某航空乘客滿意度

## 一、資料集概述
Here you should give a general idea of what a user will need in order to use your library or application. List requirements and then link to another resource with detailed installation or setup instructions.

- 原始資料集 [airline_passenger_satisfaction](https://www.kaggle.com/datasets/ahmedelsharkaw/airline-passenger-satisfaction)


| Variable                           | Definition                 | Dtype    | Key                                                 |
|------------------------------------|---------------------------|---------|----------------------------------------------------|
| Gender                             | 性別                      | Category | Male: 男性；Female: 女性                           |
| customer_type                      | 顧客類別                  | Category | Loyal Customer: 忠誠顧客；disloyal Customer: 不忠誠顧客 |
| age                                | 年紀                      | Numeric  |                                                    |
| type_of_travel                     | 旅行類型                  | Category | Personal Travel: 個人旅行；Business travel: 商務旅行 |
| customer_class                     | 顧客等級                  | Category | Eco、Eco Plus、Business                           |
| flight_distance                    | 飛行距離                  | Numeric  |                                                    |
| inflight_wifi_service              | 機上WiFi服務評分          | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| departure_arrival_time_convenient   | 出發、抵達時間方便度評分  | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| ease_of_online_booking             | 網路預約方便度評分        | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| gate_location                      | 登機口位置評分            | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| food_and_drink                     | 飲食評分                  | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| online_boarding                    | 線上登機評分              | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| seat_comfort                       | 座椅舒適度評分            | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| inflight_entertainment             | 機上娛樂評分              | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| onboard_service                    | 機艙服務評分              | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| leg_room_service                   | 腿部空間服務評分          | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| baggage_handling                    | 行李處理服務評分          | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| checkin_service                     | 報到服務評分              | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| inflight_service                    | 機上服務評分              | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| cleanliness                         | 整潔度評分                | Numeric  | 0: 評分 = 0；1: 評分 = 1，以此類推                 |
| departure_delay_in_minutes          | 出發延遲分鐘數            | Numeric  |                                                    |
| arrival_delay_in_minutes            | 抵達延遲分鐘數            | Numeric  |                                                    |
| satisfaction                        | 滿意度                    | Category | neutral or dissatisfied: 中立或不滿意；satisfied: 滿意 |

## 二、資料集前處理
資料集描述性資料及處理詳細過程請看： [資料前處理](Data_preprocessing.ipynb)

## 三、ML演算法比較
