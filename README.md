# deep_learning
「EMNIST_classification.ipynb」：  

【概要】  
 EMNIST判別の正解率を最適化する(目標95%程度)  
<br>
【データセット】  
　EMNIST(アルファベット26文字)  
<br>
【比較モデル】  
　■全結合層ネットワーク  
　■CNNネットワーク  
　(※ バッチ正規化、ドロップアウト、初期重み等をパラメータ振って比較)  
<br>
【結果】  
　■全結合のみの場合 = 89.7%  
　■CNN層を用いた場合 = 94.8%  
  
# Python  
「qc20241001.py」・・・メインコード  
「func_qc20241001.py」・・・関数リスト  
<br>
【概要】  
　無線機のDA値をパラメータとして振ったときのパワー計自動測定ツール  
<br>
【内容】  
　■「Flet」・・・UIに使用  
　■「serial」・・・シリアル通信で無線機を制御  
　■「pyvisa」・・・パワー計制御
