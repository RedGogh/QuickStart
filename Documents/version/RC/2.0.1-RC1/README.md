# 2.0.0-RC1

---------------------

## ⭐ 新增新能

- `Workbook`工作簿支持从文件或数据流中加载数据。
- `Workbook`工作簿支持迭代器以及`forEach`等方式遍历当前`Sheet`数据。
- `Workbook`工作簿支持转`CSV`文本格式。
- 提供序列化工具，支持对象序列化以及反序列化操作。持久化保存对象数据。
- 新增`SerializationException`序列化异常类。
- 新增Linux下`globbing`路径匹配机制，支持使用`strant`函数匹配各种路径。
- 新增`nextLetterCode`随机纯英文字符生成方法。

## 👻 优化功能

- `reflection`包更新为`reflect`，这样命名会比较清晰容易理解。
- 私有化原始`arraycopy`方法，避免外部调用。
- 随机字符生成支持长度范围生成。
- 更标准化的`Assert`断言工具使用方式。

## 🐞 BUG 修复

- 修复`Workbook`读取数据时`Cell`对象可能导致空指针异常错误。
- 修复单元格为空时，数据读取忽略空单元格导致列数不一致问题。

## 🔨 依赖变更

**NOTE:** 此版本没有依赖变更记录。