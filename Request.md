### 1. 兩個Textbox，一個Label，一個ComboBox，一個Button。
1. 預設值: 
```cpp
    ComboBox四個選項: +,-,x,/
```
1. 排列順序: Textbox1 -> ComboBox -> Textbox2 -> Lable。Button隨便放
1. 需求: 選擇好ComboBox，Textbox填入文字後，按下Button，Lable顯示兩邊資料運算的結果。
1. 注意if else。

- [ ] 完成

### 2. 兩個CheckBox，一個Button，一個Label，一個Timer。
1. 預設值: 
```cpp
    CheckBox1取名數字，
    CheckBox2取名英文，
    Label.text預設為空白。
```
1. 排列順序: Button -> CheckBox1 -> CheckBox2 -> Label。timer為1秒
1. 需求: 按下Button後Lable.text預設值為Start，依照CheckBox勾選，每秒Label隨機顯示一個數字或英文字。
  沒有勾選Label就顯示"請勾選"。再按一次Button，Timer會停止，Label.text設回空白。
1. 注意async。
  
- [ ] 完成

### 3. 兩個Listbox，一個Lable，一個三維陣列。
1. 預設值:
```cpp
    三維陣列 => string[10,20,1] 一維資料1~10，二維資料各一個A\~Z隨機字，三維資料各一個隨機數字。
    ListBox1 => 三維陣列的1維資料
    ListBox2 => 空
    Label => 空
```
1. 排列順序: ListBox1 -> ListBox2 -> Label。
1. 需求: 選擇好ListBox1的item後，ListBox2顯示對應的二維資料，按下ListBox2的item後，顯示對應的三維資料。
1. 注意for。

- [ ] 完成

### 4. 兩個 Button，一個 ListBox，一個 PictureBox，一個 List<Data>，一個 Data結構{Name, Bitmap}
1. 預設皆為空。
```cpp
    Button1.text = "載入"，
    Button2.text = "刪除選擇"
```
1. 排列順序:ListBox -> PictureBox。Button1在ListBox下方，Button2在ListBox右方。
1. 需求: 按下Button1開啟OpenFileDialog，選擇電腦內的隨便一張圖片，點選開啟後，List<Data>存入一筆資料，ListBox同步刷新，ListBox的item對應Data.Name。按一下ListBox的item，PictureBox會顯示對應的Bitmap。按下Button2的時候，會刪除掉選擇的ListBox項目，ListBox同步刷新。
1. 注意class

- [ ] 完成

### 5. 三個Button，一個ComboBox，一個Lable，一個分頁。分頁上:一個TextBox，跟一個Button。
1. 預設值: 
```cpp
    ComboBox四個選項: +,-,x,/
```
1. 排列順序: Button1 -> ComboBox -> Button2 -> Button3 -> Lable。
1. 需求: 按下Button1與Button2，會跳出分頁，分頁上的TextBox會顯示對應的Button.text，填入文字後按下分頁的Button會更新對應的Button.text。選擇好ComboBox後，按下Button3，Lable顯示兩邊資料運算的結果。
1. 注意Constructor

- [ ] 完成

### 6. 一個TextBox，一個Button，一個分頁。分頁上:一個Label。
1. 預設皆為空。
1. 排列順序:隨意
1. 需求: 按下Button後跳出分頁，分頁上的Label.text會與TextBox.text相等。分頁顯示時，會強制鎖定螢幕中央的最上方，主頁面不能關閉，分頁關閉時，主頁面才能關閉。
1. 注意delegate

- [ ] 完成

### 7. 兩個Listbox，一個Lable，一個，一個三維陣列，一個分頁。分頁上:一個DataGridView
1. 預設值:
```cpp
    三維陣列 => string[10,20,1] 一維資料1~10，二維資料各一個A~Z隨機字，三維資料各一個隨機數字。
    ListBox1 => 三維陣列的1維資料
    ListBox2 => 空
    Label => 空
    分頁上的DataGridView => 空
```
1. 排列順序: ListBox1 -> ListBox2 -> Label。Button在ListBox1下方。
1. 需求: 選擇好ListBox1的item後，ListBox2顯示對應的二維資料，按下ListBox2的item後，顯示對應的三維資料。按下Button顯示分頁，將三維陣列的資料顯示到DataGridView。DataGridView可以改動三維陣列的內部資料。關閉分頁後，將主頁面刷新。
1. 第一次總複習

- [ ] 完成

### 8. 兩個Progressbar，兩個NumericUpDown，1個timer。
1. 預設值:
```cpp
    NumericUpDown1預設值為0，最大為10，ProgressBar1的value對應他。
    NumericUpDown2預設值為0，最大為10，ProgressBar2對value對應他。
    ProgressBar1的MaxValue = 100。
    ProgressBar2的MaxValue = 150。
    Timer1 每7秒 trigger 一次。
```
1. 排列順序:ProgressBar1 -> ProgressBar2。NumericUpDown1 -> NumericUpDown2
1. Progressbar1由timer1控制，Progressbar2自己寫一個function控制，該function每11秒重新執行一次。Progressbar的數字若超過則歸零從來，並要補上差值。
1. 同步與非同步

- [ ] 完成

### 9. 用這些東西，去寫一個小遊戲吧!
