# DMoviles
DISPOSITIVOSMOVILES
DISEÑO DE CALCULADORA (Practica 1)
![image](https://user-images.githubusercontent.com/43210654/53504916-79797400-3a78-11e9-9db5-8d6da6ad4a2f.png)

Pratica Calculadora
-------------------------------------------
--------------------activity_main------------------------------------
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent"
    android:layout_height="match_parent" android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin" tools:context=".MainActivity"
    android:background="#fcf8f8">

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="7"
        android:id="@+id/bt7"
        android:layout_above="@+id/bt4"
        android:layout_alignStart="@+id/bt4" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="/"
        android:id="@+id/division"
        android:layout_above="@+id/bt7"
        android:layout_alignParentStart="true" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="*"
        android:id="@+id/multiplicacion"
        android:layout_alignTop="@+id/division"
        android:layout_toEndOf="@+id/division" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="C"
        android:id="@+id/clear"
        android:layout_alignTop="@+id/multiplicacion"
        android:layout_toEndOf="@+id/multiplicacion"
        android:shadowColor="#ee1111"
        android:background="#ff0000"
        android:textColor="#ffffff" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="DEL"
        android:id="@+id/borrar"
        android:layout_alignTop="@+id/clear"
        android:layout_toEndOf="@+id/clear"
        android:textColor="#ffffff"
        android:background="#ff0000" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="8"
        android:id="@+id/bt8"
        android:layout_alignTop="@+id/bt7"
        android:layout_toEndOf="@+id/bt7" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="9"
        android:id="@+id/bt9"
        android:layout_above="@+id/bt6"
        android:layout_toEndOf="@+id/bt8" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="4"
        android:id="@+id/bt4"
        android:layout_above="@+id/bt1"
        android:layout_alignEnd="@+id/division" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="5"
        android:id="@+id/bt5"
        android:layout_alignTop="@+id/bt4"
        android:layout_toEndOf="@+id/bt4" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="6"
        android:id="@+id/bt6"
        android:layout_alignBottom="@+id/bt5"
        android:layout_toEndOf="@+id/bt5" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="1"
        android:id="@+id/bt1"
        android:layout_centerVertical="true"
        android:layout_alignStart="@+id/bt4" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="2"
        android:id="@+id/bt2"
        android:layout_alignTop="@+id/bt1"
        android:layout_toEndOf="@+id/bt4" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="3"
        android:id="@+id/bt3"
        android:layout_alignTop="@+id/bt2"
        android:layout_toEndOf="@+id/bt5" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="0"
        android:id="@+id/bt0"
        android:layout_below="@+id/bt1"
        android:layout_alignEnd="@+id/division" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="."
        android:id="@+id/btpunt"
        android:layout_below="@+id/bt2"
        android:layout_toEndOf="@+id/bt1" />

    <Button
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="( )"
        android:id="@+id/btpar"
        android:layout_below="@+id/bt3"
        android:layout_toEndOf="@+id/bt2" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="+"
        android:id="@+id/suma"
        android:layout_above="@+id/bt6"
        android:layout_alignParentEnd="true" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="-"
        android:id="@+id/resta"
        android:layout_below="@+id/suma"
        android:layout_toEndOf="@+id/clear" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Raiz"
        android:id="@+id/raiz"
        android:layout_below="@+id/resta"
        android:layout_alignParentEnd="true" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="%"
        android:id="@+id/porcentaje"
        android:layout_below="@+id/bt3"
        android:layout_toEndOf="@+id/clear" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="="
        android:id="@+id/button20"
        android:layout_alignParentBottom="true"
        android:layout_toEndOf="@+id/btpunt" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="OFF"
        android:id="@+id/off"
        android:layout_below="@+id/porcentaje"
        android:layout_toEndOf="@+id/clear"
        android:background="#4e4a4a"
        android:textColor="#ffffff" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="SUBNETEO"
        android:id="@+id/sub"
        android:layout_below="@+id/bt0"
        android:layout_alignEnd="@+id/multiplicacion" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:text="Name"
        android:ems="10"
        android:id="@+id/caja"
        android:layout_alignParentTop="true"
        android:layout_alignStart="@+id/multiplicacion" />

</RelativeLayout>

-----------------MainActivity-------------------
package com.example.ivonn.calculadorat;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.EditText;

public class MainActivity extends AppCompatActivity {
    public EditText pant;
    public double operan1, operan2, res;
    int ope;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        pant=(EditText)findViewById(R.id.caja);
    }

    public void bt1 (View v){
        String cap= pant.getText().toString();
        cap=cap+"1";
        pant.setText(cap);
    }

    public void bt2 (View v){
        String cap= pant.getText().toString();
        cap=cap+"2";
        pant.setText(cap);

    }
    public void bt3 (View v){
        String cap= pant.getText().toString();
        cap=cap+"3";
        pant.setText(cap);

    }
    public void bt4 (View v){
        String cap= pant.getText().toString();
        cap=cap+"4";
        pant.setText(cap);

    }
    public void bt5 (View v){
        String cap= pant.getText().toString();
        cap=cap+"5";
        pant.setText(cap);

    }
    public void bt6 (View v){
        String cap= pant.getText().toString();
        cap=cap+"6";
        pant.setText(cap);

    }
    public void bt7 (View v){
        String cap= pant.getText().toString();
        cap=cap+"7";
        pant.setText(cap);

    }
    public void bt8 (View v){
        String cap= pant.getText().toString();
        cap=cap+"8";
        pant.setText(cap);
    }

    public void bt9 (View v){
        String cap= pant.getText().toString();
        cap=cap+"9";
        pant.setText(cap);
    }

    public void bt0 (View v){
        String cap= pant.getText().toString();
        cap=cap+"0";
        pant.setText(cap);

    }

    public void btpunt (View v){
        String cap=pant.getText().toString();
        cap=cap+".";
        pant.setText(cap);
    }

    public void btpar(View v){
        String cap=pant.getText().toString();
        cap=cap+"( )";
        pant.setText(cap);
    }

    public void suma(View v){
        try{
            String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText("");
        ope=1;
    }

    public void resta(View v){
        try{
            String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText("");
        ope=2;
    }
    public void multiplicacion (View v){
        try{
            String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText("");
        ope=3;
    }

    public void division (View v){
        try{
            String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText("");
        ope=4;
    }


    public void porcentaje (View v) {
        try{ String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText("");
        ope=6;
    }

    public void raiz (View v) {
        try{
            String aux1= pant.getText().toString();
            operan1= Double.parseDouble(aux1);
        }catch(NumberFormatException nfe){};
        pant.setText(" v(" +operan1+")");
        ope=7;
    }


    public void igual (View v){
        try{
            String aux2= pant.getText().toString();
            operan2= Double.parseDouble(aux2);
        }catch(NumberFormatException nfe){};
        pant.setText("");

        if (ope==1){
            res=operan1+operan2;

        }else if (ope==2){
            res=operan1-operan2;

        }else if (ope==3){
            res=operan1*operan2;

        }else if (ope==4){
            if(operan2==0){
                pant.setText("Numero no se puede dividir para 0");
            }else{
                res= operan1/operan2;
            }

        }else if (ope==5){
            res=Math.pow(operan1, operan2);

        }else if (ope==6){
            res=operan2*(operan1/100.0);

        }else if (ope==7){
            res=Math.sqrt(operan1);

        }else if(ope==8){
            double rad=Math.toRadians(operan1);
            res= (Math.sin(rad));

        }else if(ope==9){
            double rad=Math.toRadians(operan1);
            res= (Math.cos(rad));

        }else if(ope==10){
            double rad=Math.toRadians(operan1);
            res= (Math.tan(rad));

        }else if(ope==11){
            double angulo = (Math.asin(operan1));
            res=Math.toDegrees(angulo);

        }else if(ope==12){
            double angulo = (Math.acos(operan1));
            res=Math.toDegrees(angulo);

        }else if(ope==13){
            double angulo = (Math.atan(operan1));
            res=Math.toDegrees(angulo);

        }else if (ope==14){
            res=1;
            for(double i=operan1; i>=1; i--){
                res=res*i;
            }
        }
        pant.setText(""+res);
        operan1=res;
    }

    public void clear (View v){
        pant.setText("");
        operan1=0.0;
        operan2=0.0;
        res=0.0;
    }

    public void borrar (View v){
        if (!pant.getText().toString().equals("")){
            pant.setText(pant.getText().subSequence(0,pant.getText().length()-1)+"");
        }
    }

    public void off (View v){
        finish();
    }
}

-----------------------------------------------------------------------------
![calfinal](https://user-images.githubusercontent.com/43210654/54401517-9a071800-468d-11e9-9aba-61c8863864e8.png)

