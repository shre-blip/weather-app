# weather-app
main code
  String city = cityName.getText().toString();
                try{
                    if(city!=null){
                        url = "https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid=d3e1a6d4468a8819de7625a952e08b1c";
                        url = "https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid={Enter your api Key Here}";
                    }else{
                        Toast.makeText(MainActivity.this, "Enter City", Toast.LENGTH_SHORT).show();
                    }
@@ -102,4 +102,4 @@ public void onClick(View v){
        });
