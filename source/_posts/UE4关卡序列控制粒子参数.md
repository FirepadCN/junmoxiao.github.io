---

title: UE4关卡序列控制粒子参数

date: 2019-03-14 15:58:34

tags: UE4,关卡序列,粒子特效

---

# UE4中通过关卡序列控制粒子特效参数
> 今天公司美术正好问这个问题，就稍微总结了下QAQ
<!--more-->

## 1.修改粒子参数类型
修改为：*****parame，并修改下方ParameterName为后续需要控制的名称。


![Parameter](UE4关卡序列控制粒子参数/Parameter.png)
## 2.暴露参数
在世界大纲视图中选择该需要控制的粒子，选择其细节中发射器动作下的“暴露参数”按钮，此时之前修改的PrameterName的参数就会出现在细节面板上。
![Emiter](UE4关卡序列控制粒子参数/Emiter.png)
## 3.添加粒子特效到关卡序列
在前面的设置都正确后，将粒子特效拖动到关卡序列中。现在为其添加“粒子参数轨道”,并在参数下拉选项中选择我们命名的参数。我们就可以像控制其他属性一样控制粒子参数，实现漂亮的效果了。
![se](UE4关卡序列控制粒子参数/se.png)

