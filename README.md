# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

package com.example.exp1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart() {
        super.onStart();
        Toast toast1 = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast1.show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast2 = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast2.show();
    }

    protected void onPause() {
        super.onPause();
        Toast toast3 = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast3.show();
    }

    protected void onResume() {
        super.onResume();
        Toast toast4 = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast4.show();
    }

    protected void onStop() {
        super.onStop();
        Toast toast5 = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast5.show();
    }

    protected void onDestroy() {
        super.onDestroy();
        Toast toast6 = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast6.show();
}

}


## OUTPUT
![WhatsApp Image 2024-03-11 at 09 12 58_58e0792f](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/d083ca79-52d3-4894-9eab-6d6a5c768745)

![WhatsApp Image 2024-03-11 at 09 12 58_416cea2a](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/9b3256ec-c11a-46f5-8bb8-c1954eef3a40)

![WhatsApp Image 2024-03-11 at 09 12 58_d537cbb7](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/fec96d53-f7a6-4980-8acc-0c5f0e3ab377)

![WhatsApp Image 2024-03-11 at 09 12 58_e93cd077](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/73bb46ec-479c-449e-b6d9-6fe9defa7e28)


![WhatsApp Image 2024-03-11 at 09 12 58_8092fcd6](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/59d17f54-905d-4325-a45d-1df59695595b)

![WhatsApp Image 2024-03-11 at 09 12 58_0d0042ec](https://github.com/Ritz514/lifecyclemethods-120/assets/142646304/6b7c166c-1c53-43fd-acbb-2dee10610faa)



## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
