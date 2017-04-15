設定ファイルを編集する場合は、必ずネストしたXサーバ上で動作・表示確認を行ってから反映する。

・Xサーバをネストする起動コマンド
$ Xephyr :1 -ac -br -noreset -screen 1152x720 &
$ DISPLAY=:1.0 awesome -c ~/.config/awesome/rc.lua.new &
