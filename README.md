# cs-form-mtn-010-vs2022
ComboBox 用クラスで固定データを使用

```cs
private class ComboData
{

    public ComboData(string Text, string Data)
    {
        this.Text = Text;
        this.Data = Data;
    }

    public string Text { get; set; }
    public string Data { get; set; }

    public override string ToString()
    {
        return this.Text;
    }
}
```

![image](https://github.com/winofsql/cs-form-mtn-010-vs2022/assets/1501327/d4a15d5b-43cb-49bd-87d5-1f64eaec199b)

# ソース分割されているソリューションを読み込んだ場合以下の設定が必要です

## 入れ子機能( Web ) を使用した機能のソース分割( partial )

![245340963-e68c31c7-8b00-4e8c-9f7f-75ed0a0b058e](https://github.com/winofsql/cs-form-mtn-010-vs2022/assets/1501327/19a28a55-9e9c-4b58-ba84-95001e6ca982)
