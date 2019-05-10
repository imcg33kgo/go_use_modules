# ReadMe

## Q&A
1. How to call  go_math_modules.minus() ? Why go build error "unknown field  'x' in struct ..." ?
Attempt 1: create a go file which name is the same with package name
Result: Doesn't work,  QAQ....
Attempt 2: create new project <testmodule>, change go.mod first line to 'module github.com/imcg33kgo/testmodule"
Result: It works well now!

2. How to download modules before coding? To avoid that IDEA auto complete not work
