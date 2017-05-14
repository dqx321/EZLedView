# EZLedView


<img src="./img/img_head.gif?raw=true" alt="Example" width="200" />

我不知道是不是应该叫LedView，或者叫点阵图，就是把图片或文字转换成由点阵构成的效果。

## Demo

<table>
<tr>
<td>
<img src="./img/img_0.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_1.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_2.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_3.png?raw=true" alt="Example" width="200" />
</td>
</tr>
<tr>
<td>
<img src="./img/img_4.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_5.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_6.png?raw=true" alt="Example" width="200" />
</td>
<td>
<img src="./img/img_7.png?raw=true" alt="Example" width="200" />
</td>
</tr>
</table>


## Usage


#### For Text
````
     <com.goyourfly.ezledview.EZLedView
            android:id="@+id/ledView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:text="HELLO"
            app:led_color="#000"
            app:text_size="200dp" />
````

#### For Image
````
        <com.goyourfly.ezledview.EZLedView
            android:id="@+id/ledView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:image="@drawable/simpson" />
````

#### Params
| Name | Format | Explain |
|-----|:-----:|:------:|
|led_radius|dimension|radius of led point|
|led_space|dimension|space between led point|
|led_color|color|color of led point,does not work if the content is image|
|led_type|enum|type of led light:`circle`,`square`,`drawable`|
|led_drawable|reference|if `led_type` is drawable|
|content_type|enum|type of content:`text`,`image`|
|image|reference|the reference of image|
|text|string|the content of text|
|text_size|dimension|size of text|


## Compile