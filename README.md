<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/crazy4"
        android:scaleType="centerCrop"/>

    <TextView
        android:layout_width="331dp"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:id="@+id/Begining"
        android:layout_margin="16dp"
        android:text="I wish you a hundred year of .."
        android:textColor="#ffffff"
        android:textSize="36dp" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:layout_marginBottom="16dp"
        android:layout_marginRight="16dp"
        android:text=" Nadeem"
        android:textColor="#ffffff"
        android:textSize="36dp" />
    <TextView
        android:id="@+id/Happiness"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Begining"
        android:layout_marginLeft="16dp"
        android:layout_marginTop="32dp"
        android:text="Happiness"
        android:textColor="#ffffff"
        android:textSize="26dp"
     />
    <TextView
        android:id="@+id/Love"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Happiness"
        android:layout_marginLeft="16dp"
        android:text="Love"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />
    <TextView
        android:id="@+id/Health"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Love"
        android:layout_marginLeft="16dp"
        android:text="Health"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />
    <TextView
        android:id="@+id/Luck"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Health"
        android:layout_marginLeft="16dp"
        android:text="Luck"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />
    <TextView
        android:id="@+id/Peace"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Begining"
        android:layout_alignParentRight="true"
        android:layout_marginRight="16dp"
        android:text="Peace"
        android:layout_marginTop="32dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />
    <TextView
        android:id="@+id/Joy"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Peace"
        android:layout_marginRight="16dp"
        android:text="Joy"
        android:layout_alignParentRight="true"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />

    <TextView
        android:id="@+id/Prosperity"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Joy"
        android:layout_marginRight="16dp"
        android:text="Prosperity"
        android:layout_alignParentRight="true"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />
    <TextView
        android:id="@+id/success"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Prosperity"
        android:layout_marginRight="16dp"
        android:text="Success"
        android:layout_alignParentRight="true"
        android:layout_marginTop="24dp"
        android:textColor="#ffffff"
        android:textSize="26dp" />

    <TextView
        android:id="@+id/All"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="87dp"
        android:fontFamily="serif"
        android:text="And all the best"
        android:textColor="#ffffff"
        android:textSize="30dp" />

</RelativeLayout>
