<!-- chapters/01-Introduction.md -->
# 1. AppleScript 核心概念

## 1.1 事件驱动模型
```applescript
-- 应用间通信示例
tell application "Mail"
    activate
    set newMessage to make new outgoing message ¬
        with properties {subject:"项目更新", content:"附件已包含最新进度"}
    tell newMessage
        make new to recipient ¬
            with properties {name:"项目经理", address:"pm@example.com"}
        send
    end tell
end tell