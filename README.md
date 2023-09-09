
### 运行环境
```python
python 3.6.8
torch 1.0.1
torchvision 0.2.2
```

### 运行示例

- 运行预处理代码

```sh
python ./datasets/prprocess.py --dataset diginetica
```

- 运行训练测试代码

```sh
python ./pytorch_code/main_new.py --hier 2 --dataset diginetica
```
文献

Yan-Hui Chen, Ling Huang, Chang-Dong Wang and Jian-Huang Lai. "Hybrid-Order Gated Graph Neural Network for Session-Based Recommendation", TII2022
