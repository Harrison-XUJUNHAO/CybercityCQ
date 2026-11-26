# 思渺寺资源镜像（待推送）

仓库根就是镜像基址，例如推到 GitHub 公开仓库后：`https://cdn.jsdelivr.net/gh/<账号>/<仓库>@<提交号>`，
游戏里把这个基址填进 `src/modules/cq-config/assets.js` 的 `mirrorBase`，资源地址 = 基址 + 文件清单里的 path。

公开仓库：https://github.com/Harrison-XUJUNHAO/CybercityCQ（只放游戏运行要下载的文件，不放源代码）。推上去以后镜像基址是

    https://cdn.jsdelivr.net/gh/Harrison-XUJUNHAO/CybercityCQ@<这次推送的提交号>

每次发版推一次：仓库里只留这一版的文件（旧版本的文件靠旧提交号继续能取到），这样某个提交的仓库大小不会越积越大，超过 jsDelivr 的 50 MB 限制。

共 165 个文件，46.86 MB（原始大小）。每个文件的大小和 sha256 见 文件清单.json。
