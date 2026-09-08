> 🌐 本文档由 [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) 翻译,英文原版见原项目。

# 索引

SQL 中的索引(Index)是一种数据库对象,用于提升对数据库表进行数据检索操作的速度。它的工作方式类似书籍的索引,为查找具有特定列值的行提供快速定位机制。索引会创建一个独立的数据结构,使数据库引擎无需扫描整张表即可定位数据。索引虽然能加速 `SELECT` 查询,但会拖慢 `INSERT`、`UPDATE` 和 `DELETE` 操作,因为索引结构必须随之更新。合理的索引设计对优化数据库性能至关重要,尤其是针对大表或频繁查询的列。

访问以下资源了解更多:

- [@video@SQL 索引最佳实践](https://www.youtube.com/watch?v=BIlFTFrEFOI)
