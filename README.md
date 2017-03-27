# Templates
模板用於快速建立各類型文件。
Ubuntu 下的範例：下載後放入家目錄的 Templates 資料夾，在右鍵「新增文件」中便能使用。

若沒有 Templates 資料夾：
mkdir ~/Templates
再開啟設定檔：
gedit ~/.config/user-dirs.dirs
在最底下加入這行：
XDG_TEMPLATES_DIR="$HOME/Templates"
