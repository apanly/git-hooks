Git Hooks 整理
=================
## 使用方法
* 所有的Hooks脚本都应该放置在该项目目录下的.git/hooks 目录下
* 所有的Hooks脚本都应该有执行权限

## Hooks列表
* Api (每次push的时候进行 api测试,做业务测试) [pre-push](api/pre-push)
* commit 备注检查
* commit php语法检查
