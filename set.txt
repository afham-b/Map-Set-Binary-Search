#include <string>
#include <set>
#include<iostream>
using namespace std; 

int main ( ) {

  string s;
  set<string> myset;

  myset.insert("cat"); 
  myset.insert("dog"); 
  myset.insert("horse"); 
  myset.insert("chicken"); 
  myset.insert("goat"); 
  myset.insert("giraffe"); 
  myset.insert("elephant"); 


 // set<string>::iterator i; 
 // for (i= myset.begin(); i != myset.end(); i++)
 //   cout << *i << endl;

for (auto x: myset) 
  cout <<x << endl; 

  return 0; 
}