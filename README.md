# RedRising-book-quiz
Audacity Project3: Quiz App, it is a quiz of an amazing trilogy, which i truly recommend.
Also i insertd an image, of the book cover, in the drawable folder

The XML code:

<ScrollView
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:id="@+id/activity_main"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:paddingBottom= "@dimen/activity_vertical_margin"
        android:paddingLeft="@dimen/activity_horizontal_margin"
        android:paddingRight="@dimen/activity_horizontal_margin"
        android:paddingTop="@dimen/activity_vertical_margin"
        tools:context=".MainActivity"
        android:weightSum="1">
        <EditText
            android:id="@+id/edittextid"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:inputType="textCapWords"
            android:layout_marginTop="8dp"
            android:layout_marginBottom="8dp"
            android:hint="Name"/>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:text="@string/red_rising_quiz"
            android:textColor="#D50000"
            android:textAllCaps="true"
            />

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="209dp"
            android:layout_marginBottom="8dp"
            android:src="@drawable/redrising"
            android:id="@+id/imageView" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q1_text_view"
            android:text="1) Number of colors in the Society? "
            />
        <RadioGroup xmlns:android="http://schemas.android.com/apk/res/android"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">
            <RadioButton android:id="@+id/radio_1a"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="12"/>
            <RadioButton android:id="@+id/radio_1b"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="14"/>
            <RadioButton android:id="@+id/radio_1c"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="10"/>
        </RadioGroup>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginTop="8dp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q2_text_view"
            android:text="2) Which house drafted Darrow?"/>
        <RadioGroup xmlns:android="http://schemas.android.com/apk/res/android"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">
        <RadioButton android:id="@+id/radio_2a"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Mars"/>
        <RadioButton android:id="@+id/radio_2b"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Minerva"/>
        <RadioButton android:id="@+id/radio_2c"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Diana"/>
        </RadioGroup>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginTop="8dp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q3_text_view"
            android:text="3) Who is a member of the Howlers?"/>
        <CheckBox android:id="@+id/checkbox_sevro"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Sevro"/>
        <CheckBox android:id="@+id/checkbox_antonia"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Antonia"/>
        <CheckBox android:id="@+id/checkbox_pebble"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Pebble"/>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginTop="8dp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q4_text_view"
            android:text="4) Which quotes are Darrow's?"/>
        <CheckBox android:id="@+id/checkbox_quote1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            android:text="I would have lived in peace. But my enemies brought me war."
           />
        <CheckBox android:id="@+id/checkbox_quote2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            android:text="Friendships take minutes to make, moments to break, years to repair."
            />
        <CheckBox android:id="@+id/checkbox_quote3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            android:text="You can treat your friends like servants and they'll love you, but you tell them they're servants and they'll kill you. "
            />
        <CheckBox android:id="@+id/checkbox_quote4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            android:text="In a world of killers, it takes more to be kind than to be wicked."
            />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q5_text_view"
            android:text="5) Which weapon is Darrow's favourite? "
            />
        <RadioGroup xmlns:android="http://schemas.android.com/apk/res/android"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">
            <RadioButton android:id="@+id/radio_5a"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="IonBlade"/>
            <RadioButton android:id="@+id/radio_5b"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="PulseFist"/>
            <RadioButton android:id="@+id/radio_5c"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="SlingBlade"/>
        </RadioGroup>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginBottom="8dp"
            android:id="@+id/q6_text_view"
            android:text="6) House Augustus's motto."
            />
        <RadioGroup xmlns:android="http://schemas.android.com/apk/res/android"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">
            <RadioButton android:id="@+id/radio_6a"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Hic sunt leones."/>
            <RadioButton android:id="@+id/radio_6b"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ad astra per aspera."/>
            <RadioButton android:id="@+id/radio_6c"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ominis vir lupus."
                android:layout_marginBottom="8dp"/>
        </RadioGroup>

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/submitResults"
            android:layout_below="@+id/price_text_view"
            android:onClick="submitResults"
            android:textAllCaps="true"
            android:text="show results"/>

    </LinearLayout>
</ScrollView>

