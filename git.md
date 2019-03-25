
<!-- MarkdownTOC levels="1,2,3,4,5,6" autolink="true" bracket="round" autoanchor="false" style="unordered" indent="\t" -->

- [git使用流程](#git%E4%BD%BF%E7%94%A8%E6%B5%81%E7%A8%8B)
    - [克隆GitHub到本地](#%E5%85%8B%E9%9A%86github%E5%88%B0%E6%9C%AC%E5%9C%B0)
    - [Git仓库的三大区域](#git%E4%BB%93%E5%BA%93%E7%9A%84%E4%B8%89%E5%A4%A7%E5%8C%BA%E5%9F%9F)
- [second](#second)

<!-- /MarkdownTOC -->
#git使用流程
##克隆GitHub到本地
（1）使用git clone +[仓库地址]就能克隆到本地
如：git clone https：//github.com/Manchangdx/shiyanlou.git
(2)进入仓库主目录有个.git隐藏目录，它里面包含了仓库的全部信息
，删掉这个目录，仓库就变成普通目录了。进入到仓库目录中
命令行的前缀发生一些变化，出现了红色的master，它就是当前所在的分支名
##Git仓库的三大区域 
（1）工作区、暂存区、版本区
所有Git命令都是以git开头
（2）首先进入仓库主目录，执行git status
查看整个仓库的状态
（3）当我们在GitHub上创建一个仓库时，同时生成了仓库的默认主机名origin
并创建了默认分支master，在GitHub上创建仓库，会自动生成一个仓库地址
克隆一个GitHub仓库（远程仓库）到本地，本地仓库则会关联到这个远程仓库，
执行git remote -v命令可以查看本地仓库所关联的远程仓库信息。

# second
