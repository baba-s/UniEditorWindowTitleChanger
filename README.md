# Uni Editor Window Title Changer

Unity エディタのタイトルを変更できるエディタ拡張

## 使用例

```cs
using UniEditorWindowTitleChanger;
using UnityEditor;

public static class Example
{
	[MenuItem( "Tools/Hoge" )]
	private static void Hoge()
	{
		EditorWindowTitleChanger.SetTitle( "ピカチュウ" );
	}
}
```

![2020-04-21_133747](https://user-images.githubusercontent.com/6134875/79825992-80c6b400-83d5-11ea-88fc-f43b92b60b94.png)


## 謝辞

* このリポジトリは下記のサイト様を参考にさせていただいております  
    * https://qiita.com/mob-sakai/items/f3bbc0c45abc31ea7ac0  
