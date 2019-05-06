<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:context="com.example.hp.myapplication6.MainActivity"
    tools:showIn="@layout/activity_main">



    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="40dp"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:gravity="center"
        android:text="输入你的姓名"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView3" />


    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="40dp"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:gravity="center"
        android:text="手机号"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />




</android.support.constraint.ConstraintLayout>
