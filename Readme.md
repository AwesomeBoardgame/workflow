# Workflow
--------
## 克隆/更新分支
### 本地未有工作目录
* 克隆代码
```bash
git clone git@github.com:AwesomeBoardgame/workflow.git
```
* 根据开发分支创建一个新分支，并切换至新分支（最后一个参数为上游分支，请输入合适的分支，但不要跟踪master分支或不填写）
```bash
git checkout -b your-branch dev
```
* 查看分支树，输出（\*号后为当前分支)：
```bash
 git branch
 * your-branch
   dev
   master
```
### 本地已有工作目录
（待补充）

---
## 编辑

## 提交

## 申请合并

------
## 参考链接
[git flow的使用](https://www.cnblogs.com/lcngu/p/5770288.html)
