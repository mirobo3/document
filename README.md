# trump picking

## インストール方法
ターミナルで次のようなコマンドを打つ
~~~ 
git clone https://github.com/mirobo3/mirobo3_3_2020_crane_x7_ros.git
~~~
.gazeboディレクトリに移動する
~~~
rm -rf models
git clone https://github.com/mirobo3/models.git 
~~~



## 使い方
~~~
roslaunch crane_x7_gazebo crane_x7_card_stand.launch
~~~
別のターミナルを起動して
~~~
rosrun crane_x7_example test.py
~~~
