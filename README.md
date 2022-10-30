# DesainProjectPEApps
Desain Project sesuai yang di desain pada CorelDraw
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_alignTop="@id/FirstFragment"
    android:layout_alignParentEnd="true"
    android:background="#20C8C4">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#085F8E"
        android:orientation="horizontal">

        <ImageButton
            android:id="@+id/imageButton3"
            android:layout_width="139dp"
            android:layout_height="622dp"
            android:backgroundTint="#1EFFFFFF"
            android:contentDescription="@string/forklift"
            android:cropToPadding="false"
            android:paddingStart="@dimen/activity_vertical_margin"
            android:paddingTop="@dimen/activity_forkliftatas_margin"
            android:paddingEnd="@dimen/activity_bawah_margin"
            android:paddingBottom="@dimen/activity_bawah_margin"
            android:scaleType="fitCenter"
            android:scrollbarSize="20dp"
            app:srcCompat="@drawable/forklift"
            tools:ignore="SpeakableTextPresentCheck,ImageContrastCheck,DuplicateSpeakableTextCheck" />

        <ImageButton
            android:id="@+id/imageButton5"
            android:layout_width="139dp"
            android:layout_height="622dp"
            android:backgroundTint="#1EFFFFFF"
            android:contentDescription="@string/weld"
            android:cropToPadding="false"
            android:paddingStart="@dimen/activity_vertical_margin"
            android:paddingTop="@dimen/activity_forkliftatas_margin"
            android:paddingEnd="@dimen/activity_bawah_margin"
            android:paddingBottom="@dimen/activity_bawah_margin"
            android:scaleType="fitCenter"
            android:scrollbarSize="20dp"
            app:srcCompat="@drawable/weld"
            tools:ignore="SpeakableTextPresentCheck,ImageContrastCheck" />

        <ImageButton
            android:id="@+id/imageButton6"
            android:layout_width="148dp"
            android:layout_height="622dp"
            android:backgroundTint="#1EFFFFFF"
            android:contentDescription="@string/painting"
            android:cropToPadding="false"
            android:paddingStart="@dimen/activity_vertical_margin"
            android:paddingTop="@dimen/activity_forkliftatas_margin"
            android:paddingEnd="@dimen/activity_bawah_margin"
            android:paddingBottom="@dimen/activity_bawah_margin"
            android:scaleType="fitCenter"
            android:scrollbarSize="20dp"
            app:srcCompat="@drawable/brush"
            tools:ignore="SpeakableTextPresentCheck,ImageContrastCheck" />

    </LinearLayout>

    <FrameLayout
        android:layout_width="match_parent"
        android:layout_height="232dp"
        android:background="#CFCFCF">

        <TextView
            android:id="@+id/textView2"
            android:layout_width="match_parent"
            android:layout_height="227dp"
            android:background="#BAB9B9"
            android:fontFamily="@font/aldrich"
            android:paddingStart="@dimen/activity_kiri_margin"
            android:paddingTop="@dimen/activity_atas_margin"
            android:paddingEnd="@dimen/activity_kanan_margin"
            android:paddingBottom="@dimen/activity_bawah_margin"
            android:text="@string/maintenance_sumitomo_team"
            android:textAlignment="center"
            android:textColor="#0277BD"
            android:textColorHighlight="#000000"
            android:textSize="20sp"
            android:textStyle="bold"
            app:autoSizeTextType="none"
            tools:ignore="TextContrastCheck" />

        <ImageView
            android:id="@+id/imageView4"
            android:layout_width="209dp"
            android:layout_height="254dp"
            android:contentDescription="@string/logo"
            android:cropToPadding="false"
            android:paddingStart="@dimen/activity_kanan_margin"
            android:paddingTop="@dimen/activity_vertical_margin"
            android:paddingEnd="@dimen/fab_margin"
            android:textAlignment="center"
            app:srcCompat="@drawable/_280px_sumitomo_rubber_industries_logo"
            tools:ignore="ImageContrastCheck" />

    </FrameLayout>

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#1EA3AF"
        android:text="@string/peapps"
        android:textAlignment="center"
        android:textColor="#000000"
        android:textSize="34sp" />

    <ImageButton
        android:id="@+id/imageButton"
        android:layout_width="59dp"
        android:layout_height="49dp"
        android:contentDescription="@string/PEApps"
        android:scaleType="fitCenter"
        app:srcCompat="@drawable/menu"
        tools:ignore="ImageContrastCheck,DuplicateSpeakableTextCheck" />

    <ImageButton
        android:id="@+id/imageButton2"
        android:layout_width="55dp"
        android:layout_height="47dp"
        android:layout_marginStart="356dp"
        android:contentDescription="@string/PEApps"
        android:scaleType="fitCenter"
        android:textAlignment="center"
        app:srcCompat="@drawable/iconbell"
        tools:ignore="ImageContrastCheck" />

</RelativeLayout>
