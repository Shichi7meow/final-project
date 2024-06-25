# final-project
## 題目
Home robot vacuum

## 說明
### Steps
#### Step 1:
roslaunch myrobot_1100336_description gazebo.launch
#### Step 2: 在gazebo_empty_world加入model
![螢幕截圖 2024-06-25 22 51 37](https://github.com/Shichi7meow/final-project/assets/100356928/e9928cfa-53f8-4c06-8eb7-278a54e92fe3)
![螢幕截圖 2024-06-25 22 52 11](https://github.com/Shichi7meow/final-project/assets/100356928/9b98c6f5-3b7b-4b0d-8d39-c9ce9fa7b8db)

#### Step 3: 切換目錄
cd catkin_ws/src/myrobot_1100336_description/scripts
#### Step 5: 跑程式
rosrun myrobot_1100336_description turtlebot3_random_walk.py
## 範例(影片)
https://youtu.be/Hol6IXRyPyw

## 注意事項
沒有想用掃瞄並建構地圖的原因是因為家裡的物品位置有時會更動，讓它自己隨機在公共區域跑就可以了(另外兩格為房間)

## 參考資料
`1. 老師上課講義 & 影片
`2. Chatgpt 
3. https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/

## 備註
原本做出來的環境是長這樣，但不知為何有兩扇窗戶轉成gazebo_empty_world時會消失。
![螢幕截圖 2024-06-25 18 14 36](https://github.com/Shichi7meow/final-project/assets/100356928/4efeb8b8-ebac-4ca5-8eb6-77e91bd7b88c)
