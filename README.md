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
