Java Type casting

Converting of data from 1 data type to another data type is called type casting. Type casting supports primitive and reference data type. Casting can of implicit and explicit. Implicit in  primitive data type can be done casting automatically. Meanwhile Explicit casting in  primitive data type should be done by developers. Implicit in  primitive data type happens when we apply a lower data type to higher data type (eg:- byte to int or int to long).Explicit in  primitive data type happens when we apply higher data type to lower data type (eg. int to byte or long to int).

Reference data type (i.e in object casting) is also having implicit and explicit. Implicit in reference data type happens when we assign child class object to parent class object. Explicit in  reference data type when we assign parent class object to child class object.


package com.bini.babu;

public class ExplicitCast {

	public static void main(String[] args) {
     int i = 100;
     byte b = (byte)i;
     System.out.println(b);
     
     int s = 97;
     char ch = (char)s;
     System.out.println(ch);
	}

}

Output
100
a


when we want to the convert the variable from high data type to low data type we need to explicit casting. (eg: byte b = (byte)i;) The high data type int converted to byte by putting low data type in bracket(like this: '(byte)i'  ). Similarly 's' variable is assigned 97 and when we assign to char by casting to char the int and when we print we will get character 'a'.
