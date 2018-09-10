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
## 编辑及提交
编辑工作目录下的文件，并保存，然后在工作目录下执行以下git命令
```bash
git add .
git commit -m "commits of your changes"
git push -u origin your-branch
```
---

## 申请合并（Pull Request）
在github上切换至对应的分支(branch)，然后点击New pull request

在PR页面上选择base分支（上游跟踪分支）及compare分支（你需要申请合并的分支），然后填写合并原因，并通过页面正文的diff对比确认修改，最后点击Create pull request，申请合并至base分支。

管理员将会接收到Pull Request后，确认base分支以及diff无误后，填写confirm原因，并点击Confirm，合并至分支。
------
## 参考链接
[git flow的使用](https://www.cnblogs.com/lcngu/p/5770288.html)
