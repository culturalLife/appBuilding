


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
     xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/tvHeading"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Add Personal Details"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_marginTop="16dp"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        android:textColor="@color/black"/>

    <ImageView
        android:id="@+id/ivProfileImage"
        android:layout_width="150dp"
        android:layout_height="150dp"
        android:layout_below="@id/tvHeading"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="28dp"
        android:src="@drawable/ic_baseline_add_a_photo_24" />

    <LinearLayout
        android:id="@+id/ll1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_below="@id/ivProfileImage"
        android:layout_marginTop="24dp">

        <TextView
            android:id="@+id/etNAME"
            android:layout_width="100dp"
            android:layout_height="wrap_content"
            android:text="Name"
            android:textSize="18dp"
            android:padding="10dp"
      />

        <EditText

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="null"
            android:padding="10dp"
            android:textSize="18sp"
            android:hint="Enter Your Name"
            android:inputType="textPersonName"/>

    </LinearLayout>
    <LinearLayout
        android:id="@+id/ll2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_below="@id/ll1">

    <TextView
        android:id="@+id/etage"
        android:layout_width="100dp"
        android:layout_height="wrap_content"
        android:text="Age"
        android:textSize="18dp"
        android:padding="10dp"
        />

    <EditText

        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="null"
        android:padding="10dp"
        android:textSize="18sp"
        android:hint="Enter Your age"
        android:inputType="number"/>

    </LinearLayout>
    <LinearLayout
        android:id="@+id/ll3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_below="@id/ll2">

        <TextView
            android:id="@+id/etnumber"
            android:layout_width="100dp"
            android:layout_height="wrap_content"
            android:text="Phone Number"
            android:textSize="18dp"
            android:padding="10dp"
            />

        <EditText

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="null"
            android:padding="10dp"
            android:textSize="18sp"
            android:hint="Enter Your Phone Number"
            android:inputType="phone"/>

    </LinearLayout>
  <Button
          android:id="@+id/btnSubmit"
          android:layout_width="match_parent"
            android:layout_height="wrap_content"
          android:layout_below="@id/ll3"
          android:layout_counterHorizontal="true"
          android:layout_marginTop="26dp"
          android:text="@string/submit"
          android:textAllCaps="false" />
                                            





</RelativeLayout>
