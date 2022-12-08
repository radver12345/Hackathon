# Hackathon

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/signin"
        android:text="Sign in"
        android:textColor="@color/purple_200"
        android:textSize="35dp"
        android:textStyle="bold"
        android:layout_margin="50dp"
        android:gravity="center"
        />
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/username"
        android:layout_below="@id/signin"
        android:hint="Username"
        android:textColorHint="@color/black"
        android:textColor="@color/black"
        android:layout_margin="10dp"
        android:padding="20dp"
        android:drawableLeft="@drawable/ic_baseline_person_outline_24"
        android:drawablePadding="20dp"
        />
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/password"
        android:layout_below="@id/username"
        android:hint="Password"
        android:textColorHint="@color/black"
        android:textColor="@color/black"
        android:layout_margin="10dp"
        android:padding="20dp"
        android:drawableLeft="@drawable/ic_baseline_perm_device_information_24"
        android:drawablePadding="20dp"
        android:inputType="textPassword"
        />
   <Button
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:id="@+id/loginbtn"
       android:layout_below="@id/password"
       android:text="LOGIN"
       android:backgroundTint="@color/purple_200"
       android:layout_centerHorizontal="true"
       android:layout_margin="20dp"
       />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/forgotpass"
        android:layout_below="@id/loginbtn"
        android:text="Forgot Password?"
        android:textColor="@color/black"
        android:layout_centerHorizontal="true"
        android:layout_margin="20dp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/others"
        android:layout_below="@id/forgotpass"
        android:text="or sign in with"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        />






