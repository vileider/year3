int 10
float 2.0f
decimal 10.0m
bool true
char "c"
string "a string"
var - compiler is figuring out what type of variable is it
int[] = new int[5] //array of 5 intigers
string[] = {"a", "b", "c", "d}
Console.WriteLine("{0}",variablename);

float i_to_f = (float)i; //converted to float
a = a+b
a+= b
str ??= "new string //if str is null then new value will be asigned"
switch(theVal){
    case 50:
    Console.Writline("something",);
    break;
    case 100:
    Console.WriteLine("something);
    break;

}
try{

}
catch{

}

(int a,int b) tup1 = (5,10);
Console.WriteLine($@{tup.a},{tup.b}");

static (int,int) PlusTimes (inta , int b){
    return (a+b, a-b)
}

This is called property with "backing field"
public string Name {
    get {
        return _name;
    }
    set{
        _name = value
    }
}
shorthand way of writing "expression-bodied" property
public string Author{
    get => _author;
    set => _author = value;
}

public string Describtion {
    get => $"{Name} by {Author}"
}