# title：python学习笔记
## 1.函数：
### 1.1定义
增强程序的复用性，减少重复性代码，提高开发效率
### 1.2函数的基础定义语法
```markdown
def 函数名(传入参数)：
        函数体
        return 返回值
```
### 1.3函数的传入参数
传参定义：
```python
def add(x,y)：
    result=x+y
    print (f"{x}+{y}的结果为：{result}")
```
### 1.4函数的返回值定义语法
return返回结果
函数体遇到return就不会再运行了，所以return之后的代码不会执行

### 1.5函数返回值之<span class="red-text">None类型</span>
<style>
    .red-text {
        color: red;
    }
</style>
应用场景：
- 1.函数无返回值时使用  
- 2.用在if判断上（if判断里，None等同于False
- 3.用于声明无内容的变量上（定义变量暂时不需要具体值）
  >name=None

### 1.6函数的说明文档
帮助理解函数的作用
（<span class="red-text">内容需写到函数体之前</span >）  
通过多行注释

