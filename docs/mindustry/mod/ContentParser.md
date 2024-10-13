# ContentParser
- 路径: [mindustry.mod](../mod.md)
- 类型: public class
- 描述: 负责解析 JSON 模组文件并将数据转换为游戏中的内容。

---

### 关于变量
- ignoreUnknownFields
> 类型: private static final boolean
> 
> 描述: 字面意思，在获取到json中值为null的时候是否报错。
> 
> 默认值: `true`
> 

- contentTypes
> 类型: private ObjectMap<Class<?>>
> 
> 描述: 存储不同类型的内容（如单位、子弹等）。
> 
> 默认值: 
> 

- implicitNullable
> 类型: private ObjectSet<Class<?>>
>
> 描述: 包含那些默认可以为空的类类型，例如 TextureRegion 及其数组形式。
>
> 默认值:
>

### 关于方法


