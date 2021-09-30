

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题


## 使用\` \` 凸显关键字
正文内容，一段技术的描述以及基本概述信息</br></br>
新的一行，一些细节概述，包含：`架构分析`、`细节设计`、`模块分析及解耦`

## 使用\* 内容\* 修饰为斜体
*斜体数据*

## \*\*内容\*\* 修饰为粗体
**粗体数据**

***数据***


## \* 编写无序列表

## 技术列表

* 负载均衡
	* 子集内容A
		* 三级内容
* 分布式及横向扩展
* 高可用HA数据库
* 长连接有效认证

## 有序列表

1. 第一层
	1. 第一层
	2. 第二层
2. 第二层

## 分割线

可以使用`-`或者`*`创建分割线</br>

- - -
* * *


## Tree效果
> TREE_01
>> TREE_02
>>> TREE_03

## 使用\`\`\`语言 代码内容\`\`\` 格式加入代码块

```c
	#include <stdio.h>
	#include <stdlib.h>
	#include <string.h>
	//这是一段c代码
```

```cpp
	#include <iostream>
	using namespace std;
	/* 这是一段c++代码 */
```

```python
	import 库名
	#一段python代码
```

```bash
	sudo apt-get install git #安装git的命令
```

## \`\`\`flow 流程内容 \`\`\` ,绘制流程图

```flow
st=>start: START
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(Yes)->e
cond(No)->op
```

