## 关于

该项目是游戏 [Breeders of the Nephelym: Alpha](https://store.steampowered.com/app/1161770/Breeders_of_the_Nephelym_Alpha/) 的汉化补充模组

## 如何使用

下载并解压 [release.zip](https://github.com/xiyuesaves/translation-module/releases/latest) 将两个文件夹覆盖到游戏目录的 OBF 文件夹内即可

## 如何优化翻译

- 下载本项目，使用 `Excel` 打开 `OBF.csv` 文件
- 在 `target` 列中填写新的翻译内容，保存表格
- 双击 `打包.bat` 文件，生成新的 `OBF.locres.new` 文件
- 将 `OBF.locres.new` 文件移动到 `OBF/Content/Localization/OBF/zh-Hans` 文件夹下，删除原有的 `OBF.locres` 文件
- 将 `OBF.locres.new` 文件重命名为 `OBF.locres` 文件
- 重启游戏