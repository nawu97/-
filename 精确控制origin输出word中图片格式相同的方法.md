# 精确控制origin输出word中图片格式相同的方法
@https://www.docin.com/p-1845682483.html

## 第一部分：精确控制Origin输出到Word中图片的大小：包括线宽，文字还有图例
### 1.Tool---> Option 里设置几个参数:
#### (1) 页面复制比例设置

Page ---> 在Copy Page Setting下的Ratio选择100，其他可继续设置，如Advance:Set Resolution；600

(设置复制比例100%，可以将此设为默认)


#### (2) 字体设置

Text Fonts ---> 勾选 WYSIWYG in Page View Model,Origin默认是视图方式是Page View，而WYSIWYG是所见即所得，这样可以保证2
打印效果与屏幕显示的是一致的，这里也可以设置字体格式及其大小。

### 2.Format--->Page:设置图片窗口的大小，例如ACS要求图片Width不大于3.25inch，对于两栏排版，建议设置7.5cm-8.0cm宽

### 3.将图片所有信息粗略的调整到Page空间中（步骤2启用后，Page可能很小，需要后续细致设置）
### View---> Whole Page(快捷键Ctrl+W)此时屏幕上的尺寸可能大于设置尺寸，但不影响输出效果


### 4.详细设置图片格式，建议线宽0.5，图标3磅，字体9~10磅，坐标轴Title&Format--->Thickness:0.5,Major Tick:3

### 5.Edit--->Copy Page(快捷键ctrl+J)直接在word直接Ctrl+V,也可以“复制”---“选择性粘贴"---"图元文件”
**注：**【前者可以打开word修改图片，后者仅仅是图片】 *1 inch=2.54 cm*

## 第二部分：保持Origin作图格式一致
### 如果要做很多格式相同的图，一一去设置显然低效，另按上述要求设置图片可满足大多数期刊投稿要求，因此，这也希望能快速设置，减少工作量，Origin的自定义模板可以实现该目的。
### 具体步骤如下：
#### 1.在已经完成各项设置的图片上右键选择：Save Format as Theme
#### 2.在Name of the new 里定义一个名字，建议Format to save里All前面的勾去掉，选择Fonts，Colors，Symbol，Dimension,Background和Text
 
 **注意:** All Styles和scale不建议选择；如果选择Set as System Theme，以后画的图都是这个图的格式了，在确定满意之前，最后检查一下，所以这里尽量不选择这一项，
#### 3.另画一图时，然后在菜单Tools里选择Theme Organizer找到定义的模板，然后点击Apply now
#### 4.检查应用模板后的图片是否满足要求，如果满足要求可以设置为系统模板，右侧点击Set as System Theme
