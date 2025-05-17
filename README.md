## 樹梅派安裝一些套件
sudo apt update  
sudo apt install python3-opencv python3-flask python3-pip  
pip3 install mediapipe --break-system-packages  
pip3 install scikit-learn --break-system-packages  
  
  
### 在自己的電腦訓練的時候先安裝python虛擬環境  
python3 -m venv myenv  
那啟動方式如下：  
#### Linux / macOS：  
source myenv/bin/activate  
#### Windows（cmd）:  
cmd  
myenv\Scripts\activate  
  
啟動完之後安裝一些套件  
pip install mediapipe opencv-python scikit-learn matplotlib pandas  
  
#### 跌倒判斷訓練資料(kaggle)  
https://www.kaggle.com/datasets/uttejkumarkandagatla/fall-detection-dataset?resource=download  
