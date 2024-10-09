<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:orientation="vertical"
    android:layout_margin="10dp"
    >

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Calculadora do perimetro e da área "
        android:textSize="25sp"
         />

<LinearLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="horizontal"
    >
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        >
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="largura A"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="73dp" />

    <EditText
        android:id="@+id/larguraA"
        android:layout_width="147dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="84dp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        >

    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="largura B"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="233dp"
        tools:layout_editor_absoluteY="73dp" />

    <EditText
        android:id="@+id/larguraB"
        android:layout_width="147dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="233dp"
        tools:layout_editor_absoluteY="84dp" />

    </LinearLayout>
</LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="largura C"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="153dp"

        />

    <EditText
        android:id="@+id/largurac"
        android:layout_width="147dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="165dp" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="largura D"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="233dp"
        tools:layout_editor_absoluteY="153dp" />

        <EditText
            android:id="@+id/larguraD"
            android:layout_width="147dp"
            android:layout_height="48dp"
            tools:layout_editor_absoluteX="233dp"
            tools:layout_editor_absoluteY="165dp" />

</LinearLayout>
    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="Perimetro"
        android:textSize="25sp"
        android:layout_marginBottom="2dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="236dp" />
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="000000"
        android:textSize="25sp"
        android:layout_marginBottom="3dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="236dp" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
        <TextView

        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="Àrea"
        android:textSize="25sp"
        android:layout_marginBottom="2dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="296dp" />
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="000000"
        android:textSize="25sp"
        android:layout_marginBottom="3dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="236dp" />
    </LinearLayout>
    </LinearLayout>
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="Endereço"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="384dp" />

    <EditText
        android:id="@+id/Endereço"
        android:layout_width="match_parent"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="422dp" />


    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >

    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="Bairo"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="474dp" />

    <EditText
        android:id="@+id/Bairo"
        android:layout_width="147dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="512dp" />
        </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:orientation="vertical"
        >
    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="cidade"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="248dp"
        tools:layout_editor_absoluteY="482dp" />

    <EditText
        android:id="@+id/Cidade"
        android:layout_width="147dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="248dp"
        tools:layout_editor_absoluteY="512dp" />
        </LinearLayout>
    </LinearLayout>

    <TextView
        android:layout_width="184dp"
        android:layout_height="38dp"
        android:text="Observações"
        android:textSize="25sp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="574dp" />

    <EditText
        android:id="@+id/Obs"
        android:layout_width="321dp"
        android:layout_height="48dp"
        tools:layout_editor_absoluteX="41dp"
        tools:layout_editor_absoluteY="627dp" />
<LinearLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
    <Button
        android:layout_width="198dp"
        android:layout_height="106dp"
        android:text="Cancelar"
        android:textSize="25dp"
        android:id="@+id/Cancelar" >
    </Button>
    <Button
        android:id="@+id/salvar"
        android:layout_width="198dp"
        android:layout_height="106dp"
        android:text="Cancelar"
        android:textSize="25dp">
    </Button>
</LinearLayout>
</LinearLayout>
    </LinearLayout>