The Java Code:

 package com.example.android.quizapp;

    import android.content.Intent;
    import android.net.Uri;
    import android.os.Bundle;
    import android.support.v7.app.AppCompatActivity;
    import android.util.Log;
    import android.view.View;
    import android.widget.CheckBox;
    import android.widget.EditText;
    import android.widget.RadioButton;
    import android.widget.TextView;
    import android.widget.Toast;

    import static android.R.attr.checked;
    import static android.R.attr.name;

    public class MainActivity extends AppCompatActivity {


        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_main);
        }


        /**
         * This method is called when the show results button is clicked.
         */
        public void submitResults(View view) {

            EditText nameField = (EditText)findViewById(R.id.edittextid);
            String name = nameField.getText().toString();

            // For question 1
            RadioButton radioButton1A =(RadioButton) findViewById(R.id.radio_1a);
            boolean hasA1= radioButton1A.isChecked();

            RadioButton radioButton1B =(RadioButton) findViewById(R.id.radio_1b);
            boolean hasB1= radioButton1B.isChecked();

            RadioButton radioButton1C =(RadioButton) findViewById(R.id.radio_1c);
            boolean hasC1= radioButton1C.isChecked();

            // For question 2
            RadioButton radioButton2A =(RadioButton) findViewById(R.id.radio_2a);
            boolean hasA2= radioButton2A.isChecked();

            RadioButton radioButton2B =(RadioButton) findViewById(R.id.radio_2b);
            boolean hasB2= radioButton2B.isChecked();

            RadioButton radioButton2C =(RadioButton) findViewById(R.id.radio_2c);
            boolean hasC2= radioButton1C.isChecked();

            // For question 3
            CheckBox checkBoxSevro = (CheckBox) findViewById(R.id.checkbox_sevro);
            boolean hasSevro = checkBoxSevro.isChecked();

            CheckBox checkBoxAntonia = (CheckBox) findViewById(R.id.checkbox_antonia);
            boolean hasAntonia = checkBoxAntonia.isChecked();

            CheckBox checkBoxPebble = (CheckBox) findViewById(R.id.checkbox_pebble);
            boolean hasPebble = checkBoxPebble.isChecked();

            // For question 4
            CheckBox checkBoxQ1 = (CheckBox) findViewById(R.id.checkbox_quote1);
            boolean hasQ1 = checkBoxQ1.isChecked();

            CheckBox checkBoxQ2 = (CheckBox) findViewById(R.id.checkbox_quote2);
            boolean hasQ2 = checkBoxQ2.isChecked();

            CheckBox checkBoxQ3 = (CheckBox) findViewById(R.id.checkbox_quote3);
            boolean hasQ3 = checkBoxQ3.isChecked();

            CheckBox checkBoxQ4 = (CheckBox) findViewById(R.id.checkbox_quote4);
            boolean hasQ4 = checkBoxQ4.isChecked();

            // For question 5
            RadioButton radioButton5A =(RadioButton) findViewById(R.id.radio_5a);
            boolean hasA5= radioButton5A.isChecked();

            RadioButton radioButton5B =(RadioButton) findViewById(R.id.radio_5b);
            boolean hasB5= radioButton5B.isChecked();

            RadioButton radioButton5C =(RadioButton) findViewById(R.id.radio_5c);
            boolean hasC5= radioButton5C.isChecked();

            // For question 6
            RadioButton radioButton6A =(RadioButton) findViewById(R.id.radio_6a);
            boolean hasA6= radioButton6A.isChecked();

            RadioButton radioButton6B =(RadioButton) findViewById(R.id.radio_6b);
            boolean hasB6= radioButton6B.isChecked();

            RadioButton radioButton6C =(RadioButton) findViewById(R.id.radio_6c);
            boolean hasC6= radioButton6C.isChecked();


            // Calculate the price
            int finalResult = calculateResult(hasA1,hasB1,hasC1, hasA2,
                    hasB2, hasC2, hasSevro, hasAntonia, hasPebble,
                    hasQ1, hasQ2, hasQ3, hasQ4, hasA5, hasB5, hasC5,
                    hasA6, hasB6, hasC6);
            Toast.makeText(this, name+" you got " + finalResult +" out of 8!", Toast.LENGTH_SHORT).show();

        }
        private int calculateResult(boolean add1A, boolean add1B, boolean add1C, boolean add2A, boolean add2B, boolean add2C
                                   ,boolean add3A,boolean add3B, boolean add3C, boolean add4A, boolean add4B, boolean add4C,boolean add4D
                                   ,boolean add5A,boolean add5B, boolean add5C, boolean add6A, boolean add6B, boolean add6C) {
            int result = 0;

            if (add1A) {
                result = 0;
            }
            if (add1B) {
                result = result + 1;
                // 14 is the answer.
            }
            if (add1C) {
                result = 0;
            }
            if (add2A) {
                result = result + 1;
                // Mars is the answer.
            }
            if (add2B) {
                result=result+0;
            }
            if (add2C) {
                result=result+0;
            }

            if (add3A) {
                result = result + 1;
                // Sevro is answer
            }
            if (add3B) {
                result=result+0;
            }
            if (add3C) {
                result = result + 1;
                // Pebble is answer
            }
            if (add4A) {
                // The right one
                result = result + 1;
            }
            if (add4B) {
                result=result+0;
            }
            if (add4C) {
                result=result+0;
            }
            if (add4D) {
                // The right one.
                result = result + 1;
            }
            if (add5A) {
                if (result != 0) {
                    result = result - 1;
                } else {
                    result = 0;
                }
            }
            if (add5B) {

            }
            if (add5C) {
                // SlingBlade is the answer
                result = result + 1;
            }
            if (add6A) {
                // The right answer.
                result = result + 1;
            }
            if (add6B) {
                result=result+0;

            }
            if (add6C) {
                result=result+0;
            }
            return result;

        }

    }
    
    Styles.XML:
    <resources>

    <!-- Base application theme. -->
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">#E53935</item>
        <item name="colorPrimaryDark">#B71C1C</item>
        <item name="colorAccent">#D50000</item>
    </style>

</resources>

Strings.XML:
<resources>
    <string name="app_name">Red Rising App</string>
    <string name="red_rising_quiz">Red Rising Quiz</string>
</resources>
