# yt-bbs
---
某掲示板付きYouTube動画視聴サイトの後継になるべく

## BBSの構成
```mermaid
flowchart TD

    Main[BBS-Server]
    A[Instance] --> Main
    B[Instance] --> Main
    C[Instance] --> Main
    User[User]-->A
    User2[User]-->B
    User4[User]-->B
    User3[User]-->C
```