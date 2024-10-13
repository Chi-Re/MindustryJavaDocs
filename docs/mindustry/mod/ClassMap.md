# ClassMap
- 路径: [mindustry.mod](../mod.md)
- 类型: public class
- 描述: 提供了一个从简单的类名到具体类的映射。这个映射主要用于 JSON 配置文件中的反序列化过程，使得开发者可以在 JSON 文件中使用简单的字符串来引用复杂的类类型。

---

### 关于变量
- classes
> 类型: public static final ObjectMap<String, Class<?>>
> 
> 描述: 将简单的类名字符串映射到具体的类对象。这个映射主要用于在JSON模组文件中引用这些类时进行反序列化。
> 
> json: 一般作为`type`, `template`, `controller`, `defaultController`的value使用。
> ```json
> {
>   "type": "value",
>   "template": "value",
>   "controller": "value",
>   "defaultController": "value"
> }
>```
> 


### classes
这里其实是想写写关于json语法之类的，不过有点太多了，等java文档写完了在写json文档吧
