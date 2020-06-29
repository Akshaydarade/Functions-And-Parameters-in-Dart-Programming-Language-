# Functions-And-Parameters-in-Dart-Programming-Language-
Dart Programming Language is General Purpose Object  Oriented Programming  Language . In Dart There Are  Various Way to Define a Function And Accordingly There Are Various Ways to Passing A Parameter To a Function as Need as by User



void main(){
  
 
  PrintCities("Nashik","Mumbai","Pune");
  PrintCountries("Nashik","Mumbai");
  PrintName(name1:"Manoj",name3:"akshay",name2:"Akash");
  print(Volume1(2,3,h:5));
 
}


//Required Parameters

void PrintCities( String name1, String name2 , String name3){
  
  print("city name 1 : ${name1}");
  print("city name 2 : ${name2}");
  print("city name 3 : ${name3}");
  
  
 }

//Optional positinal parameters
// by using the [ ] brackets to the parameter 

void PrintCountries( String name1, String name2 , [String name3]){
  
  print("city name 1 : ${name1}");
  print("city name 2 : ${name2}");
  print("city name 3 : ${name3}");
  
 }

//Optional Named parameters 
// by using the { } braces to parameters

void PrintName( {String name1, String name2 , String name3}){
  
  print("city name 1 : ${name1}");
  print("city name 2 : ${name2}");
  print("city name 3 : ${name3}");
  

}

// Default parameters
int Volume1(int l, int b, { int h=10 }){
  
  return (l * b * h);

}



