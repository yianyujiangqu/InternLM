# 书生·浦语第二节

## 1 **主要内容**
- **部署 `InternLM2-Chat-1.8B` 模型**

## 2 **开始部署**

### 2.1 **环境部署**
这里是在开发机进行的部署

![alt text](image/img1.png)

### 2.2 **下载模型`InternLM2-Chat-1.8B`模型**

这里我将模型下载到了`/root/work/modes`目录下

![all text](image/img2.png)

### 2.3 **执行cli_demo**
脚本填充如下：
![all text](image/img3.png)

执行命令如
```
python /root/work/demo/cli_demo.py
```

等待模型加载完成，键入内容如：
```
请创作一个 300 字的睡前小故事
```
效果如下：
![all text](image/img4.png)
