![gif](https://github.com/jaikydota/Android-FaceView/blob/master/Demo/GIF.gif)  


# Android-FaceView
This is a Emoticon for Android.<br>
If you need to know about replay dialog information, please click here: https://github.com/jaikydota/Android-ReplayDialog<br>

Chinese blog address: http://blog.csdn.net/jaikydota163/article/details/52098873<br>
项目中文博客地址：http://blog.csdn.net/jaikydota163/article/details/52098873<br>

###*Using*
Add to your layout xml:
```
<com.jaiky.test.faceview.FaceView
    android:id="@+id/face_view"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:visibility="gone" >
</com.jaiky.test.faceview.FaceView>
```

Binding to your code:
```
FaceView faceView = (FaceView) findViewById(R.id.face_view);
//binding the faceview edit EditText
faceView.setEdit(etContent);
//bing call to the FaceBar Button
faceView.setBtnView(ivFace);
```

Showing TextView:
```
TextView.setText(Html.fromHtml(replyDialog.getContent(), new FaceImageGetter(context), null));
```

###*About Information*
Hello my friends!<br>
This is a very simple small project, so I don't upload it to 'jcenter' or 'Maven Center'.<br>
Please download it and deploy to your Android Studio.<br>
Using this demo, you will know how to achieve.<br>
And my english is very bad, so I can only write so many.<br>
Hope there is no syntax error?<br>
