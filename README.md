# Homework3
Homework3
public int StreetNumber {get; set;}
public string StreetName {get; set;}
public string State {get; set;}
public string City {get; set;}
public int ZipCode {get; set;}



public Address ()
{
	StreetNumber = 0;
	StreetName = "";
	State = "";
	City = "";
	ZipCode = 0;
	
}

public Address (int streetNumber, string streetName, string state, string city, int zipCode )
{
   streetNumber = StreetNumber;
   streetName = StreetName;
   State = state;
   City = city;
   ZipCode = zipCode;
}