# Webug4.0 源码安装手册

## 准备工具

- `Phpstudy`
- `Navicat`
- `Webug4.0`

# 安装步骤

1. 安装 `phpstudy`
2. 安装 `Navicat`
3. 创建 `webug` 数据库（数据库连接配置文件：`data\dbConfig.php`）
4. 创建 `webug_sys` 数据库
5. 创建 `webug_width_byte` 数据库
6. 对应数据库名导入`/sql/`目录下对应的 `sql` 文件
7. 将 `webug` 放置于 `phpstudy` 的 `www` 目录下。

> 源码版与虚拟机版靶场没有区别，最大的区别在于乌云知识库。
> 由于虚拟机版本的无法定位本地 `IP`，所以使用靶场中的 `ssrf` 漏洞查询了本地的靶场路径。
