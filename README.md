# modifications
Started coding 
activity_main.xml
1    <?xml version="1.0" encoding="utf-8"?>
2    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
3        xmlns:app="http://schemas.android.com/apk/res-auto"
4        xmlns:tools="http://schemas.android.com/tools"
5        android:layout_width="match_parent"
6        android:layout_height="match_parent"
7        android:orientation="vertical"
8        android:layout_gravity="center"
9        android:gravity="center"
10       android:padding="18dp"
11       tools:context=".MainActivity">
12   
13       <TextView
14           android:layout_width="match_parent"
15           android:layout_height="wrap_content"
16           android:text="Login Form"
17           android:textColor="@color/colorPrimary"
18           android:textSize="20sp"
19           android:textStyle="bold"
20           android:gravity="center"/>
21   
22   
23   
24       <com.google.android.material.textfield.TextInputLayout
25           android:id="@+id/text_input_email"
26           android:layout_width="match_parent"
27           android:layout_height="wrap_content"
28           app:errorEnabled="true"
29           android:layout_marginTop="50dp">
30   
31           <com.google.android.material.textfield.TextInputEditText
32               android:layout_width="match_parent"
33               android:layout_height="wrap_content"
34               android:hint="Email"
35               android:inputType="textEmailAddress" />
36   
37       </com.google.android.material.textfield.TextInputLayout>
38   
39       <com.google.android.material.textfield.TextInputLayout
40           android:id="@+id/text_input_password"
41           android:layout_width="match_parent"
42           android:layout_height="wrap_content"
43           android:layout_marginTop="11dp"
44           app:errorEnabled="true"
45           app:passwordToggleEnabled="true">
46   
47           <com.google.android.material.textfield.TextInputEditText
48               android:layout_width="match_parent"
49               android:layout_height="wrap_content"
50               android:hint="Password"
51               android:inputType="textPassword" />
52   
53       </com.google.android.material.textfield.TextInputLayout>
54   
55       <Button
56           android:layout_width="match_parent"
57           android:layout_height="wrap_content"
58           android:onClick="confirmInput"
59           android:text="Confirm"
60           android:textColor="@color/colorWhite"
61           android:layout_marginTop="22dp"
62           android:background="@color/colorPrimary"/>
63   
64   </LinearLayout>
