# 草莓病害数据集

## 数据集内容

- **图像数量**: 共458张图片
- **标注类别**: 包括正常植株、缺钙植株、缺肥植株、白粉病植株、叶斑病植株等共计8类标签
- **数据格式**: 原始数据集及根据YOLO标注好的数据集

### 类别

```python
flower			0	花
health			1	健康
ripe			2	熟
fruit			3	果
fertilizer		4	缺肥
powdery			5	白粉病
acalcerosis		6	缺钙
greyleaf		7	叶斑病
```

### onnx 模型转换指令

```
python export.py --weights last.pt --img 640 --batch 1             # export at 640x640 with batch size 1
```

## 使用说明

2. **数据预处理**: 数据集已经过预处理，可以直接用于训练和测试。
3. **适用场景**: 适用于计算机视觉、机器学习、农业自动化等领域的研究。



