# BootStrapStyleEditTextDemo
![test](https://github.com/475789729/BootStrapStyleEditTextDemo/blob/master/1.png)
<br>xmlʹ��:
 <br><EditText android:layout_width="match_parent"
 <br>                  android:layout_height="wrap_content"
  <br>                  android:padding="15dp"
 <br>                  android:layout_margin="14dp"
  <br>                 android:background="@drawable/edit_background"
  <br>          >
 <br>       </EditText>
 <br>����ʹ��:
<br> //wrong
<br> //edittext.setPadding(30, 30, 30, 30);
 <br>//edittext.setBackgroundResource(R.drawable.edit_background);
<br>
 <br> //right
 <br>edittext.setBackgroundResource(R.drawable.edit_background);
<br> edittext.setPadding(30, 30, 30, 30);
<br>ע�⣺����������backgroundResouce��������padding��˳���ܵߵ�

 