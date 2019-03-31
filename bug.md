# 构建 HaiKu 时遇到的 bug

- 在 Major VM 下构建时不要使用 `-j` 选项，会卡死在 `AddVariableToScript1 haiku.image-init-vars` 这里
- 构建之前要重新 ../configure，不然会出错，具体原因未知

b

b