# Architecture
# This is my experimental basic MagicOnion Architecture repo.
What I mean by 'Architecture' is:
  - Follow best practice guided in official ReadMe, CEDEC conference material, and multiple hatenablog, Qiita, Zenn.dev articles
  - Provide unified tutorial-like entry point to use MagicOnion with any kind of architecture

##This fork is only for fun. So It is very, very experimental. Will do following:
- Renewal of chat sample
- Use all Cysharp's infinity stones with VContainer 
  - (Except UniRx. IT IS DEPRECATED. ADMIT IT. OR AT LEAST SHARE INTERNAL MAINTAINED VERSION.)
  - If I have left-over time, I'll try using dotnet/reactive instead.
- .NET 8 on server side
- Completely replace MessagePack-CSharp to MemoryPack in both Unity side and server side.
- Completely replace legacy grpc c core to grpc-dotnet
- Experiment using grpc-dotnet over HTTP3
  - reqwest's experimental HTTP3
  - quiche
[My experimental fork of MagicOnion](https://github.com/SeungHuLee/MagicOnion)

