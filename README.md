# BootStrapStyleEditTextDemo
![test](https://github.com/475789729/BootStrapStyleEditTextDemo/blob/master/1.png)
<br>xml使用:
 <br><EditText android:layout_width="match_parent"
 <br>                  android:layout_height="wrap_content"
  <br>                  android:padding="15dp"
 <br>                  android:layout_margin="14dp"
  <br>                 android:background="@drawable/edit_background"
  <br>          >
 <br>       </EditText>
 <br>代码使用:
<br> //wrong
<br> //edittext.setPadding(30, 30, 30, 30);
 <br>//edittext.setBackgroundResource(R.drawable.edit_background);
<br>
 <br> //right
 <br>edittext.setBackgroundResource(R.drawable.edit_background);
<br> edittext.setPadding(30, 30, 30, 30);
<br>注意：必须先设置backgroundResouce，再设置padding，顺序不能颠倒

 