此内容适用于1.0.1以上版本，1.0.0版本请见[此处](https://page.xo.je/kongzhongtitian/wiki/recipesapi/home.html)，有序合成需要1.1.0以上版本。
## 无序合成
```json
{
  "type": "recipesapi:durability_shapeless",
  "category": "配方类型",
  "ingredients": [
    { "item": "输入物品A" },
    { "item": "输入物品B" }
  ],
  "result": {
    "item": "输出物品",
    "count": 输出数量
  }
}
```
## 有序合成
```json
{
  "type": "recipesapi:durability_shaped",
  "group": "durability_repair",
  "pattern": [
    "AAA",
    "BBB",
    "AAA"工作台里摆的顺序
  ],
  "key": {
    "A": { "item": "对应的输入物品" },
    "B": { "item": "对应的输入物品" }
  },
  "result": {
    "item": "输出物品"
  }
}
```