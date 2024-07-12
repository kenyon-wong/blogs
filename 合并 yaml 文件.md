# 合并 Yaml 文件

合并 yaml 文件

```bash
yq eval-all '. as $item ireduce ({}; . * $item)' *.yaml
```

