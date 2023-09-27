# AndroidStudio

    package com.example.imccalculadora; //pacote
    
    import androidx.appcompat.app.AppCompatActivity;                   //    
    import android.os.Bundle;                                          //
    import android.view.View;                                          // BIBLIOTECAS IMPORTADAS
    import android.widget.EditText;                                    //
    import android.widget.TextView;                                    //
    
    public class MainActivity extends AppCompatActivity {              // inicio default
    
        private TextView textResultado;                                // DECLARANDO OS 
        private EditText editPeso, editAltura;                         //   COMPONENTES
    
        @Override
        protected void onCreate(Bundle savedInstanceState) {           
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_main);
    
            textResultado = findViewById(R.id.textResultado);          // MOSTRAR AO ANDROID STUDIO 
            editPeso = findViewById(R.id.editPeso);                    //  QUE QUANDO CHAMAR ESTA
            editAltura = findViewById(R.id.editAltura);                //  SE REFERINDO AS CAMPOS
    
    
    
    
        }
    
        public void calcular (View view){                              //NOME DADO A FUNÇÃO
    
    
    
        }
    
    }
