Unityで作成した、ChatGPTとLINE風会話アプリが出来るネイティブアプリです。

こちらはAndroid版です。（iOS版も別途開発しています。）



Assets/main.unitypackage
から起動して下さい。


実際に使用するには
Assets/TextChatUI/Scripts/UI/TextChatWindow.cs内の

private readonly string apiKey = "〜〜 ここにAPIキーを入力 〜〜";

にChatGPTのAPIキーを入力してからシーン再生して下さい。
