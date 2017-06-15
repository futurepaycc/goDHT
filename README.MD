### 测试运行说明
1. go test -v //运行本包内所有测试
2. go test bencode.go bencode_test.go //单独运行要加上依赖项
3. go test "^name$" //正则表达式必须有引号
